# Semantic LKN: Knowledge & Results

This directory contains the public-facing knowledge base, logic scripts, and reasoning traces for the **Semantic LKN** project. This folder is curated for users who wish to explore the semantic capabilities of the engine without interacting with the C++ source code.

## Contents

### 1. [euclid_book1_defs.lkn](euclid_book1_defs.lkn)
A unified knowledge script containing **Definitions 1-22 of Euclid's Elements (Book 1)**. This file represents the foundational geometric truths that the engine uses for its reasoning.

### 2. [testSemantic.lkn](testSemantic.lkn)
The primary test script used to verify the engine. It includes part-of-speech definitions, the loading of generic knowledge, and a series of complex geometric questions that test the boundaries of the reasoning logic.

### 3. [actual_output_trace.txt](actual_output_trace.txt)
A complete execution trace showing the engine's responses to the `testSemantic.lkn` script. This file demonstrates real-world examples of **Deductive Subtyping** and **Complementary Inference** (e.g., calculating the number of unequal sides in an isosceles triangle).

### 4. linkedin_announcement.md
The official milestone announcement. It provides a human-readable overview of the two-phase development process:
* **Phase One**: Solo development of core semantic logic.
* **Phase Two**: AI-partnered architectural modernization.

## Purpose
These files serve as the "logical release" of the project. They can be fed into the LKN Semantic Engine to replicate the reasoning results shared in the project milestones.

---