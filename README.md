# ProductSpec.md

A simple standard for defining product wireframes in Markdown.

> "Before building the thing right, make sure you’re building the right thing." --Confucius

<br>

## What is ProductSpec.md?

ProductSpec.md is a lightweight, markdown-based convention for defining an app’s product before jumping into UX, design, and implementation.

It answers three questions:

* What screens exist in the app
* Which abstract components compose each screen
* What the primary user flows look like

<br>

## Quick Start

1. Create a `product/` folder in your project root
2. Add components to `product/components/` (start with standard ones, extend as needed)
3. Define screens in `product/screens/` using those components
4. Describe user flows in `product/flows/`

<br>

## Main Idea

When professional apps are built by large teams, the workflow typically looks like this:

1. The product manager defines what the app does and sketches rough wireframes of the different screens
2. The UX designer selects UI patterns per platform (e.g. web, iOS, Android), chooses components, and defines interactions
3. The designer creates pixel-perfect screens (colors, typography, spacing, visuals)
4. The developer implements the app based on these specifications

**ProductSpec.md focuses on step 1.**

Instead of long documents and wireframes sketches, it uses Markdown as a structured way to define the product.

In the context of LLM-driven development, this becomes especially powerful: a well-defined product spec can directly drive high-quality generation, even in a single pass.

## Principles

* **Abstract, not visual** - no pixels, no colors, no UI kits
* **Composable** - screens are built from reusable components
* **Readable** - humans first, machines second
* **Git-friendly** - easy to diff, review, and collaborate via PRs
* **LLM-friendly** - deterministic structure beats prose and sketches

<br>

# Spec