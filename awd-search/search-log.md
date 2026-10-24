# Search and verification log — AWD mission

Date: October 23, 2026, America/Chicago. Origin: ZIP 55122, Eagan area (marketplaces label it Saint Paul). Started within 100 miles, expanded to 200 miles. Preferred advertised price at most $15,000, exceptional stretch $17,000. Radius is not driving mileage. Delivery listings were not selected as nearby finalists.

## Browser tools actually exercised

CamoFox MCP server_status reported version 2.4.8 reachable. create_tab opened CarGurus; the initial accessibility snapshot returned 241 references and browserConnected became true. Actual navigation, filtering, pagination, individual listing extraction, screenshots and DOM reads worked. No reinstall or server restart was needed.

Main tab: a6103753-92af-413e-a711-5343acc22f1c. Second CarGurus tab: 7ec906bc-7882-4128-b98c-26f60e0feae0. Dedicated Visor tab: ee7097f1-3845-4bdc-aa1e-f1810c811343, user/session root-visor.

The explicit local health request to http://127.0.0.1:9377/health initially failed with a sandbox socket-access error. An approved read-only escalation succeeded: ok/running/browserConnected true, engine camoufox, version 2.4.8. This was a shell sandbox restriction, not a broken MCP browser connection. Original Owner's get_links result returned blank hrefs; reading actual DOM anchor.href recovered the dealer links.

The user authorized parallel agents. The reliability researcher completed its file. Two inventory researchers hit an account usage limit; the main session continued and independently reopened useful leads. No dealer contact, login, inquiry form, paid report, reservation or financial commitment occurred.

## CarGurus discovery

The first guessed driveTypes URL parameter did not apply AWD. The applied-filter snapshot exposed that problem; clicking Drivetrain and All-Wheel Drive produced the correct wheelSystems parameter. Subsequent snapshots verified actual filters.

- AWD hybrids, 100 miles, at most $17,000: 26 reported results, both pages captured.
- AWD hybrids, 200 miles, at most $17,000: 34 reported results, both pages captured.
- Mazda AWD, 100 miles, at most $15,000: 70 reported results; first page captured.
- Toyota AWD/4WD, 100 miles, at most $15,000: 293 reported results; first page captured.
- Honda AWD/4WD through model year 2014, 100 miles, at most $15,000: 240 reported results; first page captured. The separate broad hybrid search included the newer CR-V Hybrid.

Across the saved 200-mile hybrid pages and Mazda/Toyota/Honda pages there were **94 distinct listing IDs**. This is a discovery pool, including rejected brands, delivery listings and other non-finalists. Sponsored repetitions were deduplicated by listing ID. It is not 94 recommendations or an exhaustive inventory census.

Search URLs:
- https://www.cargurus.com/search?zip=55122&distance=200&maxPrice=17000&fuelTypes=HYBRID&wheelSystems=ALL_WHEEL_DRIVE
- https://www.cargurus.com/search?zip=55122&distance=100&maxPrice=15000&makeModelTrimPaths=m42&wheelSystems=ALL_WHEEL_DRIVE
- https://www.cargurus.com/search?zip=55122&distance=100&maxPrice=15000&makeModelTrimPaths=m7&wheelSystems=ALL_WHEEL_DRIVE,FOUR_WHEEL_DRIVE
- https://www.cargurus.com/search?zip=55122&distance=100&maxPrice=15000&makeModelTrimPaths=m6&wheelSystems=ALL_WHEEL_DRIVE,FOUR_WHEEL_DRIVE&endYear=2014

The all-make AWD-hybrid query could include newer Corolla, Venza, Prius, NX and UX configurations if present under the cap. No acceptable finalist from those newer lines was verified. This does not prove none exists anywhere. Conventional chain-CVT Subaru hybrids and Nissan were excluded. Ford/Mitsubishi/BMW/Hyundai leads did not establish a sufficiently verified reliability/value advantage.

## Visor discovery and follow-through

Actual rendered searches at 200 miles and at most $17,000:
- RAV4 Hybrid: 3 cards, all captured.
- Highlander Hybrid: 11 cards, all captured.
- Lexus RX with hybrid fuel: 4 cards, all captured.
- Prius: 41 cards captured; FWD and pre-AWD years were not promoted.
- Mazda CX-5: 69 reported, first 50 captured; some are FWD and require exclusion.
- CR-V Hybrid model and CR-V plus hybrid-fuel queries returned zero, while CarGurus had a 2020 hybrid. Treated as platform taxonomy/coverage limitation, not proof of no Honda inventory.

Example URL:
https://visor.vin/search/listings?make=Toyota&model=RAV4%20Hybrid&geo_origin_kind=postal_code&geo_origin_value=%2255122%22&geo_mode=radius&geo_distance_value=%22200%22&geo_distance_unit=mi&price_max=17000

Full URLs and snapshots are in awd-live-evidence.json. Counts overlap by VIN and cannot be added to CarGurus totals. Visor's example CARFAX/window-sticker logos are not evidence that actual documents exist.

Opened individual Visor VIN pages for East Side's 2016 RAV4, the 2011 Highlander and Rochester's 2015 Mazda. Followed their dealer links. Rochester Mazda independently confirmed AWD, six-speed automatic, 121,522 miles and $12,749 plus $350 doc = $13,099. The Highlander dealer marked its gallery SOLD despite Visor still advertising it.

## Individual listing checks and final revisits

Opened 16 CarGurus detail pages: 12 comparison vehicles plus the salvaged Prius AWD-e, 2018 Highlander Hybrid, 2012 Highlander Hybrid and high-mileage Wisconsin RAV4 Hybrid. Read VIN, asking price, mileage, drivetrain, engine/transmission, history summary, dealer description, rating and pricing age where available.

Final re-navigation confirmed matching VIN/price/miles for all 12:
462307414, 451916559, 461480319, 460509621, 461858703, 461633523, 462344738, 459875220, 458238358, 459105015, 461084646, 460589558.

Saved evidence: awd-final-verification.json. Public individual-page activity does not confirm physical stock or working AWD.

The 2017 RAV4 was also found in the dealer's Active Inventory and its exact dealer page. Dealer base $11,995 versus CarGurus $12,345 differs $350. The same dealer's 2016 base/Visor $12,995 versus CarGurus $13,345 also differs $350. RX base/Visor $9,995 versus CarGurus $10,345 similarly differs $350. Obtain written fee totals; do not double-count advertised included fees.

## History conflicts and access limits

- RAV4 2017 seller-linked vinquestion report was readable through CamoFox: government use, minor front/rear damage in 2018, 11 services and last reported 102,917 miles. Current listing is 160,048. This establishes a reporting gap, not a rollback. It is a dealer-hosted CARFAX-branded copy, not a newly ordered independent report. Supplemental web reader failed for that URL; the browser itself worked.
- East Side RAV4 2016 VIN JTMRJREV1GD017745: exact dealer page showed $14,995/115,225 and AWD. Exact-VIN web search exposed September 2026 salvage/hail auction records. Excluded preferred rankings; third-party auction history is not an authoritative current state-title certificate.
- Prius AWD-e VIN JTDL9RFU5K3011157: explicitly salvaged title; excluded.
- Highlander 2018: unresolved “No accidents, frame damage reported” wording; held out of preferred rankings.
- Highlander 2011 VIN JTEDC3EHXB2001751: dealer SOLD; removed.
- CR-V 2012 free AutoCheck button opened an unreadable iframe. Did not buy or bypass it; only the listing summary was established.
- Venza: red representative photo versus gray vehicle description; actual condition photographs unknown.
- Dealer maintenance and warranty claims remain claims until contracts/invoices are produced.

Screenshots visually reviewed the front exterior of Rochester Mazda, 2017 RAV4 and 2012 CR-V. Venza displayed the mismatched representative image. No underbody or full-gallery clearance. No photographs establish hidden rust or functioning rear-axle drive. Marketplace dealer review samples are small and are not independent reputation audits.

## Reliability, pricing and saved results

Manufacturer/NHTSA sources are in reliability-research.md, including exact 2015 Mazda and 2013 Venza supplements. A TSB is not a statistical failure rate; recall/support-program eligibility is VIN-specific. No independent current VIN-recall clearance was established.

Minnesota DOR confirmed 6.875% motor-vehicle tax on taxable price:
https://www.revenue.state.mn.us/guide/motor-vehicle-sales
Fuel at $3.25/gallon, repair reserves, insurance, fees and resale are scenario assumptions, not current quotes or forecasts.

Existing FWD-oriented main report/CSV/log/comparison were copied into prior-research/ before replacement. They are ineligible for this AWD mission. Current authoritative files:
- car-search-report.md
- vehicle-shortlist.csv
- reliability-research.md
- price-comparison.md
- search-log.md
- vehicle-comparison.md
- awd-shortlist.json
- awd-live-evidence.json
- awd-final-verification.json

Other older support files may remain in the directory and must not be treated as current AWD recommendations. Plain CSV is a research dataset, not an Excel workbook.

## Validation and limits

Twelve unique shortlisted VINs; all advertised AWD; only Toyota, Honda, Mazda and Lexus; no FWD, Nissan or conventional belt/chain CVT. Each six-category score sums to the total. Price/mileage/VIN checked against saved final snapshots. All five requested main filenames exist.

Search was broad but not exhaustive: both hybrid pages were examined, while only first gasoline result pages were captured before individual follow-up. Physical stock, actual title certificate, full service history, condition, functioning AWD and battery health require seller documents and independent inspection. No unconditional BUY is asserted.


