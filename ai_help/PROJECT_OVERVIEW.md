# Project Overview

## Project Identity
**Name:** Holistic Cardio-Nephro-Metabolic Risk Assessment Calculator
**Primary User:** Dr. Savas Yialavouzis (General Family Physician)
**Target Audience:** Greek-speaking medical professionals
**Language:** Greek (interface & terminology)

## Project Type
**Architecture:** Single-page HTML application
**Tech Stack:** HTML5 | CSS3 | Vanilla JavaScript
**Dependencies:** None (self-contained)
**Deployment:** Single file (`metabolic_full_with_targets.html`)
**Runtime:** Browser-based (offline-capable)

## Clinical Foundation

### Evidence-Based Guidelines
- **SCORE2** (ESC 2021) - CV risk for non-diabetics 40-69
- **SCORE2-OP** (ESC 2021) - CV risk for non-diabetics 70-89
- **SCORE2-Diabetes** (ESC 2021) - CV risk for diabetics
- **ASCVD** (Pooled Cohort Equations) - US-based CV risk
- **CKD-EPI 2021** - Kidney function (no race adjustment)
- **KDIGO** - CKD staging & risk stratification
- **ESC 2023** - Dyslipidemia & LDL-C targets
- **IDF** - Metabolic syndrome (European cutoffs)

### Risk Calibration
**Region:** Moderate-risk (Greece)
**Population:** European cutoffs for waist circumference
**Age Range:** 40-89 years (CV risk calculators)

## Technical Characteristics

### Architecture
- Standalone HTML file
- No build system required
- No package managers
- No external API calls
- Zero runtime dependencies

### Design Philosophy
- **Print-first:** Optimized for physical records
- **Offline-capable:** No internet required
- **Self-contained:** All logic embedded
- **Fast:** Instant calculations
- **Accessible:** Keyboard navigation

### Data Flow
1. User enters patient data via form
2. Real-time auto-calculations on input
3. Risk stratification algorithms execute
4. Color-coded results display
5. Comprehensive report generation
6. Print-ready output

### UI/UX Features
- Dark theme (reduced eye strain)
- Grid layout (efficient data entry)
- Conditional field display (diabetes-specific)
- Reference ranges inline
- Color-coded risk categories
- Dotted-line report formatting

## Deployment Model
**Distribution:** Single HTML file
**Installation:** Copy to any location
**Execution:** Open in browser (Chrome | Firefox | Safari | Edge)
**Updates:** Replace file
**Backup:** Standard file copy

## Version Control
**Repository:** Git initialized (no commits yet)
**Location:** `/Users/dimitris/Apps/savas/`

## Clinical Workflow Integration

### Typical Use Case
1. Patient visit → Enter vital signs & lab values
2. Calculator → Auto-computes all risk scores
3. Review → Assess color-coded risk stratification
4. Decision → Apply ESC 2023 LDL-C targets
5. Report → Print for patient record
6. Next patient → Clear form & repeat

### Output Use
- Patient medical records (printed)
- Treatment decision support
- Patient education & counseling
- Longitudinal risk tracking
- Quality improvement documentation

## Scope
**In Scope:**
- CV risk assessment
- Kidney function evaluation
- Metabolic syndrome screening
- LDL-C target recommendations
- BMI calculation
- Lipoprotein(a) assessment

**Out of Scope:**
- Electronic health record integration
- Patient data storage/database
- Multi-user access control
- Cloud synchronization
- Mobile app version
- Treatment tracking over time

## Maintenance Model
**Update Triggers:**
- New guideline releases (ESC, KDIGO, etc.)
- Bug fixes
- Feature requests from Dr. Yialavouzis
- User feedback

**Update Process:**
- Edit HTML file
- Test calculations
- Replace deployed version

## Future Considerations
- Potential database integration
- Longitudinal tracking
- Additional risk calculators
- Multi-language support
- Mobile optimization
