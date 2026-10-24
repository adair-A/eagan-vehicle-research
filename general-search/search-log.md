# Search and verification log

Date: October 23, 2026, America/Chicago. Location ZIP55122 (marketplaces label it Saint Paul, used as Eagan-area origin). Preferred100mi, expanded200mi. Asking cap17000, with budget preference15000. No arbitrary100000-mile exclusion.

## Tooling actually exercised

Registered CamoFox MCP server_status returned version2.4.8 reachable, initially no active browser. create_tab successfully launched and navigated to cargurus.com; snapshot returned147refs; status confirmed browserConnected true. Reused this functional setup rather than reinstalling. Used create_tab, navigate_and_snapshot, snapshot, click (pagination), screenshot and close_tab. Parallel Visor researcher used a separate userId/session/tab and UI filter interactions, individual pages and snapshots; no shared-tab conflict. No connection repair/reinstallation was needed. Existing tool metadata was discovered, then browser calls actually executed. No new repository install occurred, so install-documentation workflow was unnecessary. No external browser skill installation was needed.

## Broad discovery

CarGurus search1: https://www.cargurus.com/search?zip=55122&distance=100&maxPrice=17000&fuelTypes=HYBRID .144results including nonpreferred manufacturers; inspected first result page. Toyota/Honda/Lexus refine attempt using repeated makeModelTrimPaths applied only the final Lexus parameter, detected from Applied filters. Corrected with separate make searches, not assumed multiple makes applied.

- Lexus100mi: max17000/fuelHYBRID/m37,55results incl delivery. Saved first-page snapshot; local ES300h186730/$10100 and CT examples discovered.
- Toyota200mi: https://www.cargurus.com/search?zip=55122&distance=200&maxPrice=17000&fuelTypes=HYBRID&makeModelTrimPaths=m7 . Saved page1, clicked Next page e251 and saved distinct page2. Sponsored repeat IDs deduplicated. Results included local and out-of-state delivery; do not mistake shipping listings for200mi inventory. Selected only regional finalists.
- Honda200mi: https://www.cargurus.com/search?zip=55122&distance=200&maxPrice=17000&fuelTypes=HYBRID&makeModelTrimPaths=m6 . Snapshot showed two result pages; first captured. Visor independently examined broader Honda using correct Accord fuel filter.
- CarGurus distinct captured IDs across saved Lexus/Toyota/Honda pages:78, including rejects/unverified/delivery leads. Initial broad all-make144 page was read but not counted in the saved78.

Visor actual UI price max17000 applied, location55122/distance100 then200. Camrygas94results first50captured; CamryHybrid17; Prius41 at200mi; Insight7; AvalonHybrid4; LexusES21; Mazda first50; AccordHybrid5 after correcting model to Accord plus hybrid fuel. **196 distinct VINs** in raw pool. Not all raw discoveries meet final eligibility. Multiple searches/pages fulfilled broad discovery well beyond30 initial candidates. VIN dedup in Visor, listing-ID dedup CG, VIN final shortlist. Cross-platform196+78 must not be summed as distinct cars. See [Visor log](visor-log.md).

## Individual verification

Coordinator opened CG individual pages: Prius c2016 ONG462237146; Prius2021 Marshfield461834869; Avalon2014Walser461522933; RAV4Hybrid2016459875220; Prius c2014Midwest461912062; Insight2020458600693; Prius2016Dahl457629923; CamryHybrid2014451274127; CorollaHybrid2023456756445; AccordHybrid2023459003173; CRVHybrid2020459105015. Read overview, VIN, transmission, fuel, mileage, price, history summary, pricing, dealer and description where rendered.

Final revisits confirmed unchanged price/miles/VIN for CG Midwest c12100/98235, Corolla16999/113449, AllianceCamry9349/169727, Avalon14149/140004, MarshfieldPrius14995/136074, RAV4 13345/163600, Accord15849/186460, CRV14999/180000. Dahl independently revisited13797/134544/VINJTDKBRFU0G3505210. Bedrock direct final revisit12349/78435/VINJM1BM1L73E1188087/InStock. Raw final snapshot evidence saved JSON. These verify web advertisements, not physical stock.

Agents verified16Visor individual pages, dealer VIN pages and readable history reports, preserving exact snapshots. Subsequent coordinator web reopens confirmed MainStreetCX5 price13175/121161/VIN, HopkinsCRV VIN/VDP and InverGroveAccord model/miles121122/VIN/eCVT/OnTheLot; its dynamic web reader did not expose price, so15150 derives from agent's live CamoFox dealer evidence. Wayzata reopen via web returned cache-miss, but agent's live CamoFox had verified9399/149811 earlier same date. BrookdaleCamry web agent direct read active InStock13249/140535; coordinator CamoFox later human verification, so physical availability explicitly unverified.

Photos: coordinator screenshots visually reviewed the BedrockMazda exterior collage, MidwestPriusc front exterior and DahlPrius front exterior. No obvious major exterior defect established from these limited views; no underbody photos/physical inspection. Paint issues on Midwest and hail on Marshfield taken from explicit seller descriptions, not assumed from photos. Other galleries not exhaustively visually examined.

## Errors, conflicts and recovery

- No CamoFox connection failure. Some navigations took tens of seconds; subsequent snapshots/pages worked.
- Repeated-make URL applied only last make: corrected separate make searches after reading applied filters.
- Visor incorrect model strings initially returned0: corrected UI model/fuel taxonomy; not interpreted as no inventory.
- Several Luther/Walser/TomKadlec dealer pages showed human-verification in CamoFox. Respected challenges; used readable dealer web tool/marketplace pages and readable directly linked AutoCheck where available.
- Bedrock free CARFAX link returned iframe-only snapshot; supplemental web Internal Error/HTTP challenge. No bypass or payment. Full history remains unknown; dealer accident-free claim labeled.
- Wayzata/other CARFAX iframe inaccessible. An example badge is not history evidence. Visor itself warns document logos may only be examples; no report assumed from icons.
- CG zero accidents on Dahl does not contradict CARFAX other minor damage; both reported accurately. CG Marshfield owner count/trim differed from CARFAX/seller; retained conflict.
- SamCamry and OneWayCamry dealer rebuilt disclosures; TomKadlecMazda readable report severe collision and second collision; EastSideAccord total-loss disclosure; FleetInsight sold. Explicit exclusions.
- A local apply_patch raw-evidence replacement rejected duplicate delete/add operations for one path; retried by creating distinct final evidence filename successfully. No research data lost.

## Files and continuation

Main user outputs: car-search-report.md, vehicle-shortlist.csv, vehicle-comparison.md, reliability-research.md, search-log.md. Supporting files: finalists.json; visor-findings.json/log; alternatives-findings.json/log; cargurus-discovery.json; initial and final snapshots; Mazda and hybrid verification supplements. Original mission copied to user-request.txt. CSV carries15 uniqueVINs, direct links, score parts/confidence, date, status and unknowns. CSV is plain delimited data as requested, not an Excel workbook.

For continuation: re-open exact finalist links; recheck price/miles/VIN/availability and obtain actual history/title and itemized quote. Start with BedrockMazda and MidwestPriusc. Model recalls are research only; VIN-specific recall/support-program printouts remain required unless a readable history record explicitly reports status. Do not contact sellers without authorization. No seller contact, application, account login, reservation, personal-data entry or paid report occurred during this assignment.


