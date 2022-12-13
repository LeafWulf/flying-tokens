# To-do

## Requests
- [ ] 

## Bugs
- [ ] Flying Tokens is setting a token to fly when it moves into a grid space that has been set by Elevated Vision to be some value other than 0. For example, if you set a grid space to be elevation 20 (say, for a hill), moving the token to that grid space will adjust the token elevation from 0 to 20 (presuming the automatic elevation change setting is enabled). But most people would not interpret that as flying, because the token moved from a position where the canvas "terrain" background is 0 elevation to one where it is 20, like you are climbing a hill. 