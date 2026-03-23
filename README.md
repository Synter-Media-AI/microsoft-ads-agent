# Microsoft Ads MCP Starter Kit — Manage Bing Ads with AI

[![MCP Compatible](https://img.shields.io/badge/MCP-compatible-blue)](https://modelcontextprotocol.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform: Microsoft Ads](https://img.shields.io/badge/Platform-Microsoft%20Ads-00A4EF)](https://ads.microsoft.com)

**The overlooked goldmine of search advertising.** Open this repo in Amp, Cursor, or VS Code and manage Microsoft Ads (Bing, Yahoo, DuckDuckGo) with AI — same search intent as Google, 30% lower CPCs, and an audience that skews toward higher-income professionals.

---

## Why Microsoft Ads + AI?

Microsoft Ads reaches 724 million monthly unique searchers across Bing, Yahoo, AOL, and DuckDuckGo. That's not a rounding error — it's 33% of the US desktop search market.

The secret? Microsoft Ads audiences are disproportionately valuable. Bing is the default search engine on every Windows PC, Xbox, and Edge browser. The typical Bing searcher is older (35-65), higher income, and more likely to work in B2B roles. For many advertisers, the same keyword that costs $8 on Google costs $5 on Bing — with better conversion rates.

The other secret: you can import your entire Google Ads account into Microsoft Ads in one click. Same campaigns, same keywords, same ad copy — just cheaper clicks.

**Best for:** B2B SaaS, financial services, healthcare, legal, real estate, insurance — industries where the older, wealthier Bing demographic converts well. Also excellent as a "free money" supplement to any Google Ads account.

---

## Quick Start (30 Seconds)

### Amp / Cursor / VS Code (Copilot)

1. **Get a free API key** at [syntermedia.ai/developer](https://syntermedia.ai/developer)
2. **Set the key:**
   ```bash
   export SYNTER_API_KEY=syn_your_key_here
   ```
3. **Open this repo** in your editor
4. **Start chatting** — MCP tools are pre-configured in `.mcp.json`

### Claude Desktop

Copy `claude_desktop_config.json` to your Claude config directory and replace the API key:

- **macOS:** `~/Library/Application Support/Claude/claude_desktop_config.json`
- **Windows:** `%APPDATA%\Claude\claude_desktop_config.json`

---

## What You Can Do

| Capability | Example |
|-----------|---------|
| **Import from Google Ads** | "Import my top-performing Google campaigns into Microsoft Ads" |
| **Create Search Campaigns** | "Launch a Search campaign for 'financial planning software' on Bing" |
| **Audience Network** | "Extend my search campaigns to the Microsoft Audience Network" |
| **LinkedIn Targeting** | "Target people in the Finance industry using LinkedIn Profile Targeting" |
| **Shopping Campaigns** | "Set up a Microsoft Shopping campaign with my product feed" |
| **Adjust Bids** | "Increase bids 15% for desktop traffic — Bing desktop converts better" |
| **Keyword Management** | "Add negative keywords from my Google Ads account" |
| **Performance Comparison** | "How does my Microsoft Ads CPA compare to Google for the same keywords?" |
| **Budget Optimization** | "Shift budget from underperforming campaigns to my top 3" |
| **Geographic Targeting** | "Target the Northeast US where Bing market share is highest" |

---

## Example Conversations

### 1. The Google Ads Import Strategy

> **You:** I run $10k/month on Google Ads profitably. Should I try Microsoft Ads?
>
> **Agent:** Absolutely — and you can be live in 15 minutes by importing your Google campaigns.
>
> Here's the play:
> 1. **Import your top Google campaigns** (structure, keywords, ads, and extensions all transfer)
> 2. **Set budgets at 20-30% of your Google budgets** to start (Microsoft has ~1/3 the volume)
> 3. **Reduce bids by 25%** — CPCs are naturally lower on Bing
> 4. **Enable LinkedIn Profile Targeting** (exclusive to Microsoft Ads — target by company, industry, job function)
>
> **Expected results:**
> - 20-35% lower CPCs than Google for the same keywords
> - Similar or better conversion rates (Bing users are older, higher income)
> - You'll likely spend $2,000-3,000/month (less search volume)
> - ROAS is often 20-40% higher than Google
>
> Think of it as free money — same keywords, same ads, cheaper clicks.
>
> **You:** Let's do it. Import my top 3 campaigns by ROAS.
>
> **Agent:** Done. Imported 3 campaigns with 47 ad groups, 312 keywords, and 94 responsive search ads. I've set bids at 75% of your Google bids and budgets at 25%. All campaigns are PAUSED — want me to enable them?

### 2. LinkedIn Profile Targeting (Microsoft Exclusive)

> **You:** I sell HR software. Can I target HR professionals on Bing?
>
> **Agent:** Yes — and here's something Google can't do. Microsoft Ads has **LinkedIn Profile Targeting**, which lets you layer LinkedIn data on top of search campaigns.
>
> I can target people who search for "HR software" AND match these LinkedIn criteria:
> - **Job function:** Human Resources
> - **Company industry:** Technology, Finance, Healthcare
> - **Company size:** 50-1000 employees
>
> This means when someone at a mid-market tech company searches "employee onboarding software" on Bing, you can bid higher — because you know they're a decision-maker, not a student.
>
> **Campaign structure:**
> - Ad group 1: HR software keywords + HR job function targeting (premium bid)
> - Ad group 2: HR software keywords + no LinkedIn targeting (standard bid)
> - This lets you compare performance with and without LinkedIn targeting
>
> **You:** Create both ad groups. $50/day budget.
>
> **Agent:** Created. You'll be able to compare LinkedIn-targeted vs non-targeted performance within a week. In my experience, LinkedIn-targeted clicks convert 40-60% better — worth the higher bid.

### 3. The DuckDuckGo Opportunity

> **You:** Do Microsoft Ads show on DuckDuckGo?
>
> **Agent:** Yes — and it's an underappreciated angle. DuckDuckGo uses Bing's search results and ad network. With ~100 million daily searches, privacy-conscious users see your Microsoft Ads.
>
> What's interesting about DuckDuckGo traffic:
> - **Tech-savvy audience** — developers, engineers, security professionals
> - **Privacy-conscious** — correlates with higher education and income
> - **No tracking** — but they still click ads that are relevant
>
> I can pull your breakdown right now... Here's your traffic by search engine:
>
> | Search Engine | Clicks | CPC | Conversion Rate |
> |---|---|---|---|
> | Bing | 1,847 | $4.20 | 3.1% |
> | Yahoo | 312 | $3.80 | 2.4% |
> | DuckDuckGo | 294 | $3.50 | 4.7% |
> | AOL | 48 | $3.20 | 1.9% |
>
> DuckDuckGo has your highest conversion rate (4.7%) and lowest CPC ($3.50). If you're selling developer tools or security products, this audience is gold.

### 4. Shopping Campaign Setup

> **You:** I sell home goods on Shopify. Is Microsoft Shopping worth it?
>
> **Agent:** Definitely — Microsoft Shopping is less competitive than Google Shopping, so your products appear in premium positions at lower CPCs.
>
> Here's what I'll set up:
> 1. **Connect your Merchant Center** to Microsoft (or import from Google Merchant Center)
> 2. **Create a Shopping campaign** with auto-bidding (Enhanced CPC)
> 3. **Set priority:** High for your best-margin products, Low for everything else
>
> One unique Microsoft Shopping feature: **Buy on Bing** — users can purchase directly from search results without visiting your website. This dramatically reduces cart abandonment.
>
> Budget recommendation: Start at $30/day. Microsoft Shopping typically delivers CPCs 25-40% lower than Google Shopping for the same products.

### 5. Cross-Engine Performance Analysis

> **You:** I'm running the same campaigns on Google and Microsoft. How do they compare?
>
> **Agent:** Let me pull side-by-side metrics for the last 30 days...
>
> | Metric | Google Ads | Microsoft Ads | Difference |
> |---|---|---|---|
> | Impressions | 145,200 | 38,700 | -73% (expected) |
> | Clicks | 4,356 | 1,452 | -67% |
> | CPC | $6.80 | $4.50 | **-34% cheaper** |
> | CTR | 3.0% | 3.7% | +23% better |
> | Conv. Rate | 4.1% | 4.8% | +17% better |
> | CPA | $165 | $94 | **-43% cheaper** |
> | ROAS | 3.2x | 5.1x | **+59% higher** |
>
> **Microsoft Ads is outperforming Google on every efficiency metric.** Lower CPCs, higher CTR, better conversion rates, and nearly double the ROAS.
>
> **Why?** Less competition = cheaper clicks. Same user intent = same conversion rates. Older, wealthier audience = higher conversion rates for premium products.
>
> **Recommendation:** You're significantly under-investing in Microsoft. Increase Microsoft budget by 50% — you're leaving money on the table.

---

## Microsoft Ads Tips from the Pros

1. **Import Google campaigns first.** Don't build from scratch. Import your proven winners, reduce bids by 25%, and start profiting on day one.
2. **Desktop bids deserve a premium.** Bing has outsized desktop market share (vs mobile). Desktop searchers often have higher purchase intent and larger order values. Bid 10-20% higher on desktop.
3. **Enable LinkedIn Profile Targeting.** This is a Google Ads killer feature that most advertisers ignore. Layer LinkedIn job function, industry, and company size on your search campaigns.
4. **Don't ignore the Audience Network.** Microsoft's native ad placements on MSN, Outlook.com, and Edge new tab page have surprisingly good performance for brand awareness.
5. **Bing Shopping is under-bid.** With fewer advertisers competing, your products win top positions at CPCs 30-40% lower than Google Shopping.
6. **Check search partner performance.** Yahoo and DuckDuckGo traffic quality varies by industry. If Yahoo converts poorly, you can exclude it while keeping DuckDuckGo.
7. **30% lower CPCs is real.** This isn't marketing — it's math. Less competition in the Bing auction means you pay less per click for the same keywords. Test it with $500 and see for yourself.

---

## FAQ

### Is there an MCP for Bing Ads?
Yes — Microsoft Ads (formerly Bing Ads) is fully supported. This repo pre-configures the Synter MCP server for Microsoft Ads management.

### Can I import my Google Ads campaigns to Bing?
Yes. The agent can import campaign structure, keywords, ad copy, and extensions from Google Ads. Bids are automatically adjusted down to account for lower Bing CPCs.

### Are Bing Ads worth it?
For most advertisers, yes. Microsoft Ads delivers 20-40% lower CPCs with similar or better conversion rates. If you're profitable on Google Ads, Microsoft Ads is essentially free incremental revenue.

### What search engines do Microsoft Ads cover?
Bing, Yahoo, AOL, DuckDuckGo, and the Microsoft Audience Network (MSN, Outlook.com, Edge). Together they represent ~33% of US desktop search.

### Can I target by LinkedIn profile on Bing?
Yes — this is exclusive to Microsoft Ads. You can target searchers by LinkedIn job function, company industry, and company size. No other search platform offers this.

### What's the minimum budget for Microsoft Ads?
There's no official minimum, but $15-25/day per campaign gives the algorithm enough data to optimize. Start lower than your Google budgets since Microsoft has less search volume.

---

## Related Repos

- [google-ads-agent](https://github.com/Synter-Media-AI/google-ads-agent) — Google Search & PMax
- [linkedin-ads-agent](https://github.com/Synter-Media-AI/linkedin-ads-agent) — LinkedIn display & lead gen
- [cross-platform-ads-agent](https://github.com/Synter-Media-AI/cross-platform-ads-agent) — Compare Google vs Bing performance
- [conversion-tracking-agent](https://github.com/Synter-Media-AI/conversion-tracking-agent) — UET tag setup for Microsoft Ads
- [shopify-agent](https://github.com/Synter-Media-AI/shopify-agent) — Product feed for Microsoft Shopping
- [audience-sync-agent](https://github.com/Synter-Media-AI/audience-sync-agent) — Sync audiences across platforms

---

## License

MIT — see [LICENSE](LICENSE) for details.

Built by [Synter](https://syntermedia.ai) · [Get API Key](https://syntermedia.ai/developer) · [Documentation](https://syntermedia.ai/docs)
