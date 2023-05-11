# ThreeBodyBot

forked from [kirklong/ThreeBodyBot](https://github.com/kirklong/ThreeBodyBot)

https://github.com/star-bits/ThreeBodyBot/assets/93939472/4e6eadfb-bebe-4fb7-bd08-e613ac891c92

## To setup:
- Install Julia (tested with version 1.8.5)
- Add Julia to your PATH
```shell
open -a TextEdit ~/.zshrc

# add the following line
export PATH="/Applications/Julia-1.8.app/Contents/Resources/julia/bin:$PATH"

source ~/.zshrc
```
- Install FFmpeg

## To run:
```shell
git clone https://github.com/star-bits/ThreeBodyBot.git 
cd ThreeBodyBot

# make tmpPlots directory
mkdir tmpPlots

# launch the Julia REPL
julia

pwd()
cd("path/to/ThreeBodyBot")

# generate threeBody.mp4
include("threeBodyProb.jl")
```
