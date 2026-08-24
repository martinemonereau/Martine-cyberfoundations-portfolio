# Week 2 Lab — Cybersecurity Landscape & Digital Infrastructure Overview

**Student Name:** Martine Monereau

**Date Completed:** 8/23/26

**Module:** 1 — Digital Infrastructure & CLI | **Week:** 2  
**Submission Path:** `week-02/labs/lab-01-hardware-os-software-diagram.md`

---

## Overview

In this lab, you build a working mental model of the system you'll be securing throughout this course: the hardware, operating system, and software layers that make up every computer, and where the cybersecurity field fits around them. This lab has two parts. Part A connects this week's material to the CyberFoundations City map. Part B has you build and explain a diagram of how a computer's hardware, OS, and software layers interact.

**No terminal or command line is required this week** — that starts in Week 3.

---

## Lab Environment

| Component | Details |
|---|---|
| Environment | Browser-based Lab Portal (Module 1 orientation) |
| Required Materials | CyberFoundations City map; a diagram tool of your choice (hand-drawn and photographed, or any digital tool) |

**Prerequisite:** Portfolio repo created from the CyberFoundations student template in Week 1. This file is already in your repo at `week-02/labs/lab-01-hardware-os-software-diagram.md`, ready to fill in.

**New to the Lab Portal?** Watch this short walkthrough of how to find your Week 2 lab worksheet: [Accessing the Lab Worksheet — Step by Step](PASTE-VIDEO-LINK-HERE) *(~3 min)*.

---

## Part A — CyberFoundations City & the Cybersecurity Landscape

The CyberFoundations City map is your visual guide to the next 11 weeks. Each district represents a module of this course. This part connects this week's material to the map you were introduced to in Week 1.

### Step 1 — Open the Lab Portal Orientation Module

Log into the Lab Portal with your Microsoft account. From your Student Dashboard, open the **Module 1 orientation** module.

### Step 2 — Complete the Orientation Walkthrough

Work through the orientation content. It covers the same hardware/OS/software material as this week's lessons from a different angle — use it to check your understanding, not to replace the lessons.

### Step 3 — Locate This Week's District on the City Map

Open the CyberFoundations City map (introduced in Week 1, Lesson 6). Identify which district corresponds to Module 1 — Digital Infrastructure & CLI.

**District name:** Foundry District

```
Foundry District
```

**Why this district fits this week's topics (1–2 sentences):** The Foundry District fits this week because it shows how everything in a system is connected, not separate. It makes it easier to see how attackers, defenders, users, and the whole digital infrastructure all play a role in security.

```
The Foundry District fits this week because it shows how everything in a system is connected, not separate. It makes it easier to see how attackers, defenders, users, and the whole digital infrastructure all play a role in security.
```

---

## Part B — Hardware, OS, and Software Diagram

A computer is a stack of layers: physical hardware at the bottom, an operating system managing that hardware in the middle, and the software you actually use on top. This part has you draw that stack and explain it in your own words.

### Step 1 — Identify the Layers

Before drawing anything, list the three layers you'll diagram and one example of what lives at each layer.

**Hardware layer — one example component:** RAM: Random Access Memory

```
(e.g., CPU, RAM, storage — your choice)
```

**Operating system layer — name an OS:** Windows

```
(e.g., Windows, Linux, macOS)
```

**Software layer — one example application:** Microsoft edge

```
(e.g., a web browser, a word processor)
```

### Step 2 — Sketch Your Diagram

Sketch a simple diagram (hand-drawn and photographed, or built in any digital tool) showing how the hardware, OS, and software layers stack and interact. Arrows or labels showing "what talks to what" matter more than visual polish. If you'd like a free browser-based option instead of hand-drawing, try [draw.io](https://www.drawio.com/) — no account required to get started.

### Step 3 — Upload and Embed Your Diagram

Upload your diagram image directly into your repo's assets folder — keep it there rather than pasting it loose into this file, so all of this week's images stay together and organized.

1. Go to your portfolio repository on GitHub.com and navigate to `assets/screenshots/week-02/`.
2. Click **Add file → Upload files**, then drag in your diagram image, and give it a descriptive name (lowercase, hyphens, no spaces, no timestamps — e.g. `hardware-os-software-diagram.png`).
3. Scroll down and click **Commit changes**.
4. Click on the uploaded image's filename to open it — you'll see the image itself displayed on the page.
5. Right-click directly on the image and choose **Copy image address** (Chrome/Edge) or **Copy Image Link** (Firefox).
6. Come back to this file, open the pencil (edit) icon, and paste that link into the embed line below, in place of the placeholder:

**If right-click doesn't show that option:** click the small download-arrow icon in the top-right of the image preview instead, then copy the URL from your browser's address bar.

**My Diagram:** https://github.com/martinemonereau/Martine-cyberfoundations-portfolio/blob/main/assets/screenshots/week-02/hardware-os-software-diagram.png.png?raw=true

### Step 4 — Explain Your Diagram

In your own words — not a copied definition — explain how the three layers interact. Reference your own diagram directly.

```
The operating system acts like a manager between the hardware and the software. The hardware provides the physical parts, but it can’t do anything on its own. The OS makes sure the hardware and software communicate properly, handling requests and keeping everything running smoothly.
```

---

## Analysis Questions

Answer each question in your own words. These questions connect what you did in Parts A and B to the bigger picture of this course.

### Analysis Question 1

If the operating system crashed on the computer you diagrammed, which layer(s) would stop working, and which (if any) would keep working? Explain your reasoning.

```
If the operating system crashed, the software would stop working because the operating system is needed for the software to properly function. The hardware would still work however it would be sitting there without it's "hotel manager." While it will still be available, it's use would be limited without the OS. 
```

### Analysis Question 2

Pick one piece of software you use daily. Trace it down through the OS to the hardware it ultimately depends on. What would happen to that software if the hardware layer failed?

```
If the hardware failed, I wouldn’t be able to access the software at all. I use Microsoft Teams every day to message coworkers and join video calls, but none of that can run without the operating system and the hardware underneath it. The software relies on the OS, and the OS relies on the hardware, so if the hardware stops working, everything above it stops too.
```

### Analysis Question 3

Explain, in your own words, why a cybersecurity professional needs to understand all three layers — hardware, OS, and software — rather than just the software layer where most visible attacks (like phishing emails) happen.

```
A cybersecurity professional needs to understand the hardware, operating system, and software because attacks don’t only happen at the software level. Even though software threats like phishing are more visible, the OS and hardware are part of the foundation that everything runs on, and attacks can target those layers too. If the hardware or OS is malfunctioning or compromised, it directly affects how the software behaves, so problems don’t just start at the software layer. All three layers work together and protecting one means understanding how it depends on the others.
```

---

## Lab Report Questions

Answer each question in complete sentences.

**1. What is the cybersecurity landscape, and why does it matter to someone starting this course?**

```
The cybersecurity landscape is basically the whole digital infrastructure and everything connected to it. The attack surface is every possible point where an attacker could try to get in, and that includes the systems, the software, and even everyday users. Attackers, defenders, and users are all interacting at the same time, which is why understanding how these pieces fit together matters.
```

**2. Which CyberFoundations City district did you identify in Part A, and how does its theme connect to the hardware/OS/software material in Part B?**

```
The Foundry District connects to the hardware, OS, and software material because it shows how all those layers exist together in a real environment. Ivy is looking at a whole area full of machines, and each one depends on hardware at the bottom, an operating system in the middle, and software on top that people actually use. A lot of people who aren’t familiar with cybersecurity think each part works on its own, but they’re all connected, and problems or attacks can happen at any layer. Seeing the Foundry District helps you understand why knowing all three layers matters when you’re trying to keep everything secure.
```

**3. Of the three layers (hardware, OS, software), which one do you think is hardest to secure, and why?**

```
I think the software layer is the hardest to secure because it’s the most accessible and it’s what people interact with all day. I believe that means it is more prone to vulnerabilities.  Hardware and the OS matter as well, but they’re more stable and not touched as often by everyday users. Software is out in the open and constantly changing, so keeping it secure ends up being the biggest challenge.
```

---

## Submission Checklist

- [x] Lab Portal Module 1 orientation completed

- [x] District identified and explained

- [x] Hardware, OS, and software layer examples listed

- [x] Diagram uploaded to `assets/screenshots/week-02/` and embedded using a copied image link (not pasted loose, not a local file path)

- [x] Diagram explanation written in your own words (minimum 3 sentences)

- [x] All three Analysis Questions answered (minimum sentence counts met)

- [x] All three Lab Report Questions answered in complete sentences

- [x] This file is committed to your portfolio repo at `week-02/labs/lab-01-hardware-os-software-diagram.md`
