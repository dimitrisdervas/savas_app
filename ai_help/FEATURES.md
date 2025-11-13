# Current Features

## 1. Metabolic Syndrome Assessment (IDF Criteria)
- Central obesity measurement (waist circumference)
- European population cutoffs (≥94cm men, ≥80cm women)
- Four additional criteria: triglycerides, HDL, blood pressure, fasting glucose
- Treatment status tracking (lipid/sugar/hypertension medications)
- Automatic diagnosis based on IDF criteria

## 2. BMI Calculator
- Auto-calculation from height & weight
- Categories: Underweight | Normal | Overweight | Obese
- Color-coded results

## 3. Cardiovascular Risk Calculators

### SCORE2 (Non-diabetics, ages 40-69)
- European Society of Cardiology 2021 guidelines
- Moderate-risk region calibration (Greece)
- Age-specific risk categories
- 10-year CV death risk

### SCORE2-OP (Non-diabetics, ages 70-89)
- Older persons variant
- Separate coefficients for elderly population
- Age-adjusted risk thresholds

### SCORE2-Diabetes (Diabetics)
- HbA1c parameter integration
- eGFR parameter integration
- Age of diabetes diagnosis tracking
- Four risk categories (Low | Moderate | High | Very High)

### ASCVD (Pooled Cohort Equations)
- 10-year atherosclerotic CVD risk
- Sex-specific calculations
- Ages 40-79
- US-based algorithm

### HellenicSCORE II+ (Greek-calibrated SCORE2 with Lp(a) & Diabetes)
- Greece-specific calibration using Attica study population data
- Based on SCORE2 moderate-risk coefficients
- Automatic diabetes adjustment factors:
  - Men: ×1.39 (55-190% increased risk by age)
  - Women: ×1.48 (27-118% increased risk by age)
- Automatic Lp(a) adjustment (if >30 mg/dL):
  - Men: ×1.29 (30-45% increased risk by age)
  - Women: ×1.31 (43-77% increased risk by age)
- Age range: 40-69 years
- Combines both fatal & non-fatal CV events
- Greek population means by age/sex from Table 1 (Attica study):
  - SBP, TC, HDL, smoking prevalence interpolated for precise calibration
- Risk categories:
  - <50 yrs: Low <2.5%, Moderate 2.5-7.5%, High >7.5%
  - 50-69 yrs: Low <5%, Moderate 5-10%, High >10%
- Side-by-side display with standard SCORE2 for comparison
- Shows base risk → adjusted risk with applied multipliers
- Color-coded risk stratification
- Reference: Panagiotakos et al., Hellenic Journal of Cardiology 2024

## 4. Kidney Function Assessment

### eGFR Calculation (CKD-EPI 2021)
- Automatic calculation from serum creatinine
- Age & sex-adjusted
- No race adjustment (2021 update)
- G1-G5 staging w/ color coding
- Real-time calculation

### ACR (Albumin-to-Creatinine Ratio)
- Dual unit support (mg/dL or mmol/L for urine creatinine)
- Automatic conversion
- A1-A3 staging
- Albuminuria severity classification (Normal | Microalbuminuria | Macroalbuminuria)

### KDIGO Matrix (6×3 Risk Grid)
- Visual GFR × ACR risk stratification
- Color-coded cells (green/yellow/orange/red)
- Automatic checkmark placement based on values
- Four risk levels (Low | Moderate | High | Very High)
- Interactive grid display

## 5. Lipoprotein(a) Assessment
- Dual unit support (mg/dL or nmol/L)
- Four risk categories (<30 | 30-50 | >50 | >100)
- Color-coded risk levels (green/yellow/orange/red)
- Automatic unit conversion

## 6. ESC 2023 LDL-C Therapeutic Targets
- Personalized targets based on calculated CV risk
- Three tiers: <55 | <70 | <100 mg/dL
- Automatic recommendation in report
- Risk-stratified approach

## 7. User Interface Features
- Dark theme optimized for medical use
- Keyboard navigation (Enter key to advance fields)
- Grid layout for efficient data entry
- Reference ranges displayed inline
- Real-time auto-calculations
- Conditional field display (diabetes-specific fields appear when needed)
- Auto-sync between duplicate fields (eGFR)

## 8. Report Generation
- Comprehensive text report w/ all results
- Color-coded risk categories
- Dotted-line formatting for readability
- Timestamp inclusion
- Print-optimized layout
- Report stacking (multiple patient reports in one session)
- Copy-paste friendly format

## 9. Workflow Features
- Clear form button (reset all fields)
- Clear all reports button (stack management)
- Print-ready output
- No external dependencies (offline-capable)
- Single-file deployment
- Greek language interface
