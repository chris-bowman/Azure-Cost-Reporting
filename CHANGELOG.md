# Azure Cost Management Power BI Report Change Log

## Releases

### v3.2:
- [Link to template](Power%20BI%20Report/Azure%20Cost%20Management%20v3.2.pbit)
- Fixed bug with AHB on summary screen and AHB tabs - VM cores were incorrectly matching to _VMSizes_ so were defaulting to 8 cores.
- Extended _AHBUsage_ data table to all data for longer history.
- Update tag formulas on Resources to correctly handle start/end tags in json.
- Other misc changes (formatting, etc).

### v3.1:

- [Link to template](Power%20BI%20Report/Azure%20Cost%20Management%20v3.1.pbit)
- Added support for MCA - let me know if any issues!
- Added table "Usage Meters" to help filter on meter hierarchy instead of using "Pricesheet" due to MCA Pricesheet table including more Marketplace details and some duplicates.
- Added hidden table "WindowsLicenses" to aid lookup of PAYG pricing for AHB.
- Removed DefaultOfferId parameter, replaced with lookup.
- Updated VMsizes table.

### v3.0:

- [Link to template](Power%20BI%20Report/Azure%20Cost%20Management%20v3.0.pbit)
- Initial public release.
