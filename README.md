# Bug Hunt

## Trace and fix: Debugging pseudocode

### Overview

In the [HAP Computational Thinking](https://hap-computational-thinking.netlify.app/) stations, you traced through the Secret Number Game and discovered an infinite loop bug. This assignment gives you practice with that same skill—tracing code to find bugs—but now you'll also fix them.

You'll debug three pseudocode programs, each with a different type of bug. For each one, you'll trace through the code, identify the problem, fix it, and download the corrected flowchart.

### The tool

Use the [Pseudocode Flowchart Tool](https://pseudocode-flowchart.netlify.app) to visualize your code.

- Type pseudocode on the left, see the flowchart on the right
- **Key insight:** The flowchart shows exactly what your code says, not what you intended. If the flowchart looks wrong, that's your clue.

### Instructions

1. Open the `.pseudo` file and copy the code
2. Paste it into the [Pseudocode Flowchart Tool](https://pseudocode-flowchart.netlify.app)
3. Study the flowchart
4. Create a trace table to find the bug
5. Explain what's wrong
6. Fix the bug
7. Download the fixed flowchart as an SVG
8. Complete the corresponding file in `solutions/`

### The bugs

The `bugs/` folder contains three buggy programs. **Do not edit these files**—they are read-only references. Copy the code from each file to paste into the tool.

| File                 | Problem                               | Creative element                       |
| -------------------- | ------------------------------------- | -------------------------------------- |
| bug1-counter.pseudo  | Should count from 1 to 5, but doesn't | Imagine real-world consequences        |
| bug2-grades.pseudo   | "Excellent" never displays            | Reframe in a domain you care about     |
| bug3-greeting.pseudo | Never stops running                   | Write a warning in a character's voice |

### What to submit

Complete these files (New to Markdown? See [Markdown Guide - Basic Syntax](https://www.markdownguide.org/basic-syntax/) if you need help with tables or code blocks):

```
solutions/
├── bug1.md
├── bug2.md
├── bug3.md
└── flowcharts/
    ├── bug1-fixed.svg
    ├── bug2-fixed.svg
    └── bug3-fixed.svg
```

When finished, commit and push your work.

### Checklist

- [ ] bug1.md complete (trace table, explanation, fixed code, consequences)
- [ ] bug2.md complete (trace table, explanation, fixed code, reframed explanation)
- [ ] bug3.md complete (trace table, explanation, fixed code, character warning)
- [ ] bug1-fixed.svg downloaded and added to flowcharts/
- [ ] bug2-fixed.svg downloaded and added to flowcharts/
- [ ] bug3-fixed.svg downloaded and added to flowcharts/
- [ ] All changes committed and pushed
