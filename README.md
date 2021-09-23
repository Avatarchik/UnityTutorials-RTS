# [Unity/C#] Making a RTS game

**Mina Pêcheux - Since March 2021**

![thumbnail](imgs/thumbnail.jpg)

This repository contains the code for my on-going series of tutorials on how to make a real-time strategy (RTS) game in the well-known game engine Unity! Throughout this series of tutorials, I explore C# scripting for games, GUI building, event systems, behavior trees, sound optimization...

![demo](imgs/demo.gif)

You can find the list of all tutorials [on Medium](https://medium.com/c-sharp-progarmming/making-an-rts-game-in-unity-91a8a0720edc), or right below:

<ul class=""><li>Tutorial #1: <a rel="noopener follow" href="https://medium.com/codex/making-a-rts-game-1-placing-buildings-unity-c-c53c7180b630"><strong>Placing buildings</strong></a></li>

<li>Tutorial #2: <a rel="noopener follow" href="https://medium.com/codex/making-a-rts-game-2-adding-a-very-basic-ui-unity-c-8420480afda0"><strong>Adding a very basic UI</strong></a></li>

<li>Tutorial #3: <a rel="noopener follow" href="https://medium.com/codex/making-a-rts-game-3-setting-up-in-game-resources-unity-c-92355714b2d7"><strong>Setting up in-game resources</strong></a></li>

<li>Interlude #1: <a rel="noopener follow" href="https://medium.com/codex/rts-interlude-1-introducing-an-event-system-unity-c-14c121fb8ed"><strong>Introducing an event system</strong></a></li>

<li>Tutorial #4: <a rel="noopener follow" href="https://medium.com/codex/making-a-rts-game-4-selecting-units-unity-c-1c823b6823a5"><strong>Selecting units</strong></a></li>

<li>Tutorial #5: <a rel="noopener follow" href="https://medium.com/codex/making-a-rts-game-5-transforming-our-data-into-scriptable-objects-unity-c-d7d28a72a20"><strong>Transforming our data into Scriptable Objects</strong></a></li>

<li>Tutorial #6: <a rel="noopener follow" href="https://medium.com/codex/making-a-rts-game-6-improving-the-ui-unity-c-502a018980c4"><strong>Improving the UI</strong></a></li>

<li>Tutorial #7: <a rel="noopener follow" href="https://medium.com/codex/making-a-rts-game-7-polymorphism-take-2-unity-c-fe84d9d87844"><strong>Polymorphism, take 2!</strong></a></li>

<li>Tutorial #8: <a rel="noopener follow" href="https://medium.com/codex/making-a-rts-game-8-boosting-our-selection-feature-unity-c-8552bffd2f8b"><strong>Boosting our selection feature</strong></a></li>

<li>Tutorial #9: <a rel="noopener follow" href="https://medium.com/codex/making-a-rts-game-9-implementing-character-units-and-skills-unity-c-d89b1a3e57b7"><strong>Implementing character units and skills</strong></a></li>

<li>Tutorial #10: <a rel="noopener follow" href="https://medium.com/codex/making-a-rts-game-10-moving-the-camera-unity-c-5a2c2a6a9be2"><strong>Moving the camera</strong></a></li>

<li>Interlude #2: <a rel="noopener follow" href="https://medium.com/codex/rts-interlude-2-refactoring-the-event-system-unity-c-b52a2e3feae"><strong>Refactoring the event system</strong></a></li>

<li>Tutorial #11: <a rel="noopener follow" href="https://medium.com/codex/making-a-rts-game-11-adding-a-day-and-night-cycle-unity-c-ae0cc17a0350"><strong>Adding a day-and-night cycle</strong></a></li>

<li>Tutorial #12: <a rel="noopener follow" href="https://medium.com/codex/making-a-rts-game-12-moving-character-units-unity-c-9119ba4601d1"><strong>Moving Character Units</strong></a></li>

<li>Tutorial #13: <a rel="noopener follow" href="https://medium.com/codex/making-a-rts-game-13-adding-a-minimap-and-fog-of-war-1-3-unity-c-1a7e42bbf9cb"><strong>Adding a minimap and fog of war 1/3</strong></a></li>

<li>Tutorial #14: <a rel="noopener follow" href="https://medium.com/codex/making-a-rts-game-14-adding-a-minimap-and-fog-of-war-2-3-unity-c-bcb4e8da7593"><strong>Adding a minimap and fog of war 2/3</strong></a></li>

<li>Tutorial #15: <a href="https://mina-pecheux.medium.com/making-a-rts-game-15-adding-a-minimap-and-fog-of-war-3-3-unity-c-a89f3548275b" rel="noopener follow"><strong>Adding a minimap and fog of war 3/3</strong></a></li>

<li>Tutorial #16: <a href="https://mina-pecheux.medium.com/making-a-rts-game-16-introducing-a-sound-system-1-2-unity-c-c3153902161e" rel="noopener follow"><strong>Introducing a sound system 1/2</strong></a></li>

<li>Tutorial #17: <a href="https://mina-pecheux.medium.com/making-a-rts-game-17-introducing-a-sound-system-2-2-unity-c-bb72a51c56c1" rel="noopener follow"><strong>Introducing a sound system 2/2</strong></a></li>

<li>Tutorial #18: <a href="https://mina-pecheux.medium.com/making-a-rts-game-18-preparing-our-game-parameters-unity-c-96d3f598ecd5" rel="noopener follow"><strong>Preparing our game parameters</strong></a></li>

<li>Tutorial #19: <a href="https://mina-pecheux.medium.com/making-a-rts-game-19-displaying-our-in-game-settings-unity-c-f551e5a93032" rel="noopener follow"><strong>Displaying our in-game settings!</strong></a></li>

<li>Tutorial #20: <a href="https://mina-pecheux.medium.com/making-a-rts-game-20-saving-the-players-data-properly-unity-c-1c7f5af29329" rel="noopener follow"><strong>Saving the player’s data properly</strong></a></li>

<li>Tutorial #21: <a href="https://mina-pecheux.medium.com/making-a-rts-game-21-adding-players-and-unit-ownership-unity-c-43144a8375f" rel="noopener follow"><strong>Adding players and unit ownership</strong></a></li>

<li>Tutorial #22: <a href="https://mina-pecheux.medium.com/making-a-rts-game-22-producing-some-resources-with-our-buildings-unity-c-5dde5253f329" rel="noopener follow"><strong>Producing some resources with our buildings</strong></a></li>

<li>Tutorial #23: <a href="https://mina-pecheux.medium.com/making-a-rts-game-23-implementing-behaviour-trees-for-our-units-1-3-unity-c-1a61840058a6" rel="noopener follow"><strong>Implementing behaviour trees for our units 1/3</strong></a></li>

<li>Tutorial #24: <a href="https://mina-pecheux.medium.com/making-a-rts-game-24-implementing-behaviour-trees-for-our-units-2-3-unity-c-17f14cc3c580" rel="noopener follow"><strong>Implementing behaviour trees for our units 2/3</strong></a></li>

<li>Tutorial #25: <a href="https://mina-pecheux.medium.com/making-a-rts-game-25-implementing-behaviour-trees-for-our-units-3-3-unity-c-a132340bc71c" rel="noopener follow"><strong>Implementing behaviour trees for our units 3/3</strong></a></li>

<li>Tutorial #26: <a href="https://mina-pecheux.medium.com/making-a-rts-game-26-levelling-up-our-units-1-2-unity-c-22d3a25cc41" rel="noopener follow"><strong>Levelling up our units! 1/2</strong></a></li>

<li>Tutorial #27: <a href="https://mina-pecheux.medium.com/making-a-rts-game-27-levelling-up-our-units-2-2-unity-c-33e6959889b6" rel="noopener follow"><strong>Levelling up our units! 2/2</strong></a></li>

<li>Tutorial #28: <a href="https://mina-pecheux.medium.com/making-a-rts-game-28-adding-some-shortcuts-unity-c-c437b635ffca" rel="noopener follow"><strong>Adding some shortcuts</strong></a></li>

<li>Tutorial #29: <a href="https://mina-pecheux.medium.com/making-a-rts-game-29-improving-our-players-system-unity-c-328dfc9b818" rel="noopener follow"><strong>Improving our players system</strong></a></li>

</ul>

## Known issues

### About installing / upgrading

The project was written in Unity 2019.3. This implies that, when loading it up with more recent versions of Unity, you'll need to auto-upgrade the project. This usually goes without a hitch, but there is for now 1 bug that has been spotted by the followers and I:

- **FOV shader bug** (thanks to @Oarcinae): upgrading to **Unity 2019.4** might lead to unexpected behaviour for the FOV shader (because of pipeline render defaults changes); to fix the issue, you can try modifying the `AlphaProjection.shader` and comment out the line: `#pragma exclude_renderers d3d11 gles` <i>(still an open issue #2, any help is welcome 🙂)</i>
