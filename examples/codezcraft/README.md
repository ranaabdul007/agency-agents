# CodezCraft AI Company

Teen AI teams (Sales, Development, Social Media) aur un ke upar ek Manager (Chief of Staff), jo Hussain ko roz report deta hai.

| Team | Lead role | Agents |
|---|---|---|
| 🧭 Manager | Chief of Staff | Chief of Staff, Executive Summary Generator |
| 💰 Sales | Pipeline Analyst | Offer & Lead Gen, Outbound, Email Marketing, Content Creator, SEO, Discovery Coach, Sales Engineer, Proposal, Deal, Account Strategist, Customer Success |
| 💻 Development | Senior Project Manager | Product Manager, Software Architect, Frontend, Backend, Mobile, AI Engineer, Code Reviewer, Test Automation, API Tester, Reality Checker, DevOps, Technical Writer |
| 📣 Social media | Social Media Strategist | LinkedIn Content Creator, Carousel Growth Engine, Image Prompt Engineer, Brand Guardian, Analytics Reporter |

Poora kaam ka tareeqa, handoffs aur report ka format [`CLAUDE.md`](CLAUDE.md) mein hai.

## Setup (aik dafa)

Apne computer par, is repo ke andar:

```bash
# 1. 33 agents Claude Code mein install karein (~/.claude/agents)
./scripts/install.sh --tool claude-code --agents-file examples/codezcraft/agents.txt --no-interactive

# 2. Company ka folder banayein
cp -r examples/codezcraft ~/CodezCraft
```

## Roz kaise chalayein

```bash
cd ~/CodezCraft
claude
```

Claude Code is folder ka `CLAUDE.md` parh kar Manager ban jata hai. Phir Roman Urdu mein kahein, jaise:

- `aaj ki report do`
- `is hafte Saudi ke 10 naye distributors dhoondo aur emails likho`
- `Sodipal ka jawab aaya hai, discovery call ki tayyari karo`
- `is hafte ki 3 LinkedIn posts banao`
- `Riaz Industries jaisa ERP naye client ke liye plan karo`

## Hamesha yaad rakhein
- Koi email, WhatsApp, post, proposal ya price aap ke OK ke bagair bahar nahi jata.
- Company ki maloomat sirf `company-profile.md` se aati hai. Wahan kuch badle to file update karein.
- Leads ka status `leads/` ki files mein update karte rahein, report isi se banti hai.
