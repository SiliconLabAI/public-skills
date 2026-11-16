---
name: static-ads
description: Generate on-brand static Meta ads from a brand website URL. Scrape the site and Ad Library, extract style, find messaging gaps, then produce 5 high-converting static ad concepts with headlines, body, and visuals. Use when the user gives a brand URL or asks for static ads, Meta ads, Facebook ads, or ad creatives.
metadata:
  argument-hint: <brand url> [optional ad library url or page name]
---

# static-ads

Turn a brand website into 5 ready-to-use static Meta ads.

## Workflow

1. **Gather brand inputs**
   - Open the brand website. Extract colors, fonts, logo, tone of voice, main offers, and key product images.
   - Search Meta Ad Library for the brand (or use any provided Ad Library link). Note the angles, headlines, and formats currently running.
   - Summarize what the brand already says and what it does **not** say.

2. **Create a short style guide** (keep under 15 lines)
   - Primary and secondary colors (hex)
   - Typography feel
   - Visual style (clean, lifestyle, product-focused, etc.)
   - Copy rules (short headlines, benefit-first, etc.)

3. **Propose 5 ad ideas**
   - Each idea targets a gap the current ads miss (pain, proof, offer, objection, or new angle).
   - Format for every idea:
     - Visual description (what the image should show)
     - Headline (3–8 words, uppercase preferred)
     - Sub-headline / body (1 short sentence)
     - CTA
   - Show the 5 ideas to the user and wait for approval or changes before generating.

4. **Generate the ads**
   - Create one high-quality static image per idea in 4:5 or 1080×1350 ratio.
   - Match the brand colors, logo placement, and style guide exactly.
   - Place the exact headline and CTA text in the image (or provide clean overlay versions).
   - Deliver final images + the copy text for each ad.

5. **Output**
   - Folder or zip with the 5 images named clearly.
   - A short markdown summary with the 5 concepts and full copy ready to paste into Meta Ads Manager.

## Rules

- Always start with the live website + Ad Library research. Do not invent brand colors or voice.
- Prefer benefit and pain angles that competitors are not already using.
- Keep headlines short and punchy. Never invent fake social proof or handles.
- Ask for confirmation on the 5 ideas before spending generation credits.
- If the user only wants copy or only wants images, do only that part.

## About

This skill guides Manus to use its web scraping and image generation capabilities for a complete static ad workflow. No external accounts required beyond what Manus already has.