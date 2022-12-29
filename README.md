## [MangoIV.](https://blog.mangoiv.com)

[![MangoIV's GitHub stats](https://github-readme-stats.vercel.app/api?username=MangoIV&show_icons=true)](https://github.com/anuraghazra/github-readme-stats)

## What I'm doing
- I study computer science at the university of Leipzig
- I work for MLabs as Haskell and Nix developer 
- Currently I'm interested in 
  - `singletons` (and generally all useless typelevel shenanigans) in Haskell
  - proving with Haskell 
  - Effectsystems 
  - compiling to categories
  - agda
- keyboards and PCBs such as the [DracuLad](https://github.com/MangoIV/dracuLad) and the 
[Le Chiffre Bluetooth drop-in replacement PCB](https://github.com/MangoIV/le_chiff_ble)

## Projects
- [a bunch of (mostly) haskell-related gists](https://paste.sr.ht/~mangoiv)
- [DracuLad](https://github.com/MangoIV/dracuLad)
- [Le Chiffre Bluetooth drop-in replacement PCB](https://github.com/MangoIV/le_chiff_ble)
- [Le Chiffre BLE firmware](https://github.com/MangoIV/le_chiff_ble_config)
- [My fork of the qmk firmware](https://github.com/MangoIV/qmk_firmware)
- [Pinsel, a Sweep-like keyboard based around the nrF Seeduino xiao](https://github.com/MangoIV/pinsel)
- [My a dux dux config](https://github.com/MangoIV/zmk-config-a_dux_dux)
- [My corneish-zen config](https://github.com/MangoIV/zmk-config-Corne-ish-Zen)
- [A macropad you can gift someone for christmas](https://github.com/MangoIV/christmas_board)
- [My fork of the Adafruit nrF bootloader](https://github.com/MangoIV/Adafruit_nRF52_Bootloader/tree/master)
- [DracuLady, a bluetooth split board with integrated MCU ](https://github.com/MangoIV/dracuLady)(I think at some point 
  I accidentally lost all the files, gg. got working protos tho)
- [My humminbird config](https://github.com/MangoIV/hummingbird-zmk-config)
- [Cheap boi, my first self-designed keyboard with an ortho layout](https://github.com/MangoIV/cheap_boi)
- Find other projects, such as my NixOS config over at [GitLab](https://gitlab.com/mangoiv)

## My sourcehut 

Due to recent events wrt GitHub, I have decided to leave it for my personal projects that are *not keyboard related* (most of the
keyboard related traffic still happens here). For a summary of why this is the case, please refer to [this post by the software freedom conservancy](https://sfconservancy.org/GiveUpGitHub/).

I have moved to [sourcehut](https://sr.ht/) and I can really recommend you to have a look. Other alternatives to GitHub include 
[codeberg](https://codeberg.org/) or [gitlab](https://gitlab.com/). 

### Haskell 

#### Repositories

- [A heterogeneous rose tree](https://git.sr.ht/~mangoiv/htree) (see for how to create a backtracking search on the typelevel 
  without having to backtrack via instance resolution)
- [Dependent If in Haskell](https://git.sr.ht/~mangoiv/dependent-if) (to be used with [rebindable syntax](https://ghc.gitlab.haskell.org/ghc/doc/users_guide/exts/rebindable_syntax.html?highlight=rebindablesyntax#extension-RebindableSyntax))

#### Snippets

- [Compose `n` functors](https://paste.sr.ht/~mangoiv/e2c2ca16f990754807893ce7f37e4a92e6ab556a) (see for the tradeoff between 
  creating evidence via a `GADT` and using a `newtype`)
- [stupid poc OOP experiment](https://paste.sr.ht/~mangoiv/a9e82c2769dbb5894d7ef6c884c3476e6d5a4714) [usecase 1](https://paste.sr.ht/~mangoiv/01671ce2daa3af85633a23fb3123db8753190804) [usecase 2](https://paste.sr.ht/~mangoiv/d96c842f01163c525c94dfb9ef6b24a2f1ea3934) (adaptation of the famous [comonad blogpost by Gabriela Gonzalez](https://www.haskellforall.com/2013/02/you-could-have-invented-comonads.html) with modern language features (`-XOverloadedRecordDot`))
- [most overengineered implementation of the `findS` algorithm, ever](https://paste.sr.ht/~mangoiv/73fe3895d686326d48ca7e84a5ff870308a691c1) (see for how to use `NP` from [`sop-core`](https://flora.pm/packages/@hackage/sop-core) 
  as a heterogenous list with a non-trivial functor and for how to sensibly use the god function [`hcliftA2`](https://hackage.haskell.org/package/sop-core-0.5.0.2/docs/Data-SOP.html#v:hcliftA2))

### Nix 

#### Repositories

- [My NixOS dotfiles](https://git.sr.ht/~mangoiv/dotfiles)
- [A batteries-included flake for a ghc devShell](https://git.sr.ht/~mangoiv/adhoc-ghc)

#### Snippets

- [function to flatten attributesets with a seperator](https://paste.sr.ht/~mangoiv/4117d7c81dbeec7afa2eb48fbb5a517271fde26e) (this 
  is especially useful for flake outputs which are not allowed to be nested)
