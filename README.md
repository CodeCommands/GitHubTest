# DOE Salesforce User Provisioning Demo Flow

## Opening (1 min)

• **Setup Context** - “Today I’ll show how DOE eliminated manual user provisioning, reducing time from days to hours while ensuring compliance and security”

## Phase 1: End-User Experience (8 mins)

• **Public Request Form** - Navigate to EITS portal, fill form with DOE employee data, show dynamic Application/Role selection (4BC → IRS Examiner), submit request. *Highlight: Self-service, no Salesforce license needed, DOE-specific validation*

• **Immediate Confirmation** - Show confirmation page with UAR tracking number and automated email. *Highlight: Sets expectations, provides tracking reference*

• **Status Check** - Use “Check Request Status” button, lookup by UAR-0010 or email, show status progression. *Highlight: Self-service transparency, reduces help desk calls*

## Phase 2: Internal Approval Process (8 mins)

• **UAR Record Creation** - Navigate to UAR-0010, show captured data, user details, and history panels on right. *Highlight: Complete audit trail, structured data capture, compliance ready*

• **Approval Queue** - Show approval interface for 4BC User Access Approvers, review UAR-0007 details, demonstrate approve/reject. *Highlight: Application-specific queues, complete context for decisions*

• **Approval Tracking** - Show approval history panel, email notifications to stakeholders. *Highlight: Automated workflow, transparent process*

## Phase 3: Automated User Creation (5 mins)

• **Metadata Configuration** - Quick view of Custom Metadata defining 4BC application and IRS Examiner role permissions. *Highlight: Business-configurable, no code changes needed*

• **User Creation Result** - Show completed UAR-0010 with “Created User” link to PawanTest AUPUser record. *Highlight: Zero-touch provisioning, bidirectional traceability*

• **User Verification** - Navigate to created user, show profile/role/permissions match metadata configuration. *Highlight: Consistent access, security compliance*

## Administrative Benefits (3 mins)

• **Reporting Dashboard** - Show UAR metrics: processing times, approval rates, volume trends by application. *Highlight: Data-driven insights, compliance reporting*

• **System Scalability** - Demonstrate adding new application via metadata, show role-based administration. *Highlight: Business-user maintainable, scales with DOE growth*

## Closing Summary (2 mins)

### Key Achievements:

- **End Users:** Self-service request and status checking
- **Approvers:** Streamlined, contextual approval process
- **Administrators:** Zero-touch provisioning and comprehensive reporting
- **DOE Organization:** Improved security, compliance, and operational efficiency

### Quantifiable Results:

- Provisioning time: Days → Hours
- Manual errors: Eliminated through automation
- Compliance: Complete audit trail maintained
- Administrative overhead: Significantly reduced

-----

## Demo Preparation Checklist:

- [ ] Pre-populate UAR records in various states (submitted, pending, approved, completed)
- [ ] Prepare sample approver notifications and user creation emails
- [ ] Set up demo metadata configurations for 4BC and other applications
- [ ] Create sample dashboard with realistic DOE metrics
- [ ] Have backup scenarios ready (different applications, roles, error handling)

## Key Questions to Address:

• **Integration:** “Can this connect with DOE HR systems or Active Directory?”
• **Deprovisioning:** “How do you handle access removal when employees leave?”
• **Scalability:** “How easy is it to add new DOE applications beyond 4BC?”
• **Security:** “What controls ensure federal compliance requirements?”
• **Maintenance:** “Who can manage application configurations and approval routing?”