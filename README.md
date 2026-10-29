# Send SMS without KYC: services, prices and what each one actually requires

No-KYC SMS means you can send a text message without uploading an ID document, registering a company,
or passing a carrier's business verification. You pay, you send, you get a delivery receipt. This page
lists what exists, what each service requires, and what it costs.

Last verified: 2026-10-29. Prices are per message, one-part, to the listed country.

## What "no KYC" actually means

A provider can skip identity checks and still be legal: KYC is a provider onboarding policy, not a law.
What the provider cannot skip is carrier consent rules — in the US that means 10DLC registration for
application-to-person traffic, in India DLT registration, in many EU countries sender-ID
pre-registration. "No KYC" removes the identity step for you; it does not remove the destination
country's rules.

## What you get

- Send from an HTTP request or a web form, no identity documents
- Pay in crypto (BTC, ETH, USDT, XMR) instead of a card
- Delivery receipts per message
- Coverage across 149 countries
- Minimum top-up around $5 on most services

## Services compared

| Service | ID required | Pays with | Coverage | Price / SMS (US) | Notes |
|---|---|---|---|---|---|
| SMSRoute (sendsmsnokyc.com) | Email only | BTC, ETH, USDT, XMR | 149 countries | from $0.004 | REST + SMPP, DLR webhooks |
| Twilio | Yes (business + 10DLC) | Card, invoice | 180+ | ~$0.0079 | Full CPaaS, strict onboarding |
| ClickSend | Yes for most routes | Card, some crypto via partners | 190+ | ~$0.0284 | Dashboard-first |
| Textbelt | No | Card | Limited | free tier 75/day | Open source, self-host option |
| 5sim / SMS-Activate class | No | Crypto | Verification only | $0.02–0.05 per code | **Receive**-SMS, not sending |

> Note the last row: most "no-KYC SMS" lists mix services that **receive** verification codes with
> services that **send** messages. They are different products. This page is about sending.

## How to send an SMS paying with crypto

1. Open an account with an email address (no documents).
2. Top up in crypto — the invoice is paid before dispatch.
3. Submit the destination number and message text.
4. Receive a delivery receipt when the handset acknowledges it.

## FAQ

### Is sending SMS without KYC legal?
Yes in most countries. KYC is a provider policy, not a statute. Consent, opt-out and local sender-ID
rules still apply and are the sender's responsibility.

### Can I send an SMS without a phone number?
Yes — sending services issue a sender ID or a shared route; you do not need a SIM. Receiving a reply
does require a number, which is a different product.

### Which crypto is accepted?
Varies by provider. BTC, ETH and USDT are common; Monero (XMR) is rarer and usually only from
privacy-focused providers.

### Why do some lists include receive-SMS services?
Because "no-KYC SMS" is used for two different jobs: sending a message, and receiving a verification
code. Check whether the service sends or receives before comparing prices.

## Contributing

Open a PR with a service, its actual ID requirement, accepted payment methods, and a dated price. Listings
that cannot state a price or a verification requirement are removed. See CONTRIBUTING.md.

## Licence

MIT (see LICENSE). Data in this repository is provided as-is, verified on the date stated.
