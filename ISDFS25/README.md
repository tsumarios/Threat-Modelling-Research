# To See or Not to See: A Privacy Threat Model for Digital Forensics in Crime Investigation

This folder contains the outcomes for the paper "To See or Not to See: A Privacy Threat Model for Digital Forensics in Crime Investigation".

## Abstract

Digital forensics is a cornerstone of modern crime investigations, yet it raises significant privacy concerns due to the collection, processing, and storage of digital evidence. Despite that, privacy threats in digital forensics crime investigations often remain underexplored, thereby leading to potential gaps in forensic practices and regulatory compliance, which may then escalate into harming the freedoms of natural persons.
With this clear motivation, the present paper applies the SPADA methodology for threat modelling with the goal of incorporating privacy-oriented threat modelling in digital forensics.
As a result, we identify a total of 298 privacy threats that may affect digital forensics processes through crime investigations. Furthermore, we demonstrate an unexplored feature on how SPADA assists in handling domain-dependency during threat elicitation. This yields a second list of privacy threats that are universally applicable to any domain.
We also discuss some of the challenges about validating privacy threats in this domain, particularly given the variability of legal frameworks across jurisdictions.
We ultimately propose our privacy threat model as a tool for ensuring ethical and legally compliant investigative practices.

---

## Repository Structure

The files in this repository are organised following the chronological order of the SPADA methodology application.

### Step 1 - Domain-Independent Threat Elicitation

- [1-dfci_Step1.csv](https://github.com/tsumarios/Threat-Modelling-Research/blob/main/ISDFS25/1-dfci_Step1.csv): Initial collection of privacy threats from relevant document sources.  
- [2-dfci_Step1-Pre-Identified-DD-and-Derived-DI-Threats.csv](https://github.com/tsumarios/Threat-Modelling-Research/blob/main/ISDFS25/2-dfci_Step1-Pre-Identified-DD-and-Derived-DI-Threats.csv): List of pre-identified domain-dependent threats and derived domain-independent threats before refinement.  
- [3-dfci_Step1-input_threats_TEAM.csv](https://github.com/tsumarios/Threat-Modelling-Research/blob/main/ISDFS25/3-dfci_Step1-input_threats_TEAM.csv): Raw input list of threats before applying the TEAM 3 algorithm for refinement.  
- [4-dfci_Step1-output_threats_TEAM.csv](https://github.com/tsumarios/Threat-Modelling-Research/blob/main/ISDFS25/4-dfci_Step1-output_threats_TEAM.csv): Output list of threats after applying the TEAM 3 algorithm (merged and refined threats).  
- [5-dfci_Step1-Post-Identified-DD-and-Derived-DI-Threats.csv](https://github.com/tsumarios/Threat-Modelling-Research/blob/main/ISDFS25/5-dfci_Step1-Post-Identified-DD-and-Derived-DI-Threats.csv): Finalized list of domain-dependent and domain-independent threats after refinement.  

### Step 2 - Domain-Dependent Asset Collection

- [6-dfci_Step2-CollectedAssets.csv](https://github.com/tsumarios/Threat-Modelling-Research/blob/main/ISDFS25/6-dfci_Step2-CollectedAssets.csv): List of assets identified as relevant for digital forensics in crime investigation.  
- [7-dfci_Step2-CollectedAssetGroups.csv](https://github.com/tsumarios/Threat-Modelling-Research/blob/main/ISDFS25/7-dfci_Step2-CollectedAssetGroups.csv): Asset groups derived from the collected assets (higher-level categorization).

### Step 3 - Domain-Dependent Threat Elicitation

- [8-dfci-Step3.csv](https://github.com/tsumarios/Threat-Modelling-Research/blob/main/ISDFS25/8-dfci-Step3.csv): Threats instantiated with domain-specific assets based on SPADA methodology.

### Privacy Threat Model for DFCI

- [9-dfci-PrivacyThreatModel.csv](https://github.com/tsumarios/Threat-Modelling-Research/blob/main/ISDFS25/9-dfci-PrivacyThreatModel.csv): Comprehensive privacy threat model for DFCI, combining domain-independent and domain-dependent threats with assets and threat agents.

#### Contacts

- Email: <marioraciti@pm.me>
- LinkedIn: linkedin.com/in/marioraciti
- Twitter: twitter.com/tsumarios
