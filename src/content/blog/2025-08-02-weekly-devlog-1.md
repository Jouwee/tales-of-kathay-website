---
title: 'Weekly Devlog #1 - Dungeons'
description: 'Lorem ipsum dolor sit amet'
pubDate: 'Aug 02 2025'
author: 'Jouwee'
---

<p>Hi everyone!</p>

<p>Last week, I introduced new combat skills, but combat still wasn't a big part of the gameplay. This week, I focused on bringing combat into the gameplay loop with a dungeon and a miniboss.</p>

<p>The miniboss is a creature called Varningr, which I wont spoil much about just yet.</p>

<h2>Varningrs lair</h2>

<p>The Varningrs lair is the first dungeon added to Tales of Kathay. It's a undeground cave system with wolves and, of course, the Varningr.</p>

<p>Varningrs spawn during history generation, and can attack small cities. The people of these cities might join forces and attack him back.</p>

<p>For the dungeon itself, I had to update the Jigsaw generation algorithm to allow for rotated and mirrored tiles, and also have room requirements, such as "Generate a dungeon with only 1 entrance and only 1 lair".</p>

![Screenshot of the new dungeon](../../assets/20250802-102615.png)

<p>Some polishing is still necessary before I consider de dungeon complete, but I would say it's 80% there.</p>

<h2>Storyteller</h2>

<p>During the history generation, I introduced the conecpt of a "storyteller". I borrowed the name from Rimworld, although the conecpt is different.</p>

<p>Basically, the storyteller has "desired" parameters, such as number of cities and population, and it nudges the simulation random chances to ensure it stays around those parameters. You can also specify a "strength" to the storyteller, where 1 is a strong nudge, and 0 is completely random.</p>

<h2>Visual tweaks</h2>

<p>I'm starting to do a few visual tweaks to improve the game looks.</p>

<p>So far I added:</p>
<ul>
    <li>Object shadows;</li>
    <li>Creature shadows;</li>
    <li>Creature facing last actions direction;</li>
    <li>Global vignette;</li>
</ul>

<p>In the background I'm also studying and structuring a new rendering backend to allow for more advanced shaders, effects and lighting.</p>

<p>That's it for this now, and see you next week!</p>