# AI SEO Content Quality Reviewer

## 1. Objective

Review AI-generated SEO content to identify issues with search intent, readability, keyword usage, structure, internal linking, and factual accuracy.

## 2. Input

The reviewer accepts:
- Blog title
- Target audience
- Primary keyword
- Secondary keywords
- Search intent
- Generated blog content
- Suggested internal links

## 3. AI Review Prompt

Act as an SEO content editor.

Review the SEO blog content provided below.

Evaluate the content using these criteria:

1. Search Intent
   - Does the content address the reader's search intent?
   - Does it answer the main question?

2. SEO Title and Meta Description
   - Is the title clear and relevant?
   - Is the meta description informative and accurate?

3. Heading Structure
   - Is there one clear main H1 heading?
   - Are H2 and H3 headings organized logically?

4. Keyword Usage
   - Is the primary keyword included naturally?
   - Are secondary keywords relevant?
   - Is keyword stuffing avoided?

5. Readability
   - Are sentences clear and understandable?
   - Are paragraphs easy to read?
   - Is unnecessary repetition avoided?

6. Content Quality
   - Does the content provide useful information?
   - Are explanations relevant to the target audience?
   - Are unsupported claims identified?

7. Internal Linking
   - Are relevant internal linking opportunities suggested?
   - Are the suggested links related to the topic?

8. Accuracy
   - Identify statistics, claims, business details, or other statements that require verification.
   - Do not assume unverified claims are true.
   - Do not invent sources or facts.

Return the review in this format:

A. Overall Assessment
B. Strengths
C. Issues Found
D. Suggested Improvements
E. Revised SEO Title
F. Revised Meta Description
G. Final Checklist

Do not guarantee search rankings or invent keyword metrics.

## 4. Sample Review

### Content Reviewed
Digital Marketing for Small Businesses: A Beginner's Guide

### Overall Assessment
The article introduces digital marketing strategies in a beginner-friendly format. It covers several relevant channels and provides practical starting points.

### Strengths
- Clear introduction
- Relevant headings
- Suitable for beginners
- Covers multiple digital marketing strategies
- Includes a conclusion and call to action

### Issues Found
- Keyword demand has not been verified.
- No external research sources are included.
- The article could provide more specific examples.
- Internal links are suggested but not connected to actual published pages.

### Suggested Improvements
- Research keywords before finalizing the SEO strategy.
- Add relevant, reliable references when making factual claims.
- Include practical examples for different types of small businesses.
- Add internal links after the related pages are published.
- Review all claims before publishing.

### Revised SEO Title
Digital Marketing for Small Businesses: A Beginner's Guide

### Revised Meta Description
Explore SEO, social media, content marketing, and email marketing strategies that small businesses can use to build an online presence.

### Final Checklist
- [x] Clear title
- [x] Logical heading structure
- [x] Beginner-friendly explanations
- [x] Relevant call to action
- [ ] Keyword research verified
- [ ] Claims and sources checked
- [ ] Internal links added to published pages

## 5. Expected Result

The AI reviewer should identify potential SEO and writing issues and recommend improvements.

Human review is required before publication.
