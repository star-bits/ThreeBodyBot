# ThreeBodyBot

forked from [kirklong/ThreeBodyBot](https://github.com/kirklong/ThreeBodyBot)

https://user-images.githubusercontent.com/93939472/234335201-a87a97c3-6942-4a35-a64c-e2a020b558ea.mp4

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

cd path/to/ThreeBodyBot

# make tmpPlots directory
mkdir tmpPlots

# launch the Julia REPL
julia

pwd()
cd("path/to/ThreeBodyBot")

# generate threeBody.mp4
include("threeBodyProb.jl")
```
