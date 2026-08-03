# 8. N-Grams — The Hidden Word Patterns

Welcome to Chapter 8! N-Grams sound like a math puzzle, but they are actually super simple to understand.

Imagine you are reading a cricket article. You'll see the word "bat" alone, but you'll ALSO see "cricket bat," "batting average," and "batting strike rate" — these are word GROUPS that always appear together. Google counts these patterns to decide if you're a real expert or just pretending!

---

## 1. What are N-Grams: Types, Uses
### What is it?
An **N-Gram** is just a fancy name for "a group of words sitting next to each other."

- **Unigram (1-Gram):** One single word. Example: "Biryani"
- **Bigram (2-Gram):** Two words together. Example: "Chicken Biryani"
- **Trigram (3-Gram):** Three words together. Example: "Spicy Chicken Biryani"
- **4-Gram:** Four words together. Example: "Best Spicy Chicken Biryani"

Why does Google care? Because word groups carry MORE meaning than single words.
- "Bank" alone could mean a river bank or a financial bank (ambiguous!).
- "Bank account" is clearly about finance (unambiguous!).

Google counts the N-Grams on your page and compares them with top-ranking competitors. If competitors all use the Bigram "batting average" and you don't, Google thinks your article is incomplete.

### How to practically use it:
- **Identify the important N-Grams for your topic.** 
  1. Google your target keyword.
  2. Open the top 3 results.
  3. Read through them and note the 2-word and 3-word phrases they ALL use.
  4. Make sure those phrases appear in YOUR article too.
- **Use Bigrams and Trigrams naturally.** Don't force them. They should flow naturally within sentences.
- **Tool tip:** Use free tools like "SEO Scout N-Gram Analyzer" or Google Colab scripts to automatically extract N-Grams from competitor pages.

### Example for a "Biryani Recipe" page:
| N-Gram Type | Important N-Grams to Include |
|------------|------------------------------|
| Unigram | Biryani, Rice, Chicken, Spices |
| Bigram | Chicken Biryani, Basmati Rice, Kewra Water, Cooking Time |
| Trigram | Dum Pukht Method, Saffron Infused Rice, Layer By Layer |

---

## 2. How to Do N-Gram Competitive Analysis
### What is it?
**N-Gram Competitive Analysis** is the process of "spying" on the top-ranking pages for your keyword and finding out which word groups (N-Grams) they use that YOU are missing.

Think of it like this: Before a cricket match, the team watches videos of the opponent. They study their bowling patterns, their batting weaknesses. N-Gram analysis does the same — you study your competitor's text patterns.

### Step-by-Step Process:
1. **Search your target keyword** on Google.
2. **Copy the text of the top 3 results.** (Just the main body content, not navigation or footers.)
3. **Paste each one into an N-Gram analyzer tool** (free tools: TextAnalyzer.net, WriteWords N-Gram Extractor, or a Python script using NLTK).
4. **Get a list of the most common Bigrams and Trigrams** from each competitor.
5. **Compare with YOUR article.** Which N-Grams do ALL competitors use that YOU are missing?
6. **Add the missing N-Grams** to your content naturally.

### How to practically use it:
- **Create a comparison table:**

| N-Gram | Competitor 1 | Competitor 2 | Competitor 3 | My Article |
|--------|-------------|-------------|-------------|-----------|
| Basmati Rice | ✅ | ✅ | ✅ | ❌ MISSING! |
| Cooking Time | ✅ | ✅ | ✅ | ✅ |
| Kewra Water | ✅ | ❌ | ✅ | ❌ MISSING! |

- **Fix the gaps.** Go back to your article and add "Basmati Rice" and "Kewra Water" naturally into your text.
- **Don't copy competitors.** Just use the same N-Grams — but write YOUR own original sentences around them.

---

## 3. What are Unique N-Grams?
### What is it?
**Unique N-Grams** are word groups that appear ONLY on YOUR page and NOT on any competitor's page. They represent your unique expertise and contribution.

Example: If all competitors write about "Chicken Biryani" but ONLY your page mentions "Tawa Biryani" (a pan-fried version), then "Tawa Biryani" is your Unique N-Gram.

Google LOVES Unique N-Grams because they represent **Unique Information Gain** — new information that didn't exist in the search results before.

### How to practically use it:
- **Find Unique N-Grams by researching BEYOND Google.** Read books, watch YouTube videos, talk to experts, visit Reddit forums. Find facts and terms that the top Google results missed.
- **Expert vocabulary = Unique N-Grams.** If you're writing about Cars and you mention "regenerative braking system" (a technical term for electric cars), this is likely a Unique N-Gram that competitors missed.
- **Personal experience creates Unique N-Grams.** "I tested this in Lahore's 45°C summer heat" — no competitor has this because it's YOUR experience.

---

## 4. What are Site-Wide N-Grams?
### What is it?
**Site-Wide N-Grams** are word groups that appear across your ENTIRE website, not just on one page. They include:
- Your brand name (e.g., "TechWala Pakistan").
- Repeated phrases in your header, footer, sidebar, or navigation.
- Words in your site's tagline or slogan.
- Common phrases in your boilerplate content.

These N-Grams tell Google what your entire website is about (your Source Context).

### How to practically use it:
- **Make sure your Site-Wide N-Grams match your topic.** If your site is about "Healthy Cooking," your navigation should include Bigrams like "Healthy Recipes," "Cooking Tips," "Nutrition Guide" — NOT "Buy Electronics" or "Sports News."
- **Audit your footer and sidebar.** What words appear there on EVERY page? If your footer says "Buy Cheap Stuff" on every page, that's a spammy Site-Wide N-Gram that hurts your entire website.
- **Use your brand name consistently.** Always write "TechWala Pakistan" the same way. Don't switch between "techwala," "Tech Wala," and "TECHWALA" — pick one and stick with it.

---

## 5. How to Do Site-Wide N-Gram Optimization
### What is it?
**Site-Wide N-Gram Optimization** is the process of cleaning up, improving, and controlling the word patterns that repeat across your entire website.

### Step-by-Step Process:
1. **Crawl your website** using a tool like Screaming Frog (free for up to 500 URLs).
2. **Extract all text** from headers, footers, sidebars, navigation menus, and tag lines.
3. **Run N-Gram analysis** on the extracted text.
4. **Identify problems:**
   - Spammy N-Grams (e.g., "Buy Now Free Shipping" repeated 200 times).
   - Irrelevant N-Grams (e.g., your footer has a paragraph about sports on a cooking website).
   - Missing N-Grams (e.g., your navigation doesn't mention your main topic).
5. **Fix the problems:** Clean up your boilerplate text. Remove spammy phrases. Add relevant N-Grams to your navigation.

### How to practically use it:
- **Your navigation menu is a powerful N-Gram signal.** If every page on your site has a menu item called "Biryani Recipes," Google sees that Bigram thousands of times across your site. This strongly reinforces your Source Context.
- **Reduce footer bloat.** Keep your footer clean: 3-5 essential links, copyright notice, and nothing more.
- **Check your category names.** Rename vague categories. Instead of "Blog" or "Posts," use descriptive names: "Cricket Guides," "Batting Tips," "Match Reviews."
- **After optimization, re-crawl and verify.** Run the analysis again to make sure the problematic N-Grams are gone.
