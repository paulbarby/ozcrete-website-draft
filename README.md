# Ozcrete Pools — website draft layout (Master Builders 30 Year Milestone)

**DRAFT — internal review only. Not the live ozcrete.com.au site.**

Single-page layout draft showing the Master Builders 30 Year Member Milestone placed
as its own credential band immediately below the hero, kept separate from the
supplier affiliates grid.

## Status of the artwork

The lockup in the milestone band is a **correctly proportioned placeholder**
(`assets/mb-milestone-placeholder.svg`, 3298x1858, ratio 1.775).

The official rectangular lockup — `MB_MemberMilestone_Logo_30Years_R.png`
(3298 x 1858) — has not reached the build machine. It sits on a Windows `D:` drive
that this build cannot read. To finish: replace the `src` on the lockup `<img>` in
`index.html`. Nothing else moves; the slot and clear space are already correct.

## Brand compliance applied

- Full-colour lockup only, on white clearance plate
- Official dimensions respected: rectangular 3298x1858, square 2541x2481
- Clear space: half the wordmark height is the stated minimum, generous over-clearance used
- Rendered at 430px wide, comfortably above the 15mm (~57px) minimum
- Master Builders brand colours used: PMS 144C `#F8991D`, PMS 2736C `#2D4A9F`

## Local preview

    python3 -m http.server 8080

## Notes

See the "Internal review notes" block at the foot of `index.html` for open copy
decisions — including the live site's own tenure contradiction and its remaining
Lorem Ipsum.
