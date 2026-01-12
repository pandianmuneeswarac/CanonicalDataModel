# Business Unit Analysis: COE

## Source System Details

| Business Unit | Source System Name | System Functionality | Total Number of Tables |
|--------------|-------------------|---------------------|------------------------|
| COE | AD | Active Directory for user authentication, access control, and identity management. | 12 |
| COE | AdminPortal | Administrative portal for system configuration, user management, and operational controls. | 2 |
| COE | ADO | Azure DevOps for software development, version control, and project management. | 0 |
| COE | Archive | Data archival system for long-term storage, compliance, and historical data retention. | 1,000 |
| COE | DataMart | Data warehouse for analytical reporting, business intelligence, and decision support. | 20 |
| COE | Decisions | Business rules engine for automated decision-making, workflow management, and process automation. | 18 |
| COE | DocuSign | Electronic signature platform for document management, contract execution, and digital workflows. | 3 |
| COE | DWSupport | Data warehouse support system for ETL processes, data quality, and metadata management. | 1,679 |
| COE | EnterpriseBI | Enterprise business intelligence platform for reporting, dashboards, and analytics. | 91 |
| COE | ETL | Extract, transform, load system for data integration, migration, and transformation. | 20 |
| COE | Evo | Evolution platform for application development, system integration, and process automation. | 6 |
| COE | ExcelETL | Excel-based ETL tool for data extraction, transformation, and loading operations. | 359 |
| COE | ExcelFile – Essentia | Excel file management system for essential data processing and reporting. | 2 |
| COE | Five9 | Cloud contact center platform for customer service, call routing, and interaction management. | 32 |
| COE | FraudLinks | Fraud detection system for transaction monitoring, risk assessment, and suspicious activity alerts. | 8 |
| COE | Intranet | Internal portal for employee communication, document sharing, and collaboration. | 82 |
| COE | Outsystems | Low-code development platform for rapid application development and digital transformation. | 434 |
| COE | OSPRDI | OutSystems production environment for enterprise applications and system integration. | 57 |
| COE | ReportServer | Reporting server for scheduled reports, ad-hoc queries, and data distribution. | 72 |
| COE | SharePoint | Collaboration platform for document management, team sites, and content sharing. | 179 |
| COE | Snow | IT asset management system for software licensing, hardware inventory, and compliance tracking. | 5 |
| COE | SYNRGVD01 | Synergy virtual desktop infrastructure for remote access and virtualized computing. | 21 |
| COE | WS repo | Web services repository for API management, service catalog, and integration endpoints. | 6 |

### AD - Top 20-25 Key Entity Names:

- User
- Group
- OrganizationalUnit
- Domain
- AccessControl
- Permission
- Role
- Authentication
- UserProfile
- SecurityPolicy
- GroupMembership
- DirectoryObject

### AdminPortal - Top 20-25 Key Entity Names:

- Administrator
- Configuration

### Archive - Top 20-25 Key Entity Names:

- ArchivedRecord
- Document
- Transaction
- Account
- Customer
- RetentionPolicy
- ArchiveJob
- StorageLocation
- DataClassification
- ComplianceRule
- ArchiveIndex
- RetrievalRequest
- AuditLog
- DataLifecycle
- LegalHold
- DispositionSchedule
- ArchiveMetadata
- VersionHistory
- AccessLog
- RestoreRequest
- DataIntegrity
- EncryptionKey
- BackupCopy
- RetentionPeriod
- ArchiveStatus

### DataMart - Top 20-25 Key Entity Names:

- Fact
- Dimension
- Measure
- DimensionHierarchy
- AggregateTable
- DataCube
- TimeDimension
- CustomerDimension
- ProductDimension
- GeographyDimension
- FactTransaction
- FactBalance
- MetricDefinition
- KPI
- Dashboard
- Report
- DataModel
- ETLProcess
- DataQuality
- BusinessRule

### Decisions - Top 20-25 Key Entity Names:

- DecisionRule
- BusinessRule
- Workflow
- Process
- Task
- Condition
- Action
- RuleSet
- DecisionTable
- ProcessInstance
- WorkflowStep
- Approval
- Escalation
- RuleExecution
- DecisionOutcome
- ProcessVariable
- RuleVersion
- DecisionLog

### DocuSign - Top 20-25 Key Entity Names:

- Envelope
- Document
- Signer

### DWSupport - Top 20-25 Key Entity Names:

- DataSource
- ETLJob
- DataTransformation
- DataQualityRule
- Metadata
- DataLineage
- SourceTable
- TargetTable
- TransformationLogic
- DataMapping
- ValidationRule
- ErrorLog
- JobSchedule
- DataLoad
- IncrementalLoad
- FullLoad
- StagingTable
- DataProfiling
- DataCleansing
- DataStandardization
- ReferenceData
- BusinessGlossary
- DataDictionary
- ChangeDataCapture
- DataGovernance

### EnterpriseBI - Top 20-25 Key Entity Names:

- Report
- Dashboard
- Dataset
- Visualization
- Metric
- KPI
- Dimension
- Measure
- ReportParameter
- DataSource
- ReportSchedule
- Subscription
- User
- UserGroup
- Permission
- Folder
- ReportTemplate
- ChartType
- Filter
- DrillDown
- ReportExecution
- CachedData
- ReportHistory
- AlertRule
- AnalyticsModel

### ETL - Top 20-25 Key Entity Names:

- ETLJob
- DataSource
- DataTarget
- Transformation
- DataMapping
- ValidationRule
- ErrorHandling
- JobSchedule
- DataFlow
- LoadStrategy
- DataExtract
- DataTransform
- DataLoad
- JobLog
- DataQuality
- SourceConnection
- TargetConnection
- TransformationRule
- JobDependency
- ExecutionStatus

### Evo - Top 20-25 Key Entity Names:

- Application
- Module
- Integration
- Workflow
- Configuration
- Process

### ExcelETL - Top 20-25 Key Entity Names:

- ExcelFile
- Worksheet
- DataRange
- Column
- Row
- DataMapping
- TransformationRule
- ValidationRule
- SourceFile
- TargetTable
- FileTemplate
- DataExtraction
- DataTransformation
- DataLoad
- ErrorLog
- FileSchedule
- FileArchive
- DataValidation
- FormulaMapping
- LookupTable
- ReferenceData
- FileMetadata
- LoadHistory
- DataQualityCheck
- FileProcessing

### ExcelFile – Essentia - Top 20-25 Key Entity Names:

- ExcelFile
- DataSheet

### Five9 - Top 20-25 Key Entity Names:

- Call
- Agent
- Campaign
- Queue
- Customer
- Interaction
- CallRecording
- CallDisposition
- SkillSet
- Schedule
- PerformanceMetric
- CallScript
- IVRFlow
- CallRouting
- AgentStatus
- CallLog
- QualityScore
- ServiceLevel
- AbandonRate
- WaitTime
- CallTransfer
- Conference
- Voicemail
- ChatInteraction
- EmailInteraction

### FraudLinks - Top 20-25 Key Entity Names:

- FraudAlert
- Transaction
- RiskScore
- SuspiciousActivity
- FraudRule
- Investigation
- Case
- FraudPattern

### Intranet - Top 20-25 Key Entity Names:

- Page
- Document
- News
- Announcement
- Employee
- Department
- Team
- Forum
- Discussion
- Comment
- File
- Folder
- Link
- Calendar
- Event
- Policy
- Procedure
- Form
- Workflow
- Approval
- Notification
- Search
- Tag
- Category
- UserProfile

### Outsystems - Top 20-25 Key Entity Names:

- Application
- Module
- Entity
- Screen
- Action
- Process
- Integration
- WebService
- Database
- User
- Role
- Permission
- Theme
- Widget
- Timer
- EmailTemplate
- SiteProperty
- SystemLog
- Deployment
- Version
- Environment
- Dependency
- Reference
- Extension
- APIEndpoint

### OSPRDI - Top 20-25 Key Entity Names:

- Application
- Module
- Entity
- Process
- Integration
- WebService
- Database
- User
- Role
- Configuration
- Deployment
- Environment
- APIEndpoint
- DataModel
- BusinessLogic
- Screen
- Action
- Timer
- EmailTemplate
- SystemLog
- Version
- Dependency
- Extension
- SiteProperty
- SecurityPolicy

### ReportServer - Top 20-25 Key Entity Names:

- Report
- ReportDefinition
- Schedule
- Subscription
- DataSource
- Dataset
- Parameter
- ReportExecution
- ReportHistory
- User
- Folder
- Permission
- ReportSnapshot
- CachedReport
- ReportLog
- DeliveryChannel
- EmailDistribution
- FileExport
- ReportFormat
- ReportTemplate
- DataConnection
- ReportFilter
- ReportGroup
- ExecutionLog
- ErrorLog

### SharePoint - Top 20-25 Key Entity Names:

- Site
- Library
- List
- Document
- Folder
- Item
- User
- Group
- Permission
- Workflow
- ContentType
- Column
- View
- Page
- WebPart
- Version
- CheckOut
- Approval
- Metadata
- Tag
- Search
- Navigation
- SiteCollection
- Subsite
- RecycleBin

### Snow - Top 20-25 Key Entity Names:

- Asset
- Software
- License
- Hardware
- Inventory

### SYNRGVD01 - Top 20-25 Key Entity Names:

- VirtualDesktop
- User
- Session
- Application
- Resource
- AccessPolicy
- Desktop Pool
- Connection
- Performance
- Storage
- Network
- SecurityGroup
- Configuration
- Deployment
- License
- Monitoring
- EventLog
- UserProfile
- ApplicationDelivery
- LoadBalancing

### WS repo - Top 20-25 Key Entity Names:

- WebService
- API
- Endpoint
- ServiceContract
- Operation
- Message