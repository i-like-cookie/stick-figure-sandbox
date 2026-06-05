# 🖐️ Stick Figure Sandbox

A tiny chaos toy that runs entirely in your browser. You're the cursor; the world is full of
little stick figures who wander around on their own — until you start poking at them.

**[▶ Just open `index.html` in any browser.](index.html)** No install, no build step, no internet
needed. It's one self-contained file (all the graphics *and* sound are generated procedurally).

## Tools

| Tool | What it does |
|------|--------------|
| 🖐️ **Drag** | Grab a figure and *fling* it — it tumbles like a ragdoll, then dusts itself off and gets up. |
| 🖌️ **Paint** | Hold to draw colorful trails anywhere. Brush over a figure to **repaint** it. Pick a color from the palette. |
| 🔨 **Hammer** | Click to *BONK* — squashes a figure flat with stars and a screen-shake, then it pops back up dizzy and flees. |
| ⚔️ **Saber** | A glowing, humming blade trails your cursor. **Swipe through** a figure to slice it into falling pieces. |
| 🧺 **Food** | Drop snacks. Nearby figures wander over, munch, and bounce with little ❤️s. |
| 🏷️ **Name** | Click a figure to nickname it. Type, hit Enter — they'll either **love it** (😍 + ❤️, the tag sticks) or **dislike it** and grab an eraser to wipe it out (😖). It's random — and **bad language is always rejected** (🤢, scrubbed out, never shown). |
| ✏️ **Pencil** | Sketch a **weapon** anywhere — it drops to the ground for **The Chosen One 2.0** to grab and swing at the Dark Lord. |

## The twist: they fight back 🥊

While you're holding the **hammer** or the **saber**, the figures can **leap up and snatch it right
out of your cursor**. A thief then chases down the nearest figure and **bashes *them* with your own
weapon** — which can spark a whole brawl.

- 🛡️ **Defend it:** they can only reach so high. Lift your cursor toward the **top of the screen**
  and they'll leap and fall short (watch for the shield icon — that means you're safe).
- 🤜 **Get it back:** **click an armed figure** to yank your weapon back. Thieves also get bored and
  drop it on their own after a bit.

The population always tops itself back up, so the sandbox never empties out.

## Name them 🏷️

Give the little folks nicknames with the **Name** tool. Each one reacts in its own way —
some are flattered, some are picky and erase whatever you wrote. Try anything rude and they'll
recoil and scrub it out: the nickname box runs a leet-aware profanity filter (so `sh!t`, `a$$`,
`f4ck` and friends don't get through) that still lets innocent names like *Spica* or *Cocker* by.

## The Chosen Ones vs. The Dark Lord ⚔️

Three **special characters** roam the world — you'll spot them by their **open-circle heads** and
permanent name tags:

- 🖤 **The Chosen One** — **flies**, and fires **laser eyes** + **fire from his hands** when attacked.
- 🧡 **The Chosen One 2.0** — **flies**, **regenerates fast**, and fights with **drawn weapons** (his
  own, or the ones you sketch with the ✏️ Pencil).
- ❤️ **The Dark Lord** — the villain. He's **away most of the time and appears every ~2 minutes** to
  go on a **rampage**, charging The Chosen One. The heroes take to the **air** and blast/bash him until
  he's defeated, then he **vanishes** until the next attack. Heroes who fall **regenerate** and get back
  up (the black Chosen One takes a few seconds; the orange 2.0 bounces back almost instantly).

Between battles the two heroes drift around on lazy **joy-flights** — keep an eye on the skies.

They're **immune to your tools** — and if you try to attack one, or let the Dark Lord get to your
cursor during a rampage, he'll **catch and erase your cursor** 💀. To get it back, **switch to another
browser tab and come back**.

## Controls

Everything is mouse/touch driven. The toolbar across the top switches tools; 🔊 toggles sound and
🔄 resets the world.

---

Built with vanilla JavaScript and the Canvas 2D API — no libraries, no assets, no dependencies.
