---
title: Network Delay Visualizer
date: 2026-02-17 09:00:00 -0500
categories: [Projects]
tags: [Computer Networks, Visualization, Web, JavaScript]
---

🚧 **Work in Progress** 🚧

## Overview
Network delay is one of the first concepts introduced in computer networks, but it is often difficult to develop intuition using equations alone. This project is an interactive visualization tool that models end to end network delay and shows how each delay component contributes to total latency.

The project is currently under active development as a part of my graduate-level Computer Networks course.

## What it does (Current and Planned)
Users will be able to adjust common network parameters and instantly see:
- Transmission delay
- Propagation delay
- Processing delay
- Queueing delay
- Total end-to-end delay

The tool focuses on clarity and accessibility. It is designed to run entirely in the browser so that other students can use it without installing any software.

## Why I built it
In networking courses, delay is often taught through formulas and isolated examples. This makes it easy to compute values without understanding which delay components dominate in different scenarios. A visual, interactive tool makes these trade offs easier to explore and understand.

## Tech stack
- HTML, CSS, JavaScript
- Visualization library: Chart.js or Plotly.js
- Hosted as a static site using GitHub Pages

## Current status
- Project structure and design finalized
- Delay model defined
- Visualization concepts prototyped

## Planned improvements
- Interactive parameter controls
- Delay breakdown visualization by component
- Per hop delay analysis
- Comparison mode between two configurations
- Preset scenarios such as LAN, WAN, and satellite links

## Links
- Repository: https://github.com/ginganinja04/network-delay-visualizer 

