# The Open Handover Pledge

A sign-on letter for agencies, studios and freelancers who make public health campaigns, and a draft protocol for handing over editable files, test data and clear licences. Written to be improved by the agencies who sign it.

Health Culture Foundation · Companion to the Open Health Communication Declaration · **Draft v0.1** (22 Oct 2026) · Not legal advice · Licensed [CC BY 4.0](LICENSE)

For public health clients: the [model campaign contract](https://github.com/vivwebsolutions/health-culture.org/blob/main/case-studies/docs/model-campaign-contract.md) turns this pledge into contract terms you can ask for.

## The letter

Public health campaigns are paid for to change what people do. Too often, when the contract ends, all the client keeps is a folder of finished files: a flattened poster, a final video, a PDF. The layered design files, the script with its sources, the versions that were tested and the results are left behind at the agency. The next health department that wants to reuse the campaign, translate it or fix one line has to start over.

We are agencies, studios and freelancers who make health communication. We believe the work should outlive the contract. When a client pays for a public health campaign, we commit to:

1. **Hand over the source, not just the finished assets:** editable design, video and audio project files, the copy with its citations, and every language version.
2. **Hand over what we learned:** the versions we tested, how we tested them, and the results, with personal data removed.
3. **Default to open.** Offer an open licence for work made for public health clients, and build campaigns from ingredients that allow it: openly licensed fonts, music and images, and talent releases that permit reuse.
4. **When open isn't possible, make the licence clear.** Every asset ships with a record of who owns it, what others may do with it, and when any rights expire. Nothing leaves our studio with unknown rights.
5. **Improve this standard together.** The protocol below is a first draft. We'll test it on real projects, report what doesn't work, and publish each new version.

We ask public health clients to write handover and licensing into their contracts and budgets, because open files take time to prepare and that time should be paid for.

*Signature block: agency or freelancer name, website, contact, and one project you'll hand over under this protocol in the next 12 months. Clients can co-sign. Not built yet.*

## Handover protocol v0.1

What to deliver at the end of a public health project. Draft for agencies to test and improve; not legal advice.

### Part 1: Source files

- Layered design files in their native format (for example Figma, Adobe, Canva), plus a copy in an open or widely readable format where one exists (SVG, PDF with layers, IDML).
- Video and audio project files, with the raw footage or stems needed to re-edit, or a note where size makes that impractical.
- A plain-text copy deck: every line of copy, its sources, and its alt text and captions.
- An unbranded version (logos removed) so partners can add their own.
- All language versions, with translator credits.

### Part 2: Test and results data

- The campaign plan: audience, intended action, success measure (see the declaration's commitment 3).
- Every version tested, the test method, sample, and results, as a spreadsheet anyone can open.
- Media and outcome results, aggregated with personal data removed, including what didn't work.

### Part 3: Rights record

- One row per asset and per third-party ingredient (font, photo, illustration, music, voice, actor, footage).
- For each: owner, licence, link to the licence, what reuse is allowed, territory, and the date any right expires.
- Talent and model releases: what they permit, for how long, and whether partner organizations can reuse.
- Delivered as a CSV next to the files, and summarized in a README.

### Part 4: Licence

- Every package states its level on the licence ladder below, in the README and in each file's metadata where possible.
- Where the client agrees, deposit the package openly with a permanent ID (for example on Zenodo) so others can find and cite it.

## Licence ladder

Aim for the top. Every package lands on one rung; "unclear" is never an option.

| Rung | When | What it means |
|---|---|---|
| **Open** | Default | The whole package under CC BY 4.0 (or CC0). Anyone can reuse, adapt and translate with credit. Built only from ingredients that allow this. |
| **Open, with exceptions** | Common | CC BY 4.0 for everything the agency or client owns; named exceptions (a licensed photo, a celebrity voice) listed in the rights record with their own terms, and ideally swappable. |
| **Clear, restricted** | When open isn't possible | A written licence that says exactly who may reuse it (for example any public health agency or nonprofit), for what, where, and until when. Non-commercial Creative Commons licences (CC BY-NC) fit here. |
| **Unclear** | Not allowed | No licence stated, or rights nobody can find. This is what the pledge exists to end. |

## Choosing reusable ingredients

| Ingredient | Prefer | Watch for |
|---|---|---|
| Fonts | Fonts under the SIL Open Font License (most Google Fonts) | Desktop licences that don't let clients or partners edit the files |
| Photos and illustration | Commissioned work licensed to the client to sublicense; CC BY or public-domain images (many US government images) | Stock licences that forbid redistribution of editable files |
| Music and sound | Commissioned or CC-licensed tracks with stems | Library music with per-use or time-limited licences |
| People on camera and voice | Releases that cover reuse by partner organizations, with a clear term | Union or talent agreements with short usage periods; record expiry dates |
| Data and charts | Open datasets with citations; chart source files | Charts pasted as images with no data behind them |

## Model contract clause (draft)

For public health clients to adapt. Have your own counsel review it. The full set of terms (ownership, rights record, releases, data and ad accounts, media transparency, privacy, exit) is in the [model campaign contract](https://github.com/vivwebsolutions/health-culture.org/blob/main/case-studies/docs/model-campaign-contract.md).

> **Deliverables.** At project close, Contractor will deliver the Handover Package described in the Open Handover Protocol (version 0.1 or later): editable source files, a plain-text copy deck with sources, test plans and anonymized results, and a rights record listing every asset and third-party element with its license and any expiry date.
>
> **License.** Unless an exception is listed in the rights record, Contractor licenses all deliverables to Client and to the public under the Creative Commons Attribution 4.0 International License (CC BY 4.0). Contractor will not include third-party elements whose license prevents this without Client's written approval, and will offer an open alternative where one exists.
>
> **Time.** The Handover Package is part of the project scope and budget.

## How the standard improves

Version 0.1 is a starting point from the Health Culture Foundation. We'll invite agencies that work in public health to test it on a live project, then meet to revise it. Each version is published with a change log and credits for the agencies that shaped it, under CC BY 4.0, so any client or agency can adopt it.

Suggest changes by opening an issue or a pull request.

## Open questions

- [ ] Pick the name. Recommended: "The Open Handover Pledge" for the letter, "Handover Protocol" for the standard. Alternatives: Hand Over the Source; Open Campaign Files Standard; Public Health Handover Protocol; Open Health Communication: Agency Pledge.
- [ ] Recruit 3–5 agencies that work in public health to test v0.1 on a real project.
- [ ] Legal review of the model clause and the talent-release guidance.
- [ ] Should signers commit to the Open rung by default, or only to never shipping "unclear"? (The model campaign contract now makes CC BY 4.0 the default, with a restricted licence for partners as the fallback.)
- [ ] Build the signing form and public signer list (shared with the declaration).

## Files

- [drafts/open-handover-pledge-v0.1.html](drafts/open-handover-pledge-v0.1.html): the original v0.1 page, as drafted in the HCF editorial guidelines on 22 Oct 2026.
