# Changelog

## Lecture 14 ANN rendering correction

- Fixed the ANN lecture asset insertion so bundled library code remains inside its script elements instead of appearing as visible page text.
- Verified all Lecture 14 scripts parse correctly while keeping the original neural-network lesson content unchanged.

## Lecture workspace cleanup

- Removed the large portal-level lecture title and description that duplicated each lesson's own introduction.
- Replaced the duplicated header controls with one compact Home, Topics, Complete, and Search toolbar.
- Increased the immediately visible reading area and simplified the responsive mobile toolbar.

## Navigation correction

- Fixed the topic tabs in Lectures 1–9 so they scroll to the selected section inside the active lecture instead of resolving to the portal home page.
- Corrected the Lecture 12 tab offsets so Models, Truth Tables, Wumpus World, Inference Rules, and Practice open their matching slides.
- Applied safe in-lecture anchor handling to the embedded AI Lab as well.

## Complete course portal

- Added nine classroom-ready pre-midterm lecture modules covering AI foundations, intelligent agents, problem formulation, uninformed and informed search, heuristic quality, local search, game playing, minimax, and alpha-beta pruning.
- Added interactive, animated learning activities to every new lecture, with Start, Pause, Resume, Previous, Next, Reset, and speed controls.
- Added Assignment 1 after Lecture 5, Quiz 1 after Lecture 6, and Assignment 2 after Lecture 8.
- Split the course library and navigation into **Before Midterm** and **After Midterm** sections.
- Expanded course progress tracking, lecture navigation, search, deep links, and the lecture picker to cover Lectures 1–16.
- Added the supplied AI Lab Manual as a first-class portal destination and as the standalone `ai-lab.html` file.
- Improved responsive reading space, keyboard navigation, reduced-motion support, visible focus states, and topic navigation.
- Preserved the supplied Lectures 10–16 and AI Lab content byte-for-byte inside the portal.
