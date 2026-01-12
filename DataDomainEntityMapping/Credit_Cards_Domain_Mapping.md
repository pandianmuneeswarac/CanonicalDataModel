# Domain to Entity Mapping: Credit Cards

## Business Unit Overview
Credit Cards business unit manages credit card products, cardholder accounts, transaction processing, rewards programs, and credit risk management for consumer and commercial card portfolios.

---

| Serial Number | Data Domain Name | Entity Names | Mapping Rationale |
|---------------|------------------|--------------|-------------------|
| 1 | **Party** | Cardholder, Primary Cardholder, Authorized User, Supplementary Cardholder, Cardholder Profile, Cardholder Demographics, Card Applicant, Guarantor, Cardholder Contact Information, Cardholder Employment, Cardholder Household | Primary domain for cardholder identity and profile management. All entities representing individuals who hold or apply for credit cards. |
| 2 | **Account** | Credit Card Account, Card Account Balance, Available Credit, Credit Limit, Outstanding Balance, Minimum Payment Due, Statement Balance, Payment History, Account Status, Account Lifecycle, Revolving Credit Account, Charge Card Account | Core credit card accounts and balances. All account-level information for credit card products including limits and payment obligations. |
| 3 | **Product** | Credit Card Product, Rewards Card, Cash Back Card, Travel Card, Secured Card, Business Card, Student Card, Premium Card, Product Benefits, Annual Fee Structure, Interest Rate Structure, Rewards Program, Product Terms | Credit card product catalog and definitions. All card products offered with their features, benefits, and pricing structures. |
| 4 | **Transaction** | Purchase Transaction, Cash Advance, Balance Transfer, Payment Transaction, Refund Transaction, Chargeback, Authorization, Settlement, Dispute Transaction, Recurring Payment, Contactless Payment, E-commerce Transaction, POS Transaction, ATM Cash Advance, Foreign Transaction | All credit card transaction types and payment activities. Captures authorizations, purchases, payments, and adjustments with complete details. |
| 5 | **Agreement** | Cardholder Agreement, Terms and Conditions, Credit Card Application, Credit Agreement, Rewards Program Terms, Privacy Policy, Electronic Communication Agreement, Arbitration Agreement, Credit Limit Agreement, Balance Transfer Agreement | Legal agreements governing credit card relationships. All contracts and disclosures cardholders accept when applying for or using cards. |
| 6 | **Collateral** | Security Deposit (Secured Cards), Collateral Account, Pledged Assets | Limited collateral usage primarily for secured credit card products where customers provide security deposits. |
| 7 | **Risk** | Credit Score, Credit Bureau Report, Credit Risk Rating, Fraud Score, Transaction Fraud Alert, Account Fraud Case, Credit Limit Review, Delinquency Status, Charge-off Risk, Collections Case, Credit Utilization, Payment Behavior Score, Risk-Based Pricing | Comprehensive credit and fraud risk management. All risk assessment, monitoring, and mitigation activities for credit card portfolios. |
| 8 | **Financial Performance** | Portfolio Performance, Charge-off Rate, Delinquency Rate, Net Interest Income, Interchange Revenue, Fee Revenue, Loss Provision, Portfolio Yield, Customer Lifetime Value, Acquisition Cost, Retention Rate, Activation Rate | Financial metrics and performance indicators for credit card business. Profitability analysis and portfolio health monitoring. |
| 9 | **Regulatory Compliance** | TILA Disclosure, Schumer Box, Credit CARD Act Compliance, Ability-to-Pay Documentation, Regulation Z Compliance, Fair Credit Reporting Act Records, FCRA Adverse Action Notice, ECOA Compliance, UDAAP Monitoring, Data Breach Notification | Regulatory compliance for consumer credit. All documentation and reporting required under credit card regulations. |
| 10 | **Channel** | Card Application Channel, Online Account Access, Mobile App Transaction, Call Center Interaction, Branch Application, Digital Wallet Integration, Merchant Terminal, ATM Channel, Mail Channel, Partner Channel | Channels through which cardholders apply for cards, make transactions, and manage accounts. All customer touchpoints. |
| 11 | **Pricing** | APR (Annual Percentage Rate), Purchase APR, Balance Transfer APR, Cash Advance APR, Penalty APR, Annual Fee, Late Payment Fee, Over-Limit Fee, Foreign Transaction Fee, Balance Transfer Fee, Cash Advance Fee, Rewards Redemption Value | Interest rates and fees for credit card products. All pricing components including promotional rates and penalty pricing. |
| 12 | **Reference Data** | Card Type Code, Transaction Type Code, Merchant Category Code (MCC), Response Code, Decline Reason Code, Card Status Code, Payment Type Code, Dispute Reason Code, Currency Code, Country Code | Standardized codes used in card processing and management. Industry-standard classifications and internal reference data. |
| 13 | **Location** | Cardholder Address, Billing Address, Shipping Address, Merchant Location, Transaction Location, Geographic Risk Zone, Regional Market, Service Center Location | Address and location information for cardholders, merchants, and transactions. Geographic data for risk management and marketing. |
| 14 | **Employee** | Credit Analyst, Collections Agent, Fraud Analyst, Customer Service Representative, Relationship Manager, Underwriter, Account Manager, Recovery Specialist | Bank employees managing credit card operations. Staff involved in underwriting, servicing, collections, and fraud management. |
| 15 | **Market Data** | Prime Rate, LIBOR, Credit Card Industry Benchmark, Competitor Rates, Market Share Data, Economic Indicator, Consumer Confidence Index, Unemployment Rate | External market data used for pricing and portfolio management. Economic indicators and competitive intelligence. |

---

## Key Entity Counts by Domain

| Data Domain | Number of Entities | Percentage of Total |
|-------------|-------------------|---------------------|
| Party | 11 | 16.4% |
| Account | 12 | 17.9% |
| Transaction | 15 | 22.4% |
| Product | 13 | 19.4% |
| Agreement | 10 | 14.9% |
| Risk | 13 | 19.4% |
| Channel | 10 | 14.9% |
| Regulatory Compliance | 10 | 14.9% |
| Pricing | 11 | 16.4% |
| Reference Data | 10 | 14.9% |
| Location | 8 | 11.9% |
| Employee | 8 | 11.9% |
| Financial Performance | 12 | 17.9% |
| Market Data | 8 | 11.9% |
| Collateral | 3 | 4.5% |

---

## Mapping Notes

### Primary vs. Secondary Domain Usage
- **Transaction Domain**: Highest entity count due to diverse transaction types in card processing
- **Risk Domain**: Critical for credit cards with extensive fraud and credit risk entities
- **Product Domain**: Rich product catalog with multiple card types and features

### Coverage Analysis
- **Total Entities Mapped**: 144 distinct business entities
- **Domains with Entities**: 15 out of 15 (100%)
- **Domain Coverage**: Complete coverage across all credit card operations including payments, fraud, rewards, and compliance

### Consolidation Opportunities
- Cardholder data consolidation with consumer banking: ~30% overlap
- Transaction processing standardization: ~20% consolidation potential
- Risk scoring model harmonization: ~25% reduction through unified risk framework
- Merchant data consolidation: ~15% through centralized merchant registry

### Industry-Specific Considerations
- **Payment Network Integration**: Entities aligned with Visa, Mastercard, and other network specifications
- **PCI DSS Compliance**: Security-focused entity design for cardholder data protection
- **Real-time Processing**: Entity structure supports authorization and settlement workflows
- **Rewards Management**: Dedicated entities for loyalty program operations

---

*Document Version: 1.0*  
*Business Unit: Credit Cards*  
*Last Updated: 2025*