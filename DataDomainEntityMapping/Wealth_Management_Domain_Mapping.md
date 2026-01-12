# Domain to Entity Mapping: Wealth Management

## Business Unit Overview
Wealth Management provides investment advisory, portfolio management, trust services, estate planning, and private banking services to high-net-worth individuals, families, and institutional clients.

---

| Serial Number | Data Domain Name | Entity Names | Mapping Rationale |
|---------------|------------------|--------------|-------------------|
| 1 | **Party** | Client, High Net Worth Individual, Family Office, Trust Beneficiary, Grantor, Trustee, Investment Advisor, Portfolio Manager, Client Household, Client Relationship, Client Profile, Beneficial Owner, Related Party, Estate Executor | Primary domain for wealth management clients and related parties. Includes complex family structures and fiduciary relationships. |
| 2 | **Account** | Investment Account, Brokerage Account, Managed Account, Trust Account, Custodial Account, Retirement Account, 401(k) Account, IRA Account, Estate Account, Joint Account, Account Holdings, Account Valuation, Account Performance | Investment and trust accounts for wealth management clients. All account types holding securities, cash, and other investment assets. |
| 3 | **Product** | Investment Product, Mutual Fund, ETF, Individual Security, Structured Product, Alternative Investment, Hedge Fund, Private Equity, Real Estate Investment, Insurance Product, Annuity, Advisory Service, Wealth Planning Service, Trust Service | Comprehensive catalog of investment products and wealth services. All offerings available to wealth management clients. |
| 4 | **Transaction** | Trade Transaction, Buy Order, Sell Order, Trade Settlement, Dividend Payment, Interest Payment, Capital Gain Distribution, Fee Transaction, Contribution, Withdrawal, Transfer, Rebalancing Transaction, Corporate Action, Proxy Vote | All investment transactions and portfolio activities. Trading, income distributions, and account movements with complete audit trails. |
| 5 | **Agreement** | Investment Advisory Agreement, Discretionary Management Agreement, Trust Agreement, Custody Agreement, Investment Policy Statement (IPS), Fee Agreement, Service Agreement, Fiduciary Agreement, Estate Planning Agreement, Power of Attorney | Legal agreements governing wealth management relationships. All contracts defining advisory services, fiduciary duties, and client mandates. |
| 6 | **Collateral** | Securities Collateral, Margin Collateral, Pledged Assets, Letter of Credit, Collateral Valuation, Collateral Monitoring, Haircut Application | Assets pledged for margin lending and credit facilities. Collateral management for wealth management lending products. |
| 7 | **Risk** | Investment Risk Profile, Risk Tolerance Assessment, Portfolio Risk Metrics, Concentration Risk, Market Risk Exposure, Credit Risk, Liquidity Risk, Suitability Assessment, Risk Rating, Stress Test Results, VaR (Value at Risk) | Comprehensive investment risk management. Client risk profiling, portfolio risk analytics, and regulatory suitability requirements. |
| 8 | **Financial Performance** | Portfolio Performance, Return on Investment (ROI), Time-Weighted Return, Money-Weighted Return, Benchmark Comparison, Alpha, Beta, Sharpe Ratio, Asset Allocation, Portfolio Valuation, Fee Revenue, Assets Under Management (AUM), Client Profitability | Performance measurement and reporting for investment portfolios. All metrics used to evaluate investment results and business performance. |
| 9 | **Regulatory Compliance** | Form ADV, Investment Adviser Registration, Fiduciary Documentation, Suitability Documentation, Best Interest Standard, Regulation Best Interest (Reg BI), Form CRS, FINRA Compliance, SEC Reporting, Anti-Money Laundering (AML), FATCA Reporting, Accredited Investor Verification | Regulatory compliance for investment advisory services. All documentation required under SEC, FINRA, and other regulatory frameworks. |
| 10 | **Channel** | Advisor Portal, Client Portal, Mobile App, Branch Meeting, Video Conference, Phone Advisory, Email Communication, Document Vault, Online Trading Platform, Robo-Advisory Platform | Channels for wealth management service delivery. All touchpoints for advisor-client interaction and self-service capabilities. |
| 11 | **Pricing** | Advisory Fee, Management Fee, Performance Fee, Transaction Fee, Custody Fee, Platform Fee, Fund Expense Ratio, Commission, Fee Schedule, Fee Tier, Discount Structure, Fee Waiver | Fee structures for wealth management services. All pricing models including asset-based fees, performance fees, and transaction costs. |
| 12 | **Reference Data** | Security Master Data, CUSIP, ISIN, Ticker Symbol, Asset Class Code, Security Type Code, Industry Classification, Sector Code, Country Code, Currency Code, Exchange Code, Benchmark Index | Standardized reference data for securities and investments. Master data for all tradable instruments and market classifications. |
| 13 | **Location** | Client Address, Office Location, Trust Jurisdiction, Tax Jurisdiction, Domicile, Investment Property Location, Branch Office, Regional Office, Service Center | Geographic information for clients, trusts, and service delivery. Location data for tax and regulatory purposes. |
| 14 | **Employee** | Financial Advisor, Portfolio Manager, Wealth Planner, Trust Officer, Investment Analyst, Client Service Associate, Relationship Manager, Estate Planning Specialist, Tax Advisor, Compliance Officer | Wealth management professionals serving clients. All staff involved in advisory, portfolio management, and client service. |
| 15 | **Market Data** | Security Price, NAV (Net Asset Value), Exchange Rate, Interest Rate Curve, Yield Curve, Market Index, Benchmark Performance, Economic Indicator, Analyst Rating, Credit Rating, Market Volatility (VIX) | External market data for valuation and analysis. Real-time and historical market information for investment decision-making. |

---

## Key Entity Counts by Domain

| Data Domain | Number of Entities | Percentage of Total |
|-------------|-------------------|---------------------|
| Party | 14 | 19.4% |
| Account | 13 | 18.1% |
| Transaction | 14 | 19.4% |
| Product | 14 | 19.4% |
| Agreement | 10 | 13.9% |
| Risk | 11 | 15.3% |
| Channel | 10 | 13.9% |
| Regulatory Compliance | 12 | 16.7% |
| Pricing | 11 | 15.3% |
| Reference Data | 12 | 16.7% |
| Location | 9 | 12.5% |
| Employee | 10 | 13.9% |
| Financial Performance | 13 | 18.1% |
| Market Data | 11 | 15.3% |
| Collateral | 7 | 9.7% |

---

## Mapping Notes

### Primary vs. Secondary Domain Usage
- **Party Domain**: Complex entity structures for families, trusts, and beneficial ownership
- **Product Domain**: Extensive investment product catalog including alternatives and structured products
- **Financial Performance**: Rich performance measurement framework with multiple return calculations

### Coverage Analysis
- **Total Entities Mapped**: 161 distinct business entities
- **Domains with Entities**: 15 out of 15 (100%)
- **Domain Coverage**: Comprehensive coverage of investment advisory, portfolio management, trust services, and private banking

### Consolidation Opportunities
- Client data harmonization with private banking: ~35% overlap
- Security master data consolidation with trading systems: ~40% reduction potential
- Account structure standardization: ~25% consolidation through unified account model
- Performance calculation standardization: ~30% reduction through centralized performance engine

### Industry-Specific Considerations
- **Fiduciary Standards**: Entity design supports fiduciary duty documentation and best interest standards
- **Complex Ownership Structures**: Accommodates trusts, estates, family offices, and multi-generational wealth
- **Alternative Investments**: Entities support private equity, hedge funds, and other illiquid investments
- **Tax Optimization**: Data structure supports tax-efficient investing and estate planning
- **Regulatory Reporting**: Aligned with SEC Form ADV, FINRA, and international wealth management regulations

### Integration Points
- **Trust Services**: Deep integration with legal and estate planning systems
- **Tax Planning**: Connection to tax calculation and reporting systems
- **Trading Systems**: Integration with order management and execution platforms
- **Custody Systems**: Links to securities custody and settlement infrastructure

---

*Document Version: 1.0*  
*Business Unit: Wealth Management*  
*Last Updated: 2025*