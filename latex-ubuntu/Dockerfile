FROM ubuntu:18.04
ENV TZ=America/Los_Angeles
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime \ 
 && echo $TZ > /etc/timezone 
RUN apt-get --yes -qq update \
 && apt-get --yes -qq upgrade \
 && apt-get --yes -qq install \
    texlive-full \
 && apt-get --yes -qq clean \
 && rm -rf /var/lib/apt/lists/*
