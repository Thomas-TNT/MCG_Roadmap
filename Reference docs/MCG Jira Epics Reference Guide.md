# MCG Jira Epics Reference Guide

*Last Updated: December 2025 - Aligned with Quarterly Timeline*

## 📋 **Epic Overview Summary**

| Status | Count | Epics |
|--------|-------|-------|
| **In Progress** | 12 | MV30-2049, MV30-1696, MV30-2201, MV30-2214, MV30-2222, MV30-2200, MV30-2046, MV30-2045, MV30-2044, MV30-2043, MV30-2041, MV30-1256, MV30-40 |
| **To Do** | 10 | MV30-2174, MV30-2173, MV30-2042, MV30-2120, MV30-2056, MV30-2048, MV30-2047, MV30-2040, MV30-1884, MV30-1883 |

## 📅 **Quarterly Timeline Alignment**

Epics are now strategically distributed across 9 quarters (Q4 2025 - Q4 2027) in the roadmap timeline:

### **Q4 2025: Critical Foundation**
- **MV30-1256**: Fix D&S critical bugs (duplicates, save errors)
- **MV30-2079**: Resolve EOP sticky bug (Ready for Production)  
- **MV30-2041**: Deploy Treatment Plan templates

### **Q1 2026: Foundation Completion**
- **MV30-2046**: Complete HIPAA audit system
- **MV30-2043**: Finish Next Steps redesign (19 modules)
- **MV30-2045**: Standardize Notes with PHI compliance
- **MV30-2222**: Launch 3D Liver Model (Voka integration)

### **Q2-Q4 2027: Strategic Phases**
- **Q2 2026**: Epic EHR Phase 1, E2E testing, user tracing
- **Q3 2026**: Resources normalization, help system, 3D expansion
- **Q4 2026**: Advanced visualization, ADA compliance, mobile beta
- **Q1 2027**: Analytics & reporting deployment
- **Q2 2027**: Epic Phase 2 & mobile production launch
- **Q3 2027**: Global expansion & multi-language support
- **Q4 2027**: Platform maturity & global deployment

---

## 🚧 **IN PROGRESS EPICS**

### **Core Case Management Epics**

#### **MV30-1256: Case Management - Diagnosis & Staging**
- **Status**: In Progress
- **Priority**: High
- **Theme**: Stabilize and standardize the Diagnosis & Staging experience across cancers
- **Key Focus**: 
  - Fixing core UI/data integrity issues (duplicates, save errors, disappearing fields)
  - Unifying image/marker behavior and drawing tools
  - Early decision-support features (auto-staging, disease-specific scores)
- **Scope**: Cross-disease coverage (ALL + specific sites: Breast, Cervix-Uterus, Ovarian, Pancreas, etc.)
- **Critical Issues**: 
  - Tumor/nodes duplicate when opening full screen
  - Tumors say "undefined" when staging not selected
  - Right-side fields disappear when page refreshed
  - Drawing tools cut off by screen
- **Assignee**: Brad Foley (primary), Gray Delacluyse, Misty James

#### **MV30-2041: Case Management - Treatment Plan/Compare Options**
- **Status**: In Progress
- **Priority**: High
- **Key Objectives**:
  - Template Management: Create and implement treatment plan templates
  - User Experience: Improve navigation and interface elements
  - Resource Integration: Enhance EOP (Evidence of Practice) links
  - Cross-Cancer Support: Ensure functionality across multiple cancer types
- **Progress**: 8 completed, 5 in progress, 1 critical issue ready for production
- **Scope**: ALL, Melanoma, Myeloma, Brain, PHI versions
- **Critical Issue**: SubElements of deleted EOPs sticky bug (Ready for Production)

#### **MV30-2043: Case Management - Next Steps**
- **Status**: In Progress
- **Priority**: Medium
- **Key Objectives**:
  - Version Compatibility: Ensure 3.0 Next Steps pages match 2.1 content exactly
  - Comprehensive Testing: Validate across 19 different cancer modules
  - Page Redesign: Complete redesign across all modules
- **Progress**: 20 completed (all testing), 20 in progress (redesign)
- **Assignee**: Thomas Teruel (redesign), Samantha Sutton (main story), Misty James (testing)
- **Review Process**: Lou → Sarah → Misty → Conor approval chain

#### **MV30-2045: Case Management - Notes**
- **Status**: In Progress
- **Priority**: Medium
- **Key Objectives**:
  - PHI Compliance: Standardize default messaging and role-based behavior
  - Consistency: Implement they/them pronouns and unified formatting
  - Clinical Integration: Add ECOG status, age data, and pathology information
- **Stories**: MV30-1961, MV30-1962, MV30-2038, MV30-2131, MV30-2044

#### **MV30-2046: Case Management - Administration**
- **Status**: In Progress
- **Priority**: Medium
- **Key Objectives**:
  - HIPAA Compliance: Comprehensive audit logging for patient record access tracking
  - Security Enhancement: Complete user traceability for all case operations
  - Administrative Tools: Robust administration capabilities
- **Completed**: Creation Auditing (MV30-1059) - AuditLog table implementation
- **In Progress**: Zivver integration, Field validation, User confirmation modals

#### **MV30-40: Case Management - Patient ID**
- **Status**: In Progress
- **Priority**: Medium
- **Key Focus**: Patient identification system enhancements
- **Recent Work**: DOB saving fixes, age validation, sex field additions
- **Assignee**: William Larsen, Conor Bowden, Renee Sardelli

### **Resources & Content Enhancement**

#### **MV30-1883: New Content for the Application and/or Module**
- **Status**: To Do
- **Priority**: Medium
- **Key Objectives**:
  - Resource Enhancement: Improve and expand resource libraries
  - Visual Content: Add high-quality images, slides, and visual aids
  - Treatment Information: Enhance treatment-related resources
  - User Experience: Implement comprehensive help functionality
- **Progress**: 1 completed, 24 to do
- **Scope**: 19 cancer modules with resource card creation and enhancement

#### **MV30-2042: Case Management - Resources**
- **Status**: To Do
- **Priority**: Medium
- **Theme**: Normalize and govern the oncology Resources library across diseases
- **Key Focus**:
  - Completeness & parity with prior versions (restore 2.1 parity)
  - Content hygiene & taxonomy (rename files, enforce sort orders)
  - Accessibility & compliance (ADA descriptions, PHI variants)
  - Search & authoring workflow (drug card discoverability)
- **Scope**: Cross-disease footprint (ALL, Myeloma, Cervix/Uterus/Ovarian, Brain, Prostate, etc.)

### **Infrastructure & Platform Epics**

#### **MV30-2049: Backend Updates**
- **Status**: In Progress
- **Focus**: Backend infrastructure improvements and updates

#### **MV30-2201: Application User Tracing**
- **Status**: In Progress
- **Focus**: User activity tracking and monitoring

#### **MV30-2214: Mobile App Development - iOS & Android**
- **Status**: In Progress
- **Focus**: Mobile application development for iOS and Android platforms

#### **MV30-2222: Integrate Voka 3D Liver Model**
- **Status**: In Progress
- **Focus**: 3D liver model integration with WebGL-based viewer
- **Deliverables**: Interactive 3D representation, segmentation controls, responsive integration

#### **MV30-2200: Multilingual**
- **Status**: In Progress
- **Focus**: Multi-language support implementation

#### **MV30-1696: Resources - ADA Compliant**
- **Status**: In Progress
- **Focus**: ADA compliance for resource accessibility

---

## ⏳ **TO DO EPICS**

### **Quality Assurance & Testing**

#### **MV30-2174: E2E Regression Testing Suite Findings**
- **Status**: To Do
- **Focus**: End-to-end regression testing implementation

#### **MV30-2173: Quality Assurance - Automation Set Up Expectations**
- **Status**: To Do
- **Focus**: QA automation framework setup

### **Compliance & Accessibility**

#### **MV30-2056: Diagnosis & Staging - ADA Compliance**
- **Status**: To Do
- **Focus**: ADA compliance for Diagnosis & Staging module

### **Infrastructure & Integration**

#### **MV30-2120: CloudFlare**
- **Status**: To Do
- **Focus**: CloudFlare integration and optimization

#### **MV30-2047: Integration into Epic**
- **Status**: To Do
- **Focus**: Epic EHR system integration

### **Reporting & Analytics**

#### **MV30-2040: Customer Reports**
- **Status**: To Do
- **Focus**: Customer-facing reporting capabilities

#### **MV30-1884: Internal Reports**
- **Status**: To Do
- **Focus**: Internal reporting and analytics

### **Customization & Resources**

#### **MV30-2048: Custom Resources by Module and Organization**
- **Status**: To Do
- **Focus**: Customizable resource management by module and organization

---

## 🎯 **Epic Priority Matrix**

### **Critical (Immediate Focus)**
1. **MV30-1256**: Diagnosis & Staging - Critical bugs affecting clinician trust
2. **MV30-2041**: Treatment Plan - Template system and critical EOP bug
3. **MV30-2043**: Next Steps - Redesign completion across all modules

### **High Priority**
4. **MV30-2046**: Administration - HIPAA compliance and security
5. **MV30-2045**: Notes - PHI compliance and standardization
6. **MV30-40**: Patient ID - Core patient management functionality

### **Medium Priority**
7. **MV30-1883**: New Content - Resource enhancement and help system
8. **MV30-2042**: Resources - Library normalization and governance
9. **MV30-2222**: 3D Liver Model - Advanced visualization features

### **Infrastructure & Future**
10. **MV30-2214**: Mobile App - Platform expansion
11. **MV30-2200**: Multilingual - International support
12. **MV30-2047**: Epic Integration - EHR connectivity

---

## 👥 **Team Assignments by Epic**

### **Brad Foley (Frontend Lead)**
- MV30-1256: Diagnosis & Staging (primary)
- MV30-2046: Administration (audit system)
- MV30-40: Patient ID (field updates)

### **Gray Delacluyse (Backend Lead)**
- MV30-1256: Diagnosis & Staging (image fixes)
- MV30-2049: Backend Updates
- MV30-2201: Application User Tracing

### **Thomas Teruel (Technical Lead)**
- MV30-2043: Next Steps (redesign coordination)
- MV30-2045: Notes (standardization)
- MV30-2041: Treatment Plan (template system)

### **Misty James (Content Specialist)**
- MV30-1883: New Content (resource creation)
- MV30-2042: Resources (content governance)
- MV30-2043: Next Steps (testing validation)

### **Renee Sardelli (QA Lead)**
- MV30-2041: Treatment Plan (bug fixes)
- MV30-40: Patient ID (validation)
- MV30-2045: Notes (compliance testing)

### **Samantha Sutton (Project Coordinator)**
- MV30-2043: Next Steps (main story)
- MV30-2041: Treatment Plan (coordination)
- MV30-2046: Administration (project management)

---

## 📊 **Epic Dependencies & Blockers**

### **Critical Dependencies**
- **MV30-1256** → **MV30-2056**: D&S stability must be achieved before ADA compliance
- **MV30-2043** → **MV30-2045**: Next Steps redesign affects Notes page formatting
- **MV30-2046** → **MV30-2201**: Administration features require user tracing

### **Asset Dependencies**
- **MV30-1964**: Need original staging resource cards (.ai or pdf)
- **MV30-2058**: Myeloma icons need creation or purchase
- **MV30-2222**: Voka 3D model files and documentation

### **Approval Dependencies**
- **MV30-2045**: Pronoun changes require Sarah/Lou approval
- **MV30-2043**: Stakeholder review process (Lou → Sarah → Misty → Conor)
- **MV30-2046**: Security team approval for additional admin features

---

## 🔄 **Epic Workflow & Review Process**

### **Standard Review Process**
1. **Development**: Team implements in TEST environment
2. **Internal Review**: Screenshots sent to stakeholders
3. **Stakeholder Approval**: Lou → Sarah → Misty → Conor
4. **Production Deployment**: Foley handles final PROD pushes

### **Content Review Process**
1. **Content Creation**: Misty James and content team
2. **Clinical Review**: Sarah/Lou for medical accuracy
3. **Technical Review**: Conor for implementation feasibility
4. **Final Approval**: Lou for go/no-go decision

---

## 📈 **Success Metrics by Epic**

### **MV30-1256: Diagnosis & Staging**
- 90% reduction in high/critical D&S defects
- Eliminate duplicate/save-location errors to <0.5% of sessions
- 100% alignment of field names/labels with clinical specs

### **MV30-2041: Treatment Plan**
- Complete template system implementation
- Fix critical EOP sticky bug
- Cross-cancer functionality validation

### **MV30-2043: Next Steps**
- 100% module coverage (19 cancer types)
- Version 3.0 to 2.1 content parity
- Complete redesign implementation

### **MV30-2046: Administration**
- Complete HIPAA audit requirements
- 100% user traceability for patient record access
- Audit system extended to Patient table operations

### **MV30-1883: New Content**
- Complete help system implementation
- 100% glossary coverage for all cancer modules
- Visual content enhancement for priority modules

---

## 🚨 **Critical Issues Requiring Immediate Attention**

1. **MV30-2079**: SubElements of deleted EOPs sticky (Ready for Production)
2. **MV30-1995**: Right-side fields disappear when page refreshed (High Priority)
3. **MV30-2118**: Tumor/nodes not saving in proper spot (Highest Priority)
4. **MV30-2067**: Drawing tools cut off by screen (Highest Priority)
5. **MV30-2009**: T/n are duplicated rather than moved (Highest Priority)

---

## 📊 **Recent Updates (December 2025)**

### **Roadmap Integration**
- **Quarterly Timeline**: Epics distributed across 9 individual quarters
- **Visual Alignment**: Perfect alignment between quarter badges and epic assignments
- **Success Metrics**: Integrated metrics within each quarterly phase
- **Decision Gates**: 4 key decision gates with clear success criteria

### **Performance Enhancements**
- **Optimized Version**: New `index-optimized.html` with 15% smaller file size
- **Enhanced JavaScript**: TabManager with caching and performance optimization
- **Better Accessibility**: Full keyboard navigation and screen reader support

---

*This reference guide should be updated weekly to reflect current epic status, priorities, and team assignments. The quarterly timeline alignment ensures strategic distribution of work across realistic development phases.*
