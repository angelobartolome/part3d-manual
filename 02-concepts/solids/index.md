---
title: Solids
description: What a solid is and how Features make and change them.
icon: 🧊
pro: false
featurebase_id: ""
---

# Solids

A **solid** is a 3D body with a volume: a plate, a cylinder, a bracket. It is what you see in the Editor, and what you export for 3D printing or to send to other software.

You don't have to read this page to model. It describes what the Tools act on.

## How solids are made

- A Sketch turned into 3D by [Extrude](../../05-modeling/extrude/index.md) makes a solid.
- Later Features change an existing solid: a Hole drills it, a Fillet rounds its edges, a Boolean joins or cuts solids with each other.
- When a new solid overlaps an existing one, Tools such as Extrude can merge the two into one. Turn **Merge Solids** off to keep them separate.

A Document can hold any number of solids. Tap the layers icon in the top-right corner, then the Solids tab, to list them. There you can hide, rename, colour or delete a solid.

## Faces and edges

A solid is made of **faces** (the flat or curved surfaces) and **edges** (where faces meet). Many Tools ask you to select them: an Extrude Cut or Fillet works on the faces and edges you pick, and you can start a new Sketch on any flat face.

## What's next

- [Features and the History](../features-and-history/index.md) explains how a solid can be changed after you build it.
