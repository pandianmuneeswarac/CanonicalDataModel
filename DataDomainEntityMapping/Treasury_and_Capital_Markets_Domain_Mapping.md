# Domain to Entity Mapping: Treasury and Capital Markets

## Business Unit Overview
Treasury and Capital Markets manages the bank's liquidity, funding, investment portfolio, trading operations, derivatives, and capital markets activities including fixed income, foreign exchange, and structured products.

---

| Serial Number | Data Domain Name | Entity Names | Mapping Rationale |
|---------------|------------------|--------------|-------------------|
| 1 | **Party** | Counterparty, Institutional Investor, Corporate Client, Financial Institution, Central Bank, Clearing House, Broker-Dealer, Prime Broker, Issuer, Investor, Trading Counterparty, Settlement Agent, Custodian | Primary domain for capital markets counterparties and institutional clients. All entities involved in trading and capital markets transactions. |
| 2 | **Account** | Trading Account, Nostro Account, Vostro Account, Settlement Account, Margin Account, Collateral Account, Investment Portfolio Account, Treasury Account, Liquidity Reserve Account, Central Bank Account, Clearing Account | Specialized accounts for treasury and trading operations. All accounts used for market activities and liquidity management. |
| 3 | **Product** | Fixed Income Security, Government Bond, Corporate Bond, Municipal Bond, Mortgage-Backed Security (MBS), Asset-Backed Security (ABS), Derivative Product, Interest Rate Swap, Credit Default Swap (CDS), Foreign Exchange Forward, Currency Option, Structured Product, Repo Agreement, Money Market Instrument | Comprehensive catalog of capital markets instruments. All tradable securities, derivatives, and structured products. |
| 4 | **Transaction** | Trade Execution, Buy Trade, Sell Trade, Trade Settlement, Trade Confirmation, Foreign Exchange Trade, Swap Transaction, Repo Transaction, Reverse Repo, Derivative Trade, Option Exercise, Coupon Payment, Principal Payment, Margin Call, Collateral Movement | All trading and settlement transactions. Complete lifecycle of capital markets trades from execution to settlement. |
| 5 | **Agreement** | ISDA Master Agreement, Credit Support Annex (CSA), Global Master Repurchase Agreement (GMRA), Prime Brokerage Agreement, Clearing Agreement, Custody Agreement, Netting Agreement, Collateral Agreement, Trading Authorization, Investment Management Agreement | Legal agreements governing capital markets activities. All master agreements and trading documentation. |
| 6 | **Collateral** | Cash Collateral, Securities Collateral, Initial Margin, Variation Margin, Independent Amount, Collateral Call, Collateral Substitution, Haircut, Collateral Valuation, Collateral Optimization, Tri-party Collateral | Collateral management for derivatives and securities financing. Comprehensive margin and collateral operations. |
| 7 | **Risk** | Market Risk, Interest Rate Risk, Foreign Exchange Risk, Credit Risk, Counterparty Credit Risk, Settlement Risk, Liquidity Risk, Value at Risk (VaR), Stress Testing, Scenario Analysis, Greeks (Delta, Gamma, Vega), Duration, Convexity, Credit Valuation Adjustment (CVA) | Comprehensive market and counterparty risk management. All risk metrics for trading and treasury operations. |
| 8 | **Financial Performance** | Trading Revenue, Net Interest Income, Mark-to-Market P&L, Realized Gain/Loss, Unrealized Gain/Loss, Trading Book Performance, Investment Portfolio Yield, Funding Cost, Liquidity Coverage Ratio (LCR), Net Stable Funding Ratio (NSFR), Return on Risk-Weighted Assets (RoRWA) | Financial performance metrics for treasury and trading. All P&L and balance sheet metrics for capital markets. |
| 9 | **Regulatory Compliance** | Dodd-Frank Reporting, MiFID II Reporting, EMIR Reporting, Trade Repository Reporting, Volcker Rule Compliance, Basel III Capital Requirements, Liquidity Coverage Ratio (LCR), Net Stable Funding Ratio (NSFR), Large Exposure Reporting, Stress Testing, FRTB (Fundamental Review of Trading Book) | Regulatory compliance for capital markets. All reporting requirements for trading, derivatives, and market activities. |
| 10 | **Channel** | Trading Platform, Electronic Trading System, Bloomberg Terminal, Reuters Terminal, FIX Protocol, Voice Trading, Broker Channel, Electronic Communication Network (ECN), Dark Pool, Exchange Platform, OTC Platform | Trading channels and execution platforms. All venues and systems for market access and trade execution. |
| 11 | **Pricing** | Market Price, Bid Price, Ask Price, Mid Price, Yield, Spread, Discount Rate, Forward Rate, Swap Rate, Option Premium, Implied Volatility, Credit Spread, Liquidity Premium, Funding Spread | Pricing for capital markets instruments. All market rates, prices, and valuation inputs. |
| 12 | **Reference Data** | ISIN, CUSIP, SEDOL, Bloomberg Ticker, Reuters RIC, LEI (Legal Entity Identifier), UTI (Unique Transaction Identifier), UPI (Unique Product Identifier), MIC (Market Identifier Code), Currency Pair, Maturity Date, Issue Date | Standardized identifiers for securities and counterparties. Master data for capital markets instruments and entities. |
| 13 | **Location** | Trading Desk Location, Exchange Location, Clearing House Location, Counterparty Jurisdiction, Issuer Domicile, Tax Jurisdiction, Regulatory Jurisdiction, Settlement Location, Time Zone | Geographic and jurisdictional information for trading and settlement. Location data for regulatory and operational purposes. |
| 14 | **Employee** | Trader, Sales Trader, Structurer, Quantitative Analyst, Risk Manager, Treasury Manager, Portfolio Manager, Market Risk Analyst, Credit Risk Analyst, Middle Office Analyst, Settlement Officer, Compliance Officer | Capital markets professionals. All staff involved in trading, structuring, risk management, and operations. |
| 15 | **Market Data** | Real-time Price, Historical Price, Yield Curve, Volatility Surface, Credit Spread Curve, FX Rate, Interest Rate, Index Level, Economic Release, Central Bank Rate, Market Liquidity, Trading Volume, Open Interest | Real-time and historical market data. All external data feeds for pricing, risk management, and trading. |

---

## Key Entity Counts by Domain

| Data Domain | Number of Entities | Percentage of Total |
|-------------|-------------------|---------------------|
| Party | 13 | 17.8% |
| Account | 11 | 15.1% |
| Transaction | 15 | 20.5% |
| Product | 14 | 19.2% |
| Agreement | 10 | 13.7% |
| Risk | 14 | 19.2% |
| Channel | 11 | 15.1% |
| Regulatory Compliance | 11 | 15.1% |
| Pricing | 14 | 19.2% |
| Reference Data | 12 | 16.4% |
| Location | 9 | 12.3% |
| Employee | 12 | 16.4% |
| Financial Performance | 11 | 15.1% |
| Market Data | 13 | 17.8% |
| Collateral | 11 | 15.1% |

---

## Mapping Notes

### Primary vs. Secondary Domain Usage
- **Risk Domain**: Extensive market risk and counterparty risk entities
- **Product Domain**: Complex derivatives and structured products
- **Market Data Domain**: Critical dependency on real-time market information

### Coverage Analysis
- **Total Entities Mapped**: 171 distinct business entities
- **Domains with Entities**: 15 out of 15 (100%)
- **Domain Coverage**: Complete coverage of trading, treasury, derivatives, securities financing, and capital markets operations

### Consolidation Opportunities
- Counterparty data harmonization: ~40% overlap with commercial banking
- Security master data consolidation: ~45% reduction through enterprise security master
- Market data vendor consolidation: ~30% reduction through centralized market data management
- Risk calculation engine standardization: ~35% consolidation through unified risk platform

### Industry-Specific Considerations
- **Real-time Processing**: Entity design supports high-frequency trading and real-time risk management
- **Complex Derivatives**: Accommodates exotic options, structured products, and bespoke derivatives
- **Multi-currency Operations**: Comprehensive foreign exchange and cross-currency capabilities
- **Collateral Optimization**: Advanced collateral management for margin efficiency
- **Regulatory Reporting**: Aligned with Dodd-Frank, EMIR, MiFID II, and Basel III requirements

### Integration Points
- **Trading Systems**: Integration with front-office trading platforms and order management systems
- **Market Data Vendors**: Connections to Bloomberg, Reuters, and other market data providers
- **Clearing Houses**: Integration with LCH, CME, ICE, and other central counterparties
- **Payment Systems**: Links to SWIFT, CLS, and real-time gross settlement systems
- **Risk Systems**: Integration with VaR engines, stress testing, and risk analytics platforms

### Regulatory Considerations
- **Dodd-Frank**: Swap data reporting and clearing requirements
- **EMIR**: European derivatives regulation and trade repository reporting
- **MiFID II**: Transaction reporting and best execution requirements
- **Basel III**: Market risk capital requirements and FRTB implementation
- **Volcker Rule**: Proprietary trading restrictions and compliance monitoring
- **BCBS 239**: Risk data aggregation and reporting principles

---

*Document Version: 1.0*  
*Business Unit: Treasury and Capital Markets*  
*Last Updated: 2025*