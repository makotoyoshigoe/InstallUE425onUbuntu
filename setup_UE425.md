# About this file

## This is the repository for setup UnrealEngine4.25 on Ubuntu20.04

# How to use

## step0: Clone UnrealEngine repository
```
git clone -b 4.25 git@github.com:EpicGames/UnrealEngine.git
```

## step1: Build UE4
### step1-1
```
./Setup.sh
```
### step1-2
```
./GenerateProjectFiles.sh
```
### step1-3
```
make
```

## step2: Run UE4-Editor
```
cd Engine/Binaries/Linux
```
```
./UE4Editor
```
