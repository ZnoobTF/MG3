# MG3
## Devlog
1. The default values are as follows: float->0 int->0 bool->False string->null
2. Unity calls the Update method for you every frame.
3. Kickweapon calls the timer to begin for a lifetime time (default is 0.2 seconds) on activation of the kick. Then, after that timer finishes, the kick is deactivated in an Update method, to keep track if the time finishes every frame. 
TimerText does the same thing, but for the overall timer (default is 30 seconds). When the code in the Update method detects that the timer finishes, it calls the GameOver method. 

## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)