

# dockerfiles

Dockerfiles used in https://hub.docker.com/u/rbast.


## Examples

```
$ docker pull rbast/latex
$ docker run -v $PWD:$PWD -w $PWD -it rbast/latex pdflatex example.tex

$ docker pull rbast/pandoc
$ docker run -v $PWD:$PWD -w $PWD -it rbast/pandoc pandoc --from=markdown --to=rst --output=README.rst README.md
```
