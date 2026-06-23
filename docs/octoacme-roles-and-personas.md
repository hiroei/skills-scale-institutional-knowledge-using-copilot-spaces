# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

### Interactions
- **With Product Manager**: receive specs and acceptance criteria; provide estimates and technical feasibility input
- **With Project Manager**: collaborate on scheduling and risk identification
- **With Engineering Manager**: receive mentoring, career guidance, and capacity planning direction
- **With QA Lead**: align on test coverage and acceptance criteria validation
- **With DevOps/Platform Engineer**: coordinate on deployment and infrastructure requirements
- **With Security Engineer**: participate in security reviews; address vulnerabilities

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

### Interactions
- **With Project Manager**: align on timelines, risks, and dependencies; provide prioritization input
- **With Developers**: define acceptance criteria and success metrics; answer technical questions
- **With Data Analyst**: define measurement plans and success metrics; review analysis
- **With UX Researcher/Designer**: collaborate on user research and design validation
- **With Customer Success**: incorporate customer feedback into prioritization
- **With Business Analyst**: validate compliance and regulatory requirements

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

### Interactions
- **With Product Manager**: collaborate on prioritization and milestone alignment
- **With Technical Program Manager**: coordinate cross-team dependencies and roadmap
- **With Engineering Manager**: align on capacity and resourcing
- **With Release Manager**: coordinate release planning and deployment schedules
- **With Developers**: track progress; identify and escalate blockers
- **With Stakeholders**: provide status updates and escalate business-impacting issues

---

## Technical Program Manager (TPM)

### Role Summary
Technical Program Managers coordinate cross-functional, cross-team technical delivery. They manage complex dependencies, maintain milestone and roadmap artifacts, and ensure technical initiatives align with business objectives.

### Responsibilities
- Coordinate cross-team technical delivery and integration
- Manage complex dependencies between teams and services
- Maintain roadmap and milestone artifacts for technical initiatives
- Identify and mitigate technical risks and blockers
- Facilitate technical design reviews and architecture decisions
- Track technical debt and prioritize remediation

### Goals
- Ensure timely, coordinated delivery across multiple teams
- Reduce delays caused by unmanaged dependencies
- Maintain clear technical roadmap and milestone visibility
- Enable data-driven technical prioritization

### Typical Communication
- Cross-team sync meetings and dependency reviews
- Technical roadmap and milestone updates
- Risk and dependency tracking documents
- Escalations to Project Manager and Product Lead

### Interactions
- **With Project Manager**: escalate cross-team risks; align on timelines; provide technical roadmap input
- **With Engineering Managers**: coordinate on team capacity and dependency resolution
- **With Tech Leads**: identify technical risks and design constraints
- **With Developers**: communicate technical strategy and milestone expectations
- **With DevOps/Platform Engineer**: coordinate infrastructure and deployment requirements
- **With Product Manager**: align technical roadmap with product priorities

---

## Engineering Manager (EM)

### Role Summary
Engineering Managers lead development teams through mentorship, career growth, and organizational effectiveness. They own team capacity planning, code health decisions, and engineering culture.

### Responsibilities
- People management, mentoring, and career development for direct reports
- Capacity planning and resource allocation for projects
- Codebase health decisions and technical debt prioritization
- Team culture, psychological safety, and retrospective facilitation
- Hiring and team composition decisions

### Goals
- Develop high-performing, engaged teams
- Maintain code quality and system reliability
- Enable efficient project delivery with sustainable pace
- Reduce attrition and improve team satisfaction

### Typical Communication
- One-on-ones with direct reports
- Team standups and retrospectives
- Technical hiring discussions
- Capacity and staffing planning with Project Manager and Product Manager

### Interactions
- **With Project Manager**: provide capacity estimates and resourcing input; escalate resource constraints
- **With Technical Program Manager**: align on team dependencies and cross-team coordination
- **With Developers**: mentor on technical growth; support professional development
- **With QA Lead**: coordinate on quality gates and test coverage standards
- **With DevOps/Platform Engineer**: align on deployment and infrastructure readiness
- **With Product Manager**: provide technical feasibility input on prioritization

---

## UX Researcher / Designer

### Role Summary
UX Researchers and Designers validate product usability, accessibility, and user satisfaction through research, design iteration, and user testing. They ensure features are intuitive and meet user needs.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specs
- Validate design solutions through user feedback and iteration
- Ensure accessibility compliance (WCAG, etc.)
- Provide design guidance and conduct design reviews
- Collaborate on acceptance criteria for user-facing features

### Goals
- Deliver intuitive, accessible user experiences
- Reduce support costs through improved usability
- Validate solutions early through user research
- Advocate for user needs in prioritization discussions

### Typical Communication
- User research findings and insights reports
- Design specs and wireframes
- Usability test results and feedback
- Design review meetings with Developers and Product Manager

### Interactions
- **With Product Manager**: provide research insights for prioritization; validate product direction
- **With Developers**: collaborate on design implementation; review technical feasibility
- **With QA Lead**: define acceptance criteria for user experience and accessibility
- **With Customer Success**: incorporate user feedback into design iterations
- **With Business Analyst**: validate compliance and accessibility requirements

---

## Data Analyst / Product Analyst

### Role Summary
Data Analysts and Product Analysts measure product impact, define success metrics, and inform decisions through data. They instrument features, run analyses, and provide dashboards for monitoring.

### Responsibilities
- Define measurement plans and success metrics with Product Manager
- Instrument features with analytics and monitoring events
- Run analyses to validate success metrics and user behavior
- Build dashboards for monitoring key signals (errors, latency, usage)
- Provide data-driven insights to inform prioritization and strategy
- Support post-release verification and incident investigation

### Goals
- Enable data-driven decision-making
- Validate product impact and ROI
- Identify opportunities for improvement through data analysis
- Support quick diagnosis and resolution of issues

### Typical Communication
- Success metric definitions and measurement plans
- Analysis reports and dashboards
- Weekly or milestone-based metric reviews
- Post-release verification reports

### Interactions
- **With Product Manager**: define success metrics and measurement plans; share analysis insights
- **With QA Lead**: provide dashboards for release verification and quality monitoring
- **With Release Manager**: support post-release verification and monitoring
- **With Developers**: explain metrics and monitor feature performance
- **With DevOps/Platform Engineer**: coordinate on instrumentation and logging infrastructure

---

## DevOps / Platform Engineer

### Role Summary
DevOps and Platform Engineers own CI/CD pipelines, deployment automation, observability, and infrastructure. They enable fast, safe, reliable delivery and system performance.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment automation
- Manage infrastructure as code and infrastructure provisioning
- Implement observability, logging, and monitoring
- Support incident response and post-incident analysis
- Advise Developers and Release Manager on deployment constraints
- Optimize system performance and reliability

### Goals
- Enable fast, automated, safe deployments
- Maintain system reliability and performance
- Reduce deployment-related incidents and failures
- Support rapid incident diagnosis and resolution

### Typical Communication
- CI/CD and deployment documentation
- Infrastructure and observability dashboards
- Incident response and post-incident reports
- Consultation on deployment and infrastructure requirements

### Interactions
- **With Developers**: advise on deployability and observability best practices; support CI/CD troubleshooting
- **With Release Manager**: coordinate on deployment steps and pre-release verification
- **With Security Engineer**: integrate security scanning and compliance checks into CI/CD
- **With Data Analyst**: coordinate on instrumentation and monitoring infrastructure
- **With QA Lead**: support test automation and staging environment setup

---

## Security Engineer

### Role Summary
Security Engineers identify, assess, and mitigate security risks. They conduct threat modeling, security reviews, and coordinate vulnerability remediation to protect systems and data.

### Responsibilities
- Conduct threat modeling and security architecture reviews
- Perform security code reviews and vulnerability assessments
- Coordinate vulnerability tracking, prioritization, and remediation
- Advise on compliance and regulatory requirements
- Conduct security training and awareness initiatives
- Support incident response for security incidents

### Goals
- Prevent security breaches and data loss
- Ensure compliance with security regulations
- Foster security-aware engineering culture
- Enable fast, confident security incident response

### Typical Communication
- Threat modeling and architecture review documents
- Vulnerability reports and remediation tracking
- Security incident escalations and post-incident reports
- Security training and awareness materials

### Interactions
- **With Developers**: conduct security reviews; educate on secure coding practices
- **With Product Manager**: communicate security risks and compliance implications of prioritization
- **With Project Manager**: escalate critical security issues; coordinate remediation timing
- **With DevOps/Platform Engineer**: integrate security scanning and compliance checks into CI/CD
- **With Business Analyst**: validate regulatory and compliance requirements

---

## Release Manager

### Role Summary
Release Managers orchestrate end-to-end releases, manage release plans, coordinate deployments, and ensure post-release verification. They minimize release-related risk and ensure smooth deployments.

### Responsibilities
- Create and maintain release plans and checklists
- Coordinate with DevOps, QA, and teams on cutover steps
- Run pre-release smoke tests and post-release verification
- Manage release communication and stakeholder updates
- Coordinate rollback and incident response for failed releases
- Document lessons learned and improve release processes

### Goals
- Execute smooth, low-risk releases
- Minimize deployment failures and incidents
- Reduce time to resolution for release issues
- Improve release process through continuous improvement

### Typical Communication
- Release plans and checklists
- Pre-release and post-release verification reports
- Release notes and stakeholder communications
- Incident response and rollback coordination

### Interactions
- **With Project Manager**: coordinate on release timing and milestone alignment
- **With Technical Program Manager**: align on release dependencies and cross-team coordination
- **With DevOps/Platform Engineer**: coordinate on deployment steps and automation
- **With QA Lead**: coordinate on pre-release smoke tests and acceptance verification
- **With Customer Success**: coordinate on release communication and support readiness
- **With Data Analyst**: review post-release verification dashboards and metrics

---

## Customer Success / Support Liaison

### Role Summary
Customer Success and Support Liaisons surface customer feedback, assess customer impact, and coordinate support communications. They ensure customer needs inform prioritization and that support is prepared for releases.

### Responsibilities
- Surface customer feedback and feature requests
- Assess customer impact of issues and prioritization decisions
- Coordinate support readiness for new features and releases
- Provide customer perspective in prioritization discussions
- Manage customer escalations and communication
- Track customer satisfaction and NPS metrics

### Goals
- Maximize customer satisfaction and retention
- Ensure customer voice is heard in prioritization
- Reduce customer-impacting issues and support load
- Improve customer outcomes and time-to-value

### Typical Communication
- Customer feedback and impact assessments
- Feature request and prioritization input
- Release communication and support readiness coordination
- Customer satisfaction and NPS reports

### Interactions
- **With Product Manager**: provide customer feedback for prioritization; validate product direction
- **With Release Manager**: coordinate on release communication and support readiness
- **With Developers**: help reproduce issues and provide customer context
- **With Project Manager**: escalate critical customer issues and business impact
- **With UX Researcher/Designer**: share user feedback for design iteration

---

## Business Analyst / Subject Matter Expert (SME)

### Role Summary
Business Analysts and Subject Matter Experts clarify domain-specific requirements, validate compliance and regulatory needs, and ensure solutions meet business objectives. They bridge business and technical teams.

### Responsibilities
- Clarify and document domain-specific requirements
- Validate compliance with regulatory and legal requirements
- Identify business risks and dependencies
- Provide subject matter expertise for design and implementation decisions
- Conduct requirements analysis and trade-off assessment
- Support user acceptance testing and business verification

### Goals
- Ensure solutions meet business objectives and compliance needs
- Reduce rework due to misaligned or missed requirements
- Enable informed trade-off decisions
- Minimize compliance and regulatory risks

### Typical Communication
- Requirements documentation and analysis
- Compliance and regulatory guidance
- Trade-off analysis and recommendation documents
- Business verification and acceptance reports

### Interactions
- **With Product Manager**: clarify requirements and business objectives; validate prioritization against compliance needs
- **With Developers**: explain domain requirements; support implementation decisions
- **With Security Engineer**: validate regulatory and compliance requirements
- **With QA Lead**: define business acceptance criteria and test scenarios
- **With Project Manager**: identify business risks and dependencies

---

## QA Lead

### Role Summary
QA Leads define test strategies, validate acceptance criteria, and coordinate test execution and automation. They ensure quality gates are met and systems are reliable before release.

### Responsibilities
- Define test strategies and test plans for features and releases
- Validate acceptance criteria and definition of done
- Coordinate test execution and automation
- Execute pre-release smoke tests and regression testing
- Identify quality gaps and track quality metrics
- Support incident investigation and root cause analysis

### Goals
- Ensure features meet quality and acceptance criteria before release
- Reduce production defects and customer-impacting issues
- Enable fast, confident feature delivery
- Continuously improve test coverage and automation

### Typical Communication
- Test plans and test case documentation
- Quality reports and metrics
- Pre-release and post-release verification reports
- Quality trend analysis and improvement recommendations

### Interactions
- **With Developers**: align on test coverage and acceptance criteria; support troubleshooting
- **With Product Manager**: validate acceptance criteria and user story clarity
- **With Engineering Manager**: coordinate on quality standards and test automation investment
- **With UX Researcher/Designer**: define user experience and accessibility test scenarios
- **With Release Manager**: execute pre-release smoke tests and post-release verification
- **With Data Analyst**: monitor quality metrics and trends; support post-release verification

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the Interactions section to understand cross-functional dependencies and communication patterns.
- Use the Responsibilities and Goals sections to clarify ownership and decision-making authority in ambiguous situations.
