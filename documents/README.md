# OWASP DevSecOps Guideline

This is a new structure of this documents and it's in-progress to improve it as much as we can. 
If you need the old verion please check [document-old-structure](../document-old-structure/) directory.

If you need a diagram version of this new structure please check [Project restructure](./assets/docs/Project-restructure-darft.pdf).



## Table of Contents:

- [0-Intro](./0-Intro)
  - [0-1-Intro](./0-Intro/0-1-Intro.md)
  - [0-2-Overview](./0-Intro/0-2-Overview.md)
- [1-Init](./1-Init)
  - [1-1-Shape-the-team](./1-Init/1-1-Shape-the-team)
    - [1-1-1-Security-champions](./1-Init/1-1-Shape-the-team/1-1-1-Security-champions.md)
  - [1-2-Training](./1-Init/1-2-Training)
    - [1-2-1-Secure-coding](./1-Init/1-2-Training/1-2-1-Secure-coding.md)
    - [1-2-2-Security-CICD](./1-Init/1-2-Training/1-2-1-Security-CICD.md)
- [2-Pre-commit](./2-Pre-commit)
  - [2-1-Pre-commit](./2-Pre-commit/2-1-Pre-commit.md)
  - [2-2-Threat-modeling](./2-Pre-commit/2-2-Threat-modeling.md)
  - [2-3-Repository-hardening](./2-Pre-commit/2-3-Repository-hardening.md)
  - [2-4-Secrets-Management](./2-Pre-commit/2-4-Secrets-Management.md)
  - [2-5-Linting-code](./2-Pre-commit/2-5-Linting-code.md)
- [3-Commit-CI](./3-Commit-CI)
  - [3-2-Interactive-Application-Security-Testing](./3-Commit-CI/3-2-Interactive-Application-Security-Testing.md)
  - [3-1-Static-analysis](./3-Commit-CI/3-1-Static-analysis)
    - [3-1-1-Static-Application-Security-Testing](./3-Commit-CI/3-1-Static-analysis/3-1-1-Static-Application-Security-Testing.md)
    - [3-1-2-Software-Composition-Analysis](./3-Commit-CI/3-1-Static-analysis/3-1-2-Software-Composition-Analysis.md)
    - [3-1-3-Container-Security](./3-Commit-CI/3-1-Static-analysis/3-1-3-Container-Security)
      - [3-1-3-1-Container-scanning](./3-Commit-CI/3-1-Static-analysis/3-1-3-Container-Security/3-1-3-1-Container-scanning.md)
      - [3-1-3-2-Container-hardening](./3-Commit-CI/3-1-Static-analysis/3-1-3-Container-Security/3-1-3-2-Container-hardening.md)
    - [3-1-4-Infastructure-as-code](./3-Commit-CI/3-1-Static-analysis/3-1-4-Infastructure-as-code.md)
- [4-Continuous-delivery-CD](./4-Continuous-delivery-CD)
  - [4-1-Dynamic-Application-Security-Testing](./4-Continuous-delivery-CD/4-1-Dynamic-Application-Security-Testing.md)
  - [4-2-Mobile-Application-Security-Test](./4-Continuous-delivery-CD/4-2-Mobile-Application-Security-Test.md)
  - [4-3-API-Security](./4-Continuous-delivery-CD/4-3-API-Security.md)
  - [4-4-Miss-Configuration-Check](./4-Continuous-delivery-CD/4-4-Miss-Configuration-Check.md)
- [5-Deploy-CD-Golive](./5-Deploy-CD-Golive)
  - [5-1-Key-and-certificate-management](./5-Deploy-CD-Golive/5-1-Key-and-certificate-management.md)
  - [5-2-Cloud-Native-Application-Protection-Platform](./5-Deploy-CD-Golive/5-2-Cloud-Native-Application-Protection-Platform.md)
- [6-Operation](./6-Operation)
  - [6-1-Runtime|Continuous-test](./6-Operation/6-1-Runtime|Continuous-test)
    - [6-1-1-Infra-scanning](./6-Operation/6-1-Runtime|Continuous-test/6-1-1-Infra-scanning)
      - [6-1-1-1-Could-resources](./6-Operation/6-1-Runtime|Continuous-test/6-1-1-Infra-scanning/6-1-1-1-Could-resources.md)
      - [6-1-1-2-K8S-resources](./6-Operation/6-1-Runtime|Continuous-test/6-1-1-Infra-scanning/6-1-1-2-K8S-resources.md)
    - [6-1-2-Image-scanning](./6-Operation/6-1-Runtime|Continuous-test/6-1-2-Image-scanning.md)  
  - [6-2-Breach-and-attack-simulation](./6-Operation/6-2-Breach-and-attack-simulation.md)
  - [6-3-Logging-and-Monitoring](./6-Operation/6-3-Logging-and-Monitoring.md)
  - [6-4-Pentest](./6-Operation/6-4-Pentest.md)
  - [6-5-VDP|Bug-bounty](./6-Operation/6-5-VDP|Bug-bounty.md)
- [7-Governance](./7-Governance)
  - [7-1-Compliance-Auditing](./7-Governance/7-1-Compliance-Auditing)
    - [7-1-1-Compliance-Auditing](./7-Governance/7-1-Compliance-Auditing/7-1-1-Compliance-Auditing.md)
    - [7-1-2-Policy-as-code](./7-Governance/7-1-Compliance-Auditing/7-1-2-Policy-as-code.md)
    - [7-1-3-Security-benchmarking](./7-Governance/7-1-Compliance-Auditing/7-1-3-Security-benchmarking.md)
  - [7-2-Data-protection](./7-Governance/7-2-Data-protection.md)
  - [7-3-Reporting](./7-Governance/7-3-Reporting)
    - [7-3-1-Tracking-maturities](./7-Governance/7-3-Reporting/7-3-1-Tracking-maturities.md)
    - [7-3-2-Central-vulnerability-management-dashboard](./7-Governance/7-3-Reporting/7-3-2-Central-vulnerability-management-dashboard.md)