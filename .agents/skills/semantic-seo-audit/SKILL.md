---
name: semantic-seo-audit
description: Audits websites, articles, and pages against comprehensive Semantic SEO principles (E.A.V., Topical Maps, Content Briefs, Semantic On-Page, Writing Rules, E-E-A-T, N-Grams, and Ecommerce SEO). Generates an interactive, sequential 1-step-at-a-time execution plan detailing exact line-by-line changes for every article.
---

# Semantic SEO Audit Skill (`/semantic-seo-audit`)

When activated, this skill performs an exhaustive, granular Semantic SEO audit of a website, individual article, or page set. It scrutinizes content against the 11 Semantic SEO Clusters and produces an actionable, step-by-step audit report that shows **exact text revisions, structural fixes, and code changes—executing 1 step at a time**.

---

## 🎯 Core Operating Rules

1. **Granular Article-by-Article Inspection:** Do not give vague advice like "improve content." Point out exact sentences, paragraphs, headings, and schema blocks that need changing.
2. **1 Step at a Time Protocol:** Present the overall audit checklist, then zoom in on **Step 1 only**. Give the exact before/after text or code fix, and wait for user confirmation before moving to Step 2.
3. **5th-Grade Relatable Explanation:** Briefly explain *why* each change is being made using simple, logical reasoning.

---

## 🔬 Comprehensive Article & Page Audit Checkpoints

When auditing any article or page, systematically evaluate each of the following 9 areas:

### 1. Title Tag, H1 & Meta Description Audit
- [ ] **Title Tag:** Includes Central Entity + Qualifier (Year/Location/Audience), under 60 characters, keyword near front.
- [ ] **H1 Heading:** Exactly ONE H1 tag per page, similar to Title Tag but slightly varied to capture extra long-tail terms.
- [ ] **Meta Description:** 150–160 characters, includes Central Entity, contains a clear Call-to-Action (CTA).

### 2. Candidate Answer Passage (Featured Snippet) Audit
- [ ] **Direct Answer Passages:** Every question heading (H2) MUST be followed by a 40–50 word self-contained, bolded answer passage in the very next sentence.
- [ ] **Boolean Questions:** Yes/No questions MUST start directly with "Yes," or "No," followed by the explanation.
- [ ] **Signal Phrases:** Uses answer signals ("The main reason is...", "The answer is...") to guide Google's Information Extraction (IE) engine.

### 3. Information Density & Fluff Removal
- [ ] **Fluff Words Check:** Highlight and eliminate contextless words ("basically", "very", "really", "quite", "stuff", "things").
- [ ] **Fact-to-Sentence Ratio:** Ensure every single paragraph contains at least 2–3 verifiable facts, numbers, dates, or measurements.
- [ ] **No Opinions or Analogies:** Convert subjective opinions ("I think this is awesome") and analogies ("flies like a cheetah") into objective data ("has a top speed of 200 km/h").

### 4. E.A.V (Entity-Attribute-Value) & Formatting
- [ ] **Central Entity Focus:** Ensure the article revolves around ONE primary Central Entity.
- [ ] **Objective Attribute Coverage:** Verify key attributes (specs, price, dimensions, history) are covered.
- [ ] **Structured Tables & Lists:** Check that E.A.V pairs are organized in clean HTML tables or bulleted/numbered lists (not walls of text).

### 5. Semantic Writing Rules Compliance (66 Rules)
- [ ] **Sentence Length:** Keep sentences under 20 words.
- [ ] **Active Voice & SRL:** Use active Subject + Verb + Object structure ("Babar Azam hit the ball" instead of "The ball was hit by Babar Azam").
- [ ] **No Sentence-Starting "If":** Rewrite condition clauses so the main statement comes first ("Exercise daily to lose weight, if combined with diet" instead of "If you want to lose weight, exercise daily").
- [ ] **Coreference Resolution:** Replace ambiguous pronouns ("he", "it", "they") with explicit Entity names to prevent Google NLP coreference errors.
- [ ] **Consistent Listing Parts of Speech:** Ensure all items in a bulleted list start with the exact same part of speech (e.g., all starting with action verbs).

### 6. Contextual Flow & Structure
- [ ] **Table of Contents (TOC):** Verify a clickable Table of Contents exists right after the introduction.
- [ ] **Logical Section Flow:** Order content logically (What → Why → How → What Else / FAQs).
- [ ] **Contextual Bridges:** Ensure every section ends with a transitional sentence connecting smoothly to the next H2 topic.

### 7. N-Gram & Disambiguation Check
- [ ] **Missing Competitor N-Grams:** Identify key Bigrams and Trigrams used by top-ranking competitors that are missing in the target article.
- [ ] **First Paragraph Disambiguation:** Check if the first paragraph contains 3–5 context words to resolve polysemy or homonymy.

### 8. Schema & Technical On-Page
- [ ] **JSON-LD Schema:** Check for presence of `Article`, `FAQPage`, `BreadcrumbList`, and `Product`/`Organization` schemas.
- [ ] **Image Optimization:** Check that image filenames are descriptive (e.g., `sindhi-biryani-recipe.jpg`) and Alt Text describes the image concisely.
- [ ] **Anchor Text:** Ensure internal links use descriptive anchor text (zero instance of "Click Here" or "Read More").

### 9. E-E-A-T (Author & Trust)
- [ ] **Author Bio Box:** Check for visible author name, professional headshot, credentials, and social links.
- [ ] **Sources & Citations:** Verify claims are linked to authoritative primary sources or research papers.

---

## 🛠️ Required Output Format During Audits

When conducting an audit, present the results using this exact structure:

```markdown
# 🔍 Granular Semantic SEO Audit: [Article Title / Page URL]

## 📊 Quick Health Summary
- **Central Entity:** [Identified Central Entity]
- **Information Density:** [Low / Medium / High]
- **Featured Snippet Readiness:** [Pass / Needs Fix]
- **Schema Compliance:** [Missing / Partial / Complete]

---

## 🛠️ Step-by-Step Action Plan (Executing 1 Step at a Time)

- [ ] **Step 1:** Fix Title Tag & H1 Alignment
- [ ] **Step 2:** Add 40-Word Candidate Answer Passage under H2
- [ ] **Step 3:** Convert Paragraph 3 to High Information Density & Remove Fluff
- [ ] **Step 4:** Format E.A.V Attributes into HTML Table
- [ ] **Step 5:** Fix Coreference Errors (Pronoun Ambiguity)
- [ ] **Step 6:** Add JSON-LD Schema Code

---

### ▶️ CURRENT TASK: Step 1 — [Task Title]

#### ❌ Current Issue:
[Explain what is currently wrong in simple terms]

#### 📝 Existing Content:
```text
[Paste the exact existing text/code from the article]
```

#### ✅ Recommended Revision (Copy-Paste Ready):
```text
[Provide the exact rewritten text, heading, or code snippet ready for production]
```

#### 💡 Why This Helps SEO:
[1-2 sentences in simple 5th-grade Pakistani relatable tone explaining the benefit]

---

*Reply "Done" or "Apply Step 1" to proceed to Step 2!*
```
