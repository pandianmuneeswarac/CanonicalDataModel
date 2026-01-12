# Canonical Data Domains

## Enterprise Banking Data Domain Framework

| Serial Number | Data Domain Name | Definition |
|---------------|------------------|------------|
| 1 | **Party** | Comprehensive data about individuals, organizations, and legal entities that interact with the bank in any capacity. Includes customers, prospects, third parties, beneficial owners, and their identifying attributes, demographics, and relationships. This domain serves as the master reference for all entity identification across the enterprise. |
| 2 | **Account** | Data representing contractual agreements between the bank and parties for holding, managing, or transacting financial resources. Encompasses deposit accounts, loan accounts, investment accounts, and their associated balances, terms, conditions, status, and lifecycle events from origination through closure. |
| 3 | **Product** | Standardized definitions of financial offerings, services, and instruments provided by the bank to customers. Includes product specifications, features, pricing structures, eligibility criteria, terms and conditions, and product hierarchies that define the bank's commercial catalog across all business lines. |
| 4 | **Transaction** | Detailed records of financial movements, exchanges, and operations that change account balances or positions. Covers payments, transfers, deposits, withdrawals, trades, and all monetary flows with complete audit trails including amounts, timestamps, channels, authorization details, and settlement status. |
| 5 | **Agreement** | Legally binding contracts, commitments, and arrangements between the bank and parties governing financial relationships. Includes loan agreements, credit facilities, service agreements, terms of business, covenants, collateral arrangements, and all contractual obligations with their terms, conditions, and lifecycle management. |
| 6 | **Collateral** | Assets pledged or held as security against credit exposures and obligations. Encompasses real estate, securities, cash deposits, equipment, inventory, and other tangible or intangible assets with their valuations, ownership details, lien positions, and monitoring requirements for risk mitigation. |
| 7 | **Risk** | Quantitative and qualitative assessments of potential losses, exposures, and uncertainties across credit, market, operational, and compliance dimensions. Includes risk ratings, scores, limits, concentrations, loss provisions, stress testing results, and risk mitigation strategies aligned with regulatory frameworks like Basel III. |
| 8 | **Financial Performance** | Aggregated financial metrics, indicators, and analytical data reflecting the bank's economic results and position. Covers profit and loss, balance sheet items, capital adequacy, liquidity ratios, return metrics, and performance indicators used for management reporting, regulatory filings, and stakeholder communications. |
| 9 | **Regulatory Compliance** | Data required to meet legal, regulatory, and supervisory obligations across jurisdictions. Includes regulatory reports, capital calculations, liquidity coverage ratios, anti-money laundering records, tax reporting, audit trails, and documentation supporting compliance with banking regulations, consumer protection laws, and industry standards. |
| 10 | **Channel** | Information about customer interaction points, delivery mechanisms, and touchpoints through which banking services are accessed and delivered. Encompasses branch networks, ATMs, online banking, mobile apps, call centers, and third-party platforms with their capabilities, transactions, and customer experience data. |
| 11 | **Pricing** | Rate structures, fee schedules, and cost models applied to products, services, and transactions. Includes interest rates, service charges, commissions, penalties, discounts, and pricing tiers with their calculation methodologies, effective dates, and approval workflows ensuring competitive and compliant pricing strategies. |
| 12 | **Reference Data** | Standardized codes, classifications, and lookup values used consistently across the enterprise for data harmonization. Covers currency codes, country codes, industry classifications, account types, transaction codes, status values, and other controlled vocabularies that ensure data consistency and interoperability. |
| 13 | **Location** | Geographical and physical address information for parties, branches, properties, and operational facilities. Includes addresses, coordinates, jurisdictions, regions, and spatial relationships used for service delivery, risk assessment, regulatory reporting, and market analysis with standardized geocoding and validation. |
| 14 | **Employee** | Data about bank workforce members including personal details, organizational assignments, roles, responsibilities, and employment terms. Covers employee identification, hierarchies, compensation, performance, access privileges, and HR lifecycle events supporting operations, compliance, and human capital management. |
| 15 | **Market Data** | External financial market information including securities prices, exchange rates, interest rate curves, commodity prices, and economic indicators. Provides reference pricing, valuation inputs, benchmarks, and market intelligence used for trading, risk management, product pricing, and financial reporting. |

---

## Domain Design Principles

### Mutual Exclusivity
Each domain has clear boundaries with no overlapping scope. Entities are assigned to exactly one primary domain based on their core business purpose and lifecycle management.

### Collective Exhaustiveness
The 15 domains comprehensively cover all banking data requirements across retail, commercial, wealth management, treasury, and capital markets business lines.

### System Agnostic
Domains are defined independent of source systems, applications, or technology platforms, focusing on business concepts and enterprise-wide data semantics.

### Regulatory Alignment
Domain structure supports compliance with Basel III, BCBS 239, IFRS 9, Dodd-Frank, MiFID II, GDPR, and other relevant banking regulations.

### Scalability
The framework accommodates future business expansion, new products, emerging channels, and evolving regulatory requirements without structural redesign.

---

*Document Version: 1.0*  
*Last Updated: 2025*  
*Owner: Enterprise Data Architecture*