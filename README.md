## Overview

The `DIVS` model is a simple agile process model designed for startups with smaller teams. It follows the `Design`, `Iterate`, `Validate`, and `Ship` stages in doing software development. This is the process model used in [Alphaus](https://www.linkedin.com/company/alphaus/), a Tokyo-based startup.

## Principles

These are some of the guiding principles that that `DIVS` model follows:

* The process should "feel" lightweight.
* The process should be generic enough to be tailored or tweaked within a team.
* Releases should be smaller, incremental, and frequent.
* Weekly, monthly, and quarterly checkpoints are important for alignment.

## The model

**Design**

Design is essential. The output of this stage is a design document (`DD`). It is optional for bug fixes, unless it changes the original design significantly then it should contain both the details of the issue and the design of the proposed solution.

**Iterate**

The implementation attempt(s) of the design. Output is `v0+` of the working code.

**Validate**

Validate `v0+` against the `DD` and subsequent feedback. Update `DD` if needed. Output is `v1+` (v1+ could be the same as `v0+`) working code, and an updated `DD` (optional).

**Ship**

Ensure production readiness. This covers testing, security, scaling, observability, etc. Output is the updated `DD`, production version and documentation.

## FAQ

**What's with the name?**

While it means `Design`, `Iterate`, `Validate`, and `Ship`, it is also a play-on-word to the `div` html element which is usually used for grouping or organizing.
