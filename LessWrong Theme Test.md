---
title: LessWrong Theme Test
aliases:
  - Theme Stress Test
tags:
  - theme-test
  - lesswrong
status: draft
rating: 4
---
# LessWrong Theme Test

This note is designed to exercise a wide range of Obsidian styles in one place. 

A normal paragraph should be comfortable to read for several lines. The ideal look is closer to a long-form essay than a dashboard: generous line-height, restrained contrast, and a readable measure. This sentence includes **bold text**, *italic text*, ***bold italic text***, ~~strikethrough~~, ==highlighted text==, `inline code`, and a [standard Markdown link](https://lesswrong.com).

Internal links should also be easy to distinguish without becoming visually loud: [[Example Note]] and [[Example Note|aliased internal link]].

---

## Heading Level Two

This section tests secondary headings and paragraph spacing.

### Heading Level Three

A third-level heading should remain clearly subordinate to H2.

#### Heading Level Four

Useful for long structured essays.

##### Heading Level Five

Small headings should still be legible.

###### Heading Level Six

The smallest heading level.

---

## Lists

### Unordered

- First-level item
- Another item with **emphasis**
  - Nested item
  - Another nested item
    - Third-level item
- Final item

### Ordered

1. Define the problem.
2. Separate observation from inference.
3. Consider alternative explanations.
4. Update based on evidence.

### Tasks

- [ ] Unfinished task
- [x] Completed task
- [ ] Task with a [[linked note]]
- [ ] Task with `inline code`

---

## Blockquote

> The purpose of this blockquote is to test spacing, border treatment, typography, and contrast.
>
> A second paragraph makes it easier to see how multi-paragraph quotations behave.

> [!note]
> This is a standard Obsidian note callout.

> [!info] Custom title
> Callouts should feel restrained and editorial rather than like colorful application cards.

> [!warning]
> This is a warning callout with enough text to check padding, border treatment, and title weight.

> [!tip] A useful heuristic
> Prefer simple explanations until the evidence requires more complexity.

---

## Code

Inline code looks like `P(A|B) = P(B|A)P(A)/P(B)`.

```python
def bayes(prior, likelihood, evidence):
    return (likelihood * prior) / evidence

posterior = bayes(0.10, 0.80, 0.20)
print(f"{posterior:.2%}")
```

```css
.theme-light {
  --background-primary: #fffdf8;
  --text-normal: #2f2a25;
  --text-accent: #8b3f2f;
}
```

---

## Table

| Hypothesis | Prior | Evidence fit | Posterior direction |
|---|---:|---:|---|
| H1 | 0.50 | High | ↑ |
| H2 | 0.30 | Medium | → |
| H3 | 0.20 | Low | ↓ |

---

## Math

Inline math: $P(H\mid E) \propto P(E\mid H)P(H)$.

Display math:

$$
P(H\mid E)
=
\frac{P(E\mid H)P(H)}
{P(E)}
$$

Another expression:

$$
\operatorname{logit}(p)=\ln\left(\frac{p}{1-p}\right)
$$

---

## Footnotes

A claim can have a footnote attached to it.[^1] Another sentence can reference a longer note.[^long]

[^1]: A short footnote for testing typography.
[^long]: This is a longer footnote. It should remain readable and visually secondary to the main essay text while still being easy to scan.

---

## Definition-style content

**Bayesian update.** A change in credence caused by observing evidence.

**Calibration.** The degree to which stated probabilities correspond to observed frequencies.

**Expected value.** The probability-weighted average of possible outcomes.

---

## Horizontal Rule

Text before the rule.

---

Text after the rule.

---

## Links and Tags

External: [LessWrong](https://www.lesswrong.com)

Internal: [[Rationality]], [[Decision Theory]], [[Bayesian Epistemology]]

Tags: #rationality #epistemology #theme-test

---

## Long-form Reading Test

There is a particular kind of interface that almost disappears when it works well. The typography does not call attention to itself. The margins feel large enough to make the text breathable without turning every paragraph into a narrow column. Links remain discoverable without dominating the page. Headings provide structure while preserving continuity.

For a theme inspired by essay-oriented sites, the main design problem is not ornament. It is hierarchy. Primary text must dominate secondary metadata; content must dominate navigation; strong emphasis must remain exceptional; and components such as tags, callouts, tables, and code blocks should feel like extensions of the document rather than separate pieces of application chrome.

A good stress test is to read several consecutive paragraphs without consciously noticing the interface. If the eye keeps being pulled toward borders, pills, icons, shadows, or saturated accent colors, the visual hierarchy is probably too aggressive. If everything looks identical, however, structure disappears. The useful middle ground is quiet distinction.

The quick brown fox jumps over the lazy dog.  
THE QUICK BROWN FOX JUMPS OVER THE LAZY DOG.  
0123456789 — – - “double quotes” ‘single quotes’ … ellipsis.

---

## Metadata-like Text

Author: Example Author  
Published: 5 September 2026  
Reading time: 8 minutes  
Confidence: 70%  
Status: Draft

---

## Nested Quote and List

> A quoted argument:
>
> 1. Premise one.
> 2. Premise two.
>    - Supporting observation.
>    - Counterpoint.
> 3. Conclusion.

---

## Image Test

![Obsidian logo placeholder](https://obsidian.md/images/obsidian-logo-gradient.svg)

_Image caption or explanatory text beneath an image._

---

## Obsidian Embed Syntax

Embedded note:

![[Example Note]]

Embedded heading:

![[Example Note#Section]]

Embedded block:

![[Example Note#^block-id]]

---

## Final Typography Sample

**Strong:** Evidence should change beliefs.

*Emphasis:* Uncertainty is a feature of the problem, not a formatting error.

`Monospace:` 0.001 → 0.01 → 0.1 → 1.0

==Highlight:== this sentence is intentionally highlighted.

~~Deleted hypothesis~~ → revised hypothesis.

> Clear writing should make the structure of an argument easier to inspect.


