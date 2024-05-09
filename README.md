## Overview

The **DIVS** model is a lightweight agile process designed for startups with small teams. It centers around the "**Design**, **Iterate**, **Validate**, and **Ship**" stages of doing software development. This is the methodology used in [Alphaus](https://www.linkedin.com/company/alphaus/), a Tokyo-based startup.

## Guidelines

These are the guidelines that the DIVS model follows:

* The process should "feel" lightweight.
* The process should be generic enough to be tweaked within a team.
* Releases should be smaller, incremental, and frequent.
* Weekly, monthly, and quarterly checkpoints are important for alignment.
* The process doesn't enforce any style of communication.
* The process doesn't enforce any specific development methods within each stage.

## The model

The DIVS model centers around SODs, the four DIVS stages, views, and checkpoints.

### SODs

An SOD (shorthand for "<ins>So</ins>ftware <ins>D</ins>eliverable") is a software artifact that a team will implement and deliver using the DIVS model. There are no rules on how high-level or specific an SOD is other than in the DIVS model, a single DD (see **Design** section below) is tied to a single SOD. SODs could be initiatives, projects, features, subsystems, etc.

SODs are the main artifacts that will go through the four DIVS stages, be it on a single cycle, or multiple cycles.

### The four stages

**Design** - This is the first stage of the DIVS model. The expected output is a design document (or **DD**). A DD must be tied to an SOD. DIVS doesn't provide a specific format, although Alphaus uses [this](https://github.com/alphauslabs/dd-fmt) format.

**Iterate** - The implementation iterations of the DD. The expected output is a version of the working code.

**Validate** - This stage validates the output version of the previous stage against the DD. This stage provides feedback to the code version being validated.

**Ship** - This stage ensures production readiness of the validated code. The expected output is the updated DD, the production version, and documentation.

While it is expected for a full DIVS cycle to start with **Design** and ends with **Ship**, the DIVS model doesn't enforce a linear sequence of all stages. For example, it is valid to do multiple iterations of **Iterate** and **Validate** before doing a single **Ship**, or multiple iterations of **Iterate**, **Validate**, and **Ship** under a single **Design** stage.

### Views

Views are visual representations of the state of software development in relation to the DIVS model. The DIVS model requires only two (2) views: the **Timeline**, and the **DIVS** view.

**Timeline view** - The Timeline view is the view of the development progress against the planned schedule. It contains a list of SODs with their associated schedules and priorities, and its up-to-date progress against those schedules. This view is aimed for both engineering and non-engineering audiences. The Timeline view should be able to display the current and historical state of software development on a monthly, quarterly, and a yearly basis.

**DIVS view** - The DIVS view is the view of the progression of SODs, and its optional sub-items, in relation to the four stages. This view is intended for engineering.

### Checkpoints

Checkpoints are recurring meetings that the team needs to do to ensure alignment across relevant groups. The DIVS model recommends four (4) checkpoints: weekly, monthly, quarterly, and prioritization.

**Weekly checkpoint** - Weekly checkpoints are intended to keep track of the development progress on a weekly basis.

**Monthly checkpoint** - Monthly checkpoints are intended to ensure alignment between relevant groups on a monthly basis.

**Quarterly checkpoint** - Quarterly checkpoints are intended to ensure alignment between relevant groups on a quarterly basis.

**Prioritization** - Prioritization checkpoints are intended to keep the **Timeline view** up-to-date and prioritized.

## FAQ

**What's with the name?**

If you're referring to "DIVS": while it means <ins>D</ins>esign, <ins>I</ins>terate, <ins>V</ins>alidate, and <ins>S</ins>hip, it is also a play-on-word to the `div` HTML element which is usually used for grouping or organizing.

If you're referring to "SOD": it's a shorthand for "<ins>So</ins>ftware <ins>D</ins>eliverable". It's easier to say "SOD" than "deliverable", or "software deliverable", although we read it as "S.O.D.", not "sod". It is also inspired by `git`.
