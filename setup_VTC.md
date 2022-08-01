## step1: Clone repository
```
git clone git@github.com:furo-org/VTC.git
```
## step2: Clone submodule

### step2-1 Edit git config
```
git config -e
```

### step2-2: Change protocol
CagePlugin: git@github.com:furo-org/CagePlugin.git

PxArticulationLink: git@github.com:yosagi/PxArticulationLink.git

ZMQUE: git@github.com:furo-org/ZMQUE.git

### step2-3: Clone submodule
```
git submodule update --init --recursive
```
