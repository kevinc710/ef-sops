# Changelog

Live SOP pages stay current. This file is the dated history of what changed.

Do not stack "Updated Aug 14" footnotes on the CS page. Put the date here and rewrite the SOP body in place.

## 2026-10-28

- Redo confirmed our volume (under 100 returns a month) does not qualify for Managed Returns. No Brisbane AU hub. All returns stay on the Salt Lake City hub.
- Redo's cheaper options: green return (no label, customer keeps the item and is refunded; Redo recommends it), cap or discount the quoted label (we absorb), or deduct the label from the refund (customer pays). Kevin chose green return.
- Rule: use a green return when the label costs more than the order or more than about half the order total (example: $113 label on an ~$80 AU order). Otherwise normal return flow. Store credit is still offered first. Full refund beyond goodwill still needs Kevin or Leandro. Abby approves and processes the refund; Mike never touches money.
- Rewrote "International Return Shipping" to apply by label cost, not only unsupported regions. Updated the size exchange bullet and the return fee note to point to it.

## 2026-10-25

- Added "Size Exchanges: Say Exchange, Not Return" to the CS page. Always call it an exchange, never a return. Order already shipped means wait for arrival, then use the Redo portal. Offer exchange or store credit before refund.
- Steps and labels were checked on the live Redo portal on Oct 25, not copied from a help bot. There is no "Select different style" or "Exchange for same item" option and no item or reason picker. The customer clicks "Start a return", types a free-text reason, and picks a size from Redo's size buttons.
- Label cost: our mistake means we cover it. A customer's own size swap without Checkout+ pays the return shipping fee shown on the review screen.
- Added a size exchange customer macro that signs off as info@.

## 2026-09-01

- Repo is two layers, not a third dump: live SOP pages are current how; this changelog is dated history.
- Added `ops/` backend playbook (Adam's lane). Keep it out of the VA customer-support pages.
- Fulfillment app is **Beehiveship** (Cherry/Beehive). Do not tell VAs to ping Lay or Dropsure.
- Fluid Pant is Cherry/Beehive only. Wiio/Hart is phased out. Duplicate-fulfillment guidance is Redo vs Cherry/Beehive, not old Wiio double-pull as the live bug.
- `x-redo` with dummy USPS tracking (`TX…`) is the Redo protection line, not a second pant.
- Exchange/replacement: ping Cherry only after Redo confirms out of stock in `#06-fitz-redo-external`.
- Customer-facing CS email is **info@ellisonandfitz.com**. `hello@` is marketing and the Trustpilot Business owner. `support@` is not the live CS inbox. Sign-off stays Ellison & Fitz Support / Tina M.
- Trustpilot on the VA SOP stays light: no AFS, no review gating, no discount-for-review, no asking a reviewer to change or delete a review for credit. Mike drafts public replies. Nothing auto-posts. Invites are not live until Kevin or Leandro turns week 1 on.
- Ops how (see `ops/`): dropship, no warehouse; Tapestitch is POD blanks, not a Fluid Pant backup; if Redo accepts/ships and Beehiveship is still pending/paid, cancel Cherry in `#08-cherry-beehive` and do not re-ping; two Shopify Flow workflows are live (Hold Beehive when Redo has the item; Catch Redo accept) and tag `redo-accepted` + Slack `#04-ops-alerts`; do not wait for two trackings.
- Illustration: Ellison10713Fitz — Redo shipped Mixed L to PR while Cherry was still pending paid.
- Open Loops: Shane owns the Drive sheet. Weekday 5-item stuck ping. No Notion or ClickUp as team workspace.
- WhatsApp: Adam reads for intake. Nobody sends unless Kevin explicitly says to send that message.
- Shopify writes for agents need Kevin's explicit OK. Abby still processes CS money per the Commslayer split.

## 2026-08-30

- Commslayer split locked:
  - **Mike** — live chat and first-pass tickets (WISMO, tracking, policy, SOP answers). Never touches money.
  - **Abby** (Abigail Go; customer-facing name Tina) — refunds, store credit, Redo, chargebacks, damaged/missing, manager escalations. In Commslayer, not Gmail.
  - High-risk cancels stay with Kevin or Leandro.
  - Do not mark Instagram threads as read without a reply.

## 2026-08-15

- Do not tell customers Cherry/Beehive consolidation resolved hemming or sizing. Joel Marazzo case: inconsistent sizing and unfinished hems. Wait for Cherry to confirm a new proven supplier in writing.
- Duplicate-detection checker is live: Flow #2 is a trigger only; verdict uses SKU overlap and `x-redo` exclusion. Old "Flag possible duplicate shipments" workflow is off.
- Creator affiliate and UGC performance SOP added under `sops/` (separate from CS).

## 2026-08-14

- No flat $15 return processing fee. Return shipping is Checkout+ (Redo) or paid by the customer. Do not quote a dollar processing fee.
- Photo rules: Type A preference/fit — photos not required, send the customer to Redo. Type B damaged/defective — photos required within 48 hours of delivery.
- Split fulfillments are not duplicates when items do not overlap and quantity matches (example: Ellison10404Fitz).

## 2026-08-12

- Exchange/replacement standing rule: process Redo first; only ping fulfillment after Redo confirms it cannot cover the item in `#06-fitz-redo-external`.
- `x-redo` fulfillment records are a false positive for "two shipments," not a second pant.
- Fulfillment verification before promising a reship, refund, or replacement on a missing-item or short-shipment claim. Confirm with Cherry what was packed. Clinton Green / Ellison9946Fitz.

## 2026-08-10

- Fluid Pant fulfillment consolidated to Cherry/Beehive. Wiio/Hart phased out.

## 2026-08-06

- International return shipping for unsupported Redo regions: store credit first, then partial refund, full refund only with Kevin or Leandro approval. Do not ask the customer to ship back when return postage is at or above product value.
