---
title: Vernal Visages
published: 2026-02-01
description: My Global Game Jam 2026 submission.
image: cover.png
tags: [Godot Engine, Blender]
category: Games
draft: false
---

Vernal Visages is my submission to [Global Game Jam 2026](https://globalgamejam.org/jam-sites/2026/vancouver-island-game-devs-nanaimo). Vernal Visages is a (somewhat unfinished) split-screen arena shooter where players pick up masks to grant them abilities in battle. This was my second game jam, and this time I had the pleasure of working with a larger team.

## 🔗 Links

- [Submission page](https://globalgamejam.org/games/2026/vernal-visages-9)

## 🏞️ Images

![A screenshot of a lobby/character select screen with a purple eggplant character as player 1 and a yellow parsnip character as player 2.](lobby.png)

![A screenshot of the development game window in top and bottom splitscreen. The top player is looking at the yellow parsnip character and the bottom player is looking at the purple eggplant character. Nothing particularly interesting is happening.](split_screen.png)

## 👨‍💻 Process

This year I teamed up again with my favourite co-developer, Alister. However, we also had the help of additional team members [Nolan](https://github.com/NolanMeske) and Jordan. We had a fifth team member who unfortunately had to cancel due to extraneous circumstances. I enjoyed working with something of a larger team and resolving some of the version control complications that come with that (unpopular opinion I know).

The theme of this year's GGJ was mask. We quickly came up with the idea of an arena shooter where masks grant abilities. This made sense as we had been interested in making a split screen multiplayer game. Originally, I proposed the idea with a large emphasis on masks obscuring the player's vision, with more powerful masks being harder to see through for "balancing". Unfortunately (or maybe fortunately as this quirk might have sucked), we didn't have this functionality in our completed demo.

We wanted Vernal Visages to have simple retro-fps style gameplay, and since we also had a good artist on our team this time, we decided to use 2D sprites for the characters and masks. We wanted to make the sprites billboard and also change perspective based on which direction you viewed them from, but we ran into some issues configuring this functionality as there were multiple cameras in the same local scene due to the splitscreen aspect. Instead, we decided to make the sprite rotate with the player view because we thought it was funny, which had the effect of making the players invisible from a side profile.

## 🎓 Lessons Learned

**I think the most important lesson I learned from this project is one I've learned before but clearly didnt get the memo: Watch your scope!** We knew going into this project that a split screen arena shooter was a lot to do in a two-day game jam, but there wasn't much on the line and we were passionate about the project. Still, I think that next year I'd like to make a simpler game and instead see how polished I can make it within the time allotted, instead of trying do do something so ambitious.
