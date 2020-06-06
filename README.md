# Wishbringer (for Docker)

From [Wikipedia](https://en.wikipedia.org/wiki/Wishbringer#Plot_and_gameplay): The player's character is a postal clerk in the small fishing village of Festeron. The cranky postmaster, Mr. Crisp, orders the player to deliver an important envelope to the proprietor of Ye Olde Magick Shoppe. The proprietor in question, a kindly old lady, then asks the player to rescue her cat from a mysterious sorceress known only as The Evil One. Stepping out of the store, the player finds that quaint Festeron has mysteriously been transformed into a more sinister town called Witchville. There are but a few hours to defeat The Evil One. Fortunately, the player soon finds the Wishbringer, a magical stone that can grant seven wishes if a suitable object is used in conjunction. To see the future, for example, the player must be wearing glasses and holding the stone. The seven wishes that can be granted by the stone are for advice, darkness, flight, foresight, freedom, luck, and rain. Each wish can only be used once per game, and requires that the player possess some related object.

## I just want to play the game!

Want to play Wishbringer? Easy-peasy. Just type the following:

`docker run -it clockworksoul/wishbringer`

## What if I want to save my games?

Still pretty easy. All you need to do it volume in a save directory as follows:

`docker run -it -v ~/saves/wishbringer:/save clockworksoul/wishbringer`

## Potential terminal issues

If you receive a terminal error, such as `Error opening terminal: rxvt-unicode-256color`, type the following and re-run:

```export TERM=xterm```

## History/Legal
The _Zork_ games (including _Wishbringer_) were created by the now-defunct [Infocom, Inc.](https://en.wikipedia.org/wiki/Infocom), the intellectual property of which has since been acquired by Activision. Much of Infocom's library was released for free some 20 years ago as part of a promotional campaign for the graphic adventure _Zork: Grand Inquisitor_.  It's unclear, however, whether these were intended to be permanently and perpetually free or whether this was something with a limited window. While Activision has had nothing to say on the subject, they done nothing to interfere with the numerous sites that have sprung up over the years that allow you to download the games directly or even play in your browser... so interpret that as you will.
