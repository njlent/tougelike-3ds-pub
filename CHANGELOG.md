# 3DS changelog

What changed in Tougelike for Nintendo 3DS, newest first. Only changes to the game are listed. The
game's CHANGELOG screen shows these above the notes of the web game it is built on.

Found a bug or have an idea? Tell us on the game's page, [njlent.de/games/tougelike](https://njlent.de/games/tougelike/), which links the
Discord, or [open an issue](https://github.com/njlent/tougelike-3ds-pub/issues) on GitHub.

## 3DS 00.01.69
- A busy race could freeze the whole console, and only the power button got you out. A rare mix of what was on screen stopped the 3DS's graphics chip. A n3DS has since driven the same busy late-game descent 20 times in a row without a freeze.
- A few kilometres into a run, road and rock textures at the sides and bottom of the screen no longer smear into streaks.

## 3DS 00.01.68
- The title screen and the CHANGELOG screen now give tougelike.com for bug reports and ideas, in place of njlent.de/games/tougelike.

## 3DS 00.01.67
- Drafts, route choices and part offers show your CONDITION at the top right, beside your chips, so you can see how much a repair would help before you pick.
- SPOOL's multiplier is boost blue, as in the web game.
- The combo's timer bar sits clear below its number instead of touching it, and the HAIRPIN warning under it moved down to make room.

## 3DS 00.01.66
- Leaving the garage with a long-played save could run out of memory. When memory is short, the game now clears it up before it saves, which on an o3DS adds about half a second to the save.

## 3DS 00.01.65
- SMOOTH FRAMES now starts off on a n3DS/n2DS, where its extra pictures cost the game more steps than they add pictures. A choice you make in OPTIONS, VISUAL is kept, and an o3DS/o2DS keeps it on unless you had turned it off.
- The CIA's version, as FBI shows it, is now 2.1.0. The old numbering stopped at 1.63.

## 3DS 00.01.63
- Saving stops the game for much less time with a long-played save. At o3DS speed, getting a save of about 250 runs ready to write went from 1.2 seconds to under 0.4, every time the game saves. Writing it to the SD card takes as long as before.
- The garage menu keeps responding while it brings in the car you stopped on. At o3DS speed its slowest frames went from 0.3 seconds to about 0.1, and the car arrives just as soon. Loading behind prompts and the results screen works the same way now.
- A new draft, route or part offer shows up before the game cleans up memory, not after. The cleanup comes right after it appears, while the prompt usually doesn't take a pick yet.
- tougelike.log's upkeep line counts the saves and how long the longest took to get ready and to write. A test build installed as a CIA also times another way of getting memory ready for the graphics chip.

## 3DS 00.01.62
- An o3DS's log showed the game stopping for about a fifth of a second every 600 frames, while it wrote tougelike.log to the SD card. The log now has a writer of its own, and the game no longer waits for it.
- Drafts, routes and part offers clean up memory much less often. A cleanup takes about 0.4 seconds at o3DS speed and holds up the cursor, and they used to do one every time they opened or changed.
- tougelike.log adds a line under each row with the free memory, the cleanups and the log's own writing.

## 3DS 00.01.61
- Scrolling the garage's car list no longer loads every car you pass. The top screen brings in the car the cursor stops on, or right away when you press A or change tab.
- The garage saves once, when you leave it, instead of after every upgrade, perk or paint change. With a long-played save each of those saves froze the garage for 1.7 seconds in an emulator running at o3DS speed.
- With a long-played save, OPTIONS, SAVE could run out of memory and stop the game, on opening or on EXPORT TO SD and IMPORT FROM SD. It now needs much less memory, and the screen says what it is doing while it works.

## 3DS 00.01.60
- On an o3DS each step of the game should take a little less time. How much it saves on a real console is not measured yet.
- BENCHMARK's census, and the measurements a test build takes at start, write more figures on copying and flushing memory to tougelike.log.

## 3DS 00.01.59
- Headlights and lamps cost the graphics chip less. A corner outside a light's beam or reach now skips that light's sums, which in a late race is four in five of them, and the picture stays exactly the same.
- BENCHMARK adds a short census after its timed run. It draws pictures with one part of the work left out at a time, so they look wrong for a few seconds, and writes what each part costs to tougelike.log.

## 3DS 00.01.58
- The test drive list, which the web game's secret code opens on the title screen, now starts with BENCHMARK. It drives the same late-game descent every time and shows how fast your console ran it, on screen and in tougelike.log, and your save stays as it was.
- Holding SELECT while the game starts measures the console's graphics chip and second core and writes the figures to tougelike.log.

## 3DS 00.01.57
- Corners no longer snap to the pixel grid unless you turn on OPTIONS, VISUAL, VERTEX SNAP, so edges hold still instead of wobbling as things move. Without the snap each picture gives the graphics chip about a tenth less work.
- The CIA carries its version, 1.57.0, where every CIA since 00.01.25 said 1.0.0.

## 3DS 00.01.56
- The game no longer freezes on a 3DS once loading reaches 100%, as it did since 00.01.54. Its 3D graphics broke a rule of the console's graphics chip that emulators do not check, and keeping to it gives the chip about a twentieth more work for each picture.
- On a real Old 3DS a race shows about 35 fps from 20 to 22 steps of the game, where 00.01.45 showed 15 to 17.

## 3DS 00.01.55
- On slower devices such as phones, emulators like Azahar no longer run the game in slow motion with the sound breaking up. In 00.01.54 they had to work out much of each picture on the processor instead of the graphics card.

## 3DS 00.01.54
- The picture moves much more smoothly. While the game works out its next step, the console draws the last one again from where the camera will be by then, so the screen shows more pictures than the game takes steps. OPTIONS, VISUAL, SMOOTH FRAMES turns this off.
- In the emulator each step of the game takes less time than in 00.01.53, late in a long run about two fifths less. The game's script runs faster, and the markers over rivals, the sprites and the HUD cost less.
- By the emulator's count each picture gives the graphics chip about a sixth less work, with nothing on the screen changed.
- Cars that are small on the screen are drawn with fewer triangles. Up close a car looks as it did, and its lamps stay whole at any distance.
- Your headlights now light the trees, rails and other cars as one wide beam. On the road itself you still see both.
- Guard rails, posts and tree trunks no longer draw the faces nobody sees.

## 3DS 00.01.53
- A New 3DS is no longer held at 30 frames a second where it cannot reach 60. Each frame is shown as soon as it is ready, so the game runs at whatever the console manages above 30. OPTIONS, VISUAL, FRAME RATE 30 still gives the even 30.

## 3DS 00.01.52
- On a New 3DS a race no longer changes its frame rate every half minute. The game stepped up from 30 whenever a moment of light frames suggested more was in reach, and stepped back a few seconds later. It now waits for a longer stretch of them, and each try that fails makes the next one wait twice as long.
- `tougelike.log` no longer counts time in the HOME menu or asleep as loading.

## 3DS 00.01.51
- A race no longer hitches about once a second on an Old 3DS or 2DS. The signs, lamps and posts beside the road were all placed again in a single frame each time. What decides where they stand is now kept until they move on, and late in a long run fewer than half as many frames take over a tenth of a second.
- A car model that loads in the middle of a race holds the game for less time. Its file is read in a third of the time it took.
- A frame takes slightly less time to draw.

## 3DS 00.01.50
- Late in a run an Old 3DS or 2DS no longer stops for a tenth of a second every three seconds. The bottom screen worked the whole run out again each time, and that took longer with every part fitted.
- A car model that has to load in the middle of a race no longer freezes it. The load is spread over a few seconds of driving, and a third car of a kind is made ready the same way.
- Tunnels and the reservoir no longer hitch once a second while you drive past them.
- A New 3DS can now show more than 30 frames a second where it cannot hold 60. FRAME RATE 30 in the options keeps the even 30.

## 3DS 00.01.49
- The freeze as a landmark comes up beside the road is gone. Placing a shrine's or a lay-by's trees and bushes held an Old 3DS or 2DS for a quarter to three quarters of a second each time. The console's second core now places them while you drive, and they stand exactly where they did.
- With SECOND CORE off in the options the same moment takes about a twentieth of a second.
- A car of a kind not seen yet in the run, and the cars parked at a landmark, no longer hold an Old 3DS or 2DS for up to a tenth of a second the first time they are drawn.

## 3DS 00.01.48
- Less stutter in a race on an Old 3DS or 2DS. A new car coming onto the road held the game for over a tenth of a second, and one whose model had to be loaded first for over a second. Cars are now made ready when their model loads, and loading one is much shorter. The game also starts about seven seconds sooner there.
- The cars are drawn with about a third fewer triangles and look the same, in the garage too. The valley beyond the road is drawn only where you can see it. Together a race has about a quarter less to draw, which takes work off the console's graphics chip.
- Tunnels and the landmarks beside the road cost less while they are near, and drifting costs a little less again.

## 3DS 00.01.47
- Drifting costs less. On an Old 3DS or 2DS the skid marks behind the car took more of every frame the longer a drift went on. A race with a lot of drifting runs about a twentieth faster.
- The title screen and the garage run faster on an Old 3DS or 2DS, by about a tenth of the work in each frame. They also no longer slow down, for minutes at times, while a drifting rival waits out of sight for a bend to slide through.
- tougelike.log on the SD card now says where the longest frames went, so the next log can explain the stutter that this one could only count.

## 3DS 00.01.46
- The garage flickered. Stretches of the guard rail with its posts, the striped barriers, and trees and bushes beside the road dropped out of the picture and snapped back about once a second, and whatever stands behind them showed through. It showed most on an Old 3DS or 2DS. They stay in the picture now.
- The road and the ground at the far end of the garage's view, in the top left corner of the screen, were missing. They are drawn now.

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
