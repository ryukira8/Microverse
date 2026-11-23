# Microverse: Containment Systems

A browser game about plastic-eating bacteria, made for children aged 8–12 to
play with a parent.

**▶ Play it: https://USERNAME.github.io/microverse-containment/**

No installation, no account, works on a phone. Replace `USERNAME` above with
your GitHub username once Pages is enabled.

---

## What it teaches

You drive a small cleaning drone inside a recycling facility. You collect
plastic from the water, sort it, and treat it in a sealed tank where bacteria
break it down.

Three ideas are built into the rules rather than explained in pop-ups:

**Not all plastics are the same.** The enzyme PETase works on PET — drinks
bottles — and does nothing to polyethylene carrier bags or polypropylene pots.
Those have to be diverted. Sorting is a mechanic because specificity is the
lesson.

**Conditions matter.** *Ideonella sakaiensis* grows between 15 °C and 42 °C,
best around 30–37 °C. The tank has three settings. At 30 °C it works; at 10 °C
and 45 °C it visibly stalls. Engineered enzymes such as FAST-PETase are
designed to run warmer, and the game says so.

**It is slow, and it happens in a tank.** Real PET takes weeks to break down
under good conditions. The game is sped up and states this on screen. Bacteria
are never released into open water — the drone removes the plastic physically
and the bacteria stay sealed inside the reactor. This is deliberate: "bacteria
will eat the plastic in the ocean" is the misconception the game exists to
avoid creating.

## Science and sources

[References and evidence registry](references.html) — the six primary papers
behind the biology, plus a table separating what is established science from
what is a game rule, with the simplifications stated.

The organism has since been reclassified as *Pseudideonella sakaiensis*. The
game keeps the name *Ideonella sakaiensis* because that is the name used
throughout the cited literature.

Processing rates, charge, damage and the day counter are illustrative game
values and are not laboratory measurements.

## Install it like an app

From the link above, add it to your home screen and it runs full screen with
its own icon, and keeps working with no internet.

- **Android / Chrome:** menu (⋮) → *Add to Home screen* → *Install*
- **iPhone / iPad, Safari:** Share → *Add to Home Screen*
- **Desktop Chrome or Edge:** the install icon at the right of the address bar

It is a progressive web app, not a Play Store or App Store download. After the
first visit the whole game is cached, so it opens offline afterwards.

## Running it without installing

Open `index.html` in any modern browser. It is one self-contained file with no
build step, no dependencies and no network requirement, so it also runs offline
from a USB stick or a downloaded copy.

Built with vanilla JavaScript, Canvas 2D, the Web Audio API and Pointer Events.
No game engine and no external libraries.

## How it was made

This game was developed with AI assistance. See [AI_USE.md](AI_USE.md) for the
full declaration of which tools were used and what each contributor did.

## Status

Coursework for BABS3 Science Communication, University of York.

Not yet tested with children, which is the main outstanding evaluation step.

No licence is granted for reuse; this is submitted academic work. The
background artwork is AI-generated illustration, not scientific imagery.
