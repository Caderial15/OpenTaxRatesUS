# OpenTaxRatesUS
A free, community-maintained database of U.S. sales tax rates across all jurisdictional levels (state, county, city, district) and economic nexus thresholds. We're liberating publicly available tax data from expensive subscription services and making it accessible to everyone in a standardized, usable format.

# USA - Sales Tax & Economic Nexus - Official Information Sources

# US Sales Tax & Economic Nexus Information Sources

## Alabama

### Economic Nexus Source
- **Source URL**: Alabama Department of Revenue – [Simplified Sellers Use Tax (SSUT) page](https://www.revenue.alabama.gov/sales-use/simplified-sellers-use-tax-ssut/)
- **Update Frequency**: Changes reflected as legislation updates (e.g., Act 2018-539; Act 2019-382)
- **Data Format**: Webpage with program guidance (HTML, with PDF notices)
- **API Available**: No (informational page only)

### Sales Tax Rate Sources
- **State Rate URL**: Alabama Department of Revenue – [Sales and Use Tax Rates](https://www.revenue.alabama.gov/sales-use/tax-rates/) (state rate listed under "Sales Tax General")
- **Local Rates URL**: Alabama Department of Revenue – [Local Cities and Counties Tax Rates](https://www.revenue.alabama.gov/sales-use/local-cities-and-counties-tax-rates-text-file/) (monthly CSV of all city/county rates)
- **Special Districts URL**: Not applicable (Alabama uses city/county taxes; police jurisdiction taxes listed on state site)
- **ZIP Code Mapping URL**: Alabama DOR [Address Search Tool](https://www.revenue.alabama.gov/sales-use/tax-rates/) for local rates
- **Data Format**: Downloadable CSV updated **monthly** (taxrates.csv, with current and historical local rates)
- **API Available**: No (rates provided via file download)
- **GIS Resources**: No dedicated public GIS; address lookup tool available for local rate search

## Alaska

### Economic Nexus Source
- **Source URL**: Alaska Remote Seller Sales Tax Commission – [For Businesses/Sellers page](https://arsstc.org/business-sellers/)
- **Update Frequency**: As needed by Commission (threshold updated effective Jan 1, 2025)
- **Data Format**: Webpage (HTML) with guidelines and adopted Uniform Code
- **API Available**: No (online portal for registration, no public API)

### Sales Tax Rate Sources
- **State Rate URL**: Not applicable – Alaska has **no state sales tax** (tax-free at state level)
- **Local Rates URL**: Alaska Remote Seller Sales Tax Commission – [Tax Rates page](https://arsstc.org/business-sellers/tax-rates/) (monthly rate sheets for all member local jurisdictions)
- **Special Districts URL**: Not applicable (local sales taxes are by borough/city; no separate state-administered districts)
- **ZIP Code Mapping URL**: ARSSTC [Tax Rate Sheet with ZIP Codes](https://arsstc.org/business-sellers/tax-rates/) (Excel files combining rates by ZIP)
- **Data Format**: Downloadable Excel sheets (updated monthly with current and historical rates)
- **API Available**: No (rate tables provided in files)
- **GIS Resources**: No standalone GIS; Commission provides an online lookup tool via partner service

## Arizona

### Economic Nexus Source
- **Source URL**: Arizona Department of Revenue – [Out-of-State Sellers Economic Threshold page](https://azdor.gov/business/transaction-privilege-tax/retail-sales-subject-tpt/out-state-sellers/economic-threshold)
- **Update Frequency**: Threshold phased in (2019–2021; now fixed)
- **Data Format**: Webpage (HTML) summarizing nexus law (HB 2757)
- **API Available**: No (informational page only)

### Sales Tax Rate Sources
- **State Rate URL**: Arizona DOR – [Transaction Privilege Tax (TPT) Rate Tables](https://azdor.gov/sites/default/files/2023-05/TPT_RATETABLE_01012021.pdf) (state TPT base rate included)
- **Local Rates URL**: Arizona DOR – [TPT and Other Tax Rate Tables](https://azdor.gov/sites/default/files/2023-05/TPT_RATETABLE_01012021.pdf) (comprehensive PDF of state, county, and city TPT rates)
- **Special Districts URL**: Arizona DOR – [County & Special District Codes](https://azdor.gov/sites/default/files/2023-05/TPT_RATETABLE_01012021.pdf) (included in rate tables, e.g. Table 3 for special districts)
- **ZIP Code Mapping URL**: Arizona DOR – [Tax Rate Look Up Tool](https://azdor.gov/business/transaction-privilege-tax/tax-rate-table) (interactive address/ZIP search for TPT rates)
- **Data Format**: PDF rate tables updated **monthly**; interactive web lookup
- **API Available**: No public API (online lookup provided via AZTaxes.gov)
- **GIS Resources**: Yes – integrated map locator in the lookup tool (no separate shapefile download publicly)

## Arkansas

### Economic Nexus Source
- **Source URL**: Arkansas Department of Finance & Administration – [Remote Sellers guidance](https://www.dfa.arkansas.gov/office/taxes/excise-tax-administration/sales-use-tax/remote-sellers/)
- **Update Frequency**: Established by Act 822 (2019); changes require new legislation
- **Data Format**: Webpage (HTML) with statutory threshold definition
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Arkansas DFA – [State Sales & Use Tax Rates page](https://www.dfa.arkansas.gov/office/taxes/excise-tax-administration/sales-use-tax/sales-use-tax-rates/state-sales-use-tax-rates/) (statewide 6.5% rate detailed)
- **Local Rates URL**: Arkansas DFA – [City and County Sales & Use Tax Rates page](https://www.dfa.arkansas.gov/office/taxes/excise-tax-administration/sales-use-tax/sales-use-tax-rates/city-and-county-sales-use-tax-rates/) (quarterly updated tables of local rates)
- **Special Districts URL**: Not applicable (Arkansas local taxes are city/county only)
- **ZIP Code Mapping URL**: Arkansas DFA – [Local Tax Lookup Tools page](https://www.dfa.arkansas.gov/office/taxes/excise-tax-administration/sales-use-tax/local-tax-lookup-tools/) (includes downloadable tax rate text file by jurisdiction)
- **Data Format**: PDF and XLS tables by quarter; also a **monthly** updated CSV (tax rates file)
- **API Available**: No (but a downloadable **taxrates.txt** file is provided monthly)
- **GIS Resources**: No dedicated GIS; DFA provides an online ZIP+4 lookup and jurisdiction code file for rate determination

## California

### Economic Nexus Source
- **Source URL**: California Department of Tax and Fee Administration – [Wayfair & AB 147 Use Tax Collection guide](https://www.cdtfa.ca.gov/industry/wayfair/)
- **Update Frequency**: Updated upon AB 147 enactment (2019); otherwise static
- **Data Format**: Webpage (HTML) outlining $500,000 threshold and provisions
- **API Available**: No (informational guide only)

### Sales Tax Rate Sources
- **State Rate URL**: CDTFA – [City & County Sales & Use Tax Rates page](https://www.cdtfa.ca.gov/taxes-and-fees/sales-use-tax-rates.htm) (statewide base rate noted)
- **Local Rates URL**: CDTFA – [Tax Rates Effective January 1, 2025](https://www.cdtfa.ca.gov/taxes-and-fees/sales-use-tax-rates.htm) (downloadable dataset of each county/city rate)
- **Special Districts URL**: CDTFA – [District Taxes, Rates, and Effective Dates](https://www.cdtfa.ca.gov/taxes-and-fees/sales-use-tax-rates.htm) (listing all local district tax components)
- **ZIP Code Mapping URL**: CDTFA – [Find a Sales and Use Tax Rate by Address tool](https://www.cdtfa.ca.gov/taxes-and-fees/sales-use-tax-rates.htm)
- **Data Format**: Excel/CSV available via CDTFA Open Data Portal (export of tax rates); interactive map/lookup
- **API Available**: Yes (CDTFA Open Data Portal offers API access to rate datasets)
- **GIS Resources**: Yes – CDTFA's [online map for current rates](https://www.cdtfa.ca.gov/taxes-and-fees/gis/SUTMap/) (interactive GIS map updated regularly)

## Colorado

### Economic Nexus Source
- **Source URL**: Colorado Revised Statutes §39-26-102(3)(c) – [Economic Nexus Definition](https://law.justia.com/codes/colorado/2022/title-39/article-26/part-1/section-39-26-102/)
- **Update Frequency**: Set by statute (effective 2019; transaction threshold eliminated 2019)
- **Data Format**: Statutory text (available via state code)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Colorado Division of Taxation – Colorado Sales/Use Tax Rates (DR-1002) publication (lists 2.9% state tax)
- **Local Rates URL**: Colorado DOR – DR-1002 Sales/Use Tax Rates (semiannual PDF of all state-collected local tax rates, updated Jan 1 and Jul 1)
- **Special Districts URL**: Colorado DOR – included in DR-1002 (regional transportation, etc., where applicable)
- **ZIP Code Mapping URL**: Colorado Sales Tax GIS Lookup Tool (state-provided address locator via Colorado SUTS)
- **Data Format**: PDF (DR-1002) updated **twice yearly**; online GIS lookup for addresses
- **API Available**: No public API (state provides a downloadable jurisdiction database for SUTS users)
- **GIS Resources**: Yes – Sales & Use Tax System (SUTS) Geographic Information System for address-based rate lookup

## Connecticut

### Economic Nexus Source
- **Source URL**: Connecticut DRS – [2019 Legislative Update](https://portal.ct.gov/DRS/Legislative-Summaries/2019-Legislative-Updates/Regular-Session-State-Tax-Legislation-Overview) (economic nexus threshold reduction)
- **Update Frequency**: One-time law change effective July 1, 2019
- **Data Format**: Webpage (CT.gov legislative summary)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Connecticut DRS – State Tax Legislation Overview (notes base sales tax changes, e.g., 6.35% general rate)
- **Local Rates URL**: Not applicable – Connecticut **does not allow local sales taxes** (single statewide rate)
- **Special Districts URL**: Not applicable (no local or special sales tax jurisdictions)
- **ZIP Code Mapping URL**: Not applicable (same rate statewide)
- **Data Format**: Web only (state rate info provided in DRS publications; no separate data file needed)
- **API Available**: No
- **GIS Resources**: No (uniform state rate, no local mapping necessary)

## Delaware

### Economic Nexus Source
- **Source URL**: Delaware Division of Revenue – [Doing Business in Delaware: No Sales Tax](https://revenue.delaware.gov/business-tax-forms/doing-business-in-delaware/step-4-gross-receipts-taxes/)
- **Update Frequency**: Not applicable (Delaware imposes **no sales tax**)
- **Data Format**: Webpage (business tax info confirming no sales tax)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Not applicable – Delaware **has no state or local sales tax**
- **Local Rates URL**: Not applicable
- **Special Districts URL**: Not applicable
- **ZIP Code Mapping URL**: Not applicable
- **Data Format**: N/A (tax-free state)
- **API Available**: N/A
- **GIS Resources**: N/A

## District of Columbia

### Economic Nexus Source
- **Source URL**: D.C. Office of Tax and Revenue – Remote Seller guidance
- **Update Frequency**: Implemented Jan 1, 2019 (no recent changes)
- **Data Format**: Webpage (CFO/OTR site) describing $100,000 or 200 transactions threshold
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: D.C. OTR – Tax Rates and Revenues (DC general sales tax information on OTR site)
- **Local Rates URL**: Not applicable (DC is a single jurisdiction; no sub-local sales taxes)
- **Special Districts URL**: Not applicable
- **ZIP Code Mapping URL**: Not applicable (one jurisdiction)
- **Data Format**: Web (DC publishes its sales tax rate (6%) on OTR site; various specific category rates listed in tax publications)
- **API Available**: No
- **GIS Resources**: No (single jurisdiction)

## Florida

### Economic Nexus Source
- **Source URL**: Florida Department of Revenue – [Tax Information Publication #21A01-03](https://floridarevenue.com/taxes/tips/Documents/TIP_21A01-03.pdf)
- **Update Frequency**: Enacted 2021 via SB 50; static threshold thereafter
- **Data Format**: PDF bulletin (official TIP)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Florida DOR – [Discretionary Sales Surtax page](https://floridarevenue.com/taxes/taxesfees/Pages/discretionary.aspx) (explains 6% state sales tax plus county surtaxes)
- **Local Rates URL**: Florida DOR – Form DR-15DSS: Discretionary Sales Surtax Information (annual PDF listing each county's surtax rate)
- **Special Districts URL**: Not applicable (surtaxes are county-imposed; no separate special districts outside county scope)
- **ZIP Code Mapping URL**: Florida DOR – [Address/Jurisdiction Database](https://floridarevenue.com/taxes/taxesfees/Pages/discretionary.aspx) for sales tax (GIS tool for address-based county surtax)
- **Data Format**: PDF rate table updated annually; online address lookup (point-and-click GIS)
- **API Available**: No (the DOR provides a downloadable jurisdiction database, but no public API)
- **GIS Resources**: Yes – official GIS lookup for county surtax rates by address

## Georgia

### Economic Nexus Source
- **Source URL**: Georgia Department of Revenue – Remote Seller guidance (per HB 61 and 2020 amendment)
- **Update Frequency**: Updated Jan 1, 2020 (removed 200-transaction threshold)
- **Data Format**: Webpage (Georgia DOR FAQ) and legislative reference (HB 61)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Georgia DOR – [Sales Tax Rates – General Rate Chart](https://dor.georgia.gov/document/document/general-rate-chart-effective-january-1-2025-through-march-31-2025/download) (state 4% base noted in rate chart code 000)
- **Local Rates URL**: Georgia DOR – [Sales & Use Tax Rate Charts](https://dor.georgia.gov/document/document/general-rate-chart-effective-january-1-2025-through-march-31-2025/download) (quarterly PDF listing combined state+local rates by county/city code)
- **Special Districts URL**: Georgia DOR – included in rate chart (special jurisdiction codes for MARTA, etc., e.g., Fulton Co. special district entries)
- **ZIP Code Mapping URL**: Georgia DOR – no direct public tool by ZIP; rate charts by jurisdiction code are provided (GIS integration through third-party services)
- **Data Format**: PDF rate charts updated **quarterly** (state-provided)
- **API Available**: No (rates must be obtained from published charts)
- **GIS Resources**: No official GIS tool from DOR (businesses use address-to-code mapping via DOR's jurisdiction tables)

## Hawaii

### Economic Nexus Source
- **Source URL**: Hawaii Department of Taxation – [Act 221 Economic Nexus Standards](https://files.hawaii.gov/tax/legal/tir/tir20-05.pdf) (HRS §235-4.2)
- **Update Frequency**: Enacted 2018 (no further updates; in effect via HRS)
- **Data Format**: Tax Information Release (TIR 2020-05) quoting law
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Hawaii Department of Taxation – General Excise Tax (GET) Information (base 4% GET noted)
- **Local Rates URL**: Hawaii DOTAX – [County Surcharge page](https://tax.hawaii.gov/geninfo/countysurcharge/) (lists counties with 0.5% GET surcharges and effective dates)
- **Special Districts URL**: Not applicable (surcharges are county-wide; no other local sales tax jurisdictions)
- **ZIP Code Mapping URL**: Not applicable (Hawaii surcharges apply by island/county uniformly)
- **Data Format**: Webpage (HTML list of county surcharge rates)
- **API Available**: No
- **GIS Resources**: No (simple county-based rates; see county list on DOTAX site)

## Idaho

### Economic Nexus Source
- **Source URL**: Idaho State Tax Commission – Remote Seller Nexus guidance (official FAQ/notice referencing $100,000 sales threshold)
- **Update Frequency**: Implemented June 1, 2019; static threshold (no transaction count)
- **Data Format**: Webpage/Notice (HTML)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Idaho State Tax Commission – Sales Tax page (state 6% rate information on Tax Commission site)
- **Local Rates URL**: Not applicable – Idaho **does not have general local option sales taxes** (some resort city taxes exist separately)
- **Special Districts URL**: Not applicable (no general local sales tax jurisdictions under state administration)
- **ZIP Code Mapping URL**: Not applicable (statewide 6% for general sales tax)
- **Data Format**: Web (state rate info only; any resort city taxes are administered locally, not listed by ISTC)
- **API Available**: No
- **GIS Resources**: No (single state rate for most purposes)

## Illinois

### Economic Nexus Source
- **Source URL**: Illinois Department of Revenue – Remote Seller guidance (state law effective Oct 1, 2018)
- **Update Frequency**: Static (post-Wayfair law set $100k/200 transactions)
- **Data Format**: Webpage (IDOR guidance and regulations)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Illinois DOR – Tax Rate Database (state 6.25% base rate noted; available via IDOR website)
- **Local Rates URL**: Illinois DOR – Tax Rate Finder (online tool for all state and local sales/use tax rates by address or jurisdiction, including home rule municipalities)
- **Special Districts URL**: Illinois DOR – included in Tax Rate Database (special business district or transit rates if applicable are in the lookup)
- **ZIP Code Mapping URL**: Illinois DOR – Sales Tax Rate Finder (address and ZIP-based search on IDOR site)
- **Data Format**: Online database (searchable by address or jurisdiction code; downloadable rate tables by jurisdiction via IDOR site)
- **API Available**: No formal API (data accessible through IDOR's online lookup tool)
- **GIS Resources**: No public GIS shapefile, but address lookup tool available

## Indiana

### Economic Nexus Source
- **Source URL**: Indiana Department of Revenue – Remote Seller Nexus update (effective Jan 1, 2024, $100k sales only)
- **Update Frequency**: Updated 2024 (removed 200 transaction clause)
- **Data Format**: Webpage (DOR notice/FAQ)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Indiana DOR – Sales Tax Rates (statewide 7% rate; IN has no local sales tax)
- **Local Rates URL**: Not applicable – Indiana **has no local sales taxes** (7% state rate applies uniformly)
- **Special Districts URL**: Not applicable
- **ZIP Code Mapping URL**: Not applicable (single rate statewide)
- **Data Format**: Web (rate information on IN DOR site or Tax Handbook)
- **API Available**: No
- **GIS Resources**: No

## Iowa

### Economic Nexus Source
- **Source URL**: Iowa Department of Revenue – Remote Seller guidance (effective Jan 1, 2019, $100k threshold)
- **Update Frequency**: Static (Iowa law requires $100k sales in current or prior year)
- **Data Format**: Webpage (IDR remote seller FAQ)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Iowa DOR – Sales Tax info (state 6% base rate, 1% local option framework)
- **Local Rates URL**: Iowa DOR – Local Option Tax Rates (IDR maintains list of cities/counties with 1% local option sales tax)
- **Special Districts URL**: Not applicable (local option is by jurisdiction; no separate districts beyond city/county)
- **ZIP Code Mapping URL**: Iowa DOR – Tax Rate Lookup by Address (online tool to find state+local tax by address)
- **Data Format**: Web and PDF (IDR publishes local option tax rate schedules; interactive lookup available)
- **API Available**: No
- **GIS Resources**: No standalone GIS, but address lookup tool on IDR site

## Kansas

### Economic Nexus Source
- **Source URL**: Kansas Department of Revenue – Remote Seller Notice 21-17
- **Update Frequency**: Enacted July 1, 2021 (threshold $100k sales; Kansas had no transaction threshold)
- **Data Format**: PDF notice and web guidance
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Kansas DOR – Sales Tax Rate Charts (state 6.5% base noted; KDOR website provides current rate info)
- **Local Rates URL**: Kansas DOR – Jurisdiction Code Rate Tables (KDOR publishes sales tax rates by city/county code, updated quarterly)
- **Special Districts URL**: Included in Kansas rate tables (transit authority districts, etc., are reflected in local codes where applicable)
- **ZIP Code Mapping URL**: Kansas DOR – Sales Tax Rate Locator (online lookup by address/ZIP on KDOR site)
- **Data Format**: PDF/Excel tables per quarter; online lookup tool
- **API Available**: No
- **GIS Resources**: No public GIS, but address lookup on KDOR site

## Kentucky

### Economic Nexus Source
- **Source URL**: Kentucky DOR – Remote Seller FAQ (HB 487 effective Oct 1, 2018)
- **Update Frequency**: Static (requires >$100k or ≥200 transactions per year)
- **Data Format**: Webpage (TaxAnswers.ky.gov guidance)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Kentucky DOR – Sales Tax info (statewide 6% rate; KY has no local sales taxes)
- **Local Rates URL**: Not applicable – Kentucky **does not have local sales tax** (state rate only)
- **Special Districts URL**: Not applicable
- **ZIP Code Mapping URL**: Not applicable
- **Data Format**: Web (state rate noted on DOR site; no local data needed)
- **API Available**: No
- **GIS Resources**: No

## Louisiana

### Economic Nexus Source
- **Source URL**: Louisiana Department of Revenue – Remote Sellers Information (effective July 1, 2020)
- **Update Frequency**: Static (>$100k or ≥200 transactions per year, as per Act 216, 2019)
- **Data Format**: Webpage (LDR remote seller guidance)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Louisiana Department of Revenue – Sales Tax Rates (state 4.45% rate noted in LDR publications)
- **Local Rates URL**: Louisiana Sales & Use Tax Commission for Remote Sellers – Parish Sales Tax Lookup (central portal for parish rates for remote sellers)
- **Special Districts URL**: Louisiana Parish Sales Tax Offices – official parish tax tables (each parish's sales tax rates, via LATA)
- **ZIP Code Mapping URL**: Parish e-File system or Remote Sellers Commission lookup (address-based parish rate finder)
- **Data Format**: Web (parish rate tables, PDF or database per parish)
- **API Available**: No public API (rate lookup via commission portal)
- **GIS Resources**: No statewide GIS (parish boundaries determine rates; lookup tools available on commission site)

## Maine

### Economic Nexus Source
- **Source URL**: Maine Revenue Services – Remote Seller Nexus guidance (effective July 1, 2018)
- **Update Frequency**: Static (>$100k or ≥200 transactions per year)
- **Data Format**: Webpage (MRS guidance and statute reference)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Maine Revenue Services – Sales, Use & Service Provider Tax page (state 5.5% sales tax info)
- **Local Rates URL**: Not applicable – Maine **has no local sales tax** (uniform statewide rate)
- **Special Districts URL**: Not applicable
- **ZIP Code Mapping URL**: Not applicable
- **Data Format**: Web (state rate on MRS site; no local data)
- **API Available**: No
- **GIS Resources**: No

## Maryland

### Economic Nexus Source
- **Source URL**: Maryland Comptroller – Sales Tax – Remote Seller guidance (effective Oct 1, 2018)
- **Update Frequency**: Static ($100k or 200 transactions threshold in law)
- **Data Format**: Webpage (MarylandTaxes.gov FAQ)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Maryland Comptroller – Sales and Use Tax page (state 6% rate; 0% local – Maryland prohibits local sales tax)
- **Local Rates URL**: Not applicable – Maryland **does not allow local sales taxes**
- **Special Districts URL**: Not applicable
- **ZIP Code Mapping URL**: Not applicable
- **Data Format**: Web (state rate info only)
- **API Available**: No
- **GIS Resources**: No

## Massachusetts

### Economic Nexus Source
- **Source URL**: Massachusetts DOR – Remote Seller FAQ (effective Oct 1, 2019)
- **Update Frequency**: Static ($100k annual sales threshold)
- **Data Format**: Webpage (Mass.gov DOR guidance)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Massachusetts DOR – Sales and Use Tax page (statewide 6.25% rate)
- **Local Rates URL**: Not applicable – Massachusetts **does not have local sales tax**
- **Special Districts URL**: Not applicable
- **ZIP Code Mapping URL**: Not applicable
- **Data Format**: Web (state rate only)
- **API Available**: No
- **GIS Resources**: No

## Michigan

### Economic Nexus Source
- **Source URL**: Michigan Department of Treasury – Remote Seller Bulletin (RAB 2018-16)
- **Update Frequency**: Static (>$100k or 200 transactions, from Oct 1, 2018)
- **Data Format**: Webpage/PDF (Revenue Administrative Bulletin)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Michigan Treasury – Sales Tax info (state 6% rate; no local sales tax allowed in MI)
- **Local Rates URL**: Not applicable – Michigan **has no local sales taxes**
- **Special Districts URL**: Not applicable
- **ZIP Code Mapping URL**: Not applicable
- **Data Format**: Web (state rate only)
- **API Available**: No
- **GIS Resources**: No

## Minnesota

### Economic Nexus Source
- **Source URL**: Minnesota Dept. of Revenue – Remote Seller Fact Sheet
- **Update Frequency**: Updated Oct 1, 2019 (threshold simplified to $100k or 200 in 12 months)
- **Data Format**: Webpage (MN DOR guidance)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Minnesota DOR – Sales Tax Rate Calculator (state 6.875% base, used by calculator)
- **Local Rates URL**: Minnesota DOR – Local Sales Tax page (list of current city/county transit taxes and rates)
- **Special Districts URL**: Minnesota DOR – included in local tax list (e.g., transit improvement taxes)
- **ZIP Code Mapping URL**: Minnesota DOR – Sales Tax Rate Calculator (enter address or ZIP to get combined rate)
- **Data Format**: Web (interactive calculator and PDF list of local taxes)
- **API Available**: No public API (calculator on website only)
- **GIS Resources**: No (address lookup via DOR site)

## Mississippi

### Economic Nexus Source
- **Source URL**: Mississippi Department of Revenue – Remote Seller guidance (implementing $250k threshold from Sept 1, 2018)
- **Update Frequency**: Static (Mississippi law uses $250,000 annual sales)
- **Data Format**: Webpage (DOR guidance)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Mississippi DOR – Sales Tax page (state 7% general rate; MS does not allow local add-on sales taxes)
- **Local Rates URL**: Not applicable – Mississippi **has no local general sales taxes** (cities may levy special tourism taxes separately)
- **Special Districts URL**: Not applicable
- **ZIP Code Mapping URL**: Not applicable
- **Data Format**: Web (state rate info only; any special local taxes are separate and not part of sales tax system)
- **API Available**: No
- **GIS Resources**: No

## Missouri

### Economic Nexus Source
- **Source URL**: Missouri DOR – Wayfair Implementation FAQ (effective Jan 1, 2023, $100k threshold)
- **Update Frequency**: New as of 2023 (economic nexus law SB 153)
- **Data Format**: Webpage and statute (RSMo §144.605 defining 12-month $100k test)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Missouri DOR – Sales Tax Rate Tables (state 4.225% base noted on rate publications)
- **Local Rates URL**: Missouri DOR – GIS Sales Tax Rate Map (online map listing state, county, city, and district rates by location)
- **Special Districts URL**: Missouri DOR – included in GIS rate lookup (special taxing districts like transportation, CID, etc., appear for addresses)
- **ZIP Code Mapping URL**: Missouri DOR – Sales Tax Rate GIS Lookup (enter address or ZIP for detailed rates)
- **Data Format**: GIS web interface (downloadable jurisdiction rate tables also available as PDF via DOR)
- **API Available**: No public API (GIS tool provided on DOR site)
- **GIS Resources**: Yes – interactive map for tax rates by address on MoDOR site

## Montana

### Economic Nexus Source
- **Source URL**: Not applicable – Montana imposes **no state sales tax** (and thus no economic nexus for sales tax)
- **Update Frequency**: N/A
- **Data Format**: N/A
- **API Available**: N/A

### Sales Tax Rate Sources
- **State Rate URL**: Not applicable – Montana **has no general sales tax** (0%)
- **Local Rates URL**: Not applicable (no state sales tax; a few resort areas levy a local-option tax outside state administration)
- **Special Districts URL**: Not applicable
- **ZIP Code Mapping URL**: Not applicable
- **Data Format**: N/A
- **API Available**: N/A
- **GIS Resources**: N/A

## Nebraska

### Economic Nexus Source
- **Source URL**: Nebraska Department of Revenue – Remote Seller Guidance (effective Jan 1, 2019)
- **Update Frequency**: Static ($100k or 200 transactions)
- **Data Format**: Webpage (Nebr. DOR notice)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Nebraska DOR – Sales Tax Rate Reference (state 5.5% base rate)
- **Local Rates URL**: Nebraska DOR – Local Sales and Use Tax Rates (Nebraska Revenue publishes a list of current city local option sales tax rates and changes)
- **Special Districts URL**: Not applicable (NE local taxes are city-level only, up to 2%)
- **ZIP Code Mapping URL**: Nebraska DOR – Sales Tax Rate Finder (by city or ZIP on DOR site)
- **Data Format**: PDF (quarterly update of local rates) and web lookup
- **API Available**: No
- **GIS Resources**: No (simple list by city provided)

## Nevada

### Economic Nexus Source
- **Source URL**: Nevada Department of Taxation – Remote Seller FAQ (effective Oct 1, 2018)
- **Update Frequency**: Static ($100k or 200 transactions)
- **Data Format**: Webpage and Tax Dept press release
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Nevada Department of Taxation – Sales/Use Tax Rates (state 4.6% base + mandatory local rates summarized on Tax Dept site)
- **Local Rates URL**: Nevada Department of Taxation – Sales Tax Rate Chart (detailed breakdown by county – total rates in each county/city, including local school, road, etc., taxes)
- **Special Districts URL**: Included in NV rate chart (e.g., Live Entertainment tax areas in certain districts)
- **ZIP Code Mapping URL**: Nevada Tax – Tax Rate Lookup (address or county-based lookup available via Dept's website)
- **Data Format**: PDF rate schedule updated semiannually (and web lookup)
- **API Available**: No
- **GIS Resources**: No (rate info by county provided in tabular form)

## New Hampshire

### Economic Nexus Source
- **Source URL**: Not applicable – New Hampshire has **no statewide sales tax** (thus no economic nexus for sales tax)
- **Update Frequency**: N/A
- **Data Format**: N/A
- **API Available**: N/A

### Sales Tax Rate Sources
- **State Rate URL**: Not applicable – **no sales tax in NH** (0% rate)
- **Local Rates URL**: Not applicable
- **Special Districts URL**: Not applicable
- **ZIP Code Mapping URL**: Not applicable
- **Data Format**: N/A (tax-free state)
- **API Available**: N/A
- **GIS Resources**: N/A

## New Jersey

### Economic Nexus Source
- **Source URL**: New Jersey Division of Taxation – Remote Seller guidance (effective Nov 1, 2018)
- **Update Frequency**: Static ($100k or 200 transactions)
- **Data Format**: Webpage (NJ Taxation remote seller FAQ)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: New Jersey Division of Taxation – Sales Tax Overview (statewide 6.625% rate; NJ does not allow local general sales taxes)
- **Local Rates URL**: Not applicable – New Jersey **has no local sales tax** (only state rate, with certain UEZ program reduced rates)
- **Special Districts URL**: Not applicable
- **ZIP Code Mapping URL**: Not applicable
- **Data Format**: Web (state rate on NJ Taxation site)
- **API Available**: No
- **GIS Resources**: No

## New Mexico

### Economic Nexus Source
- **Source URL**: New Mexico Taxation & Revenue – Remote Seller info (threshold in effect as of July 1, 2019 – $100k, per HB6)
- **Update Frequency**: Static ($100k sales in prior calendar year; NM eliminated transaction count in 2019 law)
- **Data Format**: Webpage (TRD guidance and bulletin)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: New Mexico TRD – Gross Receipts Tax Rates (state 5.0% base rate)
- **Local Rates URL**: New Mexico TRD – GRT Rate Schedule by Location (comprehensive PDF of combined state+local Gross Receipts Tax rates for each city/county)
- **Special Districts URL**: Included in GRT schedule (e.g., Environmental or Transportation district increments if any)
- **ZIP Code Mapping URL**: New Mexico TRD – Tax Rate Map (online GIS map and address lookup for GRT rates)
- **Data Format**: PDF rate schedule updated **periodically** (usually January and July); interactive map lookup
- **API Available**: No official API (data via published tables)
- **GIS Resources**: Yes – NM GIS **Tax Rate Lookup** tool for addresses on TRD site

## New York

### Economic Nexus Source
- **Source URL**: New York State Department of Taxation – Remote Seller Guidance (NY Tax Law §1101(b)(8)(iv) effective June 21, 2018)
- **Update Frequency**: Static (NY threshold: >$500k and >100 sales/year, per statute)
- **Data Format**: Webpage (NYDTF remote seller FAQ)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: NY Department of Taxation – Publication 718 (state 4% base rate and combined rates by jurisdiction)
- **Local Rates URL**: NY Department of Taxation – Publication 718 (lists each county and city's total sales tax rate) and **Online Sales Tax Jurisdiction Database**
- **Special Districts URL**: NYDTF – included in Publication 718 (metropolitan commuter transportation district add-on in certain counties)
- **ZIP Code Mapping URL**: NYDTF – Sales Tax Jurisdiction Lookup (by address or ZIP+4 on NY tax website)
- **Data Format**: PDF publication updated **quarterly**; also a downloadable jurisdiction CSV via NY Open Data
- **API Available**: Yes – New York provides a **Sales Tax API** for address-based rate lookup (via the NY Geocode API)
- **GIS Resources**: Yes – jurisdiction boundaries used internally; public can use the address lookup tool for mapping rates

## North Carolina

### Economic Nexus Source
- **Source URL**: North Carolina DOR – Remote Sales FAQ (effective Nov 1, 2018; updated July 1, 2024)
- **Update Frequency**: Updated 2024 (removed 200-transaction threshold)
- **Data Format**: Webpage (NCDOR guidance)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: North Carolina DOR – Sales and Use Tax Rates (state 4.75% base and uniform 2% local)
- **Local Rates URL**: North Carolina DOR – Form 202 instructions (list of all counties' rates; most counties 2.25% total local including transit where applicable)
- **Special Districts URL**: NC DOR – noted in county rate list (e.g., Mecklenburg transit 0.5% is included in that county's 2.5% local rate)
- **ZIP Code Mapping URL**: North Carolina DOR – Local Tax Rate Lookup by Address (via NCDOR website or "Tax Lookup" tool)
- **Data Format**: PDF/Excel list of county rates; web lookup
- **API Available**: No
- **GIS Resources**: No (address lookup tool available on NCDOR site)

## North Dakota

### Economic Nexus Source
- **Source URL**: North Dakota Tax Commissioner – Remote Seller guidance (effective Oct 1, 2018; updated July 1, 2019 to remove 200 transactions)
- **Update Frequency**: Updated 2019 (now $100k sales only)
- **Data Format**: Webpage (ND Tax remote seller FAQ)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: ND Office of State Tax Comm. – Sales Tax info (state 5% base rate)
- **Local Rates URL**: ND Tax – Local Sales Tax Rates by City/County (Tax Commissioner publishes a booklet of local city/county rates and codes)
- **Special Districts URL**: Included in local rate lists (e.g., ND lists any special lodging or resort taxes separately)
- **ZIP Code Mapping URL**: ND Tax – Tax Rate Lookup (GIS system to find city/county tax by address or ZIP)
- **Data Format**: PDF list updated periodically; online lookup tool
- **API Available**: No
- **GIS Resources**: Yes – ND "Local Sales Tax Rate Locator" (interactive tool on tax.nd.gov)

## Ohio

### Economic Nexus Source
- **Source URL**: Ohio Department of Taxation – Remote Seller FAQ (effective Aug 1, 2019)
- **Update Frequency**: Static ($100k or 200 transactions)
- **Data Format**: Webpage (Ohio Tax remote seller guidance with ORC references)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Ohio Department of Taxation – Sales and Use Tax Rates (state 5.75% base rate noted; links to county rate chart)
- **Local Rates URL**: Ohio Dept. of Tax – County Sales Tax Rate Schedule (list of each county's total rate) and **"The Finder"** address lookup
- **Special Districts URL**: Not applicable (Ohio only levies at state and county level)
- **ZIP Code Mapping URL**: Ohio DOR – **The Finder** (official GIS tool to find sales tax rates by address/ZIP)
- **Data Format**: Web (HTML/PDF of county rates); interactive Finder tool
- **API Available**: No public API (The Finder must be used via web)
- **GIS Resources**: Yes – _The Finder_ provides mapping of addresses to tax rates

## Oklahoma

### Economic Nexus Source
- **Source URL**: Oklahoma Tax Commission – Remote Seller Guidance (effective July 1, 2018; updated Nov 1, 2019 and Jan 1, 2023)
- **Update Frequency**: Updated 2019 and 2023 (current law: $100k sales/year)
- **Data Format**: Webpage (OK OTC guidance and notices)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Oklahoma Tax Commission – Sales and Use Tax Rate Charts (state 4.5% base)
- **Local Rates URL**: Oklahoma Tax Commission – City/County Sales Tax Rates (monthly publication of local rates by jurisdiction code)
- **Special Districts URL**: Included in OTC rate charts (e.g., transportation districts or special assessments if any, shown under jurisdiction listings)
- **ZIP Code Mapping URL**: Oklahoma Tax Commission – GIS Rate Locator (map-based lookup by address or ZIP on OTC site)
- **Data Format**: PDF rate tables (updated monthly); GIS web lookup
- **API Available**: No
- **GIS Resources**: Yes – OTC's online GIS tool for sales tax rates

## Oregon

### Economic Nexus Source
- **Source URL**: Not applicable – Oregon has **no general sales tax**
- **Update Frequency**: N/A
- **Data Format**: N/A
- **API Available**: N/A

### Sales Tax Rate Sources
- **State Rate URL**: Not applicable – **no sales tax in Oregon**
- **Local Rates URL**: Not applicable
- **Special Districts URL**: Not applicable
- **ZIP Code Mapping URL**: Not applicable
- **Data Format**: N/A
- **API Available**: N/A
- **GIS Resources**: N/A

## Pennsylvania

### Economic Nexus Source
- **Source URL**: Pennsylvania Dept. of Revenue – Remote Seller Information (effective July 1, 2019, $100k threshold)
- **Update Frequency**: Static ($100k/year, no transaction count)
- **Data Format**: Webpage (PA DOR remote seller guidance)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Pennsylvania DOR – Sales Tax page (state 6% base rate, with notes on local add-ons)
- **Local Rates URL**: Pennsylvania DOR – Sales Tax Rate Chart (Philadelphia 8% and Allegheny 7% noted)
- **Special Districts URL**: Not applicable (only Philly and Allegheny have different rates by statute)
- **ZIP Code Mapping URL**: Pennsylvania DOR – Tax Register lookup (by locality code)
- **Data Format**: Web (rate info provided in PA Tax Compendium)
- **API Available**: No
- **GIS Resources**: No (only two local jurisdictions with fixed differences)

## Rhode Island

### Economic Nexus Source
- **Source URL**: Rhode Island Division of Taxation – Remote Seller FAQ (effective July 1, 2019)
- **Update Frequency**: Static ($100k or 200 transactions)
- **Data Format**: Webpage (RI Taxation guidance)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Rhode Island Division of Taxation – Sales & Use Tax info (statewide 7% rate)
- **Local Rates URL**: Not applicable – Rhode Island **has no local sales taxes**
- **Special Districts URL**: Not applicable
- **ZIP Code Mapping URL**: Not applicable
- **Data Format**: Web (state rate only)
- **API Available**: No
- **GIS Resources**: No

## South Carolina

### Economic Nexus Source
- **Source URL**: South Carolina DOR – Remote Seller FAQ (effective Nov 1, 2018)
- **Update Frequency**: Static ($100k annual gross revenue)
- **Data Format**: Webpage (SCDOR advisory)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: South Carolina DOR – Sales & Use Tax page (state 6% base rate)
- **Local Rates URL**: South Carolina DOR – Local Sales Tax brochure (list of county local option sales taxes, typically 1% extra per county)
- **Special Districts URL**: Included in county list (e.g., school district capital project taxes)
- **ZIP Code Mapping URL**: South Carolina DOR – Sales Tax Rate by Address lookup (via MyDORWAY portal)
- **Data Format**: PDF of local tax rates updated periodically; online lookup tool by address
- **API Available**: No
- **GIS Resources**: No dedicated GIS (address lookup through DOR portal)

## South Dakota

### Economic Nexus Source
- **Source URL**: South Dakota DOR – Remote Seller Information (effective Nov 1, 2018; updated July 1, 2023 to remove transaction threshold)
- **Update Frequency**: Updated 2023 (now $100k sales only)
- **Data Format**: Webpage (SD DOR remote seller guidance)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: South Dakota DOR – Sales Tax info (state 4.5% rate)
- **Local Rates URL**: South Dakota DOR – Municipal Tax Information Bulletin (lists each city's local sales tax rate and codes; many municipalities impose 1-2%)
- **Special Districts URL**: Included in municipal list (SD allows some tribal sales taxes and special excise taxes, listed where relevant)
- **ZIP Code Mapping URL**: South Dakota DOR – Tax Rate Lookup (address lookup on SD DOR site)
- **Data Format**: PDF list updated quarterly; online lookup tool
- **API Available**: No
- **GIS Resources**: No (address lookup available on DOR site)

## Tennessee

### Economic Nexus Source
- **Source URL**: Tennessee Department of Revenue – Notices #19-04 & #20-15 (economic nexus effective Oct 1, 2019 with $500k, lowered to $100k Oct 1, 2020)
- **Update Frequency**: Updated 2020 (threshold reduced to $100k)
- **Data Format**: PDF notices (TN DOR Tax Notice 20-15)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Tennessee DOR – Sales and Use Tax Guide (state 7% base rate detailed; food 4% etc., but base 7%)
- **Local Rates URL**: Tennessee DOR – Local Option Tax Rates (list of each county/city local sales tax rate up to 2.75%)
- **Special Districts URL**: Not applicable (TN local tax is county/city general, capped at 2.75%)
- **ZIP Code Mapping URL**: Tennessee DOR – GIS Sales Tax Rate Lookup (address lookup tool on TNTAP or DOR site)
- **Data Format**: PDF list of local rates; GIS lookup
- **API Available**: No public API (the state provides a downloadable local rate file on request)
- **GIS Resources**: Yes – Sales Tax API for GIS (Tennessee offers a GIS-based lookup for tax jurisdictions internally, accessible via their online portal)

## Texas

### Economic Nexus Source
- **Source URL**: Texas Comptroller of Public Accounts – Remote Seller Rule (effective Oct 1, 2019, $500k threshold)
- **Update Frequency**: Static ($500k in preceding 12 months)
- **Data Format**: Webpage (Comptroller remote seller guidance)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Texas Comptroller – Texas Sales and Use Tax Rates (state 6.25% base rate noted)
- **Local Rates URL**: Texas Comptroller – Local Sales Tax Rate Database (searchable by city/county/Transit Authority; 2% local cap)
- **Special Districts URL**: Texas Comptroller – included in local database (transit authority, special purpose district taxes part of the 2% local cap)
- **ZIP Code Mapping URL**: Texas Comptroller – Rate Locator (official address-based sales tax rate lookup tool)
- **Data Format**: Downloadable data (Comptroller provides a GIS dataset and a CSV of local rates updated quarterly)
- **API Available**: Yes – Texas offers a **Sales Tax Rate API** for developers via the GIS Data Hub
- **GIS Resources**: Yes – detailed GIS dataset of local taxing jurisdictions (available on Comptroller's website)

## Utah

### Economic Nexus Source
- **Source URL**: Utah State Tax Commission – Remote Seller & Marketplace Info (effective Jan 1, 2019)
- **Update Frequency**: Static ($100k or 200 transactions)
- **Data Format**: Webpage (Tax.Utah.gov guidance)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Utah Tax Commission – Sales & Use Tax Rates (state 4.85% general rate listed)
- **Local Rates URL**: Utah Tax Commission – Sales Tax Rate Charts (detailed rates by locality, including county, city, and transit taxes)
- **Special Districts URL**: Utah Tax Commission – included in rate charts (transit district rates, highway project taxes, etc.)
- **ZIP Code Mapping URL**: Utah Tax – Tax Rate Lookup (address lookup tool, with API for sales tax rates by location)
- **Data Format**: Database and charts (UTC updates an online lookup and downloadable rate files monthly)
- **API Available**: Yes – **Utah provides an API** for sales tax rate by GPS/address via the Utah Geospatial Tax Rate Lookup
- **GIS Resources**: Yes – GIS-based address lookup and boundary data for taxing jurisdictions

## Vermont

### Economic Nexus Source
- **Source URL**: Vermont Department of Taxes – Remote Seller guidance (effective July 1, 2018)
- **Update Frequency**: Static ($100k or 200 transactions)
- **Data Format**: Webpage (Vermont Tax FAQ)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Vermont Department of Taxes – Sales & Use Tax page (state 6% base rate)
- **Local Rates URL**: Vermont Tax – Local Option Tax page (list of municipalities with 1% local option sales tax)
- **Special Districts URL**: Not applicable (local option is only 1% in certain towns)
- **ZIP Code Mapping URL**: Vermont Tax – Local Option Tax Town Map (map or list of towns with local tax; not a full lookup tool)
- **Data Format**: Web (list of local option towns and rates)
- **API Available**: No
- **GIS Resources**: No (simple list of towns that have the additional 1%)

## Virginia

### Economic Nexus Source
- **Source URL**: Virginia Tax – Remote Seller Rules (effective July 1, 2019)
- **Update Frequency**: Static ($100k or 200 transactions)
- **Data Format**: Webpage (Virginia Tax remote seller FAQ)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Virginia Tax – Sales Tax Rates (state 4.3% base + 1% uniform local listed)
- **Local Rates URL**: Virginia Tax – Sales Tax Rates by Locality (includes regional additional taxes – e.g., 0.7% in Northern VA, Hampton Roads)
- **Special Districts URL**: Virginia Tax – noted on locality rate page (regional Transportation District taxes included in combined rate)
- **ZIP Code Mapping URL**: Virginia Tax – Sales Tax Rate Lookup (lookup by locality or ZIP on tax.virginia.gov)
- **Data Format**: Web (PDF lists of rates by locality, updated when legislation changes)
- **API Available**: No
- **GIS Resources**: No (rates determined by city/county code)

## Washington

### Economic Nexus Source
- **Source URL**: Washington Dept. of Revenue – Remote Seller Nexus info (effective Oct 1, 2018; threshold revised Jan 1, 2020)
- **Update Frequency**: Updated 2020 (now $100k gross receipts only)
- **Data Format**: Webpage (DOR remote seller guidance)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Washington DOR – Sales & Use Tax Rates (state 6.5% base noted)
- **Local Rates URL**: Washington DOR – Tax Rate Lookup (GIS) (official WA DOR tool to get combined state + local rates by address)
- **Special Districts URL**: Washington DOR – included via lookup (Regional Transit Authority taxes, etc., are included for addresses in those areas)
- **ZIP Code Mapping URL**: Washington DOR – GIS Tax Rate Lookup (allows search by address or ZIP, returns all taxing jurisdictions)
- **Data Format**: GIS data and downloadable rate tables (DOR provides quarterly rate tables and a GIS boundary dataset)
- **API Available**: Yes – **Washington DOR offers a Sales Tax Rate API** for developers (JSON lookup by address)
- **GIS Resources**: Yes – WA DOR provides a GIS system and downloadable shapefiles for tax boundaries (for use with their lookup service)

## West Virginia

### Economic Nexus Source
- **Source URL**: West Virginia State Tax Dept. – Remote Seller Guidance (effective Jan 1, 2019)
- **Update Frequency**: Static ($100k or 200 transactions)
- **Data Format**: Webpage (WV Tax remote seller FAQ)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: West Virginia Tax Dept. – Sales Tax info (state 6% base rate)
- **Local Rates URL**: West Virginia Tax – Municipal Sales Tax List (list of cities with 1% local sales tax authorized – e.g., Charleston, etc.)
- **Special Districts URL**: Not applicable (local sales taxes are at municipal level only, max 1%)
- **ZIP Code Mapping URL**: West Virginia Tax – Municipal Tax Lookup (table of ZIP codes overlapping municipalities with local tax)
- **Data Format**: Web/PDF list (periodically updated as cities adopt 1%)
- **API Available**: No
- **GIS Resources**: No (manual reference of city boundaries)

## Wisconsin

### Economic Nexus Source
- **Source URL**: Wisconsin Department of Revenue – Remote Seller Fact Sheet (effective Oct 1, 2018; 200-transaction rule removed 2021)
- **Update Frequency**: Updated Feb 2021 (now $100k sales only)
- **Data Format**: Webpage (WI DOR news release Tax Bulletin)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Wisconsin DOR – Sales Tax Rates (state 5% base rate noted; WI DOR website)
- **Local Rates URL**: Wisconsin DOR – County Sales Tax Report (lists 0.5% county-option taxes for counties that impose it – most counties)
- **Special Districts URL**: Not applicable (only state and county levels in WI; former stadium district tax ended)
- **ZIP Code Mapping URL**: Wisconsin DOR – Sales Tax Rate Lookup (address or county lookup on DOR site)
- **Data Format**: Web (list of counties with 0.5% tax; DOR online lookup tool)
- **API Available**: No
- **GIS Resources**: No (simple county list; address lookup available on DOR site)

## Wyoming

### Economic Nexus Source
- **Source URL**: Wyoming Dept. of Revenue – Remote Seller Guidance (effective Feb 1, 2019; updated July 1, 2024)
- **Update Frequency**: Updated 2024 (removed 200 transaction clause)
- **Data Format**: Notice (WyDOR guidance bulletin)
- **API Available**: No

### Sales Tax Rate Sources
- **State Rate URL**: Wyoming DOR – Sales Tax Rates (state 4% base rate)
- **Local Rates URL**: Wyoming DOR – Sales/Use Tax Rate Charts (lists combined state+county rates, including the default 1% county tax and any optional city/county taxes up to an additional 1%)
- **Special Districts URL**: Not applicable (WY sales tax is state + county; additional local optional taxes are county-wide or specific purpose but reflected in total county rate)
- **ZIP Code Mapping URL**: Wyoming DOR – Sales Tax Rate by Location (lookup tool or tables by city/county)
- **Data Format**: PDF rate chart updated periodically (usually when local option taxes change)
- **API Available**: No
- **GIS Resources**: No (simple county-based rates; state provides tables of city/county rates)
