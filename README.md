# Adversarial Analysis and Security Taxonomy of Blockchain Systems
**A Comprehensive Survey of Consensus Attacks, MEV, and Emerging Defenses**

A comprehensive adversarial analysis and 5-layer security taxonomy of blockchain consensus, MEV, and smart contracts. Grounded in the review of 30+ IEEE/ACM papers (2018–2025) focusing on the Integrity and Availability of decentralized service networks.

### **Authors**
* [cite_start]**Karthikeya Moturi** – University of South Florida [cite: 2, 3]
* [cite_start]**Ravuri Sivaram** – University of South Florida [cite: 19, 20]

---

## **Project Overview**
[cite_start]As blockchain technology expands into critical infrastructure—including **5G service networks**, **IoT**, and the **Metaverse**—the attack surface has shifted from simple double-spending to complex, multi-layer vulnerabilities[cite: 5, 6, 15, 186]. [cite_start]This project presents a structured adversarial analysis and security taxonomy based on a rigorous review of 30 peer-reviewed publications spanning 2018–2025[cite: 7, 246].

[cite_start]Our research addresses the **Integrity** and **Availability** pillars of the CIA triad, analyzing how consensus protocols respond to targeted cyber-attacks in high-stakes environments[cite: 32, 248].

---

## **Repository Structure**
* [cite_start]**`/Documentation`**: Contains the [Final Report](./Documentation/Final_Report.pdf) and [Research Proposal](./Documentation/Research_Proposal.pdf)[cite: 34, 35].
* [cite_start]**`/Taxonomy`**: High-resolution diagrams of our [Five-Layer Security Taxonomy](./Taxonomy/Figure1_Taxonomy.png)[cite: 59, 67].
* [cite_start]**`/References`**: Complete list of the [30 IEEE Bibliography](./References/bibliography.md) used in this study[cite: 246, 257].

---

## **Key Research Components**

### **1. Five-Layer Security Taxonomy**
[cite_start]We categorize the threat landscape into five distinct layers to provide a "Defense-in-Depth" perspective[cite: 8, 56, 59]:
* [cite_start]**Layer 1: Network & Propagation** – Focuses on Race, Sybil, and Eclipse attacks[cite: 62, 69, 72].
* [cite_start]**Layer 2: Consensus & Mining** – Analyzes 51% attacks, Selfish Mining, and Goldfinger variants[cite: 60, 103, 106].
* [cite_start]**Layer 3: Smart Contract & Execution** – Examines reentrancy, timestamp manipulation, and the upgradability paradox[cite: 60, 129, 141].
* [cite_start]**Layer 4: Transaction Ordering & MEV** – Investigates Front-running, Back-running, and Sandwich attacks[cite: 60, 151, 154].
* [cite_start]**Layer 5: Hardware & IoT** – Anchors security in physical chips (TPM/PUF) to mitigate resource-constrained threats[cite: 60, 186, 190].

### **2. Technical Comparisons (Head-to-Head)**
[cite_start]The study conducts three rigorous comparisons of competing defensive frameworks[cite: 9, 10, 191]:
* [cite_start]**Timelock Shield vs. PACC**: Evaluating VDF-based content hiding against collateralized commit-reveal schemes for **MEV defense**[cite: 192, 198, 201].
* [cite_start]**PUFchain vs. HA-CAAP**: Comparing hardware-assisted device authentication against continuous behavioral attestation for **IoT security**[cite: 204, 210, 211].
* [cite_start]**5G AKA vs. appXchain**: Analyzing formally verified network protocols against application-level interoperability solutions[cite: 214, 218, 219].

### **3. Major Findings**
* [cite_start]**Network Resilience**: Empirical evidence shows that knowledge of network topology can raise the success rate of a Race attack from **12% to over 60%**[cite: 65, 78].
* [cite_start]**Security Gains**: Formal analysis of a blockchain-integrated 5G AKA protocol confirmed a **60% improvement** in satisfied security properties[cite: 24, 250].
* [cite_start]**Systemic Bias**: Analysis of over 36 million Ethereum transactions confirmed that **90.6% of blocks** are produced by MEV relay infrastructure[cite: 162, 163, 231].

---

## **Future Research Directions**
[cite_start]Our analysis identifies several open challenges for the next generation of decentralized infrastructure[cite: 33, 222, 252]:
1. [cite_start]**Post-Quantum Migration**: Implementing NIST-standardized algorithms to defend against quantum-era cryptographic breaches[cite: 51, 251].
2. [cite_start]**AI-Augmented Security**: Utilizing Generative AI for anomaly detection while defending against AI-generated adversarial sequences[cite: 237, 238, 239].
3. [cite_start]**Formal Verification**: Expanding Petri-net and process algebra modeling to cover complex DeFi composition and cross-contract interactions[cite: 148, 241, 252].

---

## **References**
[cite_start]This survey is grounded in a corpus of 30 academic papers[cite: 7, 246], including:
* [cite_start]**Narwal et al.**, "Evaluating the impact of consensus mechanisms on blockchain-based data security," IEEE DELCON, 2024[cite: 39, 258].
* [cite_start]**Mohanty et al.**, "PUFchain: A hardware-assisted blockchain for sustainable simultaneous device and data security," IEEE Consumer Electronics Magazine, 2020[cite: 187, 290].
* [cite_start]**Arote & Kuri**, "A study of double-spending causes and countermeasures in Bitcoin network," IEEE BCCA, 2024[cite: 269].

---

### **License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
