# docker-reshack
Resource Hacker Dockerfile

Run [Resource Hacker](http://www.angusj.com/resourcehacker/) in docker

## Usage:
```
docker run -v `pwd`:/files -w /files sporsh/reshack -addoverwrite original.exe, modified.exe, mynewicon.ico, IconGroup, IDR_MAINFRAME, 1033
```

```
docker run -v `pwd`:/files -w /files sporsh/reshack -script myreshackscript
```
