## Proofing Tests

Proofing to fix errors is common sense. However, if any steps are skipped, the cost of fixing errors becomes
prohibitive.

### Reviewers

One reviewer is fine; two reviewers, better. Crowdsourcing? Perfect.

### Tests

The following is a list of tests designed to minimize chart errors:
  + Implement 48-hour cooling period between chart completion and proofing.
  + Labels
    + Make sure the title and model numbers match the source document specification.
    + Make sure there is a Creative Commons Public Domain (Zero) marking is somewhere on the chart.
      + Do not use vector or raster images, to avoid scaling problems for corner cases.
    + Make sure that the printed page source document is 11" x 17" Tabloid.
      + Can be proofed on A4 or 8.5" x 11".
  + Controlled Items
    + Count each data item from 1 to 214. **Twice.**
    + Count each header item from 1 to 17. **Twice.**
    + Review the expected content of each data item, alongside the specification. **Twice.**
    + Review the expected content of each header item, alongside the specification. **Twice.**
  + Extras
    + (Optional) Review variants to ensure accuracy. 
      + Variant list need not be complete.
      + However, any listed variant must be accurate.
  
### Expected Output

  + Chart with no mistakes (or mistakes corrected).
  + All mistakes should be logged and recorded for future proofing.
  
