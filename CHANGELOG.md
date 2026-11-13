# 3DS changelog

What changed in Tougelike for Nintendo 3DS, newest first. Only changes to the game are listed. The
game's CHANGELOG screen shows these above the notes of the web game it is built on.

Found a bug or have an idea? Tell us on the game's page, [njlent.de/games/tougelike](https://njlent.de/games/tougelike/), which links the
Discord, or [open an issue](https://github.com/njlent/tougelike-3ds-pub/issues) on GitHub.

## 3DS 00.01.45
- The Circle Pad steers by how far you push it. A light push turns the car a little, and near the rim it is full lock. Any push was full lock before. The D-pad steers as it did, and STEERING RAMP in OPTIONS, GAME now shapes the D-pad only.
- The title screen and the CHANGELOG screen show where to send bug reports and ideas: njlent.de/games/tougelike, which links the Discord, and github.com/njlent/tougelike-3ds-pub.
- The game underneath is Tougelike 00.22.41, which added controllers to the web game. The Circle Pad steers like a controller's stick does there.

## 3DS 00.01.44
- tougelike.log on the SD card is shorter and easier to read. It starts with the game's version and your options, then lists the game's speed as a table with one row for every 600 frames. Each of those was one very long line before.
- The log notes it when you change an option that affects speed.

## 3DS 00.01.43
- On an Old 3DS or 2DS a landmark with trees and rocks planted around it cost a race up to a third of its frame rate for as long as it was in view. A second log from a real console showed it. The game now places those plants once, where it worked them out again in every frame.
- With DEBUG on, the menus run faster. Its figures change four times a second.

## 3DS 00.01.42
- An Old 3DS or 2DS runs a race about a tenth faster again, early in a run and late in a long one. Part of that comes from the second processor core, so leave SECOND CORE on in OPTIONS, VISUAL unless the game misbehaves.

## 3DS 00.01.41
- On an Old 3DS or 2DS the game dropped to 7 to 9 frames a second whenever a breakdown lay-by came up beside the road. That lasted about a quarter of a minute in a run and over half a minute on the title screen. A log from a real console showed it, and it is fixed.
- Races run about a tenth faster on an Old 3DS or 2DS, and the menus about a fifth.
- The speed lines in tougelike.log now say what the game was doing, count the slow frames they used to leave out and split the time by more parts.

## 3DS 00.01.40
- Late in a long run, cars could lose their bodies and drive on as wheels and lights. The game had filled its graphics memory with roadside landmarks it had long passed, so a car that arrived found no room for its body. It now frees what is no longer on screen.
- The speed lines in tougelike.log now say how much graphics memory is free and whether anything was left out for lack of it.

## 3DS 00.01.39
- OPTIONS, VISUAL, PARTICLES now sets how much the module effects draw. DYNAMIC draws every spark, flame and puff of smoke, STATIC about half of them, DISABLED the fewest. Before, DYNAMIC and STATIC looked the same on the 3DS.
- PARTICLES starts on STATIC, which runs a little faster in runs full of effects. A setting saved by an earlier version moves to STATIC once, and DISABLED stays.

## 3DS 00.01.38
- An Old 3DS or 2DS that cannot hold 30 frames a second no longer drops to a steady 20. It shows every frame as soon as it is ready. A real Old 3DS ran the last version at 20 early in a run, and the emulator at that console's speed runs this one at 24.
- The installed version never used the second processor core on an Old 3DS or 2DS, because the system refused the share of it the game asked for. It gets that share now.
- Late in a run the game stuttered twice a second while it rebuilt the module list on the bottom screen. It now rebuilds the list only when it changes.
- Below 30 frames a second the gauges on the top screen are redrawn every other frame, which leaves more time for the race.
- The speed lines in tougelike.log now say which part of the game the time went to.

## 3DS 00.01.37
- The speed-ups in this version are still experimental. So far they have run in the emulator and passed one test on a real console. If the picture looks wrong or the game stutters, turn OPTIONS, VISUAL, SECOND CORE off or set FRAME RATE to 30, and report what you saw.
- A New 3DS now runs the game at 60 frames a second where it keeps up, and holds a steady 30 where it does not. OPTIONS, VISUAL, FRAME RATE set to 30 keeps it at 30 all the time.
- An Old 3DS or 2DS holds 30 frames a second through much more of a run. In the emulator at their speed, a late run went from 19 to 27 frames a second.
- Driving looks smoother at the same frame rate. The game's clock used to follow how long each frame took to work out. It now follows the pictures on the screen.
- The scenery is rebuilt on the console's second processor core. OPTIONS, VISUAL, SECOND CORE turns that off.
- DEBUG now shows the frame rate, the CPU and GPU time of a frame and the free memory.
- The game writes a line about its speed to tougelike.log on the SD card every 600 frames.

## 3DS 00.01.36
- HOW TO PLAY no longer cuts its pages off. Every picture on the top screen scrolls to its end, the route map no longer covers the heat chart, and long text on the bottom screen scrolls too.
- HOW TO PLAY now shows the rival tag key with its icons, the set bonuses and what each heat level adds, as the web game does.

## 3DS 00.01.35
- The HOME Menu version crashed right at launch on a New 3DS or New 2DS. It now starts.

## 3DS 00.01.34
- Quitting the game on a real 3DS showed a crash screen and shut the console down. It now goes back to the HOME Menu or the Homebrew Launcher.

## 3DS 00.01.25
- The game can now be installed to the HOME Menu, with its own icon, banner and jingle.
- The intro no longer plays at every start. Turn it back on under OPTIONS, GAME, INTRO.

## 3DS 00.01.24
- The game now shows its own icon, name and description in the Homebrew Launcher and in emulators.

## 3DS 00.01.23
- A SAVING mark now shows in the corner while the 3DS writes your save, so the short pause at drafts, routes and results no longer looks like a freeze.

## 3DS 00.01.22
- FIREWORKS NIGHT and CHAIN REACTION explosions, lightning from STORM CHASER and TYPHOON, and DRAGON PIPES and AFTERFIRE flames all lag less on the 3DS.

## 3DS 00.01.21
- Runs with DRAGON PIPES, AFTERFIRE or CHAIN REACTION lag much less on the 3DS when their flames and shockwaves fill the screen.

## 3DS 00.01.20
- Drifting with lots of tyre smoke runs smoother on the 3DS.

## 3DS 00.01.19
- Races with many cars on the road run a little smoother on the 3DS.

## 3DS 00.01.18
- The 3DS port now has its own version number, shown on the title screen beside the game's.
- The changelog screen lists the 3DS notes first, then the game's.

## 3DS 00.01.17
- Bosses and rivals no longer turn invisible on the 3DS late in a run.
- The 3DS no longer freezes for seconds when it saves a long-played game or when a landmark comes into view.
- Busy late-game runs with many modules run more smoothly on the 3DS.

## 3DS 00.01.16
- Races on the Old 3DS and 2DS now aim for 30 fps, and only hold a steady 20 when the console cannot keep up.
- Music and rival radio start without a stutter on the 3DS.

## 3DS 00.01.15
- Races on the Old 3DS run much more smoothly, especially around reservoirs and tunnels.
- Boost streaks, achievement pop-ups and scanlines no longer flicker on the 3DS.

## 3DS 00.01.14
- Races on the 3DS run a little smoother again, with no change to how the game looks.

## 3DS 00.01.13
- Races on the 3DS run smoother on slower consoles, most of all in heavy traffic.

## 3DS 00.01.12
- 3DS menus and between-race screens now respond to touch as well as buttons. Driving stays on the buttons.

## 3DS 00.01.11
- On the 3DS, car headlights and tail lights glow properly again, and regional windows light up.

## 3DS 00.01.10
- The 3DS test build shows a real loading bar and starts about four times faster on slower consoles.

## 3DS 00.01.09
- The 3DS test build now has sound: music, engines, effects and radios, a soundtrack player and the intro film.
- On the 3DS, rain darkens the road and boosting draws speed streaks.

## 3DS 00.01.08
- The 3DS test build now has the full garage, Mountain Atlas, Pacts, Statistics, Achievements, How to Play, Options and save tools, all on buttons.

## 3DS 00.01.07
- The 3DS test build runs about twice as fast, with far fewer stutters. Slower consoles now get a steady 20 fps with a slightly shorter draw distance.

## 3DS 00.01.06
- The 3DS test build shows the route map when a run starts, no longer leaves stray terrain over the road at hairpins, and runs a little faster.

## 3DS 00.01.05
- The 3DS test build no longer slows to a crawl in tunnels and near the reservoir, and long runs no longer run out of memory.

## 3DS 00.01.04
- The 3DS test build now plays a full run from the title screen, with the route map, drafts, part offers, pause, results and a garage. Progress saves to the SD card.

## 3DS 00.01.03
- The 3DS test build now shows a loading screen instead of staying black while it starts.

## 3DS 00.01.02
- The 3DS test build now shows the race display across both screens and plays on buttons only. Cars, trees, signs and the night sky draw correctly too. The browser game is unchanged.

## 3DS 00.01.01
- Work has started on a Nintendo 3DS version. This update only adds the tools to build and test it, so the browser game plays the same.
