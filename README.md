# Brand Archetypes, Design, and Persuasion

**Build a visual reference guide in a team of four.** Research real design examples, use ChatGPT to create hero mockups, and collaborate through GitHub before writing code.

**For next class:** each student brings **one researched design-style page with two historical examples**. Choose from your team's six modernist and six postmodernist styles. The full guide and hero images come later; your instructor will provide those deadlines.

## 1. Divide the work

Choose a project lead to set up the shared repository, invite collaborators, maintain this README, and merge reviewed work. Everyone, including the lead, produces and reviews content.

| Each student owns | Team total |
|---|---|
| 3 archetype pages, each with 4 hero images | 12 archetypes; 48 final heroes |
| 3 design-style pages | 6 modernist + 6 postmodernist styles |
| 1–2 persuasion-principle pages | All 7 Cialdini principles |
| 1 personal page and peer reviews | 4 personal pages; reviewed contributions |

Assign each topic once. Spread modernist and postmodernist research across the team. Record owners and reviewers in GitHub issues; each issue names the exact files to change. **You own your assigned pages and images. Reviewers suggest changes through pull requests.**

Use this README as the team's index. The lead fills in the table with links as pages are completed; separate topic indexes are unnecessary.

| Student / personal page | 3 archetypes | 3 design styles | 1–2 persuasion principles |
|---|---|---|---|
| Student 1 | | | |
| Student 2 | | | |
| Student 3 | | | |
| Student 4 | | | |

## 2. Research first

Write short, useful reference pages using bullets and images. Every page needs **what it is, when to use it, how to apply it, and direct source links**. Link back to this README.

| Page | Include |
|---|---|
| Design style | Historical context; relationship to modernism; 3 recognizable visual features; 2 historical examples |
| Persuasion principle | How it works; one concrete headline/CTA example; why it demonstrates the principle; a misuse to avoid |
| Archetype | Audience motivations; visual and verbal cues; one real brand example with a source; the four heroes from Step 3 |

For each historical example, include an image or viewing link, title, creator, date, institution, direct source URL, and image credit/reuse terms. Add **one sentence identifying a feature you could use in your design**. Two examples per style are required; a third is optional.

Use museum collections, archives, and authoritative sites. An original poster or designer's writing is primary evidence; a museum essay provides interpretation. Check the actual sources. AI output is not evidence. Link to an image instead of copying it when reuse permission is unclear.

**Next-class checkpoint:** compare your four sample style pages, check their sources, and agree on a reusable format.

## 3. Make four heroes for each archetype

A hero is a webpage's introductory section. Each finished mockup must show **an image, headline, short supporting copy, and a visible CTA button**. Submit static images; coding comes later.

For each archetype, keep one brand concept, audience, product, and core offer. Choose two persuasion principles and two researched styles—one modernist and one postmodernist:

| | Principle A | Principle B |
|---|---|---|
| Modernist style | Hero 1 | Hero 3 |
| Postmodernist style | Hero 2 | Hero 4 |

Name the specific styles and principles. Keep the image dimensions consistent. Make the principle visible in the copy, offer framing, or imagery; a label in the caption is not enough. Do not fabricate endorsements, statistics, or urgency.

**Pilot checkpoint:** finish and peer-review one four-hero archetype package before producing the other eleven. It counts toward its owner's three packages and the team's twelve.

For each completed archetype page, include:

- **Brief:** audience, product, core offer, and intended action.
- **Four heroes:** under each, explain the archetype cue, persuasion mechanism, and a visual feature borrowed from a linked research source. Two or three sentences are enough.
- **Decision:** choose the strongest hero and explain why; compare what changed with style versus persuasion.
- **Process evidence:** key prompt(s), one rejected draft, and a short note on what you revised.

Use your own ChatGPT account to generate and revise. Correct text or layout as needed. You must be able to explain your decisions.

Across all twelve archetypes, use **all twelve researched styles and all seven persuasion principles**. Plan this before generating images. The lead maintains this coverage table:

| Archetype / page link | Owner | Modernist style | Postmodernist style | Principles A / B | Reviewer |
|---|---|---|---|---|---|
| Fill in all 12 archetypes | | | | | |

## 4. Use Git for every contribution

**Issue → branch → commit → pull request → peer review → merge.**

Use one issue and pull request per page or archetype package. If research was merged earlier, extend that page in a new pull request. Batch related images with their page.

Another student reviews before the lead merges. Each student must review at least one other student's complete archetype package and contribute useful feedback. Address feedback on the same branch.

**Review these four things:**

- **Evidence:** do the sources support the explanation, and are images credited?
- **Design:** can you recognize the archetype, style, and persuasion mechanism?
- **Action:** is the headline readable and the CTA clear?
- **Delivery:** do images and links work, and does the package meet its requirements?

Useful feedback names a problem and a next step: “You call this social proof, but nothing shows other people choosing the offer. Revise the design or reconsider the principle.”

Never push directly to `main`, force-push over teammates, or edit files assigned to someone else without agreement.

<details>
<summary>Git commands and file organization — open when needed</summary>

Create these folders as you work:

```text
members/first_last.md
archetypes/explorer.md
persuasion/reciprocity.md
modernism/style-name.md
postmodernism/style-name.md
assets/heroes/explorer/          # final images; rejected image in drafts/
assets/references/style-name/    # historical images you may reproduce
```

Embed images with descriptive alt text and relative paths:

```markdown
![Explorer hero offering a free trail guide](../assets/heroes/explorer/modernist-reciprocity.png)
[Back to the guide](../README.md)
```

For an archetype package, replace the example issue number and names:

```bash
git switch main
git pull --ff-only
git switch -c issue-12-explorer
# Create or edit your assigned page and images.
git status
git add archetypes/explorer.md assets/heroes/explorer/
git commit -m "Add Explorer package #12"
git push -u origin issue-12-explorer
```

Open a pull request into `main`, include `Closes #12`, and request a teammate's review. Resolve conflicts together without overwriting anyone's work.

</details>

## 5. Submit and keep the evidence

Create your personal page with your name, chosen archetype, and a brief explanation of whether you agree with ChatGPT's suggestion. Add suggested imagery, colors, typography, and one headline/CTA applying a persuasion principle.

Before submission, add links to your three archetype packages and pull requests you authored or reviewed. In a short paragraph, explain your contribution, one improvement after feedback, and what you learned. Credit shared work.

The lead submits the shared repository link through the course's submission channel after checking:

- [ ] **31 topic pages:** 12 archetypes, 12 design styles, 7 persuasion principles.
- [ ] **24 required historical examples** with source records and credits.
- [ ] **48 finished heroes:** four per archetype, twelve per student; coverage table complete.
- [ ] Briefs, explanations, comparisons, prompts, and rejected drafts included.
- [ ] **4 personal pages** with contribution records.
- [ ] Peer review completed; all required work merged; README links and images work.

## Where this leads

Next, you will brand a **plain white T-shirt** in class using a separate assignment repository. After the test, you will build the brand's website with **your own Express server and templates written by hand**.

By the end of the course, you will have a **professional GitHub portfolio and personal website for self-promotion and professional networking**. Your personal site will present your work, including the T-shirt project as a credited case study.

**Skills you are building now:** source evaluation and attribution; design history and visual composition; audience analysis and branding; persuasive copy and CTAs; AI prompting and revision; Markdown and asset management; Git collaboration, critique, and documentation. Later units add HTML/CSS, Express, templating, and professional portfolio presentation.
