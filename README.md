# Ysaere for Cursor

Ysaere gives your Cursor agent traceable research and counterparty checks. Every paid result can carry a Trust Receipt you can verify later.

## What you can do

- **Vendor KYB:** screen a company against public records (GLEIF, SEC EDGAR, OFAC, SAM.gov) before you pay or onboard it.
- **SAM contractor check:** confirm a federal contractor's registration and UEI.
- **Sanctions and wallet screen:** check a person, company, or wallet against sanctions lists.
- **Notary receipt:** hash and timestamp a document or result so anyone can verify it later.
- **Research:** quick briefs, sourced briefs, company, market, and competitive intelligence, and due diligence reports.

## Setup

Install the plugin, then sign in to Ysaere when Cursor asks. Signing in uses OAuth with your Ysaere account (Google or email). New accounts get 150 free credits.

The free tools (`company_snapshot`, `estimate_credits`, `check_balance`) work right away. Paid tools draw from your credit balance. Use `estimate_credits` to see a cost before you run anything.

## Example prompts

- "Run a KYB check on Acme Corp before I approve this invoice."
- "Is this vendor registered in SAM.gov? UEI is ..."
- "Give me a sourced brief on Stripe's latest funding."
- "Notarize this file's hash so I can prove it later."

## Server

Remote MCP over Streamable HTTP: `https://mcp.ysaere.com/mcp`

## Links

- Website: https://ysaere.com
- Privacy: https://ysaere.com/privacy
- Terms: https://ysaere.com/terms
- Support: ysaere.inc@gmail.com
