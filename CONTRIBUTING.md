# Contributing

This list has one job: give a normal person, in a fight with an institution, the exact lever — the right regulator, statute, deadline or letter — with a primary source behind every claim. Contributions are judged against that job, and against one further test most lists never face: **someone may act on this in a legal dispute.** Accuracy is not a style preference here.

## The inclusion bar

An entry gets in only if it clears **all** of these:

1. **Actionable by a non-technical person.** If using it requires a law degree, a developer account, or a computer-science vocabulary, it belongs in a different list.
2. **Primary source only.** Link to the statute (Cornell LII, govinfo, eCFR), the regulator's own page (consumerfinance.gov, ftc.gov, fcc.gov, usa.gov, the agency itself), or the official organization's own page. Never a law-firm marketing page, a news article, or a blog post *as the authority* for a legal claim.
3. **Verified current.** Rules change and courts vacate them — the click-to-cancel rule, the CARS Rule and the medical-debt reporting ban all died in court in 2025. Before adding or citing any rule, check its status *today*. A repealed, vacated, stayed or merely *proposed* rule stated as live law is the worst bug this repo can ship.
4. **The lever is named.** One line must say what the entry does *and* what it gives the reader: the deadline, the dollar cap, the window, the forced response. "File a complaint" is not an entry; "file here — the company must respond within 15 days" is.
5. **Honestly priced.** Tag it `Free`, `Freemium` (the free tier must be genuinely usable, not a 7-day trial funnel), or `Paid`. If the price model changed, that's a bug worth a PR.
6. **No affiliate or referral links.** Ever. A recommendation you get paid for is an ad.
7. **It earns its place.** "Also exists" is not a reason.

## What gets rejected

- **False-dispute tactics, always.** This list is lawful self-defense: dispute what is inaccurate, unauthorized or not yours. Anything that coaches fabricated chargebacks, fake identity-theft claims, manufactured evidence or lying to a regulator is rejected on sight — and reported if it's a PR pattern.
- Credit-repair "secrets," debt-elimination schemes, and anyone charging to do what this list teaches free.
- Entries whose authority is a secondary source (law-firm SEO pages, lead-generation "consumer guides," AI content farms) even when the underlying claim happens to be true. Re-anchor it to the primary source or it doesn't ship.
- Claims stated more strongly than the source supports: a voluntary industry policy is not "the law," a proposed rule is not "your right," and a state-specific protection is not national.
- Dead links, and region- or state-specific entries without a region note.

## Entry format

```markdown
- **[Name](https://primary-source.example)** — What it does, in one plain sentence, ending with the lever it gives the reader (the deadline, the window, the forced response). `Free`
```

- Plays (actions, deadlines and status checks, not tools) start with 📋 and link only to a primary source.
- Keep the line under ~45 words. If it needs a paragraph, it's two entries or it's out.
- New sections need an issue first — sections are promises, and this list keeps its promises few and kept.

## The border rule

Three sister lists stay in their lanes. If your entry is about *preventing* a scam, verifying something in the moment, or the first 72 hours after one, it belongs in **Awesome Scam Defense**. If it's a veteran-specific benefit or program, it belongs in **Veteran Arsenal**. The long institutional fight — disputes, complaints, opt-outs, rights — lives here. Cross-list entries live in exactly one home and get linked, not copied.

## Maintenance

Links are checked automatically every week (see `.github/workflows/link-check.yml`), and legal claims are re-verified against their sources on a rolling basis — a link that still resolves can still be *wrong* if the rule behind it changed. A dead link or a dead rule gets one fix cycle, then the entry is removed — a shorter list that's accurate beats a longer list that isn't.
