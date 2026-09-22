# Methodology

## Scope

The analysis asks whether Morrisons can service the proposed debt, how liquidity behaves under stress and which lender protections are needed. Public disclosure is not detailed enough for a reliable three-statement forecast, so the workbook uses a focused cash-flow and debt schedule.

## Public facts and assumptions

Public/historical inputs are shown in green, illustrative inputs in blue and formulas in black in the workbook. Labels and source notes govern classification; a forecast is never a public fact merely because it links to another sheet. The main anchors are FY2024/25 revenue of £15.8bn, underlying EBITDA of £835m, approximately £3.5bn of gross debt after the 2025 refinancing, a £1.0bn RCF and the publicly announced debt instruments and maturities.

Historical revenue is not fully comparable: FY23A and FY24A are revenue excluding fuel, while the FY25 trading update reports total revenue. Those figures provide scale rather than a like-for-like trend. Forecast growth, margins, cash conversion, opening cash, interest rates, GBP translation and proposed covenant levels are independent assumptions, not company guidance.

## Timing convention

FY26E is a full-year pro forma case: post-refinancing debt and cash are applied at the beginning of the modelled year. July 2026 is the analysis date, not a forecast closing date. The model does not estimate an actual mid-year closing or stub period. August 2032 is the proposed facility’s indicative maturity; the stated approximately six-year tenor is illustrative.

## Transaction funding

The debt takeout is approximately **£895.8m**:

| Instrument refinanced | Principal |
|---|---:|
| Residual 2027 GBP notes | £20.533m |
| Residual 2027 EUR notes, translated at 0.86 GBP per EUR | £125.299m |
| 2028 senior notes | £750.000m |
| **Total debt takeout** | **£895.832m** |

A £900m facility issued at 99 OID generates **£891.0m** of cash proceeds. The **£4.8m shortfall** is funded from cash. The model also assumes **£5.0m of other transaction fees**; this is an illustrative input, not a publicly disclosed amount. Starting from assumed cash of **£350.0m immediately before closing**, the £9.8m total cash use leaves **£340.2m after closing**. That post-closing amount flows into the forecast. The refinancing is broadly debt-neutral on a gross-principal basis, but not cash-neutral at close. Gross principal rises by approximately £4.2m and net debt by £14.0m (the £9m OID discount plus £5m assumed fees). The closing bridge uses a signed funding adjustment: a positive value uses cash and a negative value retains surplus proceeds. Debt summaries, rates, amortisation and sensitivity exposures link to the same inputs; the checks compare both scenarios with that stack and use the editable minimum cash.

## Opening debt and maturities

| Instrument | Opening principal | Legal maturity used | Modelled cash rate |
|---|---:|---:|---:|
| Existing term loans | £1,650m | Nov-2030 | 7.50% |
| 2031 secured notes | £930m equivalent | Jan-2031 | 7.82% weighted |
| Proposed term-out | £900m | Aug-2032 | 8.25% |
| RCF | £0m drawn / £1,000m committed | Aug-2030 | 7.50% when drawn |

The £3.48bn opening principal reconciles to Morrisons' public description of approximately £3.5bn gross debt. Exact tranche allocation remains an estimate because complete post-refinancing debt documents and the relevant period-end cash balance are not public. The 2030 facilities are subject to customary springing mechanics described in the facility-extension announcement.

## Forecast and debt mechanics

Revenue grows from the FY2024/25 reported base and EBITDA equals revenue multiplied by the scenario margin. Cash flow before debt paydown is EBITDA less debt interest, lease interest, cash tax, capital expenditure, working-capital and other cash movement, and lease principal.

Scheduled amortisation is paid first. The model then draws on the RCF as needed to target £300m minimum cash, capped by the undrawn portion of its £1.0bn commitment. Available surplus repays the RCF before the leverage-based cash sweep. If a stress case needs more than the RCF can provide, closing cash falls below £300m, the unfunded need is displayed, and the minimum-cash check fails. The sweep uses cash above the minimum after scheduled amortisation and RCF repayments, including retained opening surplus. It is capped at the remaining proposed-facility balance; this model does not sweep other loans after that facility is fully repaid. The sweep is applied to the proposed term-out: 50% at or above 3.25x pre-sweep net leverage, 25% from 2.75x up to but excluding 3.25x, and zero below 2.75x.

Debt cash interest is calculated on **opening annual balances**. This avoids circularity and is conservative when debt is repaid during the year, but it does not charge a full year's interest on RCF drawings made during that same year. Downside coverage should therefore be treated as directional; a live underwriting model would use monthly balances and interest periods.

Rate sensitivity applies only to the floating-rate existing term loans and proposed term-out. The fixed-rate 2031 secured notes are excluded from the basis-point shock. It is a static FY26 EBITDA/interest-coverage matrix, not an integrated leverage or liquidity reforecast.

RCF commitment fees on undrawn capacity are excluded because the actual rate is not independently verified. The FY2024 accounts state that such fees accrue. Illustrative fees of 50 / 100 bps on £1,000m undrawn capacity would cost £5m / £10m annually and reduce FY26 base cash flow before debt paydown from £34m to £29m / £24m before subsequent financing effects. These are sensitivity examples, not assumed contractual rates. Redemption premiums and accrued settlement interest are also excluded; the £5m input represents illustrative other transaction fees.

A separate interest-timing sensitivity, with half-year interest on each new RCF draw and subsequent borrowing feedback, produces FY30 downside RCF of £479.3m, conditional liquidity of £820.7m, minimum coverage of 1.91x and peak leverage of 4.499x. A full-year charge on each new draw is a stronger stress: £500.3m RCF, £799.7m conditional liquidity, 1.89x minimum cover and 4.511x peak leverage. These do not replace the published opening-balance case and exclude commitment fees. The 4.5x leverage guardrail has little headroom and is not a legal covenant.

## RCF and refinancing treatment

The RCF legally matures in August 2030, before the assumed FY30 year-end. FY30E liquidity therefore assumes that the RCF is extended or replaced on equivalent commitment terms. Under the downside:

- RCF drawings reach **£461.3m**.
- Conditional FY30E liquidity is **£838.7m**, consisting of £300m cash and £538.7m undrawn replacement capacity.
- Without extension or replacement, the annual model indicates **£461.3m of replacement funding** to repay the drawn RCF while retaining the £300m minimum cash balance. Spending that entire minimum cash balance would give a different, less protective shortfall measure, which is not used for the recommendation.

The base case also leaves **£1,567.5m** of term loans due in November 2030 and **£930m** of secured notes due in January 2031. The recommended terms therefore require both an RCF solution and a plan for the approximately **£2.50bn** 2030-31 maturity wall by August 2029.

The maturity chart groups **FY30E closing balances** by their contractual maturity dates. Its proposed-facility bar is the balance at FY30E, not a forecast of what will remain payable in August 2032.

## Scenarios and lender protections

The base case assumes modest nominal sales growth and gradual margin improvement. The downside assumes flat-to-declining revenue, a 4.65% EBITDA margin trough, weaker working capital and only partial capital-expenditure flexibility.

The recommendation assumes SONIA +450 bps with a 50 bps floor, 99 OID, 1% annual amortisation, the cash sweep described above, £300m minimum cash, £500m minimum total liquidity, a 5.25x first-lien springing leverage covenant when more than 40% of the RCF is drawn, restricted-payment controls and at least 80% guarantor EBITDA coverage.

The proposed lender terms are recommendations, not verified existing covenants. Total net leverage is only an analytical proxy for the proposed first-lien measure. At annual dates the >40% RCF-use trigger is reached only in downside FY30 (46.13%); a legal compliance conclusion requires facility definitions and guarantor-level information.

## Limitations

The analysis does not model monthly seasonality, a full working-capital build, covenant EBITDA add-backs, legal recovery, store-level capital expenditure, tax-group detail, hedging or non-public debt documentation. It is a portfolio exercise based on public information, not a financing recommendation.
