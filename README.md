# [WIP]verified-plasma-mvp
Formal Verification for Plasma-mvp

## Dependencies
You need to install [klab](https://github.com/dapphub/klab).

## Building
In `src` directory, 
```
klab build 
```

When you use klab with docker, 
```
docker run --rm -it -v $(pwd):/docker --name klab klab
klab server
```
```
docker exec -it klab bash
cd /docker
klab build
klab run --spec out/specs/proof-RootChain_operator_succ.k
```