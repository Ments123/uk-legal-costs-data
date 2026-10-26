# UK legal costs open data (England and Wales)

Free, citable datasets on civil litigation costs in England and Wales, published by [DMD Costs](https://www.dmdcosts.co.uk/), law costs draftsmen. Each file is built from the same data the free tools on [dmdcosts.co.uk](https://www.dmdcosts.co.uk/legal-costs-help) use, and every figure is tied to its official source.

This repository mirrors [dmdcosts.co.uk/open-data](https://www.dmdcosts.co.uk/open-data). A GitHub Action re-syncs the files from the site every month, so a fee, rate or table changed on the site appears here too.

## Datasets

| File | What it holds | Source |
|---|---|---|
| [`data/civil-court-fees-history.csv`](data/civil-court-fees-history.csv) | Every version since 22 April 2014 of the main civil court fees in Schedule 1 to the Civil Proceedings Fees Order 2008 (issue fees, applications, hearing fees, detailed assessment, default costs certificates, appeals, fixed costs determinations, Solicitors Act applications), with the amending statutory instrument and dates | [legislation.gov.uk](https://www.legislation.gov.uk/uksi/2008/1053/schedule/1) |
| [`data/guideline-hourly-rates.csv`](data/guideline-hourly-rates.csv) | Solicitors' guideline hourly rates by table (2010, 2021, 2024, 2025, 2026), band and grade, with the dates each table was in force | [GOV.UK](https://www.gov.uk/guidance/solicitors-guideline-hourly-rates) |
| [`data/bank-rate.csv`](data/bank-rate.csv) | Every change in Bank of England Bank Rate since 4 November 1999 (enhanced interest under CPR 36.17, Late Payment Act interest) | [Bank of England](https://www.bankofengland.co.uk/boeapps/database/Bank-Rate.asp) |
| [`data/special-account-rate.csv`](data/special-account-rate.csv) | The Court Funds Office special account rate since 1 February 1993 (interest on past losses in personal injury claims) | [GOV.UK](https://www.gov.uk/government/news/interest-rate-decreased-on-the-court-funds-office-special-and-basic-accounts) |
| [`data/costs-rules-timeline.csv`](data/costs-rules-timeline.csv) | When each costs rule, rate and limit applied: VAT, judgment and late payment interest, small claims limits, LASPO 2012, QOCS, costs budgeting, Part 36, electronic bills, provisional assessment, fixed recoverable costs, the whiplash reforms; one citation and source per row | legislation.gov.uk, justice.gov.uk, GOV.UK, HMRC |
| [`data/county-court-waiting-times.csv`](data/county-court-waiting-times.csv) | Median and mean weeks from claim issue to the first small claims hearing and to trial, for each County Court hearing centre, with the same quarter a year earlier | [Ministry of Justice, Civil Justice Statistics Quarterly](https://www.gov.uk/government/collections/civil-justice-statistics-quarterly) |

Each dataset is also explained on its tool page: [costs rules by date](https://www.dmdcosts.co.uk/costs-rules-by-date), [County Court waiting times](https://www.dmdcosts.co.uk/county-court-waiting-times), the [Part 36 calculator](https://www.dmdcosts.co.uk/part-36-calculator) and the [interest on damages calculator](https://www.dmdcosts.co.uk/interest-on-damages-calculator).

## Licence and how to credit

The compilations are licensed under [Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/): copy, share and adapt them for any purpose, including commercially. The figures are public sector information licensed under the [Open Government Licence v3.0](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/). Please credit:

> Source: DMD Costs, dmdcosts.co.uk/open-data. Contains public sector information licensed under the Open Government Licence v3.0.

The data shows published figures and the dates they applied. It is not legal advice, and it doesn't say which rates or rules apply to particular work.

## Corrections

Found an error? Email info@dmdcosts.co.uk with the file and row. We check it against the source and correct it on the site; this repository follows at the next sync. How the site's content is checked: [editorial standards](https://www.dmdcosts.co.uk/editorial-standards).

## About DMD Costs

[DMD Costs](https://www.dmdcosts.co.uk/) is a firm of law costs draftsmen in Greater Manchester, instructed by claimant solicitor firms across England and Wales. Free costs tools and guides: [dmdcosts.co.uk/legal-costs-help](https://www.dmdcosts.co.uk/legal-costs-help). Short costs explainers with transcripts: [YouTube @dmdcosts](https://www.youtube.com/@dmdcosts) and [dmdcosts.co.uk/costs-explainer-videos](https://www.dmdcosts.co.uk/costs-explainer-videos). Also on [LinkedIn](https://www.linkedin.com/company/dmd-costs). The same tables are also on Hugging Face: [dmdcosts/uk-legal-costs](https://huggingface.co/datasets/dmdcosts/uk-legal-costs).
