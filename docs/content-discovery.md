---
sidebar_position: 3
---

# Content Discovery

Search engines like Google need to **discover** your website before they can **index** or **rank** it.  
Think of it this way, if Google doesn’t know your site exists, it can’t show it in search results.

In this section, we’ll look at how Google finds your website and how you can help speed up the discovery process.

---

## Ways to Let Google Know About Your Website

There are several ways Google can discover your content:

### 1. **Manually via Google Search Console**

You can directly **submit your website** or **specific URLs** to Google using [Google Search Console](https://search.google.com/search-console).

Once verified, you can:

- Submit your **sitemap.xml**
- Request indexing for new pages
- Monitor crawling errors
- Track impressions and clicks

**Example:**  
If you publish a new blog post, go to **Search Console → URL Inspection → Request Indexing**.  
Google will then prioritize crawling that page.

---

### 2. **Backlinks (External Links)**

When other websites link to your content, Google can **discover your site through those links.**

Backlinks act like **recommendations** they signal to search engines that your site is worth visiting.

**Example:**  
If a popular blog links to your article on “Best Mugs in Kenya,” Google’s crawlers will follow that link and discover your page even if you never submitted it manually.

:::tip
Backlinks help both **discovery** and **ranking** so aim for high-quality, relevant links, not spammy ones.
:::

---

### 3. **Internal Linking**

Google also discovers new pages through links within your own website.

**Example:**  
If you add a new product page (`/mugs-collection`) and link to it from your homepage or blog, Google’s bots will follow that internal link and index the new page.

**Good practice:**

- Always link new pages from your main content
- Maintain a clear site structure (categories, menus, sitemaps)

---

### 4. **XML Sitemap**

A **sitemap** is a file (usually at `yourdomain.com/sitemap.xml`) that lists all the important pages on your site.  
It helps Google know what to crawl and when pages were last updated.

SEO plugins like **Yoast** or **RankMath** automatically generate sitemaps for WordPress.

**Benefits:**

- Faster discovery of new or updated pages
- Better coverage of your site’s structure

---

### 5. **Social Media Mentions**

While social media links are usually “no-follow,” they still help discovery because they **drive traffic** and **expose URLs** to crawlers.

If your new post is shared widely on X (Twitter), Facebook, or LinkedIn chances are, Google will pick it up faster.

---

### 6. **RSS Feeds**

For blogs or news sites, RSS feeds provide another route for crawlers to find new content quickly.

Make sure your RSS feed is:

- Updated automatically when new content is published
- Linked in your site’s header or footer

---

## How Google Decides What to Index

Just because a page is discovered doesn’t mean it’s indexed.

Google evaluates:

- **Content quality** (original, useful, readable)
- **Crawlability** (no `noindex` tags, accessible by bots)
- **Relevance** (matches what people search for)
- **Duplicate content** (avoiding multiple pages with same info)

:::info
To check if your page is indexed, search:
**site:yourdomain.com/page-name**

:::
