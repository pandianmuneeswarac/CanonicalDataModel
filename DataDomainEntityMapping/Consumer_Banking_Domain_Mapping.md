# Domain to Entity Mapping: Consumer Banking

## Business Unit Overview
Consumer Banking focuses on retail banking services for individual customers including deposit accounts, personal loans, mortgages, credit cards, and wealth management services.

---

| Serial Number | Data Domain Name | Entity Names | Mapping Rationale |
|---------------|------------------|--------------|-------------------|
| 1 | **Party** | Individual Customer, Retail Customer Profile, Customer Demographics, Customer Identification, Beneficial Owner, Joint Account Holder, Authorized Signer, Customer Household, Customer Segment, Customer Preferences, KYC Records, Customer Consent | Primary domain for all customer identity and profile information. These entities represent individuals and their relationships with the bank. |
| 2 | **Account** | Savings Account, Checking Account, Money Market Account, Certificate of Deposit (CD), Individual Retirement Account (IRA), Custodial Account, Account Balance, Account Status, Account Ownership, Dormant Account, Closed Account | Core banking accounts for consumer deposits and savings. All account-related entities managing customer funds and balances. |
| 3 | **Product** | Savings Product, Checking Product, CD Product, IRA Product, Debit Card Product, Overdraft Protection Product, Product Features, Product Pricing, Product Terms, Product Catalog, Product Eligibility, Fee Schedule | Standardized product definitions for consumer banking offerings. These entities define what products are available to retail customers. |
| 4 | **Transaction** | Deposit Transaction, Withdrawal Transaction, Transfer Transaction, ATM Transaction, POS Transaction, Online Transfer, Bill Payment, Direct Deposit, ACH Transaction, Wire Transfer, Check Transaction, Transaction History, Transaction Authorization, Transaction Settlement | All financial movements and operations on consumer accounts. Captures every monetary activity with complete audit trails. |
| 5 | **Agreement** | Account Opening Agreement, Terms and Conditions, Service Agreement, Fee Agreement, Electronic Banking Agreement, Overdraft Agreement, Privacy Notice, Account Disclosures, Truth in Savings Disclosure, Regulation E Agreement | Legal contracts governing consumer banking relationships. All agreements customers sign when opening accounts or using services. |
| 6 | **Collateral** | N/A - Limited application in basic consumer banking | Consumer deposit accounts typically don't require collateral. This domain is more relevant for secured lending products. |
| 7 | **Risk** | Customer Risk Rating, Fraud Alert, Suspicious Activity, Transaction Monitoring Alert, AML Risk Score, Credit Bureau Score, Overdraft Risk, Account Risk Profile, Fraud Detection Case | Risk assessment and monitoring for consumer accounts. Includes fraud detection, AML compliance, and customer risk profiles. |
| 8 | **Financial Performance** | Account Balance Summary, Interest Income, Fee Revenue, Cost to Serve, Customer Profitability, Product Performance Metrics, Branch Performance, Retention Rate, Cross-sell Ratio | Aggregated financial metrics for consumer banking portfolio. Performance indicators and profitability analysis. |
| 9 | **Regulatory Compliance** | CIP Documentation, BSA/AML Reports, CTR (Currency Transaction Report), SAR (Suspicious Activity Report), OFAC Screening, Regulation D Compliance, Regulation E Claims, FDIC Insurance Records, Privacy Compliance Records, Escheatment Records | Regulatory reporting and compliance documentation. All records required to meet consumer banking regulations. |
| 10 | **Channel** | Branch Transaction, ATM Transaction, Online Banking Session, Mobile Banking Session, Call Center Interaction, IVR Session, Branch Visit, Digital Enrollment, Channel Preference, Self-Service Transaction | Customer interaction channels and touchpoints. All methods through which consumers access banking services. |
| 11 | **Pricing** | Interest Rate, APY (Annual Percentage Yield), Service Fee, ATM Fee, Overdraft Fee, Wire Transfer Fee, Stop Payment Fee, Monthly Maintenance Fee, Minimum Balance Fee, Pricing Tier, Rate Sheet | Rates and fees applied to consumer products and services. All pricing structures for retail banking offerings. |
| 12 | **Reference Data** | Account Type Code, Transaction Type Code, Product Code, Status Code, Currency Code, Country Code, State Code, Channel Code, Fee Type Code, Document Type Code | Standardized codes and classifications used across consumer banking. Ensures data consistency and interoperability. |
| 13 | **Location** | Customer Address, Branch Location, ATM Location, Mailing Address, Service Address, Billing Address, Geographic Region, Market Area, Branch Service Area | Physical and geographical information for customers and service points. Address management and location-based services. |
| 14 | **Employee** | Personal Banker, Branch Manager, Customer Service Representative, Relationship Manager, Teller, Branch Staff, Employee Assignment, Service Team | Bank employees serving consumer banking customers. Staff assignments and customer relationship ownership. |
| 15 | **Market Data** | Interest Rate Benchmark, Competitor Rates, Market Index, Economic Indicator, Regional Market Data | External market information used for pricing and product management. Reference data for rate setting and competitive analysis. |

---

## Key Entity Counts by Domain

| Data Domain | Number of Entities | Percentage of Total |
|-------------|-------------------|---------------------|
| Party | 12 | 18.5% |
| Account | 11 | 16.9% |
| Transaction | 14 | 21.5% |
| Product | 11 | 16.9% |
| Agreement | 9 | 13.8% |
| Risk | 9 | 13.8% |
| Channel | 10 | 15.4% |
| Regulatory Compliance | 10 | 15.4% |
| Pricing | 10 | 15.4% |
| Reference Data | 10 | 15.4% |
| Location | 9 | 13.8% |
| Employee | 8 | 12.3% |
| Financial Performance | 9 | 13.8% |
| Market Data | 5 | 7.7% |
| Collateral | 0 | 0.0% |

---

## Mapping Notes

### Primary vs. Secondary Domain Usage
- **Primary Domain**: The domain that owns the entity lifecycle and is the authoritative source
- **Secondary/Reference Usage**: Domains that reference or use the entity but don't own it

### Coverage Analysis
- **Total Entities Mapped**: 127 distinct business entities
- **Domains with Entities**: 14 out of 15 (93.3%)
- **Domain Coverage**: Comprehensive coverage across all consumer banking operations

### Consolidation Opportunities
- Customer data consolidation across channels: ~25% reduction potential
- Transaction data harmonization: ~15% consolidation through standardization
- Product catalog rationalization: ~20% reduction through product simplification

---

*Document Version: 1.0*  
*Business Unit: Consumer Banking*  
*Last Updated: 2025*