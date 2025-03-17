# Proposal: Streamlining Deployments on Akash Network from GitHub/GitLab/Bitbucket [Phase 2]

<table>
  <tr>
    <td width="60%">
      <h2>Proposal Overview</h2>
      <p>Following extensive community feedback and our presentations at both the Steering Committee and SIG-Clients meetings, we're pleased to present our revised proposal for Phase 2 of the deployment streamlining initiative. Based on valuable input received, we've optimized our approach and reduced the total budget from $70,000 to $62,000 while maintaining all core deliverables.</p>
      <p><strong>Key Revisions Based on Feedback:</strong></p>
      <ul>
        <li>Reduced documentation costs by identifying components that can be community-contributed</li>
        <li>Optimized testing processes without compromising quality</li>
        <li>Streamlined frontend development costs</li>
        <li>Added community participation guidelines for future framework support</li>
      </ul>
    </td>
    <td width="40%">
      <img src="https://github.com/user-attachments/assets/1ce609ae-e546-4397-9367-5901294abbc9" alt="Akash Network Deployment" width="100%">
    </td>
  </tr>
</table>

## Background

Phase 1 of our initiative successfully introduced automatic deployments for popular JavaScript frameworks from GitHub onto Akash Network. This implementation has already simplified deployment for hundreds of developers, creating a strong foundation for expansion.

![image](https://github.com/user-attachments/assets/a85e400a-e4b2-45ba-80f8-ef8fa5684793)


Since its launch at [console.akash.network](https://console.akash.network), the feature has been embraced by a lot of developers in the community. We've seen growing adoption rates and positive feedback on discord, particularly regarding the simplified deployment process. This demonstrates not only the value of our approach but also the strong demand for these features within the ecosystem.

## Current Achievements (Phase 1 Recap)

Phase 1 successfully provided developers with a seamless, automated deployment experience similar to Vercel and Netlify. It supports deploying applications from GitHub, GitLab, and BitBucket repositories directly onto the Akash Network.

**Frameworks Currently Supported:**
- **JavaScript Frameworks:** React, Vue.js, Next.js, Angular, Ember.js
- **Static Site Generators:** Gatsby.js, Nuxt.js, Astro, VitePress, 11ty.js
- **Full-stack Frameworks:** Remix, Vite, Express.js

**Phase 1 Implementation Details:**
- PR merged: [feature: Enable Deployment from Git Repositories to Akash Network console#417](https://github.com/akash-network/console/pull/417)
- Proposal: [https://www.mintscan.io/akash/proposals/258](https://www.mintscan.io/akash/proposals/258)
- Current Status: Live at [console.akash.network](https://console.akash.network)

## Phase 2 Objective

Our goal is to expand support to new technology stacks, including Go frameworks, Python frameworks, Ruby on Rails, and WordPress. This expansion will attract a wider range of developers and projects, enhancing the Akash Network's utility and appeal.

## Proposed New Features

### Go Web Frameworks
- Gin
- Echo
- Beego
- Buffalo
- Fiber

### Python Frameworks
- Django
- Flask
- FastAPI

### Ruby Framework
- Ruby on Rails

### CMS Platform
- WordPress

## Implementation Plan

Our implementation strategy follows a structured approach to ensure quality and comprehensive coverage:

### 1. Framework Analysis & Integration
- Research Build Requirements
- Environment Setup
- Automation Development
- CI/CD Configuration

### 2. Testing & Quality Assurance
- Comprehensive test suite development
- Security testing

### 3. Documentation & User Support
- Technical documentation for core functionality and integration
- Community contribution guidelines for user guides
- Framework-specific integration documentation

### 4. GUI Integration
- Console interface updates
- Streamlined framework selection
- Enhanced user feedback mechanisms

## Detailed Timeline

### Month 1: Framework Analysis & Initial Development
**Week 1-2**
- Project infrastructure setup
- Go frameworks integration (Gin, Echo)
- Python frameworks research
- Testing environment configuration
- Beego and Fiber implementation
- Docker configurations for FastAPI, Flask and Django

**Week 3-4**
- Ruby on Rails integration
- WordPress deployment templates
- Initial framework testing
- Complete Go framework integration
- Django, Flask and FastAPI deployment finalization
- Console UI design drafting

### Month 2: Integration Completion & Testing
**Week 5-6**
- Python framework integration completion
- Performance testing
- Ruby on Rails automation testing
- WordPress compatibility testing
- Security assessments

**Week 7-8**
- Cross-framework integration testing
- Pipeline optimization
- Final integration testing
- Compatibility validation

### Month 3: Documentation, Console Integration & Launch
**Week 9-10**
- Technical documentation writing
- User guide framework setup
- Console interface updates
- Community contribution guidelines development

**Week 11-12**
- UI/UX updates and integration completion
- Security and performance testing
- Quality assurance
- Launch and feedback collection

## Revised Budget Breakdown

### 1. Development & Integration

**Go Frameworks: $13,000 (130 hrs)**
- Framework setup & configuration: 50 hrs
- Deployment script development: 25 hrs
- Integration testing & optimization: 35 hrs
- Documentation & examples: 20 hrs

**Python Frameworks: $12,500 (125 hrs)**
- Framework environment configuration: 45 hrs
- Deployment automation: 30 hrs
- Package dependency management: 30 hrs
- Testing & validation: 20 hrs

**Ruby on Rails: $9,000 (90 hrs)**
- Framework configuration: 30 hrs
- Database & asset pipeline integration: 25 hrs
- Deployment workflow automation: 20 hrs
- Performance optimization: 15 hrs

**WordPress: $8,500 (85 hrs)**
- Core configuration setup: 20 hrs
- MySQL database integration: 25 hrs
- Deployment automation: 25 hrs
- Environment optimization: 15 hrs

### 2. Documentation & Console Integration

**Technical Documentation: $5,000 (50 hrs)**
- Akash docs core updates: 30 hrs
- Developer integration guides: 20 hrs

**UI Updates & Integration: $4,000 (40 hrs)**
- UI design revisions: 15 hrs
- Console integration: 25 hrs

**Community Contribution Framework: $3,000 (30 hrs)**
- Contribution guidelines: 15 hrs
- Template creation: 15 hrs

### 3. Quality Assurance

**Testing: $4,000 (40 hrs)**
- Critical path testing: 20 hrs
- Automated testing: 20 hrs

**Deployment Optimization: $3,000 (30 hrs)**
- Deployment scripts: 15 hrs
- Performance tuning: 15 hrs

### Total Breakdown
- Development & Integration: $43,000 (430 hrs)
- Documentation & UI Enhancements: $12,000 (120 hrs)
- Quality Assurance: $7,000 (70 hrs)
- **Grand Total: $62,000**

## Community Participation Framework

A key addition to Phase 2 will be the development of comprehensive guidelines and templates that enable community members to contribute to framework support expansion. This approach will:

- Prevent monopolistic control over deployment solutions
- Create pathways for community members to add support for new languages and frameworks
- Establish clear quality standards and testing requirements
- Provide technical documentation templates for consistent expansion

These guidelines will be developed in coordination with the Akash community, ensuring that they align with community values and technical capabilities.

## Benefits

### Expanded User Base
- Support for Go, Python, Ruby, and WordPress
- Broader developer attraction
- Increased project diversity

### Enhanced Versatility
- Support for diverse use cases
- Comprehensive framework coverage
- Improved deployment options

### Competitive Advantage
- Feature parity with centralized platforms
- Unique decentralized benefits
- Enhanced developer experience

### Community Empowerment
- Clear pathways for community contributions
- Documentation templates for consistent expansion
- Democratized framework support development

## Conclusion

Phase 2 will establish Akash Network as a comprehensive platform for decentralized deployments, offering developers across various ecosystems a powerful, versatile solution for their deployment needs. By reducing our budget while maintaining quality, and by establishing pathways for community contribution, we're building not just technical capabilities but a sustainable ecosystem for ongoing innovation.

Our team's participation in both the Steering Committee and SIG-Clients meetings has provided valuable insights that have shaped this proposal, ensuring alignment with the broader Akash Network vision and community needs. We're excited to continue this collaborative approach throughout the implementation phase.
