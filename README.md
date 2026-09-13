# Pricing Calculator

An interactive pricing and ROI calculator for use live on a call. You put the
prospect's own numbers in while they watch, and it works out the annual impact
before it shows the fee.

One HTML file. Open it in a browser and it works, offline included. Nothing is
sent anywhere, so the numbers you type stay on your machine.

## Using it

Keep it in a pinned tab. Share your screen, ask the discovery questions, and
fill it in together:

- How many hours a week does this task take?
- What's the loaded hourly cost?
- How many additional leads could this generate?
- What's your average deal value?

Show the calculated impact first and the fee after. The ROI figure is what
answers a price objection, and it only lands if the prospect watched you type
their own inputs into it.

## The four calculators

**Chatbot.** One-time project pricing scaled by page count and complexity. It
recommends a tier and lets you override it.

**Automation, one-time.** Two modes. Revenue generating takes leads and value per
lead, works out annual impact, and prices the fee as a share of it. Operational
efficiency takes hours saved and hourly cost, works out annual savings, and
prices against that.

The two modes carry different fee bands because saved time and new revenue aren't
worth the same to a buyer. Money that shows up is easier to attribute than money
that stopped leaving.

**Automation retainer.** Monthly recurring across three tiers, showing total
contract value and what each tier includes.

**Revenue share.** Long-term partnership modelling, either on total revenue or on
attribution.

## Adjusting the numbers

The tiers, rates, and fee bands are constants at the top of the script in
`index.html`. They're set for one consultancy's pricing, so change them to yours
before showing this to anybody.

## Limitations

- The fee percentages ship as-is and won't match your business.
- Nothing is saved. Refreshing loses the inputs, which is deliberate, since a
  calculator that remembers the last prospect's numbers is a liability on a
  shared screen.
- It calculates annual impact from the figures given. Whether those figures are
  real is the discovery conversation, not the tool.

## License

MIT. See [LICENSE](LICENSE).

More at [benattanasio.com/lab](https://benattanasio.com/lab).
