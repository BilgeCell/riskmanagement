# riskmanagement
MSc Cyber Security: Risk Management Executive Summary
Project: Digitalisation & Global Supply Chain Risk Assessment (Pampered Pets)

# 📌 Overview
This repository contains the strategic risk assessment and technical documentation for Pampered Pets, a premium pet food provider undergoing a global digital transformation. The project evaluates the impact of international supply chains and automated warehouses on product quality and availability, specifically addressing the concerns of high-profile stakeholders.

Context: University of Essex, MSc Cyber Security - Risk Management (Unit 11 Assessment).

# 📂 Repository Structure
ExecutiveSummary.pdf: The core strategic report outlining quantified risks, financial/reputational impacts, and executive recommendations.

Appendix_A_Methodology.pdf: Detailed technical breakdown of the quantitative models, assumptions, and data sources used.

MonteCarlo_Model_PamperedPets.xlsx: The functional stochastic model used to calculate availability risks through 10,000 iterations.

README.md: Project overview and repository guide.

# ⚙️ Methodology & Modelling
The assessment utilizes a hybrid quantitative approach to provide high-fidelity risk estimates:

Monte Carlo Simulation (Availability Risk):

Iterations: 10,000 plausible operational scenarios.

Variables: International logistics volatility, warehouse automation downtime (MTBF/MTTR), and demand surges.

Key Result: Estimated 11.8% probability of a stockout exceeding 48 hours in Year 1.

Scenario-Based Probability (Quality Risk):

Focus: Probability of a "Quality Escape" reaching premium customers.

Key Result: Estimated 6.5% annual probability of a quality incident without additional controls.

# 🛡️ Strategic Solutions & Compliance
The proposed risk treatment plan is aligned with international standards and technical best practices:

Disaster Recovery: AWS-based Active-Active multi-region architecture to meet the mandatory <1 minute RTO/RPO requirement.

Vendor Lock-in Mitigation: Use of Infrastructure as Code (Terraform) and Containerisation (Kubernetes) for platform portability.

Standards: Built upon ISO 31000:2018 (Risk Management) and ISO/IEC 27005 (Information Security Risk).

Data Protection: Fully compliant with UK GDPR and emerging EU AI Act (2024) governance for automated decision-making.

#  How to Use the Model
To verify the quantitative results:

Open MonteCarlo_Model_PamperedPets.xlsx.

Navigate to the Simulation sheet to view the 10,000 iterations.

Adjust parameters in the Parameters table to see real-time sensitivity analysis for stockout probabilities.
