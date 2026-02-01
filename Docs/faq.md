![Indexa](../Assets/indexa.png)

# Frequently Asked Questions (FAQ) - Indexa

**Last Updated:** February 1, 2026

---

## General Questions

### What is Indexa?

Indexa is a **privacy-first search engine** built to provide Google-level search quality without surveillance advertising or user tracking.

**Key Features:**
- Independent search index (not a Google proxy)
- Semantic search with AI understanding
- Dufus AI assistant for conversational search
- Image and shopping search
- 100% anonymous - no user tracking
- Self-hostable and open-source friendly

### How does Indexa differ from Google?

| Feature | Indexa | Google |
|---------|--------|--------|
| **Privacy** | Anonymous searches, no tracking | Tracks behavior across web |
| **Ads** | None (contextual in future) | Behavioral ads everywhere |
| **Data Selling** | Never | Builds profiles to sell |
| **AI Integrated** | Dufus local AI | ChatGPT partnership |
| **Self-Hosted** | Available | Not possible |
| **Business Model** | Privacy-first premium tiers | Surveillance capitalism |

### Is Indexa free?

**Yes!** Core search is completely free:
- Unlimited searches
- Image search
- Shopping search
- Basic API access

**Optional paid features** (coming soon):
- Dufus AI Premium
- Advanced search analytics
- API higher rate limits
- Ad-free experience

### Where is Indexa based?

Indexa Inc. is based in the **United States** (Delaware incorporation).

**Server locations:**
- Primary: Home server infrastructure (US)
- CDN: Cloudflare global network
- Backups: [Coming soon]

### Is Indexa safe to use?

**Yes, absolutely:**
- HTTPS encryption on all connections
- No malware or tracking scripts
- Passwords hashed with bcrypt
- Regular security audits
- Cloudflare DDoS protection
- Bug bounty program available
- No third-party analytics

---

## Search & Features

### How does search work at Indexa?

Indexa uses a **hybrid ranking system** combining:

1. **Full-Text Search (FTS5)** - Traditional keyword matching
2. **Semantic Search** - Understanding query meaning using AI embeddings
3. **PageRank** - Authority based on link analysis
4. **Domain Authority** - Trust score per domain

**Result ranking:** 60% text relevance + 20% semantic similarity + 10% PageRank + 10% domain authority

### Why is my search result not at the top?

Indexa prioritizes relevance using multiple signals:

- **Keyword match** - Does page contain your terms?
- **Semantic match** - Is content about your topic?
- **Authority** - Is the source trusted?
- **Freshness** - Is content recent?
- **Domain authority** - How credible is the site?

If you get poor results:
1. Try reformulating your query
2. Use quotes for exact phrases
3. Use minus sign to exclude terms: `python -snake`
4. Check if domain is new/low-authority

### What does "Did you mean?" mean?

**Spell Correction:** If Indexa detects typos, it suggests corrections:
- "javascrpt" → "Did you mean: javascript?"
- "machne learning" → "Did you mean: machine learning?"

**Click the suggestion** to search corrected query.

### How do autocomplete suggestions work?

As you type, Indexa suggests:
- Popular searches
- Auto-complete terms
- Related queries
- Product names (shopping)

**Keyboard navigation:**
- Arrow keys to select
- Enter to search
- Escape to dismiss

**All anonymous** - suggestions don't track who searches.

### What is Dufus AI?

**Dufus** (Data-Unified Functional Understanding System) is Indexa's conversational AI assistant.

**Current Status:** Coming Soon (infrastructure validation in progress)

**Features (when available):**
- Chat with AI about search topics
- AI summarizes search results
- Code generation and explanation
- Multi-turn conversations
- Image understanding
- Video summarization (future)

**Privacy:**
- Not trained on your data
- Conversations temporary (browser cache only)
- No personal data in responses
- Runs on local LLaMA model

### How is Image Search different?

Image Search lets you find images across indexed pages:
- Search by description, not just filename
- Alt text and surrounding content indexed
- BM25 ranking for relevance
- Source page linked
- Dimensions and metadata included

**NOT reverse image search** - use Google Images or Bing for that.

### What is Shopping Search?

Shopping Search finds products across indexed e-commerce sites:
- Price filtering and comparison
- Rating/review filtering
- Brand filtering
- Category browsing
- Trending products
- Best-deal detection

**Current Coverage:**
- Croma, Vijay Sales, Myntra (India)
- Expanding globally

### Can I use API for commercial purposes?

**Yes!** Our API is available for:
- Developers building apps
- E-commerce platforms
- Content aggregators
- Research projects
- AI/ML applications

**Pricing tiers:**
- Free: 1,000 queries/month
- Startup: $49/month (10K queries)
- Business: $199/month (100K queries)
- Enterprise: Custom pricing

See [API Documentation](https://indexa.in/api/docs)

---

## Privacy & Security

### Does Indexa track me?

**No. We explicitly don't track:**
- Your IP address (except rate limiting)
- Your search history
- Your location
- Your device fingerprint
- Your browsing behavior
- Your identity

**What we might collect (only if logged in):**
- Email address (account verification)
- Preferences you set
- Optional search history (if enabled)

See [Privacy Policy](privacy.md) for full details.

### Can I search anonymously?

**Yes!** All searches are anonymous by default:
- No login required
- No search history stored
- No tracking cookies
- No analytics
- No personal data collected

Create an account only if you want:
- Saved search history
- Personalized settings
- Dufus AI history
- Shopping wishlist

### Is my password safe?

**Yes:**
- Passwords hashed with bcrypt (industry standard)
- Never stored in plaintext
- Never logged or backed up
- Salted with 12-round iterations
- Even our admins can't see your password

### Does Indexa sell my data?

**No.** We explicitly do NOT:
- Sell personal data
- Sell search queries
- Sell tracking information
- Build behavioral profiles
- Share data with advertisers
- License data to third parties

**Only sharing:** Law enforcement with valid warrant/subpoena

### What about cookies?

We use **only essential cookies:**
- Session ID (login state)
- Preferences (language, UI settings)
- CSRF token (security)

**What we DON'T use:**
- Tracking cookies
- Behavioral cookies
- Analytics cookies
- Third-party cookies

**Delete anytime** in browser settings.

### Is Indexa GDPR compliant?

**Yes:**
- GDPR rights implemented
- Data Protection Officer appointed
- Right to access, delete, export
- No tracking without consent
- Standard Contractual Clauses signed
- EU data transfers safe

**Submit requests:** privacy@indexa.in

### What about CCPA (California)?

**Yes:**
- CCPA rights honored
- Right to know what we collect
- Right to delete
- Right to opt-out of sale (we don't sell)
- No discrimination for exercising rights

See [Privacy Policy](privacy.md) section 7.2

### Can I report a privacy issue?

**Yes:**
- Email: privacy@indexa.in
- Response time: 15-30 days
- Sensitive issues: security@indexa.in
- Bug bounty program available

---

## Accounts & OwlGuard

### Do I need an account?

**No.** Accounts are optional:
- **Without account:** Fully anonymous search
- **With account (OwlGuard):** Optional features like search history

### How do I create an account?

**Coming Soon!** OwlGuard is in beta:
1. Click "Sign Up" (when available)
2. Enter email
3. Create password
4. Verify email
5. Start using account

**Currently:** All features work anonymously

### Can I delete my account?

**Yes, anytime:**
- Settings → Account → Delete Account
- Or email: support@indexa.in
- All data deleted within 30 days
- Cannot be undone

### Can I change my email?

**Yes:**
- Settings → Account → Update Email
- Verify new email
- Old email no longer associated

### I forgot my password

**Password reset:**
1. Click "Forgot Password" on login
2. Enter email address
3. Check email for reset link
4. Create new password
5. Login with new password

**Reset link expires** in 24 hours.

### Can I have multiple accounts?

**Yes, but:**
- Each email address = separate account
- Using multiple accounts for abuse may result in ban
- Automated account creation violates Terms
- Reselling accounts violates Terms

### What is my data used for?

If you have an account:
- **Account management:** Verify identity, maintain security
- **Search history:** Remember your preferences (optional)
- **Analytics:** Improve search quality (anonymized)
- **Support:** Help with account issues

**Never for:**
- Selling to third parties
- Building behavioral profiles
- Training AI on your data
- Targeted advertising

---

## Troubleshooting

### Why are my results in another language?

**Language detection:**
- Indexa detects your browser language
- Results match your language preference
- Change language in Settings

**To search another language:**
- Use language prefix: `python site:es.wikipedia.org`
- Use language filter in Advanced Search (coming soon)

### Why did my search get no results?

**Possible reasons:**
1. **Spelling error** - Check "Did you mean?" suggestion
2. **Too specific** - Try broader terms
3. **New content** - We update index regularly
4. **Not indexed yet** - Some sites take time to crawl
5. **Blocked by robots.txt** - Site may disallow indexing

**Try:**
- Simplify your query
- Remove uncommon terms
- Search parent domain instead

### Why is search slow?

**Possible causes:**
1. **Complex query** - Semantic search takes time
2. **Network latency** - Your connection
3. **Server load** - High traffic (rare)
4. **Browser issue** - Try clearing cache

**Typical response:** 50-200ms

**If slow (>2 sec):**
- Try again (may be temporary)
- Report to support@indexa.in
- Share your query

### Why can't I see my image?

**Image indexing issues:**
- Image URL changed or removed
- Site blocks image indexing
- Image too new (recent crawl needed)
- Image copyrighted (DMCA removed)

**To index an image:**
- Email: support@indexa.in
- Include image URL
- Request manual indexing (if applicable)

### Why can't I find a product?

**Shopping coverage:**
- Currently: India only (Croma, Vijay, Myntra)
- Global expansion: Coming soon
- New sites: Suggest at support@indexa.in

**Not indexed:**
- Product too new
- Site hasn't been crawled yet
- Product out of stock

### How do I report a bug?

**Report issues:**
1. Email: support@indexa.in
2. Include: What you did, what happened, expected result
3. Attach: Screenshots if helpful
4. Browser: Chrome/Firefox/Safari version

**Critical security bugs:**
- Email: security@indexa.in
- Responsible disclosure required

---

## Technical Questions

### What data is indexed?

Indexa indexes:
- Page titles and URLs
- Text content
- Headings and subheadings
- Metadata (author, date)
- Images and alt text
- Structured data (schema.org)

**NOT indexed:**
- Private/password-protected pages
- Pages blocked by robots.txt
- JavaScript-only content (unless rendered)
- Duplicate content (SimHash detection)

### How often is the index updated?

**Crawl frequency:**
- Popular sites: Weekly crawl
- Medium sites: Monthly crawl
- New sites: As discovered
- Total index: [size TBD] documents

**Content changes:**
- Updates within 2-4 weeks typically
- Urgent updates: Manual request to support

### Does Indexa crawl all websites?

**No.** We respect:
- **robots.txt** files
- **Crawl-delay** directives
- **Noindex** meta tags
- **User-Agent blocking**
- **Rate limiting**

**Not crawled:**
- Private sites (login required)
- Paywalled content
- Adult content (minimal)
- Spam/malware

### Can I block Indexa from crawling my site?

**Yes, using robots.txt:**

```
User-agent: Indexa
Disallow: /private/
Crawl-delay: 10
```

**Or meta tag:**
```html
<meta name="robots" content="noindex">
```

See [Crawling Guide](https://indexa.in/crawl-guide)

### Does Indexa use my website for training AI?

**No:**
- Your content not used for model training
- Your content not fine-tuned into Dufus
- Your content only indexed for search
- You can opt-out via robots.txt

### How can I submit my site?

**Manual submission:**
1. Email: crawl@indexa.in
2. Include: URL, description
3. We will crawl and index

**Automatic discovery:**
- Submit sitemap.xml to crawl@indexa.in
- Indexa will follow links automatically
- Crawl-delay respected

---

## Advertising & Business

### Does Indexa have ads?

**Current:** No ads (completely ad-free)

**Future plans:**
- Optional contextual ads (keyword-based, not behavioral)
- Affiliate links in shopping search
- Clear "Sponsored" labeling
- Can be disabled for premium users

### Can I advertise on Indexa?

**Coming soon!** We're planning:
- Contextual ad program
- Keyword bidding
- Shopping feed partnerships
- Affiliate programs

**Interest?** Email: business@indexa.in

### How can I monetize my content on Indexa?

**Shopping:**
- List products in shopping search
- Affiliate opportunities (coming soon)
- Featured product placements

**Contact:** business@indexa.in

### Can I use Indexa for my app/business?

**Yes!** Multiple options:
- **White-label search** - Embed Indexa on your site
- **API access** - Build custom applications
- **Data licensing** - Access search data
- **Partnerships** - Special integrations

**Contact:** business@indexa.in

---

## Performance & Scaling

### How fast is Indexa?

**Search response times:**
- Cached results: 10-20ms
- Fresh search: 50-200ms
- Complex semantic: 200-500ms

**Typical experience:**
- Results appear in <500ms
- Image search: <1 second
- Dufus AI: <2 seconds (streaming)

### Can I use Indexa on mobile?

**Yes!**
- Full mobile browser support
- Responsive design
- Touch-optimized interface
- App (coming soon for iOS/Android)

### Is Indexa available offline?

**Not yet.** Planned features:
- Offline search of saved results
- Download search index (local)
- Self-hosted version (coming)

### Can I host Indexa myself?

**Yes!** Self-hosting options:

**Home Server (Current):**
- Deploy on your PC/Mac/Linux
- Full search engine locally
- Instructions coming soon

**Enterprise Self-Hosted (Future):**
- Docker containers
- Kubernetes deployment
- SLA and support

**Interest?** Email: enterprise@indexa.in

---

## Legal & Terms

### What are your Terms of Service?

See full [Terms of Service](terms.md)

**Key points:**
- Use license for personal/non-commercial use
- Prohibited: Illegal activity, abuse, scraping
- Liability limited to $100 or amount paid
- Binding arbitration for disputes
- Delaware law governs

### What is your Privacy Policy?

See full [Privacy Policy](privacy.md)

**Key points:**
- Queries not permanently stored
- No tracking or profiling
- Data encrypted in transit/at rest
- GDPR, CCPA, PIPEDA compliant
- Right to access, delete, export

### Can I use Indexa search results commercially?

**Yes, with conditions:**
- **Personal use:** Unlimited
- **Commercial use:** 
  - Must attribute Indexa as source
  - Must not copy entire results page
  - Must link back to our results
  - API pricing for bulk use

### Do you have a bug bounty program?

**Yes!**
- Report security issues: security@indexa.in
- Responsible disclosure required
- Rewards available for valid vulnerabilities
- Confidentiality guaranteed

### How do I contact support?

**Support channels:**
- Email: support@indexa.in
- Response time: 2-3 business days
- For urgent issues: Flag "URGENT"

**Specific topics:**
- Privacy: privacy@indexa.in
- Legal: legal@indexa.in
- Security: security@indexa.in
- Bugs: support@indexa.in
- DMCA: dmca@indexa.in

---

## Getting Help

### I have a question not covered here

**Contact us:**
- Email: support@indexa.in
- Include: Your question, context, any details
- We'll add it to this FAQ if common

### How can I suggest a feature?

**Feature requests:**
- Email: feedback@indexa.in
- Describe what you want
- Explain why you need it
- We review all suggestions

### How can I report inappropriate content?

**Content reports:**
- Email: abuse@indexa.in
- Include: Search term or URL
- Describe the issue
- Provide details

**For DMCA/Copyright:**
- Email: dmca@indexa.in
- Include: Copyright holder info
- Attach: Copyright notice

### Where can I learn more about Indexa?

**Resources:**
- [Blog](https://indexa.in/blog)
- [Documentation](https://indexa.in/docs)
- [API Guide](https://indexa.in/api)
- [Tech Stack](https://indexa.in/tech-stack)
- [GitHub](https://github.com/indexa-search)

### How do I stay updated?

**Latest news:**
- [Subscribe to newsletter](https://indexa.in/newsletter) (coming soon)
- [Follow us on X/Twitter](https://twitter.com/indexa_search) (coming soon)
- [Read our blog](https://indexa.in/blog)

---

## Quick Links

- [Privacy Policy](privacy.md)
- [Terms of Service](terms.md)
- [API Documentation](https://indexa.in/api)
- [Help & Support](https://indexa.in/support)
- [Blog](https://indexa.in/blog)
- [Contact Us](https://indexa.in/contact)

---

**Last Updated:** February 1, 2026  
**Version:** 1.0  
**Status:** Ready for Public Launch

---

## Contact

**General Support:** support@indexa.site  
**Privacy Questions:** privacy@indexa.site  
**Technical Support:** tech@indexa.site  
**Business Inquiries:** business@indexa.site

[Back to Documentation](../README.md) • [Privacy Policy](privacy.md) • [Terms of Service](terms.md)

---

<p align="center">
  <sub>© 2026 Indexa Inc. • Still have questions? We're here to help!</sub>
</p>
