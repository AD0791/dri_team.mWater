# Handwashing Observation

This survey is designed to evaluate hand hygiene (HH) compliance through observations at healthcare facilities.

## Three main sections:

Intro: Captures basic information about the healthcare facility, service area, ward, date, and the role of the person being observed.
Observations: Records specific hand hygiene observations, noting both the indication (when HH is required) and the action (whether HH was performed).
Comments: Allows additional notes or observations.
Key Survey Fields and Examples:
Health Facility Location: Identifies the facility being assessed (linked with its mWater ID).

Date: The date of the observation, which is essential for time-based analysis.

Role of Person Being Observed: Specifies the role (e.g., Medical Doctor, Nurse) and may include a sub-role (e.g., Consultant).

Example:

Role: Medical Doctor
Sub Role: Consultant
Observations:

Each observation includes:
Indication: Reason or moment when HH is expected (e.g., after body fluid exposure risk).
HH Action: The action taken, such as HW for Hand Wash.
Example:

Indication: aft-b-s (after body fluid exposure risk)
HH Action: HW (Hand Wash)

## Calculation Metrics

The survey calculations help assess hand hygiene compliance at each facility:

### HH Compliance

Calculation Name: HH compliance
Source: Derived from the Observation field under HH Action
Purpose: Evaluates the percentage of correct hand hygiene actions performed against the required indications.

### HH Assessed

Calculation Name: HH assessed
Source: Similar to HH compliance, it uses Observation > HH Action to identify all opportunities for hand hygiene.
Purpose: Counts all hand hygiene events observed, including those performed and missed.

### Compliance Numerator

Definition: The total count of HH actions that comply with hand hygiene guidelines (actions performed correctly).
Source: Derived from observations where HH Action meets compliance standards (e.g., handwashing when required).

### Compliance Denominator

Definition: The total opportunities for hand hygiene based on all observed indications, whether performed or missed.
Purpose: Acts as the baseline for assessing compliance.

### Compliance (%)

Calculation Formula: (Compliance Numerator / Compliance Denominator) * 100
Purpose: Provides the percentage of correct hand hygiene actions performed out of the total opportunities, giving an overall compliance score for a facility or a set of observations.
Interpretation: Higher percentages indicate better adherence to hand hygiene protocols.
