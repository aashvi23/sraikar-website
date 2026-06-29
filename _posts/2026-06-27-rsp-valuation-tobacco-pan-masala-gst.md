---
layout: post
title: "RSP-Based GST on Cigarettes and Pan Masala: How the Tax Is Actually Calculated Now, and Where the Real Risk Sits"
date: 2026-06-27
author: "CA Shashank K. S. Raikar"
category: GST
tags: [GST, Tobacco, Pan Masala, Cigarettes, RSP Valuation, Rule 31D, ITC, GSTR-2B, Compliance]
read_time: 9
---
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "BlogPosting",
  "headline": "RSP-Based GST on Cigarettes and Pan Masala: How the Tax Is Actually Calculated Now, and Where the Real Risk Sits",
  "author": {
    "@type": "Person",
    "name": "CA Shashank K. S. Raikar"
  },
  "publisher": {
    "@type": "Organization",
    "name": "Shashank Raikar & Co.",
    "url": "https://www.sraikar.com"
  },
  "datePublished": "2026-06-27",
  "dateModified": "2026-06-27",
  "url": "https://www.sraikar.com/blog/rsp-valuation-tobacco-pan-masala-gst/",
  "description": "A practitioner's guide to RSP-based GST valuation on cigarettes and pan masala under Rule 31D from 1 February 2026, covering the 40% rate, the invoicing workaround, the GSTR-2B mismatch risk, and what it means for distributors and retailers. Written by CA Shashank Raikar, Margao, Goa."
}
</script>

Most of my clients who trade in cigarettes and pan masala heard one thing about the 1 February 2026 changes: the rate went up to 40%. That part is true, and it stings.

But the rate is not the part that is going to throw an error on the portal, confuse your accountant, or start a mismatch in your GSTR-2B that ends in a notice. The bigger shift is in how the tax is now calculated. Same goods, completely different way of arriving at the GST figure.

If you manufacture, distribute, wholesale, or retail tobacco or pan masala, this one is worth the ten minutes.

Here's what you'll take away:

- What actually changed on 1 February 2026, beyond the rate
- What RSP-based valuation means, with the formula and a clean worked number
- A worked example running through a real Goa-style supply chain
- The invoicing problem, and the reconciliation risk that can land you a notice
- Whether the department can even do this, and where the law is still untested

## What changed on 1 February 2026

Three things moved together, and people keep mixing them up. Keep them separate.

**One, the rate.** GST on most tobacco products and pan masala went from 28% to 40%. Intra-state that is 20% CGST plus 20% SGST. Inter-state it is 40% IGST. Bidis are the exception and were reduced to 18%.

**Two, the valuation.** This is the real change. GST is now charged on the printed Retail Sale Price, the MRP on the pack, and not on the price you actually bill. This comes from a new Rule 31D in the CGST Rules.

**Three, the compensation cess is gone, and replaced.** The GST compensation cess on these goods is now nil. The government has not folded it into GST. It has plugged the revenue gap with revived Central Excise duty on cigarettes, and a separate capacity-based Health and National Security cess that, as of now, sits only on pan masala and not on cigarettes. Both of these are over and above GST. I am keeping the excise and cess arithmetic out of this post so we can focus on the GST mechanic, but note that the duty stack is not identical across products.

For the technically inclined, the legal route is worth knowing in one line: Section 15(5) of the CGST Act lets the government notify special valuation, Notification 49/2023 is the parent for that, and Notification 20/2025 inserted Rule 31D to actually prescribe the RSP method. So this is not a stray circular. It is a rule with a clear statutory backbone.

One thing I keep seeing stated wrongly, so let me clear it up: RSP-linked taxation here is not brand new. Pan masala and tobacco have been on an RSP basis for the compensation cess since April 2023. What is new from February 2026 is that the GST value itself, not just the cess, is now pegged to the printed RSP.

## What RSP-based valuation actually means

Normally GST runs on transaction value. You bill a price, GST is charged on that price. Done.

Rule 31D throws that out for these specific goods. It opens with a "notwithstanding anything contained" line, which in plain terms means it overrides the normal valuation rules. For cigarettes, pan masala and the other notified items, the value of supply is now deemed to be the RSP on the pack, no matter what price you charge your buyer.

The RSP already includes tax, so you cannot slap 40% on top of it. The law gives a back-calculation formula:

> Tax Amount = (RSP × GST Rate) / (100 + GST Rate)

> Deemed Taxable Value = RSP minus that Tax Amount

The cleanest possible example. Take a cigarette pack with an RSP of ₹140. Because the rate is 40%, the divisor is 140.

- Tax Amount = (140 × 40) / 140 = ₹40
- Deemed Taxable Value = 140 minus 40 = ₹100

So GST on that pack is ₹40, and the deemed value is ₹100. The "divide by 1.40" you will hear people quote is just a shortcut for the 40% rate. For bidis at 18% the divisor would be 1.18. Nothing magic about it.

A few edge rules worth remembering. More than one RSP on a pack, the highest applies. RSP raised later, even after the goods leave the factory, the revised higher RSP becomes the base. Different RSPs for different regions, the one for your area governs.

## A worked example through a Goa supply chain

Let me run a cigarette case through a realistic chain so you can see where the money actually sits. Made-up names.

A cigarette brand ships from Bengaluru to Sequeira Distributors in Margao. Sequeira sells to Naik Traders, a wholesaler in Mapusa. Naik sells to Fernandes Stores, a kirana in Panjim. Fernandes sells over the counter.

Take the same ₹140 pack, sold in cases of 100 packs. Aggregate RSP per case is ₹14,000. GST on that is (14,000 × 40) / 140 = ₹4,000. Deemed taxable value is ₹10,000. Hold on to that ₹10,000 figure, it runs the whole story.

| Stage | Sells to | Price billed (before tax) | GST on invoice | Net GST actually paid | Margin kept |
|---|---|---|---|---|---|
| Bengaluru manufacturer | Sequeira, Margao | ₹6,500 | ₹4,000 (IGST) | ₹4,000 less its own input credit | ₹6,500 realised |
| Sequeira, Margao | Naik, Mapusa | ₹7,700 | ₹4,000 (CGST+SGST) | Nil (credit equals output) | ₹1,200 |
| Naik, Mapusa | Fernandes, Panjim | ₹8,900 | ₹4,000 | Nil | ₹1,200 |
| Fernandes, Panjim | Customer | ₹10,000 net (sells at RSP ₹14,000 all-in) | ₹4,000 embedded | Nil | ₹1,100 |

What the table is telling you.

GST is a flat ₹4,000 per case at every stage. The RSP on the pack does not change, so the tax does not change. Discounts, margins, who you sell to, none of it moves the GST.

The whole chain shares one number, ₹10,000. That is the RSP minus the GST. Add up the manufacturer's realisation and every trade margin, ₹6,500 plus ₹1,200 plus ₹1,200 plus ₹1,100, and you land back on ₹10,000 exactly. The 40% rate squeezes how much value is left for everyone to divide. There is no more room than that.

The distributor, wholesaler and retailer all pay nil net GST, because the credit they receive equals the GST they charge onward. So nobody downstream is paying extra tax in their books. The whole tax is front-loaded to the factory gate.

## The invoicing trap, and the bigger reconciliation risk

This is the part I would flag to every accountant in a trading firm right now.

Look at Sequeira's purchase invoice. The billed price is ₹6,500, but the GST on it is ₹4,000. Your billing software, and the portal, expect tax to be 40% of the taxable value shown. Forty percent of ₹6,500 is ₹2,600, not ₹4,000. So the system sees a tax figure that does not match the value, and it either rejects the entry or flags it.

The reason is exactly what we covered. The tax is on the ₹14,000 RSP, while the value being billed is the commercial price of ₹6,500.

GSTN saw this coming and issued an advisory in January 2026 with the workaround. On the invoice and in your returns, you report it like this:

1. **Taxable value:** the actual commercial price you billed, ₹6,500.
2. **Tax amount:** the RSP-based tax, ₹4,000.
3. **Total invoice value:** the sum of the two, ₹10,500.

So the document will look like you are charging tax at far more than 40% of the taxable value. You are not. The tax is 40% of the RSP, reported against a lower commercial value, which is what the law wants.

Now the part that actually carries risk, and it is not your own invoice. It is your supplier's filing.

Say your supplier gets lazy and reports their GSTR-1 the old way, tax on the transaction value of ₹6,500, which is ₹2,600. But your books and your purchase invoice show ₹4,000 of GST. Your GSTR-2B now shows ₹2,600 against the ₹4,000 you have claimed. That is a mismatch, and mismatches in a high-risk sector like this are the single most common trigger for a short-payment or suppression notice under the demand provisions.

So this is not just about configuring your own software. You have to watch what your suppliers file, the same way you would for any reconciliation. If you already reconcile GSTR-2B every month, you know the drill. If you do not, this is the sector where it stops being optional.

## Who really carries the cost now

Two things the rate-table articles skip, and that matter for a trading business.

**Discounts have become expensive.** Earlier, when a wholesaler dropped the price to clear slow stock, the GST dropped too, because tax followed the lower billed price. Not anymore. The tax is nailed to the RSP. A discount now comes entirely out of your margin, with zero tax relief. If you run festival schemes or season-end clearances, redo that maths before the next one.

**The pain is cash flow, not extra tax.** Net GST downstream is nil, agreed. But the moment Sequeira buys that case, ₹4,000 of input credit is locked up, and it stays locked until the case is sold onward. On a godown full of stock, that is real working capital frozen on the shelf. There is a small relief here. Traders dealing in these goods have been freed from the 1% mandatory cash payment rule, as long as the supplier paid GST on the RSP basis. That helps a little. It does not unfreeze the credit.

For the small distributor running a three to five person operation, which is most of the trade in Goa, this credit lock-up is the thing to plan around, not the headline 40%.

## Can the department even do this?

Fair question, and worth being straight about.

The broad position is settled. Courts have already held that GST and central excise can sit on tobacco at the same time, and that levies like NCCD are independent and survive alongside GST. So the basic architecture, heavy layered taxation on tobacco, is not in doubt.

What has not been tested yet, as of the middle of 2026, is Rule 31D itself, specifically the idea of taxing a deemed value that is higher than the price you actually received. No High Court has ruled on it. There is a reasonable argument that taxing you on a value above your real consideration sits awkwardly with how GST is meant to work. That argument is untested, not settled.

The practical takeaway: if your actual realisation is well below the RSP, and the gap is material to you, this is worth a conversation with your CA about reporting under protest and keeping the issue on record, so the option stays open if the rule is ever struck down or read down. I am not telling you to litigate. I am telling you not to close a door that is still open.

## A short checklist if you deal in these goods

1. **Reconfigure your billing software for RSP valuation now.** The tax field will not equal 40% of the billed value. Your vendor needs to set up the override before your next invoice.
2. **Follow the GSTN reporting method.** Commercial price as taxable value, RSP-based figure as tax, sum as invoice value. Use it consistently across e-invoice, e-way bill and GSTR-1.
3. **Reconcile GSTR-2B every month, without exception.** A supplier filing on transaction value instead of RSP is your mismatch and your notice. Catch it early.
4. **Keep proof that your supplier discharged GST on RSP basis.** Your Rule 86B relief and your ITC both lean on it. Hold the invoices.
5. **Reprice your discount schemes.** Every rupee of discount is now fully out of margin. Know the real cost before you commit.
6. **Segregate your transition stock.** Keep a clean 31 January 2026 stock record separating old-regime stock (28% plus cess) from new-regime stock (40%, RSP), and clear on FIFO. This avoids under or over-taxing closing stock sold after the switch.

## Key takeaways

- The 40% rate is the smaller story. The real change is that GST on cigarettes and pan masala is now calculated on the printed RSP under Rule 31D, not on the price you bill.
- The GST per pack is fixed at every stage, and the whole chain shares the value left after that tax, which 40% squeezes hard. Distributors and retailers pay nil net GST but carry locked-up input credit.
- Your invoice will show tax that does not match 40% of the billed value. That is by design. The bigger risk is a supplier filing on transaction value, which becomes your GSTR-2B mismatch and your notice.
- Rule 31D's deeming of a value above your actual realisation is untested in court. Where the gap is material, keep your options open with your CA.

---

*This post is written for general awareness and shouldn't be read as legal or tax advice on any specific transaction. Rates, rules, and procedures referenced here, including the excise and health cess components kept out of this post, are as currently in force, and the position on Rule 31D's validity is unsettled. Verify the latest position before acting.*
