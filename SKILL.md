---
name: paypal-us-registration
description: Guide for registering a PayPal US account as a non-US resident (China mainland) with Wise USD receiving account. Covers address strategy, SSN handling, bank binding, and risk assessment.
---

# PayPal US Registration Guide (for Chinese users with Wise USD account)

## Context
- User: Chinese mainland university student, no SSN/US identity
- Goal: Receive payments from itch.io/Ko-fi/etc → PayPal US → Wise USD account
- Wise USD account: Account 216765129523, Routing 101019628, Bank: Wise US Inc, Wilmington, DE 19801

## Recommended Registration Info

### Address Strategy
- Use Delaware address (matches Wise USD bank state)
- Suggested: 108 W 13th St, Apt 4B, Wilmington, DE 19801
- Risk: PayPal may request address proof (utility bill, bank statement) for large transactions or account review
- Alternative: Use a real US package forwarding address (转运仓) that can receive mail

### Phone
- Google Voice US number (free, needs VPN to register)
- Ideal: 302 area code (Delaware), but any US number works
- Register at: voice.google.com

### SSN
- PayPal may or may not require SSN at registration (small accounts sometimes skip it)
- If required and you don't have one: no easy workaround
- Long-term option: Apply for ITIN (takes 2-3 months)

### Bank Binding (Wise USD)
- Bank Name: Wise US Inc
- Account Type: Checking
- Routing Number: 101019628
- Account Number: 216765129523

## Key Risks (HONEST assessment)

1. **Name mismatch (BIGGEST risk)**: Wise USD account holder name is "Wise US Inc", not your personal name. PayPal withdrawal requires matching account holder name. This may cause withdrawal rejection. **Untested — need to verify with small amount first.**

2. **SSN requirement**: Long-term/large-amount use of PayPal US will likely trigger SSN verification. No workaround without US identity documents.

3. **Address proof**: If PayPal requests proof of address for the Delaware address, user cannot provide utility bills. Account may be frozen.

4. **Account freeze risk**: PayPal is known for freezing accounts with suspicious activity patterns. Non-US users with mismatched info are higher risk.

## Recommended Approach
1. Register PayPal US with above info
2. Link Wise bank account
3. Test with small amount ($5-10) — receive from itch.io → withdraw to Wise
4. If withdrawal succeeds, gradually increase amounts
5. If name mismatch blocks withdrawal, consider alternative routes

## Alternative Routes if PayPal→Wise Fails
- PayPal → Chinese mainland bank card (can receive but limited)
- Direct platform payout via Stripe (requires HK address proof or US entity)
- Payoneer (works for China but has fees: $29.95 dormant fee, ~1-1.2% withdrawal + spread)
- Crypto on-ramp (complex, not recommended for beginners)
