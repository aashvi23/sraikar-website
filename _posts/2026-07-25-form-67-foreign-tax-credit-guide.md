---
layout: post
title: "You Paid Tax in the US. Don't Pay It Again in India: How to Actually File Form 67 and Claim Foreign Tax Credit"
date: 2026-07-25
author: "CA Shashank K. S. Raikar"
category: Income Tax
tags: [Income Tax, Foreign Tax Credit, Form 67, Rule 128, Schedule FSI, Schedule TR, DTAA, Compliance]
read_time: 12
---

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "BlogPosting",
  "headline": "You Paid Tax in the US. Don't Pay It Again in India: How to Actually File Form 67 and Claim Foreign Tax Credit",
  "author": {
    "@type": "Person",
    "name": "CA Shashank K. S. Raikar"
  },
  "publisher": {
    "@type": "Organization",
    "name": "Shashank Raikar & Co.",
    "url": "https://www.sraikar.com"
  },
  "datePublished": "2026-07-25",
  "dateModified": "2026-07-25",
  "url": "https://www.sraikar.com/blog/form-67-foreign-tax-credit-guide/",
  "description": "A step-by-step filing guide to foreign tax credit in the Indian ITR: building the FTC working, filing Form 67 on the e-filing portal, and filling Schedule FSI and TR field by field with worked numbers. Written by CA Shashank Raikar, Margao, Goa."
}
</script>

In [Part 1](/blog/schedule-fa-reporting-guide/), we covered disclosing foreign assets in Schedule FA and converting foreign income into rupees. This post covers the money question: you've already paid tax abroad on that income, usually withheld before it even reached your account. How do you make India give you credit for it instead of taxing the same money twice?

The relief is real and it works. But it is the most procedure-heavy claim in the individual return, and the Centralised Processing Centre denies it mechanically when the paperwork is out of sequence, even where the claim is substantively correct. So rather than walk you through the theory, I'm going to walk you through the filing, in the order you should actually do it, using one running example with real numbers at every step.

The sequence, and it matters:

1. Build the FTC working paper
2. File Form 67 on the portal, before the return
3. Fill Schedule FSI in the return
4. Fill Schedule TR
5. Cross-check the three against each other, then file the return

## The rule in two lines, then we file

Credit equals the **lower of** the foreign tax paid and the Indian tax payable on that same income, computed **separately for each source and each country**, not in aggregate. If the foreign tax is higher, the excess is a permanent cost: no carry-forward, no refund, no set-off against tax on other income. Credit applies against tax, surcharge, and cess, but never against interest or penalties.

That's the whole substantive law you need for a typical portfolio case. Everything else is execution.

## Our running example

Continuing Priya's case from Part 1. She's a resident (ROR) in Panjim filing ITR-2 for FY 2025-26 (AY 2026-27). All exchange rates are illustrative round numbers, not actual SBI TTBR figures.

During FY 2025-26, her Schwab account received one US dividend: **$200 on 18 September 2025**, from which the US withheld 25%, so **$50**, and credited $150.

Converted as per Part 1, at the assumed TTBR of ₹84.80 for 31 August 2025 (last day of the month preceding payment):

- Dividend income: 200 × 84.80 = **₹16,960**
- Foreign tax: 50 × 84.80 = **₹4,240**

The foreign tax conveniently converts at the same rate date as the income here, because the tax was deducted in the same month the dividend was paid. Where they differ, the rule for the tax is: TTBR on the last day of the month preceding the month the tax was paid or deducted.

Say Priya's marginal Indian rate on this income, including cess, works out to 31.2%. Indian tax on the dividend: 16,960 × 31.2% = **₹5,292**. Lower of ₹5,292 and ₹4,240 is **₹4,240**. That's her credit, and she pays the balance ₹1,052 in India on this dividend.

(If her marginal rate were 20.8% instead, Indian tax would be ₹3,528, the credit would cap at ₹3,528, and the excess ₹712 of US tax would simply be lost. Same form, same fields, smaller number. Keep this in mind when you see the "credit claimed" field later, it is not automatically the tax you paid abroad.)

## Step 1: Build the working paper first

Before touching the portal, build one table. Every field you'll fill in Form 67, FSI, and TR comes off this table, which is why building it first is what keeps the three documents consistent.

| Field | Priya's figure |
|---|---|
| Country / source | USA, dividend from listed US company |
| Date of income | 18 September 2025 |
| TTBR date and rate | 31 August 2025, ₹84.80 (illustrative) |
| Income offered (gross) | ₹16,960 |
| Head of income | Other Sources |
| Foreign tax paid | ₹4,240 ($50) |
| Rate of foreign tax | 25% (treaty rate, Article 10) |
| Indian tax payable on this income | ₹5,292 |
| Credit claimed (lower of the two) | ₹4,240 |

One row per dividend, per interest credit, per sale. Ten dividends means ten rows, each at its own rate date. Alongside the table, collect the evidence: the broker's annual tax statement, the US withholding certificate (Form 1042-S, which US brokers issue around March for the previous calendar year), and the SBI rate card for each conversion date.

One practical wrinkle with the 1042-S: it's a calendar-year document, while your claim is financial-year. For dividends paid between January and March, the amounts sit on the next year's 1042-S. Your working paper bridges this by transaction date; keep both years' certificates in the file.

## Step 2: File Form 67 on the portal, before the return

Form 67 is filed online, separately from the return, and must be on record before your return is processed. My rule, and I'll explain why at the end of this section: file it before you file the return itself, every single time.

The path on the e-filing portal: log in, then **e-File → Income Tax Forms → File Income Tax Forms**, search for **Form 67**, select the assessment year (**AY 2026-27** for this example), and choose to prepare the form online. Menu labels shift a little with portal updates, but Form 67 has stayed under the income tax forms section throughout.

The form has two parts. Part A is where a portfolio investor lives; Part B deals with refunds of foreign tax and previously disputed foreign tax, which most individual filers will leave blank.

**Part A, filled with Priya's row:**

- **Country or specified territory:** United States of America (picked from the dropdown; the form captures the country code)
- **Source of income:** Dividend
- **Income from outside India:** ₹16,960
- **Tax paid outside India:** ₹4,240
- **Rate of tax:** 25%, and where the form asks whether the rate is as per the DTAA, yes, Article 10
- **Tax credit claimed:** ₹4,240

If she had a second income line, say US bank interest, it goes in as a separate row with its own figures. The form totals the credit claimed across rows.

**Attachments.** Rule 128 requires evidence of the foreign tax alongside the form: a certificate or statement of the tax deducted (the 1042-S, or the broker's tax statement showing the withholding), and proof of deduction. Upload these with the form. A claim with no evidence attached is a claim inviting denial.

**Verification and acknowledgement.** Verify the form with Aadhaar OTP, EVC, or DSC, exactly like a return. Once submitted, download the acknowledgement PDF and file it in the working papers. That acknowledgement, with its date stamp showing Form 67 preceded the return, is the single most useful document if the credit is ever questioned.

**Why before the return, when the deadline is technically later.** The rule as amended allows Form 67 up to the end of the assessment year (31 March 2027 for this example), provided the return went in within the normal or belated time. But CPC checks for Form 67 when it processes the return. If the form isn't on record at that moment, the credit gets denied in the intimation and a demand lands with interest. There's a strong line of Tribunal rulings, starting with the Bangalore bench in Brinda Rama Krishna and followed widely since, holding the timeline is directory and credit can't be extinguished for a late form. Those rulings win appeals. But no High Court or the Supreme Court has settled it, and CPC keeps denying regardless, so relying on the case law means volunteering for a rectification fight you didn't need. The case law is the safety net for a slip that already happened. The plan is: Form 67 first, return second.

## Step 3: Schedule FSI in the return

Now open the ITR-2 and go to Schedule FSI. This schedule reports each item of foreign income, country-wise and head-wise, on the financial-year basis, and computes the relief line by line.

The schedule first asks for the **country code** and your **Taxpayer Identification Number in that country**. For the US, that's your SSN or ITIN if you have one; if you have no foreign TIN, the utility accepts your passport number in its place.

Then, against the head "Income from other sources", Priya's row reads:

- **(a) Income from outside India:** ₹16,960
- **(b) Tax paid outside India:** ₹4,240
- **(c) Tax payable on such income under normal provisions in India:** ₹5,292
- **(d) Tax relief available, lower of (b) and (c):** ₹4,240
- **(e) Relevant article of DTAA if relief claimed under section 90 or 90A:** 10

Two things people get wrong here.

First, column (c) is the Indian tax **on this income**, not your total tax liability. For slab-rate income like dividends, that means your marginal rate applied to this line. Your working paper should show that computation, because the utility won't do it for you.

Second, FSI is a reporting-and-relief schedule, not a taxing schedule. The same ₹16,960 must also sit in Schedule OS as dividend income, where it actually gets taxed. FSI without the corresponding OS entry, or vice versa, is a mismatch.

If Priya also had a capital gain on US shares, that would be a second FSI block: same country code, head "Capital gains", the gain figure from the Schedule CG computation, the US tax on it if any, and so on. Head-wise, line-wise, country-wise.

## Step 4: Schedule TR

Schedule TR is the summary, one row per country, drawn from FSI:

- **Country code and TIN:** same as FSI
- **Total taxes paid outside India:** ₹4,240
- **Total tax relief available:** ₹4,240
- **Section under which relief claimed:** 90 (treaty country)

The schedule also asks whether any part of the foreign tax is disputed abroad, and whether any refund of foreign tax has been claimed in the source country. For Priya: no and no. If you are contesting a foreign assessment, that disputed tax stays out of the credit until the dispute settles, so answer this honestly; claiming credit on disputed tax is a demand waiting to happen.

For a single-country individual filer, TR is one row, and its totals must equal the sums of the FSI columns. Exactly. If FSI says ₹4,240 and TR says ₹4,420 because of a typo, that inconsistency alone can get the credit denied at processing.

## Step 5: Cross-check, then file

Before submitting the return, sit with three documents open: the Form 67 acknowledgement, the FSI schedule, and the TR schedule. Check, to the rupee:

1. Form 67 total credit = FSI column (d) total = TR relief total. For Priya, ₹4,240 in all three places.
2. Every FSI income line appears in its normal head (OS, CG) at the same figure.
3. The foreign tax appears **nowhere** in the Indian TDS schedules. Foreign withholding is not TDS, it has no TAN, it will never show in Form 26AS, and entering it there creates a mismatch demand while your real claim goes unmade. This is the most frequent mis-entry I see, ahead of everything else.
4. AIS checked. Foreign dividends and proceeds are now surfacing in AIS through automatic exchange of information; reconcile against broker statements and resolve gaps before filing, not after the notice.

Then file the return, and the claim is complete: evidence in the file, Form 67 acknowledged first, schedules tied to each other.

## If CPC denies it anyway

It happens even to clean filings. The remedies run in sequence:

1. **Rectification under section 154**, filed online, pointing to the Form 67 already on record and the FSI-TR consistency. Most denials die here, and this is where that date-stamped acknowledgement earns its keep.
2. **A grievance on the portal** where the rectification sits unprocessed.
3. **Appeal to CIT(A)/NFAC** where rectification fails. This is where the directory-timeline case law does its work.

One documentation point I'm asked about often: a resident claiming FTC does **not** need a Tax Residency Certificate of the foreign country. TRC and Form 10F are what non-residents furnish to claim treaty benefits in India, the reverse situation. What you need is proof of the foreign tax: the withholding certificate and the payment trail.

## US-specific wrinkles, briefly

**Only federal tax is treaty-covered.** The India-US treaty covers federal income tax; US state taxes and Medicare sit outside it, so the straightforward section 90 credit is limited to the federal component. There is Tribunal authority supporting a section 91 route for state taxes, but that's an aggressive, contestable position, not a default. If it's material money, take it as a documented position with advice.

**25% dividend withholding is correct for individuals.** The 15% treaty rate belongs to corporate shareholders with large stakes. Don't dispute the 25%, claim credit for it.

**Whether the treaty rate caps Indian surcharge and cess is contested.** Some Tribunal decisions say yes; CPC in practice computes full slab plus surcharge and cess with credit for the US tax. Treat the cap argument as live litigation, not settled law.

## Key takeaways

- The claim is one number, the lower of foreign tax and Indian tax on that income, flowing through three documents that must match to the rupee: Form 67, Schedule FSI, Schedule TR.
- Sequence is the strategy: working paper, then Form 67 with evidence attached and acknowledgement saved, then the return. The Tribunal case law on late Form 67 is a remedy for accidents, not a plan.
- Column (c) of FSI is your Indian tax on that specific income line, and the same income must independently appear in its normal head. FSI reports and relieves; OS and CG tax.
- Foreign withholding is not TDS. It goes nowhere near the TDS schedules, and it's claimed on gross income, never netted.
- Excess foreign tax over your Indian tax on that income is permanently lost. Know that number before you file, not when the computation surprises you.

---

*This post is written for general awareness and shouldn't be read as legal or tax advice on any specific situation. Exchange rates and tax rates in the examples are illustrative, and portal menus and utility field labels change from time to time. Contested positions flagged above, including the Form 67 timing question, section 91 claims for non-treaty taxes, and the surcharge and cess cap argument, should be taken only with professional advice. Please consult a chartered accountant with the full details of your case before filing.*
