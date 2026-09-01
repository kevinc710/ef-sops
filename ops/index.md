# Backend Ops Playbook

**Brand:** Ellison & Fitz  
**Lane:** Backend ops (Adam)  
**Status:** Current how. Not a week-by-week recap.  
**Not for:** VA customer-support pages. CS truth stays on the [live SOP](../). Dated history stays in the [changelog](../CHANGELOG.md).

This playbook is the current operating how for dropship, double-ship, Trustpilot week 1, Open Loops, WhatsApp, and Shopify writes. It does not replace the CS SOP.

## Owners

| Work | Owner | Must not |
|---|---|---|
| Backend ops, Beehiveship, double-ship cancel | Adam | Do not dump this playbook onto VA CS pages |
| Live chat and first-pass tickets | Mike | Never touches money |
| Refunds, store credit, Redo, chargebacks, damaged/missing | Abby (Abigail Go; customer-facing name Tina) | Do not work these in Gmail |
| High-risk cancels, Shopify writes for agents, WhatsApp send | Kevin | Agents do not write Shopify without Kevin's explicit OK |
| High-risk cancels, Trustpilot week-1 go-live | Leandro (with Kevin) | Do not turn Trustpilot invites on until Leandro says yes |
| Open Loops Drive sheet | Shane | No Notion or ClickUp as the team workspace |

Abby still processes CS money per the Commslayer split. That is CS, not a backend Shopify-write exception for other agents.

## Fulfillment

We are dropship. There is no warehouse.

| Product / partner | Current how |
|---|---|
| Ellison Fluid Pant | **Cherry/Beehive only**, in **Beehiveship**. Wiio/Hart is phased out. |
| Tapestitch | POD blanks. Not a backup Fluid Pant supplier. |
| Dropsure / Lay | Do not use. Do not ping. |

Do not tell customers that Cherry/Beehive consolidation resolved hemming or sizing. Wait for Cherry to confirm a new proven supplier in writing.

## Double-ship (Redo vs Cherry/Beehive)

Live risk: Redo Salt Lake accepts or ships a pant while Beehiveship is still pending or paid.

1. If Redo has accepted or shipped and Cherry/Beehiveship is still pending or paid, **cancel Cherry in `#08-cherry-beehive`**.
2. Do not re-ping Cherry.
3. Do not wait for two tracking numbers. Beehive dummy **TX** tracking on the `x-redo` line is a false positive. `x-redo` is the Redo protection line, not a second pant.
4. Shopify Flow is a **draft**. Kevin turns it on. When Redo is assigned or accepts, the draft tags `redo-accepted` and posts to Slack `#04-ops-alerts`.

**Illustration:** Ellison10713Fitz — Redo shipped Mixed L to Puerto Rico while Cherry was still pending paid.

Exchange/replacement for CS: only ping Cherry after Redo confirms out of stock in `#06-fitz-redo-external`. That rule lives on the CS SOP. Ops does not re-ping Cherry to "help" an exchange that Redo already covers.

## Trustpilot week 1 (ops)

Not live. Flow stays **off** until Leandro says yes. Kevin or Leandro turns week 1 on.

| Rule | Current how |
|---|---|
| Sender | **Klaviyo**, not Commslayer, not AFS |
| Trigger | ParcelPanel delivered + 7 days |
| Who | US only |
| Cap | 50, one invite |
| Suppress | Open ticket, Redo, refund, chargeback, delay, sizing-hem |
| Copy | How was it, and point them to **info@ellisonandfitz.com** |
| Public replies | Mike drafts. Nothing auto-posts. |
| Business owner inbox | `hello@` is marketing / Trustpilot Business owner. CS stays on `info@`. |

Do not use AFS. Do not gate reviews. Do not offer a discount for a review. Do not ask a reviewer to change or delete a review for credit.

## Open Loops

Shane owns the Drive sheet.

- Weekday 5-item stuck ping.
- No Notion and no ClickUp as the team workspace.

## WhatsApp

Adam reads WhatsApp for intake.

Nobody sends a WhatsApp message unless Kevin explicitly says to send that message.

## Shopify writes

Shopify writes for agents require Kevin's explicit OK.

Abby still processes CS refunds and store credit per the CS split. That is not permission for other agents to edit orders, cancel fulfillments, or issue money.
