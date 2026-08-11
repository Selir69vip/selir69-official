# Technical SEO — SELIR69

This document outlines the technical SEO framework used within the SELIR69 digital project.

Technical SEO focuses on ensuring that websites can be efficiently accessed, crawled, rendered, and understood by search engines while maintaining a fast and reliable experience for users.

---

## Technical SEO Objectives

The primary technical objectives include:

- Maintain crawlable website architecture
- Ensure important pages are indexable
- Use consistent canonical URLs
- Maintain valid XML sitemaps
- Configure crawler directives correctly
- Improve website performance
- Maintain mobile compatibility
- Implement HTTPS correctly
- Reduce duplicate URLs
- Maintain structured internal linking
- Use structured data where appropriate

Technical implementation should support both search accessibility and user experience.

---

## Crawlability

Search engines need to access important website resources before content can be evaluated for indexing.

Technical reviews should verify:

- HTTP response codes
- Internal links
- Robots directives
- Redirect behavior
- JavaScript accessibility
- CSS accessibility
- Server availability

Important public resources should not be unintentionally blocked.

---

## Indexability

A crawlable page is not necessarily indexable.

Pages intended for search visibility should be reviewed for:

- `noindex` directives
- Canonical configuration
- HTTP status
- Duplicate content
- Redirect chains
- Sitemap inclusion

Indexing decisions should correspond with the actual purpose of each URL.

---

## Robots.txt

The `robots.txt` file provides crawler directives for supported search-engine robots.

A configuration should be reviewed carefully before deployment because incorrect directives may prevent important resources from being crawled.

Example structure:

```text
User-agent: *
Allow: /

Sitemap: https://example.com/sitemap.xml
