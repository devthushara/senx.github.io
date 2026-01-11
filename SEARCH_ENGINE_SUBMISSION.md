# Search Engine Submission Guide

## 🔍 Submit Your Website to Search Engines

### 1. Google Search Console (PRIORITY #1)

**URL:** https://search.google.com/search-console

**Steps:**
1. Go to Google Search Console
2. Click "Add Property"
3. Enter: `https://www.senexholdings.com`
4. Verify ownership (choose HTML file upload method or meta tag)
5. Once verified, go to "Sitemaps" in left menu
6. Submit: `https://www.senexholdings.com/sitemap.xml`
7. Click "Submit"

**Benefits:**
- Monitor search performance
- See which keywords bring traffic
- Identify and fix crawl errors
- Submit URLs for immediate indexing
- View mobile usability issues

---

### 2. Bing Webmaster Tools

**URL:** https://www.bing.com/webmasters

**Steps:**
1. Sign in with Microsoft account
2. Click "Add a site"
3. Enter: `https://www.senexholdings.com`
4. Verify ownership
5. Submit sitemap: `https://www.senexholdings.com/sitemap.xml`

**Benefits:**
- Powers Bing, Yahoo, DuckDuckGo search
- Provides SEO insights and recommendations
- Keyword research tools
- Site scan for errors

---

### 3. Google Business Profile (Local SEO)

**URL:** https://www.google.com/business/

**Steps:**
1. Search for "SeneX Holdings" on Google
2. Click "Claim this business" if listed
3. If not listed, create new profile
4. Add complete information:
   - Both locations (Nugegoda & Matara)
   - Phone numbers
   - Business hours
   - Categories: "Solar energy equipment supplier", "Solar energy company"
   - Photos of installations
   - Services offered
   - Website URL
5. Verify your business (postcard, phone, or email)

**Benefits:**
- Appear in Google Maps
- Show up in "near me" searches
- Display in Local Pack (top 3 results)
- Customer reviews and ratings
- Direct calls and messages

---

### 4. IndexNow (Instant Indexing)

**URL:** https://www.indexnow.org/

IndexNow allows you to notify search engines immediately when content changes.

**Supported by:**
- Bing
- Yandex
- Naver
- Seznam.cz

**How to use:**
```bash
# Submit URL via API (example)
curl -X POST "https://api.indexnow.org/indexnow" \
  -H "Content-Type: application/json" \
  -d '{
    "host": "www.senexholdings.com",
    "key": "YOUR_API_KEY",
    "urlList": [
      "https://www.senexholdings.com/"
    ]
  }'
```

**Generate API key:** Create a text file with random string (e.g., `abc123def456.txt`) and place it in your root directory.

---

### 5. Additional Search Engines & Directories

#### Yandex Webmaster (Russia/Eastern Europe)
- **URL:** https://webmaster.yandex.com/
- Submit sitemap
- Useful if targeting international audience

#### Baidu Webmaster Tools (China)
- **URL:** https://ziyuan.baidu.com/
- Chinese language
- Required for visibility in China

---

## 🤖 AI Search Engines

Most AI search engines automatically crawl websites that allow their bots. Your website already allows:
- ✅ GPTBot (ChatGPT)
- ✅ Claude-Web (Claude/Anthropic)
- ✅ PerplexityBot (Perplexity AI)
- ✅ CCBot (Common Crawl - used by many AI)
- ✅ YouBot (You.com)
- ✅ Applebot (Apple Intelligence)

**No manual submission needed!** Just wait for these bots to crawl your site naturally.

---

## 📱 Mobile App Search

### Apple (iOS Spotlight)
Your website will automatically be included in Apple's search results when users search on iOS devices.

### Android (Google Discover)
Integrated with Google Search Console submission.

---

## 📊 Directory Submissions (Sri Lanka Specific)

### Local Business Directories
1. **YellowPages.lk**
   - https://www.yellowpages.lk/
   - List business in "Solar Energy" category

2. **Lanka Pages**
   - https://www.lankapages.com/
   - Sri Lanka's business directory

3. **HiPages LK**
   - https://hipageslk.com/
   - Service provider directory

4. **YourPages.lk**
   - https://www.yourpages.lk/
   - Local directory

### Solar/Energy Specific
5. **Solar Energy Association of Sri Lanka**
   - Get listed as member company
   - Industry credibility

6. **Sri Lanka Sustainable Energy Authority**
   - Register as approved installer
   - Government recognition

---

## 🔗 Backlink Opportunities

### Get quality backlinks from:
1. **Supplier websites** (FoxESS, GoodWe, Huawei, etc.)
   - Ask for partner listing
   - Case study features

2. **Industry publications**
   - Solar Energy News
   - Renewable Energy magazines
   - Submit press releases

3. **Local news websites**
   - News articles about installations
   - Community solar projects

4. **Business associations**
   - Chamber of Commerce
   - Environmental organizations
   - Business networking groups

---

## 📝 Submission Checklist

Before submitting to search engines, ensure:

- [x] robots.txt is accessible (✓ Done)
- [x] sitemap.xml is accessible (✓ Done)
- [x] Website is fully functional on mobile (✓ Done)
- [x] All images have alt tags (✓ Done)
- [x] Meta tags are complete (✓ Done)
- [x] Structured data is valid (Test at: https://search.google.com/test/rich-results)
- [ ] Google Analytics is working
- [ ] Contact forms work correctly
- [ ] All links work (no broken links)
- [ ] HTTPS is enabled (if available)
- [ ] Page load speed is good (<3 seconds)

---

## 🎯 Post-Submission Actions

### Week 1
- Monitor Google Search Console for indexing
- Check for any crawl errors
- Verify structured data is recognized

### Week 2-4
- Start appearing in search results
- Monitor impressions and clicks
- Adjust titles/descriptions if CTR is low

### Month 2-3
- Rankings start to improve
- Rich snippets may appear
- Local pack inclusion possible

### Month 3-6
- Significant traffic growth
- Top rankings for long-tail keywords
- Brand searches increase

---

## 🆘 Troubleshooting

### "Site not indexed yet"
- Wait 3-7 days after submission
- Use "Request Indexing" in Google Search Console
- Check robots.txt isn't blocking
- Ensure no `noindex` meta tags

### "Structured data errors"
- Test with Rich Results Test tool
- Fix errors shown
- Resubmit after fixes

### "Low rankings"
- SEO takes time (3-6 months)
- Keep creating quality content
- Build backlinks gradually
- Improve user engagement metrics

---

## 📞 Need Help?

If you encounter issues:
1. Check Google Search Console Help Center
2. Bing Webmaster Support
3. Consult with an SEO specialist
4. Review SEO_OPTIMIZATION_REPORT.md

---

**Remember:** After submitting, be patient! SEO results take 3-6 months to fully materialize.

**Next Step:** Start with Google Search Console and Google Business Profile today!
