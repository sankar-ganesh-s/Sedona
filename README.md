# SEDONA INSURANCE WEB APPLICATION
## 1. Overview
### Objective
The Sedona Insurance Web Application was built to streamline General Liability and Property Insurance operations for Thoma Bravo LLC. Covering the full insurance lifecycle—from policy issuance to claims—it integrates key workflows with a responsive, cross-platform user experience. Built using React JS, Django, and REST APIs, the system enhances operational efficiency and supports agents, underwriters, and administrators.
         
# DEMO VIDEO FOR Application:



https://github.com/user-attachments/assets/ce79fc80-27a3-4b10-9308-b5d3263207ea



## Technology used
 * React JS: Front-end library used for building a responsive and dynamic user interface.
  * Django: Back-end web framework used to handle business logic, data models, and server-side processing.
  * REST API: Used to enable seamless communication between the front end and back end, supporting CRUD operations and integrations.
  * PostgreSQL: Relational database used for storing and managing structured insurance data securely and efficiently.
## 2. Key Features

### (i). Post-Issuance Feature Description:
 * The Post-Issuance feature allows users to make mid-term changes to an active insurance policy within its one-year duration. This includes updating forms, modifying coverage, and recalculating premiums based on the changes made. These updates are processed through a combination of custom-built logic components:
 * FormBasedPremiumCalculation handles recalculations based on newly added or modified policy forms.
 * EndorsementAdjustmentAlgorithm applies business rules to adjust coverage and ensure compliance during endorsements.
 *PremiumDifferenceEvaluator calculates the exact difference in premium between the original and updated policy.
 * The system then presents the revised premium and policy details to the user for confirmation. Once approved, the application activates the new policy and deactivates the previous one, ensuring a smooth, accurate transition without disrupting coverage.
         
### (ii). Cancel & Reinstate Feature:
 * The Cancel and Reinstate feature allows users to manage policy termination and reactivation efficiently during the policy term.
 * Cancellation: If a user chooses to cancel a policy before its expiry, the system calculates the earned premium based on the actual number of days the policy was active. The unused premium is then refunded accordingly, ensuring accurate pro-rata calculations.
 * Reinstatement: If the user decides to reinstate a previously canceled policy, the system recalculates the premium based on the remaining coverage period. The user is required to pay the adjusted premium for the reinstated duration, ensuring proper continuation of coverage.
 * This feature ensures financial accuracy, regulatory compliance, and user flexibility throughout the insurance lifecycle.

### (iii). Forms & Premium Calculation Feature:
 * The Forms Management feature in the Sedona Insurance Web Application is fully aligned with ISO (International Organization for Standardization) guidelines, ensuring compliance with industry-standard forms for General Liability and Property Insurance. Each policy form is dynamically selected and managed based on regulatory requirements, policy type, and coverage.
 * The premium calculation logic is state-specific, accurately determining premiums according to the rules and rates applicable in each U.S. state. This ensures precise pricing throughout the policy year, reflecting local regulations, form selections, and risk factors.

## 3. Benefits
 * Develop interactive dashboards for clients to monitor their insurance coverage, claims status, and risk exposure in real-time.
 * coverage for construction projects, including material damage and third-party liability.
 * Covers losses due to faults in construction, negligence, or natural disasters.
 * Clients can submit forms or emails anytime, from anywhere, without waiting for business hours.
## 4. Conclusion
The Sedona Insurance Web Application simplifies and automates key insurance processes for General Liability and Property coverage. With features like Post-Issuance updates, policy Cancellation and Reinstatement, and ISO-compliant form and premium handling, it ensures accurate, state-based premium calculations and smooth policy management.Built with React JS, Django, REST APIs, and PostgreSQL, the system offers a responsive experience, supports regulatory compliance, and improves efficiency for agents, underwriters, and users.
