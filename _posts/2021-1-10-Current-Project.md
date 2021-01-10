---
title: 2D Platformer Saga
author: Nick French
date: 2021-01-10 17:44:00 +1100
categories: [unity, devblog, learning]
tags: [unity, blog, game dev, learning]
---

# Getting too ambitious for my skill level
---
I only started Unity a few weeks ago, and started getting way to ambitious for my own good. I was trying to create this pretty simple game, which was still too advanced of project for my level. 

I wanted to create a 2D platformer game that I could build up alongside tutorials. 

I started off on the right track... Built a small map by learning about tile palettes and using some free assets, then followed a quick 20 min tutorial on a basic player controller (which I thought was the easy part in a game development).

This basic player controller used a the Physics Rigidbody, and applied force in a direction based on my input. It worked great as ridigbody handles all the collisions and physics (gravity, etc), but I wanted to take it one step further.

I was making a game about a ninja fighting off endless waves of baddies. So like all ninja's we need a double jump. The player controller already had a ground check to ensure I can only jump on the ground, so adding a double jump was pretty straight forward.

I later found out that ridigbody 2D player controllers come with all kinds of bugs, which explains why my double jump stopped working. After some tedious troubleshooting I found that the ground check was getting checked just as I come off the ground, which made my player think I was on the ground even though I was currently jumping. Allowing for a buggy triple jump.

I scrapped this player controller and fell into a rabbit hole. I stumbled upon a great tutorial that used Raycasting that used advanced maths to create gravity and velocity on my player. This is where I started getting too ambitious.

I quickly burnt out with all the crazy formulas and code that I had little understanding what any of it did.

So now I'm going right back to basics, following some beginner tutorials on Unity Learn and have come up with a game that will be easy to create but still fun to play. More to come on what that game is in the future. Stay tuned!