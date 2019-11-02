

# dockerfiles

Dockerfiles used in https://hub.docker.com/u/rbast.


## Examples

```
$ docker pull rbast/latex
$ docker run -v $PWD:$PWD -w $PWD -it rbast/latex pdflatex example.tex
```
