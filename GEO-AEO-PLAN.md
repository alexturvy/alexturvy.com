# GEO/AEO Optimization Plan for alexturvy.com

*Generated: January 27, 2026*

This plan outlines steps to improve your visibility in AI-powered search and chatbots (ChatGPT, Claude, Perplexity, Google AI Overviews). The goal is to be recognized and cited as an expert on TikTok, Instagram, platform studies, memes, and digital culture.

---

## What You Already Have Going For You

- Peer-reviewed publications with DOIs
- Major media mentions (Washington Post, WIRED, Reuters, Tech Crunch, etc.)
- Person schema markup on your site
- Active academic affiliations (TCRN, AoIR, Tulane CCC, ASA)
- Consistent cross-platform presence

---

## Phase 1: Highest Priority (Do First)

### 1.1 Create a Wikidata Entry

Wikidata is the #1 source for Google's Knowledge Graph. This directly feeds AI entity recognition.

**Steps:**
1. Go to https://www.wikidata.org
2. Create an account
3. Click "Create a new Item"
4. Add these properties:
   - **Label**: Alex Turvy
   - **Description**: American media sociologist and UX researcher
   - **instance of** (P31): human (Q5)
   - **occupation** (P106): sociologist (Q37226), researcher (Q1650915)
   - **field of work** (P101): platform studies, digital culture, meme studies, social media
   - **employer** (P108): [your current affiliation if applicable]
   - **educated at** (P69): Tulane University (Q578909)
   - **official website** (P856): https://alexturvy.com
   - **ORCID iD** (P496): [your ORCID]
   - **Google Scholar author ID** (P1960): [your Google Scholar ID]
   - **X username** (P2002): soc_of_internet

**Time estimate**: 30-45 minutes

---

### 1.2 Optimize Google Scholar Profile

Your Google Scholar profile feeds into Knowledge Panels and AI recognition.

**Checklist:**
- [ ] Profile is set to PUBLIC
- [ ] Professional photo uploaded
- [ ] Institutional email verified
- [ ] Affiliation listed
- [ ] Homepage URL points to alexturvy.com
- [ ] "Areas of interest" explicitly include:
  - TikTok
  - Instagram
  - platform studies
  - memes
  - digital culture
  - social media research
  - content moderation
  - platform governance

**Find your profile**: https://scholar.google.com

---

### 1.3 Set Up / Optimize ORCID

ORCID creates a persistent digital identifier that AI systems can verify.

**Checklist:**
- [ ] Create account at https://orcid.org if you don't have one
- [ ] Add all publications
- [ ] Link to Google Scholar
- [ ] Add employment history
- [ ] Add education (Tulane PhD)
- [ ] Set visibility to PUBLIC

**Then**: Add your ORCID URL to your website's schema markup (see Phase 2).

---

## Phase 2: Website Schema Enhancements

### 2.1 Expand Person Schema Markup

Your current schema is good. Enhance it by adding these properties to the JSON-LD in `index.html`:

```json
{
  "@context": "https://schema.org",
  "@type": "Person",
  "name": "Alex Turvy",
  "alternateName": "Alex Turvy, PhD",
  "description": "Media sociologist and UX researcher studying how people socialize on TikTok and Instagram",
  "url": "https://alexturvy.com",
  "image": "https://alexturvy.com/assets/images/alex.png",
  "sameAs": [
    "https://twitter.com/soc_of_internet",
    "https://bsky.app/profile/alexturvy.bsky.social",
    "https://www.linkedin.com/in/alexturvy/",
    "https://instagram.com/alexturvy",
    "https://scholar.google.com/citations?user=YOUR_ID_HERE",
    "https://orcid.org/YOUR_ORCID_HERE"
  ],
  "jobTitle": "Media Sociologist and UX Researcher",
  "knowsAbout": [
    "TikTok",
    "TikTok research",
    "Instagram",
    "Instagram research",
    "platform studies",
    "meme culture",
    "memes",
    "digital culture",
    "social media research",
    "content moderation",
    "platform governance",
    "UX research",
    "creator economy",
    "algorithmic curation"
  ],
  "hasCredential": {
    "@type": "EducationalOccupationalCredential",
    "credentialCategory": "degree",
    "name": "PhD in Sociology"
  },
  "alumniOf": {
    "@type": "CollegeOrUniversity",
    "name": "Tulane University",
    "url": "https://tulane.edu"
  },
  "affiliation": [
    {
      "@type": "Organization",
      "name": "Tulane Center for Computational Culture",
      "url": "https://ccc.tulane.edu/"
    },
    {
      "@type": "Organization",
      "name": "TikTok Cultures Research Network",
      "url": "https://tiktokcultures.com/"
    },
    {
      "@type": "Organization",
      "name": "Association of Internet Researchers",
      "url": "https://aoir.org/"
    }
  ]
}
```

**Action**: Replace the existing `<script type="application/ld+json">` block in `index.html` with this expanded version (after filling in your Google Scholar ID and ORCID).

---

### 2.2 Add FAQ Schema (Optional but Helpful)

Consider adding a brief FAQ section to your site with FAQ schema. AI systems extract these well.

Example questions to answer:
- What is your research about?
- What is platform studies?
- How do memes spread on TikTok vs Instagram?

---

## Phase 3: Content Optimization

### 3.1 Create "Answer Capsules"

AI systems love self-contained 2-3 sentence blocks that directly answer questions. Consider adding a "Research Focus" section or expanding your intro with extractable statements like:

> "My research examines how TikTok and Instagram's design shapes cultural production. I study how algorithmic recommendation, interface affordances, and platform governance influence what content gets created, how it spreads, and what it means."

> "Memes are not just jokes—they're a form of cultural participation that reveals how platforms structure creativity and social connection."

These get cited more than prose paragraphs.

---

### 3.2 Keep Content Fresh

AI systems heavily favor recently updated content (76% of most-cited pages updated in last 30 days).

**Monthly habit**: Update the "Last updated" date and make at least one small content change monthly.

---

## Phase 4: Platform Presence

### 4.1 Cross-Platform Consistency Check

Ensure your name, title, and expertise are described identically across:

| Platform | URL | Status |
|----------|-----|--------|
| Personal website | alexturvy.com | [ ] Verified |
| Google Scholar | scholar.google.com | [ ] Verified |
| ORCID | orcid.org | [ ] Verified |
| LinkedIn | linkedin.com/in/alexturvy | [ ] Verified |
| Twitter/X | twitter.com/soc_of_internet | [ ] Verified |
| Bluesky | bsky.app/profile/alexturvy.bsky.social | [ ] Verified |
| Instagram | instagram.com/alexturvy | [ ] Verified |
| University faculty page (if applicable) | | [ ] Verified |

**Check for**: Same spelling of name, similar bio language, same expertise terms.

---

### 4.2 Reddit Engagement (Optional)

40%+ of ChatGPT citations reference Reddit discussions. Consider occasional authentic engagement in relevant subreddits:

- r/TikTok
- r/socialmedia
- r/AcademicPhilosophy
- r/media_criticism
- r/UXResearch

Don't self-promote—just participate in discussions where your expertise is relevant.

---

## Phase 5: Wikipedia (Longer-Term)

Wikipedia represents ~22% of LLM training data. Being mentioned in Wikipedia dramatically improves AI citation rates.

### Notability Assessment

You may meet Wikipedia's notability guidelines based on:
- Multiple peer-reviewed publications
- Extensive coverage in major outlets (Washington Post, WIRED, Reuters, etc.)
- Expert commentary in national/international media

### Important Rules

- **Do NOT create your own Wikipedia page** (against Wikipedia guidelines)
- **Do NOT pay a service to create one** (often results in deletion)
- Focus on continuing to be cited by third-party reliable sources
- If you become notable enough, someone else may create a page, or you can request one through Wikipedia's "Articles for Creation" process with full disclosure

### Alternative: Get Mentioned in Existing Articles

Look for Wikipedia articles where you could legitimately be cited as a source:
- TikTok article
- Internet meme article
- Platform studies article
- Articles about specific memes or trends you've researched

---

## Phase 6: Monitoring

### Monthly Check-In

Search for yourself in AI systems to see how you're being represented:

1. **ChatGPT**: "Who researches TikTok and memes?" / "Who is Alex Turvy?"
2. **Claude**: Same queries
3. **Perplexity**: Same queries
4. **Google AI Overview**: Search your research topics

Note:
- Are you being mentioned?
- Is the information accurate?
- What sources are being cited instead?

---

## Quick Reference: Key Stats

| Factor | Impact |
|--------|--------|
| Brand/name search volume | #1 predictor of AI citations |
| Cross-platform presence (4+ platforms) | 2.8x citation increase |
| Content updated in last 30 days | 76% of most-cited pages |
| Clear H2/H3 structure | 40% more likely to be cited |
| Including statistics | 30-40% higher visibility |
| Wikipedia mention | ~22% of LLM training data |

---

## Checklist Summary

### Immediate (This Week)
- [ ] Create Wikidata entry
- [ ] Optimize Google Scholar profile
- [ ] Set up/optimize ORCID
- [ ] Link ORCID ↔ Google Scholar

### Short-Term (This Month)
- [ ] Update website schema markup with expanded properties
- [ ] Add Google Scholar and ORCID URLs to schema `sameAs`
- [ ] Verify cross-platform consistency
- [ ] Add 2-3 "answer capsule" statements to site

### Ongoing
- [ ] Update site content monthly
- [ ] Monitor AI search results quarterly
- [ ] Continue building media mentions and citations

---

## Resources

- [Princeton GEO Research Paper](https://arxiv.org/abs/2311.09735)
- [Wikidata](https://www.wikidata.org)
- [Google Scholar](https://scholar.google.com)
- [ORCID](https://orcid.org)
- [Schema.org Person](https://schema.org/Person)
- [Google Rich Results Test](https://search.google.com/test/rich-results) - test your schema markup
