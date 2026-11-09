## Brought up on C++, mainly **C** dev.

Right now building [SDSH](https://github.com/fevazy/sdsh) -- deterministic object
storage and update scheduler for game/physics engines/simulations. MVP is just
around the corner.

## Taskboard:
- [SDSH](https://github.com/Fevazy/SDSH) - MVP with stable API. Optimizations,
  internal refactoring, rewindable checkpoints - all later. There's a chance
  that multithreading will apear early in first versions.

- [OKNO](https://github.com/Fevazy/okno). Just improve to close the gestalt

- Rose IR (IR that will be used for Dysp as very crossplatform solution). Weakly
  documented yet, but will be simple enough to compile from.  Tooling also would
  include Rose -&gt; LLVM IR translation. The difference between LLVM and Rose
  will be in simplicity and customizability of second one.  LLVM IR is, of
  course, very good, but using it as first backend will lock-in the compiler to
  it. Think about Rose as of MIR.

- [Dysp-zg](https://github.com/dysp-lang/dysp-zg). MVP only (C-like subset),
  then selfhost.

[aRISCtotle](https://github.com/fevazy/arisctotle) is dead. Not at all, but
close to. I may return it to life later, but after PL and definitely after SDSH.

Feel free to email me (fevazy@yandex.ru), We may chat or talk about sth
serious, design a project or help each other - as you wish.

Have a nice day ig
