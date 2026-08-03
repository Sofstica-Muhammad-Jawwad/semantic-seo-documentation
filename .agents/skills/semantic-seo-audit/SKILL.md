---
name: semantic-seo-audit
description: Audits websites, articles, and pages against comprehensive Semantic SEO principles (E.A.V., Topical Maps, Content Briefs, Semantic On-Page, Writing Rules, E-E-A-T, N-Grams, and Ecommerce SEO). Generates an interactive, sequential 1-step-at-a-time execution plan.
---

# Semantic SEO Audit Skill (`/semantic-seo-audit`)

When activated, this skill guides the user through a comprehensive, step-by-step Semantic SEO audit of a website, article, or page set. It analyzes content and architecture against the 11 Semantic SEO Clusters and produces a structured, actionable task list—executing and verifying **one single step at a time**.

---

## 🎯 Audit Workflow & Execution Protocol

### Rule #1: One Step at a Time
Never overwhelm the user with a massive dump of tasks to fix simultaneously. Present the audit findings, create a numbered checklist, and **execute/guide the user through Step 1 first**. Wait for completion or confirmation before proceeding to Step 2.

---

## 📋 The 6-Phase Audit Checklist

### Phase 1: Source Context & Domain Alignment
1. **Central Entity Identification:** Verify if the website/page has ONE clear Central Entity.
2. **Topical Borders:** Check if any articles cross topical borders (e.g., a food site publishing tech news) causing Topical Map Distortion.
3. **Site-Wide N-Grams & Boilerplate:** Inspect footers, headers, and sidebars for spammy or distracting repeating word patterns.

### Phase 2: Topical Map & Architecture Audit
1. **Core vs. Outer Sections:** Ensure core pillar pages (Quality Nodes) exist and outer supporting articles properly link back to them.
2. **Taxonomy & Hierarchy:** Verify category URL paths (Root → Seed → Node) and ensure no orphan pages exist.
3. **Internal Link Network:** Verify descriptive anchor text (no "Click Here") and ensure contextual relevance of linked pages.

### Phase 3: Page Structure & Candidate Answer Passages
1. **H1 & Title Tag Optimization:** Verify single H1 per page, inclusion of Central Entity + Qualifier (Year/Location), under 60 chars.
2. **Candidate Answer Passages (Snippet Readiness):** Check if question H2s are immediately followed by a bolded/direct 40–50 word answer passage.
3. **Contextual Flow & Hierarchy:** Check logical order (What → Why → How → What Else) and verify Table of Contents (TOC) presence.

### Phase 4: Semantic Writing & NLP Compliance Audit
1. **Information Density & Fluff Check:** Ensure high ratio of factual data, numbers, and dates. Remove fluff words ("basically", "very", "really").
2. **Factuality & Certainty:** Eliminate opinions ("I think") and analogies ("flies like a cheetah"). Use direct active-voice Subject-Verb-Object sentences.
3. **Attribute Coverage & E.A.V:** Check if key objective attributes (specs, measurements, facts) are structured using lists and HTML tables.
4. **Coreference & Disambiguation:** Check for ambiguous pronouns ("it", "he") and ensure context words exist in the first paragraph.

### Phase 5: E-E-A-T & Technical Schema Audit
1. **Author Rank & Bios:** Check for real author profiles, headshots, detailed bios, and social/corroboration links.
2. **Schema Markup Integration:** Validate JSON-LD schemas (`Article`, `Product`, `Organization`, `FAQPage`, `BreadcrumbList`).
3. **Image Alt Text & Naming:** Verify descriptive filenames (e.g., `sindhi-biryani-recipe.jpg`) and detailed Alt Text.

### Phase 6: Interactive Step-by-Step Action Plan
1. Compile all audit findings into a prioritized `semantic_seo_audit_plan.md`.
2. Present **Step 1** to the user with exact instructions, code snippets, or text rewrites.
3. Once Step 1 is done, check it off and proceed to **Step 2**.

---

## 🛠️ Output Format for Audit Reports

When executing an audit, format the report as follows:

```markdown
# 🔍 Semantic SEO Audit Report: [Target URL / Site Name]

## Executive Summary
- **Central Entity:** [Identified Entity]
- **Source Context Status:** [Focused / Distorted]
- **Topical Authority Score:** [Low / Medium / High]

## 🛠️ Step-by-Step Fix List (1 Step at a Time)

- [ ] **Step 1:** [Immediate High-Impact Fix]
- [ ] **Step 2:** [Second Priority Fix]
- [ ] **Step 3:** [Third Priority Fix]
...

---

### ▶️ CURRENT TASK: Step 1 — [Task Title]
**Issue:** [What is currently wrong based on Semantic SEO rules]  
**Fix:** [Exact instructions / rewritten code / new content]  

*Let me know when you've applied Step 1 (or ask me to apply it), and we will move to Step 2!*
```
