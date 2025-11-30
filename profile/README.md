# CapCheck

The core verification infrastructure powering independent fact-checking for the internet.

## What This Is

CapCheck.ai houses the technical infrastructure that powers the nonprofit's educational tools and research initiatives. We're building the verification platform that enables media literacy education and advances fact-checking research.

**Operated by:** CapCheck (501c3 nonprofit)  
**Purpose:** Support education and research in media literacy and fact-checking  
**License:** AGPL-3.0 (open source, protects educational mission)

## Our Repositories

### Platform Core
- **[api](https://github.com/capcheck-ai/platform)** - GraphQL API and verification engine

## Current Architecture

- **Backend:** Hasura GraphQL, PostgreSQL
- **Verification:** Claude Sonnet 4.5 (primary), Claude Haiku (lightweight tasks)
- **Content Processing:** OpenAI Whisper (audio/video), Brave Search
- **Cost:** ~$0.0075 per verification in production

## Future Direction

We're pivoting to smaller, custom-trained models based on the principle that **truth should be simple**. Goals:

- Train 3B and 7B parameter models for fact-checking
- Enable local execution (complete privacy, offline capability)
- Reduce costs 10x while maintaining accuracy
- Partner with Nous Research Thinking Machines API

## Getting Started

**API Access (Coming Soon):**
```bash
# Get free API key (1,000 verifications/month)
curl https://api.capcheck.ai/v1/keys -d '{"email":"you@example.com"}'
```

**Documentation:** (coming soon)  
**API Status:** (coming soon)  
**Contact:** aaron@capcheck.ai

## Contributing

All infrastructure is open source to advance fact-checking research. We welcome:

- Performance optimizations and efficiency improvements
- Novel verification approaches and methodologies
- Research-validated model improvements
- Educational use case integrations
- Bug fixes and documentation

Check individual repos for contribution guidelines.

## Links

- 🌐 **Nonprofit:** [capcheck.org](https://capcheck.org)
- 📧 **Email:** aaron@capcheck.ai

---

*Built in the open by CapCheck 501(c)(3) for education and research. Platform access supports our nonprofit mission.*
