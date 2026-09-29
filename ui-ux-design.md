---
name: ui-ux-design
description: Design user interfaces and experiences — layout, hierarchy, color, typography, interaction patterns, and design systems. Use when creating or redesigning UI components, pages, or flows.
---

# UI/UX Design

Design with intent. Before writing any code or mockup:

1. **Define the job.** Who is the user, what task are they completing, and what does success look like? One primary action per screen.
2. **Establish hierarchy.** Decide the single most important element and make everything else visually subordinate. Use size, weight, color, and spacing — in that order of impact.
3. **Choose a constraint system.** Pick a spacing scale (e.g. 4/8/12/16/24/32), a type scale (e.g. 12/14/16/20/28/40), and a small palette (1 primary, 1-2 accents, 3-4 neutrals, semantic colors for success/warning/error). Never freehand values.
4. **Design states, not screens.** Every interactive element needs default, hover, focus, active, disabled, loading, and empty states. Touch targets at least 44x44 px.
5. **Write real copy.** Button labels are verbs ("Save draft"), errors say what happened and what to do next, empty states offer the next action.

Layout rules: content max-width ~65-75ch for reading; 12-column grid for dashboards; mobile-first stacking; whitespace is a feature, not waste.

Accessibility floor: text contrast >= 4.5:1 (3:1 for large text), visible focus indicators, keyboard-operable everything, labels tied to inputs.

When reviewing or building, check every item above and fix violations before styling polish.
