# COŠTA DEL SOL

A sunset driving game in the browser: a pseudo-3D coast road that curves and
crests, a fork at the end of every stage, and a clock that only a checkpoint
can extend. Fifteen stages arranged as a pyramid, five endings. Everything is
in a single `index.html` — no libraries, no build step.

**[▶ Play it here](https://ulebule.github.io/costa-del-sol/)**

## Not a conversion

This is an original game written for this project. The car is my own red
convertible, not anyone's licensed sports car, and the three radio tunes are
melodies I wrote rather than arrangements of anybody else's. What it takes from
the 1986 coin-op school of the genre is the structure: branch at every
checkpoint, five stages deep, a different ending down each road.

## The roads

Stage one is the same for everybody. From there the road forks near every
checkpoint and the side you are on when the split ends decides where you go
next — five stages deep, fifteen roads in all, and five destinations at the
bottom of the pyramid: MARINA, CASTILLO, LAGUNA, MIRADOR and PUERTO. Each row
of the pyramid has its own scenery, from the coast at sunset through a valley,
a night road, dunes and finally the sierra.

Reaching a checkpoint adds time. Nothing else does.

## Controls

`←` `→` steer, `↑` accelerate, `↓` brake, `SPACE` shifts between the low and
high gear, `P` pauses. `M` toggles sound, `L` cycles the language and `N`
changes your name.

Low gear pulls harder and tops out early; high gear is slower off the mark and
much faster once it is running. Going off the tarmac scrubs your speed, and a
bend throws you outward the faster you take it.

**Touch** — no on-screen buttons. The left half of the screen steers: drag left
or right. The right half is the pedals: hold to accelerate, and slide the same
finger down to brake. The game is landscape, so on a phone held upright it asks
you to turn it sideways.

## Car radio

Three original chiptunes — SUNSET CRUISE, PALM HIGHWAY and NIGHT FERRY — chosen
before you set off, exactly as the genre demands. They are sequenced live in
WebAudio, so they cost nothing to download.

## Score board

Scores are shared online through Firebase, with a top-ten table on the title
and finish screens. With no connection the game keeps working and falls back to
scores stored in the browser.

## Languages

English, Slovenian, German, Italian and French, detected from the device and
switchable with `L` or the on-screen button.

## Install it

The game is a PWA: a browser will offer to add it to the home screen (on iOS,
Share → *Add to Home Screen*), and it then opens standalone. A service worker
caches the page, so after the first visit it runs with no connection at all.

## Licence

MIT
