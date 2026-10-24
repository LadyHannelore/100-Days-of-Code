# Day 4 — Library Schumil Reply Bot

**Date:** 2026-10-24

## What I worked on

Built [Library Schumil Reply Bot](https://github.com/LadyHannelore/Library-Schumil-Reply-Bot),
a small, dependency-free reply desk inspired by the warm, bookish feel of the
Ascendance of a Bookworm Wiki. It tokenizes a message, selects the hand-written
reply whose keywords match the most words, and gives a friendly fallback when
there is no match.

## What I learned

I practiced turning free-form text into a simple matching process: tokenize the
message, compare its words against keyword rules, and return the strongest
match. A fallback keeps the interaction useful when no topic applies.

## Challenges

The key challenge was making the keyword rules useful without relying on an
LLM or server. Matching against multiple words lets the bot choose between
topics, while the fallback covers messages outside its small set of rules.

## Next

Start Day 5: build a small Ditter board prototype where two pieces move on a
grid and capture a marked tile.
