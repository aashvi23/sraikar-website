---
layout: post
title: "How to Report Foreign Assets and Foreign Income in Your ITR: A Working Guide to Schedule FA and Exchange Rates"
date: 2026-07-18
author: "CA Shashank K. S. Raikar"
category: Income Tax
tags: [Income Tax, Foreign Assets, Schedule FA, Rule 115, Rule 206, Black Money Act, ITR-2, Compliance]
read_time: 12
---

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "BlogPosting",
  "headline": "How to Report Foreign Assets and Foreign Income in Your ITR: A Working Guide to Schedule FA and Exchange Rates",
  "author": {
    "@type": "Person",
    "name": "CA Shashank K. S. Raikar"
  },
  "publisher": {
    "@type": "Organization",
    "name": "Shashank Raikar & Co.",
    "url": "https://www.sraikar.com"
  },
  "datePublished": "2026-07-18",
  "dateModified": "2026-07-18",
  "url": "https://www.sraikar.com/blog/schedule-fa-reporting-guide/",
  "description": "A practical, table-by-table guide to reporting foreign assets in Schedule FA and converting foreign income under Rule 115, with worked examples and exchange rate rules. Written by CA Shashank Raikar, Margao, Goa."
}
</script>

If you're a resident Indian holding a foreign bank account, US stocks, vested RSUs, or a retirement account left behind from a stint abroad, this is a working guide to actually reporting them: which table, which value, which exchange rate, and on which date.

Quick context on why this matters right now. Since late 2024, the Income Tax Department has been running data-matching campaigns using account information received automatically from foreign countries under CRS and FATCA, and sending SMS and email nudges to taxpayers whose returns don't match that data. The first campaign, launched in November 2024, pushed close to 25,000 taxpayers to revise returns, and a second round followed in November 2025. So the question is no longer whether the department can see your foreign accounts. It can. The question is whether your return reports them correctly.

Two ground rules before the mechanics:

**Who files Schedule FA.** Only a Resident and Ordinarily Resident (ROR). If you're RNOR (typical for the first two to three years after returning to India) or Non-Resident, Schedule FA doesn't apply to you. And if you are ROR with even one foreign asset held for a single day in the reporting period, you must file a return with Schedule FA, even if your total income is below the basic exemption limit and no tax is payable.

**Which form.** For individuals and HUFs, ITR-2 or ITR-3. Schedule FA also exists in ITR-5 (firms and LLPs), ITR-6 (companies), and ITR-7 (trusts and similar entities), so entities holding foreign assets report there. It doesn't exist in ITR-1 or ITR-4. Filing ITR-1 or ITR-4 while holding foreign assets is itself a reporting default.

## The two reporting windows: get this right first

Everything else in this guide sits on top of one distinction.

**Schedule FA runs on the calendar year.** For the return of FY 2025-26 (AY 2026-27), Schedule FA reports assets held during 1 January 2025 to 31 December 2025.

**Income runs on the financial year.** The dividends, interest, and capital gains from those same assets are taxed for 1 April 2025 to 31 March 2026, and go into Schedule OS, Schedule CG, and Schedule FSI on that basis.

So a dividend credited in February 2026 appears in your FY 2025-26 income computation but not in this year's Schedule FA figures (it falls in calendar 2026, next year's FA). A dividend credited in February 2025 is the reverse: it's inside this year's Schedule FA window but was already taxed in last year's return. Neither is an error. The mismatch is by design, and your working papers should show a date-wise bridge between the two windows rather than trying to force them to agree.

Practical step: pull two separate statements from every broker and bank. One for January to December 2025, one for April 2025 to March 2026. Label them before you start.

## Exchange rates: the TTBR rule

Every foreign currency figure in the return must be converted using the **Telegraphic Transfer Buying Rate (TTBR) of the State Bank of India**, which is the rate at which SBI buys foreign currency. Not the Google rate, not the RBI reference rate, not your broker's conversion rate, not your credit card rate. Those are non-compliant, and using them produces figures that won't reconcile if questioned.

One transition note before the tables. The return you're filing in 2026 is for FY 2025-26 (AY 2026-27), and that year is still governed by the Income-tax Act, 1961 and the Income-tax Rules, 1962. The savings provisions of the new Income-tax Act, 2025 preserve the old law for tax years that began before 1 April 2026. So the conversion rule for this return is Rule 115 of the 1962 Rules, and that's what this guide cites. From tax year 2026-27 onwards, the same conversion framework sits in Rule 206 (and Rule 207 for TDS) of the Income-tax Rules, 2026, with the specified dates carried over unchanged; the return-filing obligation for foreign asset holders moves to section 263(1)(a)(ix) of the 2025 Act, and the retirement account relief discussed later moves from section 89A to section 158. Nothing in the mechanics below changes, only the citations.

Which date's TTBR you use depends on what you're converting:

**For Schedule FA (asset values):**

| What you're converting | TTBR date |
|---|---|
| Peak balance or peak value | The date the peak occurred |
| Closing balance or value | 31 December of the reporting calendar year |
| Initial value / investment | The date of acquisition |

**For income (Rule 115):**

| Type of income | TTBR date |
|---|---|
| Salary, including RSU/ESOP perquisite on vesting | Last day of the month before the month salary is due or paid |
| Dividends | Last day of the month before the month of declaration or payment |
| Capital gains | Last day of the month before the month of transfer |
| Interest on bonds and other securities | Last day of the month before the month in which the interest falls due |
| Ordinary foreign bank interest | 31 March of the financial year |

Those last two rows are a trap worth pausing on. Interest from a foreign savings account is not "interest on securities" under the rule. It falls under Other Sources and takes the single 31 March rate for the whole year, not a month-by-month rate. Interest on a foreign bond is the opposite case: it is interest on securities, so each coupon converts at the month-end preceding the month it fell due, not at 31 March. Don't let one rate bleed into the other category. I see these converted wrongly more often than any other item.

One caveat on the 31 March rate. Rule 115 itself carves out an exception: where income in that last-day-of-the-year category is actually received in India, or brought into India, before 31 March, the rule doesn't apply to it, and the conversion follows the actual remittance. So "one rate for the whole year" holds only for amounts still sitting abroad at year-end. If you repatriated the interest during the year, use the remittance-basis figure for that portion.

Retain the rate evidence for every date you use: a printout or PDF of the SBI rate card for each specified date, filed in your working papers. If the return is ever questioned, the rate source is the first thing you'll need to produce.

## Schedule FA, table by table

Schedule FA is split into tables A1 through G. Here's what goes where, with a small example for each. All exchange rates below are illustrative round numbers for showing the method, not actual SBI rates. Look up the real TTBR for your actual dates.

### Table A1: Foreign bank accounts

Savings, current, and time deposit accounts. You report the bank's name and address, account number, opening date, **peak balance during the calendar year**, **closing balance on 31 December**, and gross interest credited.

*Example.* Sameer in Margao holds a US checking account. Balance moved between $2,000 and $9,500 during 2025, with the high point on 14 August. Closing balance on 31 December 2025 was $4,200. Assume TTBR on 14 August was ₹84.00 and on 31 December was ₹85.50. He reports peak balance ₹7,98,000 (9,500 × 84.00) and closing balance ₹3,59,100 (4,200 × 85.50). Finding the peak means going through the year's statements, not guessing. Most banks let you download a full-year transaction history; the highest end-of-day balance in that file is your peak.

### Table A2: Foreign custodial (brokerage) accounts

The account wrapper at a broker such as Interactive Brokers, Schwab, or Fidelity. Retirement wrappers like a 401(k), IRA, or UK SIPP are commonly reported here too, though the ITR instructions don't prescribe a table for them and some practitioners use Table B or the residual tables instead; whichever placement you take, take it consistently year to year. You report peak balance, closing balance, and gross amounts credited during the year, split into interest, dividends, sale proceeds, and other.

*Example.* Priya in Panjim has a Schwab account holding cash plus shares. The account's total value peaked at $22,000 on 3 March 2025 and closed the year at $18,500. During calendar 2025, the account was credited $310 in dividends and $6,000 in sale proceeds. Each of those figures goes into A2 at the appropriate TTBR, and the account as a whole is one A2 line. The individual shares inside it then go into A3, so the same holdings appear in both tables. That's the accepted practice, not double-counting.

One note on retirement accounts: Indian law lets you elect to defer tax on income accruing inside notified US, UK, and Canadian retirement accounts until withdrawal (via a specific form filed before the return). That election affects when the income is taxed. It does not remove the asset from Schedule FA. The 401(k) gets disclosed either way.

### Table A3: Foreign shares, ETFs, bonds, and vested RSUs

This is the table with the heaviest data requirement, because it works **per security, per line**. For each holding you report the entity's name and address, nature of the interest, date of acquisition, **initial value** (cost, at acquisition-date TTBR), **peak value during the year**, **closing value on 31 December**, gross amount credited (dividends), and **gross proceeds** if sold or redeemed.

Do not aggregate. Ten different stocks means ten lines. Lumping them into one line, or pushing them into Table D to avoid capturing peak values, invites an "inaccurate particulars" allegation, and that carries its own penalty exposure.

*Example.* Priya's Schwab account holds 15 shares of a US company acquired on 10 June 2024 at $130 each ($1,950). Assume acquisition-date TTBR ₹83.00: initial value ₹1,61,850. During 2025 the share peaked at $175 on 20 November (assume TTBR ₹85.20): peak value 15 × 175 × 85.20 = ₹2,23,650. Closing price on 31 December was $168 (assume TTBR ₹85.50): closing value ₹2,15,460. Each figure sits in its own column on her single A3 line for this stock. Her second holding, an ETF, gets its own separate line with the same treatment.

*RSUs.* Vested RSU shares you still hold are A3 entries like any other share. The perquisite value on vesting was already taxed as salary (on a financial-year basis, converted at the salary TTBR date). The A3 disclosure of the shares is an additional, separate requirement. Vesting tax paid does not exempt you from disclosing the holding.

A footnote on Form 16 mismatches. Your employer converts the RSU perquisite for TDS purposes at the TTBR on the date tax was required to be deducted (that's Rule 26), while the return-side conversion of salary income runs on the Rule 115 date, the month-end preceding the month the salary fell due or was paid. Two different dates, two slightly different rupee figures. A small gap between the Form 16 perquisite and your own conversion is common and explainable; keep the working showing both dates and both rates rather than silently forcing them to match.

### Table A4: Foreign insurance and annuities

Foreign life insurance or annuity contracts that carry a cash or surrender value. Report the surrender value at year-end and any gross amount credited.

### Table B: Financial interest in a foreign entity

A stake in a foreign company, LLC, or partnership: equity, voting rights, profit share, or an interest in assets. Report the nature and extent of the interest and total investment. A 5% stake in a friend's Dubai LLC belongs here even if it paid you nothing all year.

### Tables C and D: Foreign immovable property and other capital assets

Table C for real estate abroad: date of acquisition, total investment (at acquisition-date TTBR), and income derived. Table D is the residual for capital assets that fit nowhere else. It is not a parking spot for shares you'd rather not report line by line.

### Table E: Signing authority

Accounts where you can sign but which aren't yours and aren't reported in A to D. The classic case: you're a signatory on your employer's foreign account, or on an elderly parent's account abroad. Report the institution and whether any income from the account accrued to you.

### Tables F and G

Table F covers foreign trusts where you're a trustee, settlor, or beneficiary. Table G is the catch-all for any other foreign income not arising from assets in A to F. Most individual filers won't touch these, but check before assuming.

## Reporting the income side

The assets go in Schedule FA. The income they generated goes into the normal heads, on the financial-year basis, and each item also gets a line in Schedule FSI (country-wise, head-wise). Three items cover most individual cases.

### Foreign dividends

Taxed as Income from Other Sources **at your slab rate**, on the **gross** amount before any foreign withholding.

*Example.* Priya received a US dividend of $200, declared and paid on 18 September 2025, from which the US withheld 25% ($50) and credited $150 to her account. Assume TTBR on 31 August 2025 (last day of the month preceding the month of declaration and payment) was ₹84.80. She reports dividend income of ₹16,960 (200 × 84.80) in Schedule OS. Not ₹12,720. Reporting the net receipt is one of the most common errors I see, and it understates income while simultaneously messing up the foreign tax credit claim. The $50 withheld is claimable as credit, and how to claim it (Form 67, Schedule FSI and TR) is the subject of Part 2 of this series.

One timing caution on the rate date. The rule fixes the date by reference to the month in which the dividend is declared, distributed, or paid. For US stocks the declaration usually lands a few weeks before payment, and if those fall in different months, the month of declaration arguably governs, which would pull the rate date back by a month. Check the declaration date on the broker statement, don't just work off the credit date, and where the two months differ, note in the working paper which event you used and why.

One rate-related point worth flagging: US dividends to Indian individual investors are withheld at 25% under the treaty. The 15% rate you may have read about applies only to companies holding at least 10% of the payer, not to individuals. If your broker withheld 25%, that's correct, not an error to dispute.

### Foreign bank interest

Other Sources, slab rate, converted at the **31 March** TTBR for the whole year as noted above. One rate, one computation, whatever months the interest was credited in.

### Capital gains on foreign shares

Two things here: the tax treatment, and a genuine methodological controversy you should decide on consciously.

**Treatment.** Foreign shares are treated like unlisted shares for holding-period purposes: gains are long-term if held for more than 24 months, currently taxed at 12.5% plus surcharge and cess. Short-term gains go to your slab.

**The conversion controversy.** How do you convert a dollar gain into rupees? There are two readings of the rule, and they give different answers.

The **component-wise method**: convert the sale consideration at the TTBR of the month-end preceding the sale, convert the cost at the TTBR of the month-end preceding the purchase, and compute the rupee gain from the two rupee figures. This captures the rupee's depreciation over your holding period as part of the taxable gain.

The **literal method**: compute the gain in dollars first, then convert that single gain figure at the month-end preceding the sale. This ignores currency movement and generally produces a lower gain.

*Example, same facts both ways.* You bought 10 shares at $100 in June 2023 (assume month-end-preceding TTBR ₹82.00) and sold them at $150 in October 2025 (assume month-end-preceding TTBR ₹86.50).

Component-wise: sale consideration 1,500 × 86.50 = ₹1,29,750; cost 1,000 × 82.00 = ₹82,000; gain **₹47,750**.

Literal: gain of $500 × 86.50 = **₹43,250**.

The ₹4,500 difference is purely the currency movement on your cost. To be clear on where the law stands: the special currency-neutral computation written into the Act applies only to non-residents selling shares in, or debentures of, Indian companies. It does not cover a resident selling foreign shares, and the point has not been settled by any High Court that I am aware of. Each method has a textual anchor. The literal method leans on the rule's own wording, which converts the "income" under the head Capital gains at a single specified date. The component-wise method leans on section 48, which computes the gain as the full value of consideration less the cost of acquisition and transfer expenses, each of which must be a rupee figure before any gain exists at all; on that reading, the conversion happens leg by leg and the rule's date only tells you which rate to use for the sale leg. The component-wise method is the dominant, safer practice and the one I use, because the section 48 computation argument is harder to attack. If you take the literal method for the lower gain, understand that you're taking a contestable position, and document your reasoning either way. What you should not do is switch methods year to year depending on which gives the lower number.

## The penalty backdrop, briefly

The Black Money Act imposes a flat ₹10 lakh penalty per year for non-disclosure or inaccurate disclosure of a foreign asset in the return, independent of whether the income itself was taxed. Assets other than immovable property with an aggregate value up to ₹20 lakh are exempt from the penalty, though not from the disclosure requirement itself. Note that the statute says "aggregate value" without fixing the date on which that value is measured, and the point is not free from doubt; one reading measures it when the penalty notice issues, which matters if exchange movement has pushed an old holding above the line. If you are anywhere near the threshold, don't rely on the exemption, just disclose. A Special Bench of the Mumbai Tribunal held in October 2025 that the penalty is discretionary rather than automatic, which is real protection for bona fide slips, but it's case-by-case relief, not a shield to plan around. If you find a past omission, a revised or updated return filed before any notice remains your strongest move.

## Working paper checklist

1. Residential status confirmed as ROR, with the day-count working on file.
2. Calendar-year (Jan-Dec) statements from every foreign bank and broker, separate from the financial-year statements.
3. SBI TTBR rate evidence for every specified date used: each peak date, 31 December, each acquisition date, each dividend month-end, each sale month-end, and 31 March.
4. Per-security schedule for Table A3: acquisition date, cost, peak, closing, dividends, proceeds, each converted at its own rate.
5. Gross (not net) dividend figures, tied to the broker's annual tax statement and withholding certificate.
6. Capital gains computation showing the conversion method used, applied consistently.
7. A bridge reconciling calendar-year FA figures to financial-year income figures by transaction date.
8. Confirmation the return is on a form that carries Schedule FA: ITR-2 or ITR-3 for individuals and HUFs, ITR-5, ITR-6, or ITR-7 for entities.

## Key takeaways

- Schedule FA runs January to December; your income runs April to March. Pull both statements separately and reconcile by date, don't force them to match.
- Every conversion uses SBI TTBR on a rule-specified date: peak date and 31 December for FA values, month-end-preceding for dividends, capital gains, and bond interest, 31 March for foreign bank interest still held abroad at year-end. Keep the rate cards.
- Table A3 is per security, per line, with initial, peak, and closing values each at their own rate. Aggregation is exposure, not efficiency.
- Report dividends gross at slab rate; the foreign tax withheld is a credit claim, not a deduction from income.
- The capital gains conversion method for foreign shares is contested. Component-wise is the safer position; whichever you choose, document it and apply it consistently.

Part 2 covers the credit side: claiming foreign tax credit through Form 67, the Schedule FSI and TR linkage, and why the timing of Form 67 has generated more litigation than almost anything else in this space.

---

*This post is written for general awareness and shouldn't be read as legal or tax advice on any specific situation. Exchange rates used in the examples are illustrative, not actual SBI TTBR figures. Reporting requirements depend on individual facts and residential status, and contested positions flagged above should be taken only with professional advice. Please consult a chartered accountant with the full details of your case before filing.*
