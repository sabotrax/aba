# aba
An auto battler in FastBasic for the Atari 8-bits

## Features

Be warned - this is alpha code and I haven't touched BASIC in 35 years.  

* ATASCII only, no graphics. Output is mostly for debugging purpose. 
* A weak priest with a moderate healing spell is fighting against three NPCs in a row.  
  The priest will heal himself if he has enough mana.  
  After he has one a fight, you can choose a random artifact that makes him stronger.  
  The first NPC is a dog, the second is a sturdy dog with higher defense and a DOT,
  the last NPC is an aggressive dog with a stronger attack.

### Artifacts

* Endless Sandbag - lowers the enemy's hit chance.  
  You reach into the bag, aim for the eyes of the terrible monster and throw..
* Steady Shield - blocks some of the incoming damage.  
  There may be better, but there sure a much worse..

### How to run the game

* Attach ``aba.atr`` as the first disk in Altirra.
* Boot, then:
  ```
  CWD DOS
  XBW130.DOS
  LOAD ABA.COM
  RUN
  ```
* You can also edit the code in the FastBasic editor:
  ```
  LOAD FB.com
  RUN
  [CTRL-W], then Load? D:TEST3.BAS [RETURN]
  ```

## License

Distributed under the New BSD License, see LICENSE.txt.

## Acknowledgments

Inspiration, documentation, code snippets, etc.
* [FastBasic](https://github.com/dmsc/fastbasic)
* [FastBasic Manual](https://github.com/dmsc/fastbasic/blob/master/manual.md)
* [Astronarch](https://store.steampowered.com/app/1234940/Astronarch/)
