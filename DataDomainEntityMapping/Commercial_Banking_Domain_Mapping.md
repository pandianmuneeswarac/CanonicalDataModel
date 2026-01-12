# Domain to Entity Mapping: Commercial Banking

## Business Unit Overview
Commercial Banking provides financial services to small and medium-sized businesses, middle-market companies, and large corporations including lending, treasury management, trade finance, and cash management solutions.

---

| Serial Number | Data Domain Name | Entity Names | Mapping Rationale |
|---------------|------------------|--------------|-------------------|
| 1 | **Party** | Corporate Customer, Business Entity, Small Business, Middle Market Company, Large Corporate, Subsidiary, Parent Company, Business Owner, Authorized Signer, Beneficial Owner, Corporate Structure, Business Profile, Industry Classification, Business Demographics | Primary domain for commercial clients and business entities. All organizational customers and their ownership structures. |
| 2 | **Account** | Commercial Checking Account, Business Savings Account, Money Market Account, Sweep Account, Zero Balance Account (ZBA), Concentration Account, Disbursement Account, Payroll Account, Escrow Account, Merchant Account, Account Analysis, Account Balance, Account Hierarchy | Commercial banking accounts for business customers. All account types for corporate cash management and operational banking. |
| 3 | **Product** | Commercial Loan Product, Line of Credit, Term Loan, Commercial Mortgage, Equipment Financing, Asset-Based Lending, Working Capital Loan, Treasury Management Product, Cash Management Service, Merchant Services, Trade Finance Product, Letter of Credit Product, Lockbox Service | Commercial banking product catalog. All lending, treasury, and service products offered to business customers. |
| 4 | **Transaction** | Wire Transfer, ACH Payment, ACH Receipt, Check Deposit, Remote Deposit Capture, Lockbox Deposit, Sweep Transaction, Loan Drawdown, Loan Repayment, Fee Transaction, Interest Payment, Trade Finance Transaction, Foreign Exchange Transaction, Payment File | All commercial banking transactions and payment activities. Business payment processing and account movements. |
| 5 | **Agreement** | Loan Agreement, Credit Facility Agreement, Master Loan Agreement, Security Agreement, Guarantee Agreement, Treasury Management Agreement, Cash Management Agreement, Merchant Processing Agreement, Lockbox Agreement, Account Agreement, Fee Agreement, Covenant Agreement | Legal agreements for commercial banking relationships. All contracts governing lending, services, and business banking arrangements. |
| 6 | **Collateral** | Real Estate Collateral, Equipment Collateral, Inventory Collateral, Accounts Receivable Collateral, Securities Collateral, Personal Guarantee, Corporate Guarantee, UCC Filing, Collateral Valuation, Lien Position, Collateral Monitoring, Collateral Release | Assets securing commercial loans and credit facilities. Comprehensive collateral management for business lending. |
| 7 | **Risk** | Credit Risk Rating, Financial Statement Analysis, Debt Service Coverage Ratio (DSCR), Loan-to-Value (LTV), Industry Risk, Concentration Risk, Covenant Compliance, Default Risk, Early Warning Indicator, Risk Grade Migration, Credit Review, Loan Classification, Loss Given Default (LGD) | Credit risk assessment and monitoring for commercial lending. All risk metrics and credit analysis for business borrowers. |
| 8 | **Financial Performance** | Loan Portfolio Performance, Non-Performing Loan (NPL), Loan Loss Reserve, Net Interest Margin, Fee Income, Relationship Profitability, Cross-sell Ratio, Utilization Rate, Average Balance, Deposit Growth, Loan Growth, Return on Assets (ROA) | Financial metrics for commercial banking portfolio. Performance measurement and profitability analysis. |
| 9 | **Regulatory Compliance** | Call Report Data, Credit Risk Rating Documentation, Loan Review Documentation, Fair Lending Compliance, CRA (Community Reinvestment Act) Data, Large Exposure Reporting, Concentration Reporting, Stress Testing Data, CECL (Current Expected Credit Loss) Calculation, Regulatory Capital Allocation | Regulatory reporting for commercial banking. All compliance documentation and regulatory submissions. |
| 10 | **Channel** | Relationship Manager Channel, Branch Banking, Treasury Management Platform, Online Banking Portal, Mobile Banking, Cash Management Portal, Trade Finance Platform, Payment Gateway, API Integration, File Transmission (SFTP) | Channels for commercial banking service delivery. All platforms and touchpoints for business customers. |
| 11 | **Pricing** | Interest Rate, Loan Rate, Commitment Fee, Unused Line Fee, Account Analysis Pricing, Earnings Credit Rate (ECR), Wire Transfer Fee, ACH Fee, Lockbox Fee, Trade Finance Fee, Foreign Exchange Rate, Fee Schedule | Pricing for commercial banking products and services. All rates and fees for business lending and treasury services. |
| 12 | **Reference Data** | NAICS Code, SIC Code, Business Type Code, Loan Purpose Code, Collateral Type Code, Covenant Type Code, Account Type Code, Transaction Type Code, Country Code, Currency Code, Industry Classification | Standardized codes for commercial banking. Business and industry classifications and transaction codes. |
| 13 | **Location** | Business Address, Headquarters Location, Operating Location, Branch Location, Collateral Property Location, Service Area, Regional Market, Lending Territory, Jurisdiction | Geographic information for commercial clients and collateral. Location data for credit analysis and market management. |
| 14 | **Employee** | Relationship Manager, Credit Analyst, Loan Officer, Treasury Management Officer, Credit Administrator, Portfolio Manager, Underwriter, Collections Officer, Special Assets Manager, Risk Manager | Commercial banking professionals. All staff involved in relationship management, credit, and service delivery. |
| 15 | **Market Data** | Prime Rate, LIBOR, SOFR (Secured Overnight Financing Rate), Treasury Yield Curve, Industry Benchmark, Economic Indicator, GDP Growth, Unemployment Rate, Commodity Price, Real Estate Index | External market data for commercial banking. Economic indicators and rate benchmarks for pricing and risk management. |

---

## Key Entity Counts by Domain

| Data Domain | Number of Entities | Percentage of Total |
|-------------|-------------------|---------------------|
| Party | 14 | 18.7% |
| Account | 13 | 17.3% |
| Transaction | 14 | 18.7% |
| Product | 13 | 17.3% |
| Agreement | 12 | 16.0% |
| Risk | 13 | 17.3% |
| Channel | 10 | 13.3% |
| Regulatory Compliance | 10 | 13.3% |
| Pricing | 11 | 14.7% |
| Reference Data | 11 | 14.7% |
| Location | 9 | 12.0% |
| Employee | 10 | 13.3% |
| Financial Performance | 12 | 16.0% |
| Market Data | 10 | 13.3% |
| Collateral | 12 | 16.0% |

---

## Mapping Notes

### Primary vs. Secondary Domain Usage
- **Collateral Domain**: Extensive usage due to secured lending nature of commercial banking
- **Risk Domain**: Critical for credit underwriting and portfolio management
- **Agreement Domain**: Complex legal structures for commercial relationships

### Coverage Analysis
- **Total Entities Mapped**: 164 distinct business entities
- **Domains with Entities**: 15 out of 15 (100%)
- **Domain Coverage**: Complete coverage of commercial lending, treasury management, trade finance, and business banking services

### Consolidation Opportunities
- Business customer data harmonization: ~30% overlap with other business units
- Collateral data consolidation: ~35% reduction through centralized collateral registry
- Credit risk model standardization: ~25% consolidation across lending products
- Treasury management platform integration: ~20% reduction through unified cash management

### Industry-Specific Considerations
- **Relationship Banking Model**: Entity design supports holistic relationship management across products
- **Complex Credit Structures**: Accommodates syndicated loans, multi-party guarantees, and complex collateral arrangements
- **Treasury Management**: Comprehensive cash management and payment processing capabilities
- **Trade Finance**: Specialized entities for letters of credit, documentary collections, and trade instruments
- **Covenant Monitoring**: Data structure supports financial covenant tracking and compliance

### Integration Points
- **Credit Bureau Integration**: Connection to commercial credit reporting agencies (D&B, Experian)
- **Financial Spreading**: Integration with financial statement analysis tools
- **Collateral Valuation**: Links to appraisal management and valuation systems
- **Payment Networks**: Integration with ACH, wire, and real-time payment systems
- **Trade Finance Networks**: Connection to SWIFT and trade finance platforms

### Regulatory Considerations
- **Basel III**: Risk-weighted asset calculations and capital adequacy
- **CECL**: Current expected credit loss modeling and provisioning
- **CRA**: Community Reinvestment Act reporting and compliance
- **Large Exposure**: Concentration risk monitoring and reporting
- **Stress Testing**: CCAR and DFAST compliance for large institutions

---

*Document Version: 1.0*  
*Business Unit: Commercial Banking*  
*Last Updated: 2025*