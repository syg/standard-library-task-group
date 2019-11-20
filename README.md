# Standard Library Task Group for TC39

Even though JavaScript doesn’t have an officially delineated standard library, there are two distinct groups of proposals: proposals of language features, and proposals of largely orthogonal builtins.

This proposal is to spin up a Standard Library Task Group (SLTG) that meets at a faster cadence, mostly via video-conference, to both scale up our library effort and to more efficiently iterate on standard library/builtin proposals.

## Structure and Responsibilities

The structure here is largely inspired by TG2, the Intl working group, its calls and reports to TC39 plenary.

- Shall have one or more appointed chairs by TC39 plenary, whose responsibilities will include facilitating meetings, recommending whether proposals should be designed in SLTG or in plenary, presenting summary updates to plenary, and seeking constraints for advancement from plenary.
- Shall **not** have an editor, as it does not produce a new spec.
- Same IPR policy as TC39 plenary.
- Consensus-driven. The goal is a healthier feedback loop, and to that goal, consensus means general agreement. General agreement is meant to be reachable without unanimity and with objections outstanding. When general agreement is not apparent, the chair(s) may adjudicate.
- Proposals are discussed in SLTG in the first place by general agreement. Further, proposals under discussion are prioritized at the start of each meeting by general agreement. As above, when general agreement is not apparent, the chair(s) may adjudicate.
- Be responsible for producing and reporting recommendations to TC39 on the development and stage advancement of library proposals. SLTG recommendations to TC39 are to be based on internal consensus from attendees of the meeting. TC39 decisions do not require prior recommendations from SLTG, and TC39 may choose to not adopt an SLTG recommendation.

## Participation

- Participants are TC39 delegates (whether regular attendees or invited experts). Participation is open and strongly encouraged for those delegates interested in the stewardship of the standard library or any specific library proposal. Each SLTG update to TC39 should be accompanied by an active call to participation. All implementers of library features, such as browser developers, and polyfill authors, are further encouraged to regularly attend.
- Initially meet for one hour every two weeks via video-conference. It is free to update its cadence and meeting length.
- Publish minutes and updates after each meeting, including a summary of planned recommendations for TC39.

## Aspirational Norms

- SLTG is intended to be a friendly, collaborative space to foster iterative design work on proposals. Procedurally, SLTG is not intended to be a miniature TC39 for standard library proposals. The idea is to gather relevant stakeholders already participating in TC39 to iterate on library work and iron out concerns before going to plenary for approval of stage advancement.
- SLTG is intended as an attractive space for proposal champions, implementers, and reviewers to get work done and be in communication, gradually getting them all in the same space. SLTG is intended to shift the working-out-of-constraints from TC39 plenary to itself. Should discussions arise in TC39, then the earlier conclusion from the SLTG can be referenced and explained, to be revisited only if necessary. In other words, SLTG is intended to be respectful of participants' time investment in TC39 by incrementalizing the work into itself.
- The core constituency is intended to be all JavaScript developers when prioritizing proposals. In case of conflict, reach should be considered: e.g., the reach of the web. That said, being the *standard* library task group, proposals should aspire to satisfy all JavaScript developers.
- Proposal champions are free to work with SLTG, or to develop their proposals entirely in plenary. SLTG may discuss a TC39 proposal and follow up with the champion and committee about it. No up-front decision needs to be made about whether a proposal will be discussed in SLTG or not.
- To generally act as a first filter for library proposals. Stage 0 proposals recommended by SLTG should be sufficiently polished that they are more amenable for fast-tracking to stage 2 (like any other sufficiently polished proposal).

## Prior Art

- TG2 (ecma402) works well and is highly productive.
- The [C++ committee](https://isocpp.org/std/the-committee) is subdivided among domains and has a parallelized pipeline model.
- Allen Wirfs-Brock's [vision talk in 2017](https://github.com/tc39/agendas/blob/master/2017/ES-next20.pdf) envisioned smaller, parallel subgroups with fewer in-person meetings and specifically cited the C++ committee.
- Dan Ehrenberg has also done much here to scale TC39 with the various calls he's bootstrapped.

## FAQ

### Why?

To make a richer JS standard library, the TC39 process should scale. A more frequent, higher bandwidth, remote-friendly feedback loop is useful for library proposals that may have less cross-cutting concerns than core language feature proposals. Lack of a more codified committee-wide async communication norm means proposals lose momentum or have to wait another 2 months to make progress.

In the longer term, I hope we enable more granular, more frequent, remote-friendly standards participation to scale the committee and lessen the travel burden. I'm calling this the "GC optimization plan": incrementalize first (this proposal), and with any luck, in time, be both concurrent with the mutator (plenary) and parallel with other work (other task groups).

### Is this gated by built-in modules?

Library proposals could be any of, but not limited to, the following: built-in modules, or new globals, or new methods on globals or existing prototypes. This task group is intended for all such proposals, not only proposals of a particular form.

### Does this undermine plenary meeting's authority?

The plenary meeting has the final say on proposal advancement for stages. This task group is designed to promote a healthier feedback loop.

### Why not ad-hoc by proposal?

I hope bandwidth consolidation and more formal structure promotes more participation. Ad-hoc calls per proposal of course are welcome to continue being held.

### Is this extra work?

I certainly hope not. Since SLTG participants are TC39 delegates, the work I envision happening in SLTG is work that would've needed to happen in TC39 to advance stages (i.e. "work out the constraints"), except incrementalized and more frequent.

### I don't have the time?

The published notes and summaries should help if making the meetings is difficult due to time constraints. I also believe one hour every two weeks is reasonable. If this model proves successful, it may be possible to make in-person meetings less frequent to lessen the travel burden.
