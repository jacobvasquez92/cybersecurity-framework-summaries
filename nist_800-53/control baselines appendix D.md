# Control Baselines (Appendix D) and their Relevance 🛡️
### The NIST SP 800-53 Control Baselines (Appendix D) are designed to make the selection of security controls more efficient and consistent. They provide a starting point for organizations to apply a minimum set of controls based on the system's impact level.

***



The control baselines are directly tied to the RMF's **Categorize** and **Select** steps. The audience for this section includes anyone involved in system categorization and control selection.

### **Audience**
* **System and Mission Owners:** They are responsible for categorizing the system's impact and are the primary users of the baselines to choose the correct starting point for security.
* **Security Professionals & Architects:** They use the baselines to design the system's security architecture and ensure that a foundational level of protection is in place.
* **Auditors and Assessors:** They use the baselines as a checklist to verify that the minimum required controls have been implemented for a system of a given impact level.

### **Relevance to Cybersecurity**

The control baselines are a practical application of a risk-based approach to cybersecurity. They are designed to match the level of security to the level of risk, ensuring that resources are allocated effectively.

* **Low Impact Baseline:**
    * **Relevance:** This baseline is for systems where the loss of confidentiality, integrity, or availability would have a limited adverse effect on the organization. It represents a minimal, but still significant, set of security controls.
    * **Example:** A public-facing website with no sensitive data.

* **Moderate Impact Baseline:**
    * **Relevance:** This is the most common baseline and is used for systems where the loss of C, I, or A would have a serious adverse effect. It includes a more comprehensive set of controls than the low baseline.
    * **Example:** A database containing non-public organizational information or operational data.

* **High Impact Baseline:**
    * **Relevance:** This baseline is for systems where the loss of C, I, or A would have a severe or catastrophic adverse effect. It includes the most rigorous and extensive set of controls to protect mission-critical data and services.
    * **Example:** A system managing classified information, critical infrastructure, or sensitive medical records.

* **Privacy Control Baseline:**
    * **Relevance:** This baseline, which is independent of the system's impact level, focuses specifically on protecting personally identifiable information (PII). It ensures that privacy risks are addressed regardless of the system's security categorization.
    * **Example:** A human resources system that stores employee PII.

By providing these baselines, NIST helps organizations avoid "security theater" by focusing on the controls that truly matter for the system's risk profile, while also ensuring consistency across an enterprise.
