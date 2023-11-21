+++
title = 'Projects'
date = 2023-11-21T10:42:09-05:00
showToc = true
draft = false
+++

## Pocaml: poor man's OCaml

Source code: <https://github.com/Pocaml/Pocaml>.

Developed with Yunlan Li, Yiming Fang and Peter Choi.

Pocaml is a compiler written in OCaml for an OCaml-like functional language, with features such as polymorphic let-in bindings, lambda functions, pattern matching and a small standard library.

Pocaml was our final project in Fall 2021 for Columbia's [Programming Languages and Translators](http://www.cs.columbia.edu/~sedwards/classes/2021/4115-fall/index.html) course. You can find documents like the [Final Report](https://www.cs.columbia.edu/~sedwards/classes/2021/4115-fall/reports/Pocaml.pdf) on the linked course page from Prof. Stephen Edwards website (where you may also find that Pocaml is marked with a star, a.k.a one of his favorites!)

![Pocaml pipeline](/files/pocaml_pipeline.png)

## Pac-Man clone on custom FPGA graphics

Source code: <https://github.com/leoqiao18/pacman>.

Demo play on Prof. Stephen Edwards's YouTube channel: <https://www.youtube.com/watch?v=RxChYTDxNN8&ab_channel=StephenEdwards>.

Developed with Jerry Lin.

The Pac-Man clone consists of 3 parts: hardware, software and driver.
On the hardware side, we used an FPGA to create a general purpose hardware-accelerated 2-D graphics API using sprite-and-tile graphics.
For the software, the game logic, sprite graphics and game AI were implemented in C and runs on Linux. It contained all game logic as well as the driver program for USB SNES controllers.
The software and hardware are then connected by a driver program that sends data and to the byte-addressable VRAM in the hardware.

The project was our final project in Spring 2022 for Columbia's [Embedded System Design](https://www.cs.columbia.edu/~sedwards/classes/2022/4840-spring/index.html) course. You can find documents like the [Final Report](https://www.cs.columbia.edu/~sedwards/classes/2022/4840-spring/reports/MazeGame-report.pdf) on the linked course page from Prof. Stephen Edwards website.

![Pac-Man clone system diagram](/files/pacman_system_diagram.png)

## PM: parallelized minimax chess engine in Haskell

Source code: <https://github.com/leoqiao18/pm>.

Developed with Yuanyuting Wang.

Written in Haskell, PM is a minimax Chess Engine implemented with a combination of parallelization strategies and alpha-beta pruning.
If you don't think it works well, this name refers to Parallel Minimax;
otherwise, please call it Parallel Master (inspired by Grandmaster (GM) in the international chess ranking system).

The project was our final project in Fall 2021 for Columbia's [Parallel Functional Programming](https://www.cs.columbia.edu/~sedwards/classes/2021/4995-fall/index.html) course. You can find documents like the [Final Report](https://www.cs.columbia.edu/~sedwards/classes/2021/4995-fall/reports/PM.pdf) on the linked course page from Prof. Stephen Edwards website.

## Spoof: an IOS stickers app

IOS App Store: <https://apps.apple.com/us/app/spoof-make-share-stickers/id1544689978>

Spoof is an IOS app that Harvey Wu and I developed to create, send, and share iMessage stickers.
You can:
- instantly crop out people - and even pets! - using our AI-powered crop tool;
- caption your stickers with text;
- easily send your favorite stickers to your friends in iMessage;
- share any of your stickers directly through our iMessage extension.

![Spoof IOS app](/files/spoof.png)