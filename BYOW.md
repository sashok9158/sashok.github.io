---
layout: default
---
{% include nav.html %}

# Build Your Own World - Java Exploration Game

**Course:** CS61B Java and Data Structures @ UC Berkeley

As part of CS61B, I worked with a partner to build a functional 2D world exploration game from scratch that handles randomized world generation and user interaction.

While we co-designed the high-level architecture, I specifically focused on the world randomization, resource collection, NPC interaction and light level logic, while my partner handled avatar movement, Heads Up Display (HUD), and the save/load logic.

**world generation**

![world generation](/images/61b_worldgen.gif)

A user can enter a seed, creating a different randomized layout with randomly placed lights and resources. The user can also:
- load a saved game
- collect fire to increase the light gradient of the world
- portal between 2 rooms
- interact with the NPC to generate sheep!

|**Heads Up Display** ![world generation](/images/61b_hud.gif) | **portal** ![world generation](/images/61b_portal.gif)|
|:-----------|:------------|
|**lamps** ![world generation](/images/61b_lamps.gif)          |**NPC interaction and Sheep Creation!** ![world generation](/images/61b_npc-sheep.gif)|
