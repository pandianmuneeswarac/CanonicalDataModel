# Business Unit Analysis: COE (Center of Excellence)

## Business Unit: COE

---

### Source System: AD

| Attribute | Details |
|-----------|----------|
| **Business Unit Name** | COE |
| **Source System Name** | AD |
| **System Functionality** | Active Directory managing user authentication, authorization, group policies, and enterprise identity management. |
| **Total Number of Tables** | 12 |

#### Top 20-25 Key Entity Names:

- User
- Group
- OrganizationalUnit
- Computer
- Domain
- Policy
- Permission
- Role
- Authentication
- SecurityGroup
- DistributionList
- UserAttribute

---

### Source System: AdminPortal

| Attribute | Details |
|-----------|----------|
| **Business Unit Name** | COE |
| **Source System Name** | AdminPortal |
| **System Functionality** | Administrative portal for system configuration, user management, and operational administration. |
| **Total Number of Tables** | 2 |

#### Top 20-25 Key Entity Names:

- Administrator
- Configuration

---

### Source System: ADO

| Attribute | Details |
|-----------|----------|
| **Business Unit Name** | COE |
| **Source System Name** | ADO |
| **System Functionality** | Azure DevOps managing software development lifecycle, version control, CI/CD pipelines, and project management. |
| **Total Number of Tables** | 0 |

#### Top 20-25 Key Entity Names:

- Project
- Repository
- Pipeline
- Build
- Release
- WorkItem
- Sprint
- Backlog
- PullRequest
- Branch
- Commit
- TestCase
- Artifact
- Deployment

---

### Source System: Archive

| Attribute | Details |
|-----------|----------|
| **Business Unit Name** | COE |
| **Source System Name** | Archive |
| **System Functionality** | Enterprise data archival system for long-term storage, retention compliance, and historical data management. |
| **Total Number of Tables** | 1,000 |

#### Top 20-25 Key Entity Names:

- ArchivedRecord
- Document
- Metadata
- RetentionPolicy
- ArchiveJob
- StorageLocation
- DataClassification
- AccessLog
- RetrievalRequest
- ComplianceRule
- ExpirationDate
- ArchiveStatus
- DataOwner
- LegalHold
- DispositionSchedule
- IndexEntry
- SearchCriteria
- AuditTrail
- BackupCopy
- RestorationLog

---

### Source System: DataMart

| Attribute | Details |
|-----------|----------|
| **Business Unit Name** | COE |
| **Source System Name** | DataMart |
| **System Functionality** | Subject-oriented data mart for business intelligence, analytics, and departmental reporting. |
| **Total Number of Tables** | 20 |

#### Top 20-25 Key Entity Names:

- FactTable
- DimensionTable
- Measure
- Metric
- TimeDimension
- CustomerDimension
- ProductDimension
- GeographyDimension
- AggregateTable
- SummaryView
- AnalyticsCube
- KPI
- Dashboard
- ReportDefinition
- DataRefresh
- ETLLog
- DataQuality
- BusinessRule
- CalculatedField
- HierarchyLevel

---

### Source System: Decisions

| Attribute | Details |
|-----------|----------|
| **Business Unit Name** | COE |
| **Source System Name** | Decisions |
| **System Functionality** | Business rules engine and decision management platform for automated decisioning and workflow automation. |
| **Total Number of Tables** | 18 |

#### Top 20-25 Key Entity Names:

- DecisionRule
- RuleSet
- Workflow
- Process
- DecisionTable
- Condition
- Action
- RuleExecution
- DecisionLog
- BusinessLogic
- ValidationRule
- ApprovalFlow
- RuleVersion
- DecisionOutcome
- RuleParameter
- ExecutionContext
- PolicyRule
- RuleCategory

---

### Source System: DocuSign

| Attribute | Details |
|-----------|----------|
| **Business Unit Name** | COE |
| **Source System Name** | DocuSign |
| **System Functionality** | Electronic signature and digital transaction management for document signing and agreement workflows. |
| **Total Number of Tables** | 3 |

#### Top 20-25 Key Entity Names:

- Envelope
- Document
- Signer

---

### Source System: DWSupport

| Attribute | Details |
|-----------|----------|
| **Business Unit Name** | COE |
| **Source System Name** | DWSupport |
| **System Functionality** | Data warehouse support system managing ETL processes, data quality, metadata, and warehouse operations. |
| **Total Number of Tables** | 1,679 |

#### Top 20-25 Key Entity Names:

- ETLJob
- DataSource
- TargetTable
- TransformationRule
- DataQualityCheck
- ErrorLog
- JobSchedule
- DataLineage
- Metadata
- StagingTable
- LoadStatistics
- DataValidation
- ReconciliationReport
- SourceToTargetMapping
- DependencyGraph
- JobExecution
- PerformanceMetric
- DataProfile
- AuditRecord
- ChangeDataCapture
- IncrementalLoad
- FullRefresh
- DataMigration
- VersionControl
- ConfigurationParameter

---

### Source System: EnterpriseBI

| Attribute | Details |
|-----------|----------|
| **Business Unit Name** | COE |
| **Source System Name** | EnterpriseBI |
| **System Functionality** | Enterprise business intelligence platform for reporting, analytics, dashboards, and data visualization. |
| **Total Number of Tables** | 91 |

#### Top 20-25 Key Entity Names:

- Report
- Dashboard
- Dataset
- DataSource
- Visualization
- Query
- User
- Workspace
- Subscription
- Schedule
- Parameter
- Filter
- Metric
- KPI
- Dimension
- Measure
- ReportExecution
- ExportLog
- AccessControl
- ReportFolder
- DataRefresh
- CachedResult
- AlertRule
- Notification
- ReportTemplate

---

### Source System: ETL

| Attribute | Details |
|-----------|----------|
| **Business Unit Name** | COE |
| **Source System Name** | ETL |
| **System Functionality** | Extract, Transform, Load processes for data integration, transformation, and movement across systems. |
| **Total Number of Tables** | 20 |

#### Top 20-25 Key Entity Names:

- ETLJob
- SourceConnection
- TargetConnection
- Transformation
- DataFlow
- Package
- Task
- JobSchedule
- ExecutionLog
- ErrorHandling
- DataMapping
- LoadStrategy
- ValidationRule
- DependencyChain
- JobParameter
- ControlTable
- AuditLog
- PerformanceLog
- DataQuality
- RecoveryPoint

---

### Source System: Evo

| Attribute | Details |
|-----------|----------|
| **Business Unit Name** | COE |
| **Source System Name** | Evo |
| **System Functionality** | Evolution platform for application development, deployment, and lifecycle management. |
| **Total Number of Tables** | 6 |

#### Top 20-25 Key Entity Names:

- Application
- Module
- Component
- Version
- Deployment
- Configuration

---

### Source System: ExcelETL

| Attribute | Details |
|-----------|----------|
| **Business Unit Name** | COE |
| **Source System Name** | ExcelETL |
| **System Functionality** | Excel-based data extraction and loading for spreadsheet integration and manual data processing. |
| **Total Number of Tables** | 359 |

#### Top 20-25 Key Entity Names:

- Workbook
- Worksheet
- DataRange
- Column
- Row
- Cell
- Formula
- ImportJob
- ExportJob
- Template
- Mapping
- ValidationRule
- DataType
- Format
- SourceFile
- TargetTable
- TransformationLogic
- ErrorRecord
- LoadStatus
- FileMetadata
- ProcessLog
- ScheduledImport
- DataRefresh
- VersionHistory
- UserUpload

---

### Source System: ExcelFile – Essentia

| Attribute | Details |
|-----------|----------|
| **Business Unit Name** | COE |
| **Source System Name** | ExcelFile – Essentia |
| **System Functionality** | Essential Excel file management for critical business data stored in spreadsheet format. |
| **Total Number of Tables** | 2 |

#### Top 20-25 Key Entity Names:

- EssentiaFile
- FileMetadata

---

### Source System: Five9

| Attribute | Details |
|-----------|----------|
| **Business Unit Name** | COE |
| **Source System Name** | Five9 |
| **System Functionality** | Cloud contact center platform managing customer interactions, call routing, and agent performance. |
| **Total Number of Tables** | 32 |

#### Top 20-25 Key Entity Names:

- Call
- Agent
- Campaign
- Queue
- Interaction
- Customer
- CallDisposition
- Recording
- Script
- Skill
- Schedule
- PerformanceMetric
- CallOutcome
- WaitTime
- HandleTime
- TransferEvent
- IVRSession
- ChatSession
- EmailInteraction
- VoicemailMessage
- AgentState
- QualityScore
- SurveyResponse
- EscalationRule
- ServiceLevel

---

### Source System: FraudLinks

| Attribute | Details |
|-----------|----------|
| **Business Unit Name** | COE |
| **Source System Name** | FraudLinks |
| **System Functionality** | Fraud detection and prevention system linking suspicious activities and identifying fraud patterns. |
| **Total Number of Tables** | 8 |

#### Top 20-25 Key Entity Names:

- FraudCase
- Alert
- Transaction
- Customer
- RiskScore
- FraudPattern
- Investigation
- LinkedEntity

---

### Source System: Intranet

| Attribute | Details |
|-----------|----------|
| **Business Unit Name** | COE |
| **Source System Name** | Intranet |
| **System Functionality** | Internal corporate portal for employee communication, document sharing, and organizational information. |
| **Total Number of Tables** | 82 |

#### Top 20-25 Key Entity Names:

- User
- Page
- Content
- Document
- News
- Announcement
- Department
- Team
- Forum
- Discussion
- Comment
- Attachment
- Calendar
- Event
- Policy
- Procedure
- Resource
- Link
- Search
- Navigation
- Permission
- Workflow
- Approval
- Notification
- Activity

---

### Source System: Outsystems

| Attribute | Details |
|-----------|----------|
| **Business Unit Name** | COE |
| **Source System Name** | Outsystems |
| **System Functionality** | Low-code application development platform for rapid application delivery and enterprise app management. |
| **Total Number of Tables** | 434 |

#### Top 20-25 Key Entity Names:

- Application
- Module
- Entity
- Screen
- Action
- Process
- User
- Role
- Permission
- Integration
- WebService
- Database
- Environment
- Deployment
- Version
- Log
- Error
- Session
- Workflow
- BusinessRule
- DataModel
- UIComponent
- APIEndpoint
- Configuration
- Tenant

---

### Source System: OSPRDI

| Attribute | Details |
|-----------|----------|
| **Business Unit Name** | COE |
| **Source System Name** | OSPRDI |
| **System Functionality** | OutSystems production and development infrastructure managing application environments and deployments. |
| **Total Number of Tables** | 57 |

#### Top 20-25 Key Entity Names:

- Environment
- Application
- Deployment
- Server
- Database
- Configuration
- Module
- Version
- Build
- Release
- Infrastructure
- Monitoring
- Performance
- Log
- Error
- Resource
- Capacity
- Scaling
- LoadBalancer
- SecurityPolicy
- BackupJob
- RecoveryPoint
- HealthCheck
- Alert
- Maintenance

---

### Source System: ReportServer

| Attribute | Details |
|-----------|----------|
| **Business Unit Name** | COE |
| **Source System Name** | ReportServer |
| **System Functionality** | Centralized reporting server for report generation, distribution, scheduling, and report management. |
| **Total Number of Tables** | 72 |

#### Top 20-25 Key Entity Names:

- Report
- ReportDefinition
- Dataset
- DataSource
- Parameter
- Subscription
- Schedule
- Execution
- Snapshot
- User
- Folder
- Permission
- RenderFormat
- DeliveryMethod
- ReportHistory
- Cache
- Query
- Filter
- ExportLog
- ErrorLog
- PerformanceMetric
- ReportUsage
- AccessLog
- Configuration
- Catalog

---

### Source System: SharePoint

| Attribute | Details |
|-----------|----------|
| **Business Unit Name** | COE |
| **Source System Name** | SharePoint |
| **System Functionality** | Collaboration platform for document management, team sites, workflows, and content management. |
| **Total Number of Tables** | 179 |

#### Top 20-25 Key Entity Names:

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
- Metadata
- Version
- Page
- WebPart
- View
- Column
- Lookup
- Attachment
- Comment
- Approval
- Task
- Calendar
- Announcement
- Discussion

---

### Source System: Snow

| Attribute | Details |
|-----------|----------|
| **Business Unit Name** | COE |
| **Source System Name** | Snow |
| **System Functionality** | Software asset management for license tracking, compliance, and IT asset optimization. |
| **Total Number of Tables** | 5 |

#### Top 20-25 Key Entity Names:

- Asset
- License
- Software
- Computer
- Compliance

---

### Source System: SYNRGVD01

| Attribute | Details |
|-----------|----------|
| **Business Unit Name** | COE |
| **Source System Name** | SYNRGVD01 |
| **System Functionality** | Synergy virtual database for integrated data access and virtualized data layer management. |
| **Total Number of Tables** | 21 |

#### Top 20-25 Key Entity Names:

- VirtualTable
- DataSource
- Connection
- Query
- View
- Schema
- Mapping
- Cache
- SecurityPolicy
- AccessControl
- Federation
- DataService
- Metadata
- Transformation
- JoinDefinition
- FilterRule
- AggregationRule
- PerformanceLog
- QueryOptimization
- DataLineage

---

### Source System: WS repo

| Attribute | Details |
|-----------|----------|
| **Business Unit Name** | COE |
| **Source System Name** | WS repo |
| **System Functionality** | Web services repository managing API definitions, service contracts, and integration endpoints. |
| **Total Number of Tables** | 6 |

#### Top 20-25 Key Entity Names:

- WebService
- Endpoint
- Contract
- Operation
- Message
- Schema