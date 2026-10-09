---
title: Constraints
description: What a Constraint is and why Sketches use them.
icon: 📐
pro: false
featurebase_id: "4466075"
---

# Constraints

A **Constraint** is a rule a Sketch has to follow: "this line is horizontal", "these two lines are the same length", "this line is 60 mm long". When you change one thing, Part3D moves the rest of the Sketch to keep every rule true.

You don't have to read this page to draw. It explains what the small badges on your sketch mean.

## Why they matter

A Sketch with only loose lines is like a drawing on paper: if you move one corner, nothing else follows. With Constraints it behaves like a model:

- Set a line to 60 mm, and it stays 60 mm while you drag another corner.
- Make two lines parallel, and they stay parallel when either one changes.
- Change a dimension later, and the whole Sketch, and every Feature built from it, updates.

## Where they come from

Part3D adds some Constraints for you while you draw, such as a rectangle's horizontal and vertical sides. You add the rest by selecting part of the Sketch, tapping **⋯** and picking a Constraint, such as **Distance** to set a size. The tutorial does this in [Getting Started](../../01-getting-started/getting-started/index.md).

## Too many or too few

A Sketch can have too few Constraints, so something can still move freely, or too many, so two rules disagree. If the rules can't all be true at once, Part3D warns you instead of guessing. Remove or change one of the conflicting Constraints to fix it.

## What's next

- [Features and the History](../features-and-history/index.md) explains how the Sketch becomes a model.
