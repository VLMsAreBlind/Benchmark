# Vision Language Models Are Blind

This repository contains the code and data for the paper `Vision Language Models Are Blind`.

## Abstract

```
Large language models with vision capabilities (VLMs), e.g., GPT-4o and Gemini-1.5 Pro, are powering countless image-text processing applications and scoring high on existing vision-understanding benchmarks. Yet, we find that VLMs fail on 8 visual tasks that are absurdly easy for humans, such as identifying (a) whether two circles overlap; (b) whether two lines intersect; (c) which letter is being circled in a word; and (d) counting the number of circles in an Olympic-like logo. The shockingly poor performance of four state-of-the-art VLMs suggests their vision is, at best, like that of a person with myopia seeing fine details as blurry, and at worst, like an intelligent person who is blind making educated guesses.
```

## Benchmark Tasks

1. [Circled Word](./src/CircledWord/)
2. [Counting Line Intersection](./src/LineIntersection/)
3. [Counting Nested Squares](./src/NestedSquares/)