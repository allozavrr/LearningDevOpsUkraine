# LearningDevOpsUkraine - DevSecOps

**Доброго всім дня.**

**Це невеличкий конспект з допомоги тим, хто хоче вивчати DevSecOps у 2023 році.**

**Усі посилання зібрані в одній доці.**

*Перелік не є закінченим. Доповнення і зауваження дуже вітаються.*

*Також дякую телеграм-спільноті https://t.me/DevOpsMarathon та її очільнику - @edemus,
телеграм-спільноті DevOps Geeks та україномовному каналу [DevOps 01](https://www.youtube.com/@DevOps01).*

**[Don't stop believin'!!](https://www.youtube.com/watch?v=1k8craCGpgs&ab_channel=journeyVEVO)**


# Table of Contents

- **[Resourses](#resourses)**
   - **[YouTube](#youtube)**
   - **[Labs for vulnerability testing](#labs-for-vulnerability-testing)**
   - **[Maturity models](#maturity-models)**
- **[Tools](#tools)**
   - **[Threat modeling](#threat-modeling)**
   - **[SAST](#sast)**
   - **[DAST](#dast)**
   - **[Secrets search](#secrets-search)**
   - **[Аналізатори сторонніх компонентів (SCA)](#аналізатори-сторонніх-компонентів-(sca))**
   - **[Тестування за принципами Behaviour Driven Development](#тестування-за-принципами-behaviour-driven-development)**
   - **[Сканери Docker образів](#сканери-docker-образів)**
   - **[Перевірка Docker / Kubernetes на відповідність](#перевірка-docker--kubernetes-на-відповідність)**
   - **[Безпека Kubernetes](#безпека-kubernetes)**
   - **[Container Runtime](#container-runtime)**
   - **[Runtime Security](#runtime-security)**
   - **[IAST](#iast)**
   - **[Fuzzing](#fuzzing)**
   - **[MAST](#mast)**
   - **[Vulnerability Management](#vulnerability-management)**
   - **[Application Security Orchestration and Correlation (ASOC)](#application-security-orchestration-and-correlation-(asoc))**
   - **[Compliance-as-code](#compliance-as-code)**
   - **[IAC Security](#iac-security)**
    - *[Kubernetes YAML validating](#kubernetes-yaml-validating)*
    - *[Порівняння інструментів](#порівняння-інструментів)*
  



## Resourses

**Розділ з вивчення побудови безпечного CI/CD.**

### YouTube

| Name | URL | Description | Meta/Language | 
| :---------- | :---------- | :---------- | :----------: |
| **DevSecOps - Implementing Secure CI/CD Pipelines** | [Youtube](https://www.youtube.com/playlist?list=PLjNII-Jkdjfz5EXWlGMBRk63PC8uJsHMo) | Short videos for beginners in DevSecOps  |EN | |
| **Курсы по кибербезопасности с нуля до аналитика DevSecOps** | [Youtube](https://www.youtube.com/playlist?list=PLMiVLClzZDbTWSsxWfVvrvdyHgSa7Wvaw) | Введення у кібербезпеку  |ru | |
| **Информационная безопасность** | [Youtube](https://www.youtube.com/playlist?list=PLVb9C2cD47iyf_qh2bX2K4TzAutbsAPdq) | Підбірка відео з окремих аспектів DevSecOps  |ru | |


### Links

| Name | URL | Description | Meta/Language | 
| :---------- | :---------- | :---------- | :----------: |
| **Simple Guide for Development and Operation** | [devsecopsguides.com](https://devsecopsguides.com/) | The most recommended omprehensive resource for integrating security into the software development lifecycle  |EN | |
| **Ultimate DevSecOps library** | [github.com/sberdachuk-epam/DevSecOps](https://github.com/sberdachuk-epam/DevSecOps) | Ultimate DevSecOps library  |![Git Secrets](https://img.shields.io/github/stars/sberdachuk-epam/DevSecOps?style=for-the-badge) |
| **DevSecOps Roadmap** | [github.com/hahwul/DevSecOps](https://github.com/hahwul/DevSecOps) | Ultimate DevSecOps library  |![Git Secrets](https://img.shields.io/github/stars/hahwul/DevSecOps?style=for-the-badge) |
| **Awesome DevSecOps** | [github.com/TaptuIT](https://github.com/TaptuIT/awesome-devsecops) | Curating the best DevSecOps resources and tooling  |![Git Secrets](https://img.shields.io/github/stars/TaptuIT/awesome-devsecops?style=for-the-badge) |
| **Awesome DevSecOps** | [github.com/devsecops](https://github.com/devsecops/awesome-devsecops) | A collection of documents, presentations, videos, training materials, tools, services  |![Git Secrets](https://img.shields.io/github/stars/devsecops/awesome-devsecops?style=for-the-badge) |


### Maturity models

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **OWASP SAMM** | [owaspsamm.org](https://owaspsamm.org/model/) | The prime maturity model for software assurance  |EN | |
| **OWASP Devsecops Maturity Model** | [owaspsamm.org](https://owasp.org/www-project-devsecops-maturity-model/) | Security measures which are applied when using DevOps strategies and how these can be prioritized  |EN | |


### Labs for vulnerability testing

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **How To Secure A Linux Server** | [github.com/imthenachoman](https://github.com/imthenachoman/How-To-Secure-A-Linux-Server) | An evolving how-to guide for securing a Linux server  |EN | |
| **CloudFoxable** | [github.com/BishopFox](https://github.com/BishopFox/cloudfoxable) | CloudFox helps penetration testers and security professionals find exploitable attack paths in cloud infrastructure  |EN | |
| **CloudGoat** | [github.com/RhinoSecurityLabs](https://github.com/RhinoSecurityLabs/cloudgoat) | CloudGoat is Rhino Security Labs' "Vulnerable by Design" AWS deployment tool  |EN | |
| **OWASP ServerlessGoat** | [github.com/OWASP](https://github.com/OWASP/Serverless-Goat) | Educate on how serverless application layer weaknesses can be exploited  |EN | |
| **OWASP Wrongsecrets** | [github.com/OWASP](https://github.com/OWASP/wrongsecrets) | The game is packed with real life examples of how to not store secrets in your software  |EN | |
| **AWS S3 CTF Challenges** | [n0j.github.io](https://n0j.github.io/2017/10/02/aws-s3-ctf.html) |  Series of brief challenges focusing on AWS S3 misconfiguration for the CTF at AppSec USA 2017 and CactusCon 2017  |EN | |
| **Breaking and Pwning Apps and Servers on AWS and Azure** | [github.com/appsecco](https://github.com/appsecco/breaking-and-pwning-apps-and-servers-aws-azure-training) |  The training is meant to be a hands-on training with guided walkthroughs, scenario based attacks, coverage of tool that can be used for attacking and auditing  |EN | |
| **Sadcloud** | [github.com/nccgroup/sadcloud](https://github.com/nccgroup/sadcloud) |  Sadcloud is a tool for spinning up insecure AWS infrastructure with Terraform  |EN | |
| **Damn Vulnerable Cloud Application** | [github.com/m6a-UdS/dvca](https://github.com/m6a-UdS/dvca) |  A demonstration project to show how to do privilege escalation on AWS  |EN | |
| **AWS Detonation Lab** | [github.com/sonofagl1tch](https://github.com/sonofagl1tch/AWSDetonationLab) |  Scripts can be used as proof-of-concept to generate a detonation lab via a cloudformation template (AWS)  |EN | |
| **lambhack** | [github.com/wickett/lambhack](https://github.com/wickett/lambhack) |  Allows you to take advantage of our tried and true application security problems, namely arbitrary code execution, XSS, injection attacks aand more (AWS)  |EN | |
| **Cfngoat - Vulnerable Cloudformation Template** | [github.com/bridgecrewio/cfngoat](https://github.com/bridgecrewio/cfngoat) |  A learning and training project that demonstrates how common configuration errors can find their way into production cloud environments  |EN | |
| **CdkGoat - Vulnerable AWS CDK Infrastructure** | [github.com/bridgecrewio/cdkgoat](https://github.com/bridgecrewio/cdkgoat) |  Another learning and training project that demonstrates how common configuration errors can find their way into production cloud environments  |EN | |
| **AWSGoat : A Damn Vulnerable AWS Infrastructure** | [github.com/ine-labs/AWSGoat](https://github.com/ine-labs/AWSGoat) |  Learning and training AWS cloud pentesting/red-teaming, auditing IaC, secure coding, detection and mitigation  |EN | |
| **AWSGoat : A Damn Vulnerable Azure Infrastructure** | [github.com/ine-labs/AzureGoat](https://github.com/ine-labs/AzureGoat) |  Learning and training Azure cloud pentesting/red-teaming, auditing IaC, secure coding, detection and mitigation  |EN | |
| **CONVEX** | [github.com/Azure/CONVEX](https://github.com/Azure/CONVEX) |  Spins up Capture The Flag environments in your Azure tenant for participants to play through  |EN | |
| **caponeme** | [github.com/avishayil/caponeme](https://github.com/avishayil/caponeme) |  A vulnerable cloud environment that meant to mock Capital One Breach for educational purposes  |EN | |
| **TerraGoat - Vulnerable Terraform Infrastructure** | [github.com/bridgecrewio/terragoat](https://github.com/bridgecrewio/terragoat) |  A learning and training project that demonstrates how common configuration errors can find their way into production cloud environments  |EN | |
| **IAM Vulnerable** | [github.com/BishopFox/iam-vulnerable](https://github.com/BishopFox/iam-vulnerable) |  Learning how to identify and exploit vulnerable IAM configurations that allow for privilege escalation  |EN | |
| **Web-Check** | [github.com/Lissy93](https://github.com/Lissy93/web-check) | Comprehensive, on-demand open source intelligence for any website  |EN | |
| **Penetration Testing, Beginners To Expert!** | [github.com/xalgord](https://github.com/xalgord/Massive-Web-Application-Penetration-Testing-Bug-Bounty-Notes)  | Web Application Penetration Testing for everyone  |EN | |
| **TryHackMe** | [tryhackme.com](https://tryhackme.com/) | Learning cyber security  |EN | |
| **Hack The Box** | [hackthebox.com](https://www.hackthebox.com/) | The #1 cybersecurity upskilling platform  |EN | |
| **OWASP Juice Shop** | [owasp.org](https://owasp.org/www-project-juice-shop/) | Game/tutorial teaches you in security trainings, awareness demos, CTFs and as a guinea pig for security tools  |EN | |
| **Flaws** | [flaws.cloud](http://flaws.cloud/) | Game/tutorial teaches you AWS (Amazon Web Services) security concepts  |EN | |
| **Flaws2** | [flaws2.cloud](http://flaws2.cloud/) | Another game/tutorial teaches you AWS (Amazon Web Services) security concepts  |EN | |
| **AWS Well-Architected Labs** | [wellarchitectedlabs.com](https://wellarchitectedlabs.com/security/) | Through a series of levels you'll learn about common mistakes and gotchas when using Amazon Web Services (AWS)  |EN | |
| **CTF 101 worklab** | [r00tz-ctf.awssecworkshops.com](https://r00tz-ctf.awssecworkshops.com/) | Security CTF 101 worklab, sponsored by Amazon Web Services Security  |EN | |
| **Thunder CTF** | [thunder-ctf.cloud](http://thunder-ctf.cloud/) | Thunder CTF allows players to practice attacking vulnerable cloud projects on Google Cloud Platform (GCP)  |EN | |
| **The Big IAM Challenge by Wiz** | [bigiamchallenge.com](https://bigiamchallenge.com/challenge/1) | Put yourself to the test with our unique CTF challenge and boost your AWS IAM knowledge  |EN | |
| **PenTesting.Cloud** | [pentesting.cloud](https://pentesting.cloud/) | A free pentesting learning platform  |EN | |
| **GCP Goat** | [gcpgoat.joshuajebaraj.com](https://gcpgoat.joshuajebaraj.com/index.html) | Intentionally vulnerable GCP environment to learn and practice GCP Security  |EN | |

## Articles
| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **How Secrets Leak in CI/CD Pipelines** | [trufflesecurity.com](https://trufflesecurity.com/blog/secrets-leak-in-ci-cd/) | How to searh Secrets in CI/CD  |EN | |

## Tools

**Інструменти, які використовуються у DevSecOps.**

### Threat modeling

*Моделювання загроз у контексті Secure Development Lifecycle - це процес аналізу архітектури ПЗ щодо наявності в ній потенційних уразливостей та небезпечних технологій. Воно потрібне для впровадження процесу перевірок ІБ ще на етапі проектування архітектури. На цьому ж етапі формуються вимоги з боку фахівців з безпеки додатків, які надалі йдуть у backlog.*

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **Awesome Threat Modeling** | [github.com/hysnsec](https://github.com/hysnsec/awesome-threat-modelling) | A curated list of threat modeling resources (books, courses - free and paid, videos, tools, tutorials and workshop to practice on) for learning  |EN | |

**Open-source**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **OWASP Threat Dragon** | [owasp.org](https://owasp.org/www-project-threat-dragon/) | Modeling tool used to create threat model diagrams as part of a secure development lifecycle  |EN | |
| **Microsoft Threat Modeling Tool** | [learn.microsoft.com](https://learn.microsoft.com/en-gb/azure/security/develop/threat-modeling-tool) | The Threat Modeling Tool is a core element of the Microsoft Security Development Lifecycle (SDL)  |EN | |
| **pytm: A Pythonic framework for threat modeling** | [github.com/izarg](https://github.com/izar/pytm) | Shift threat modeling to the left, making threat modeling more automated and developer-centric  |EN | |
| **materialize threats** | [github.com/secmerc](https://github.com/secmerc/materialize-threats) | Developers and security practitioners who want to perform 'graph' analysis on data flow diagrams - using SQL  |EN | |
| **threatspec** | [github.com/threatspec](https://github.com/threatspec/threatspec) | Developers and security practitioners who want to threat modeling annotations as comments inside source code  |EN | |
| **The Raindance Project** | [github.com/devsecops](https://github.com/devsecops/raindance) | The attack map process for identifying target surface and adversary attack strategies that lead to exploit and compromise  |EN | |
| **threagile** | [github.com/Threagile](https://github.com/Threagile/threagile) | The open-source toolkit for agile threat modeling  |EN | |

**Paid (enterprise)**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **Iriusrisk** | [iriusrisk.com](https://www.iriusrisk.com/) | Modeling platform automates the threat modeling process, enabling developers to design and build secure software  |EN | |
| **Iriusrisk** | [threatmodeler.com](https://threatmodeler.com/) | Modeling platform can securely design, build and validate from development through deployment  |EN | |

### SAST (Статичні аналізатори апплікацій)

*Статичний аналізатор коду - інструмент, що повідомляє про вразливість програми, орієнтуючись на її вихідні коди.*

**SAST in details**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **OWASP Source Code Analysis Tools** | [owasp.org](https://owasp.org/www-community/Source_Code_Analysis_Tools) | SAST tools for all programming languages  |EN | |
| **Static Analysis Tools** | [github.com/analysis-tools-dev](https://github.com/analysis-tools-dev/static-analysis) |  Static analysis tools for all programming languages, build tools, config files and more  |EN | |

**Open-source**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **ShiftLeft Scan** | [github.com/ShiftLeftSecurity](https://github.com/ShiftLeftSecurity/sast-scan) | Scan can detect various kinds of security flaws in your application, and infrastructure code without any remote server  |EN | |
| **Salus** | [github.com/coinbase](https://github.com/coinbase/salus) | A tool for coordinating the execution of security scanners  |EN | |
| **HuskyCI** | [github.com/globocom](https://github.com/globocom/huskyci) | An open source tool that orchestrates security tests and centralizes all results into a database for further analysis and metrics  |EN | |
| **Graudit** | [github.com/wireghoul](https://github.com/wireghoul/graudit/) | A simple script and signature sets that allows you to find potential security flaws in source code using the GNU utility grep  |EN | |
| **RIPS** | [github.com/robocoder](https://github.com/robocoder/rips-scanner) | A static source code analyser for vulnerabilities in PHP scripts  |EN | |
| **Joern** | [github.com/joernio](https://github.com/joernio/joern) | Platform for analyzing source code, bytecode, and binary executables  |EN | |
| **CodeQL** | [securitylab.github.com](https://securitylab.github.com/tools/codeql/) | CodeQL lets you query code as though it were data  |EN | |
| **Semgrep** | [semgrep.dev](https://semgrep.dev/editor) | Platform for analyzing source code, bytecode, and binary executables  |EN | |
| **RIPS** | [github.com/robocoder](https://github.com/robocoder/rips-scanner) | A static source code analyser for vulnerabilities in PHP scripts  |EN | |

**Paid (enterprise)**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **Checkmarx** | [checkmarx.com](https://checkmarx.com/) | Platform for securing every phase of development  |EN | |
| **PT AI** | [ptsecurity.com](https://www.ptsecurity.com/ww-en/products/ai/) | Only source code analyzer providing analysis and convenient tools to automatically confirm vulnerabilities   |EN | |
| **Veracode Static Analysis** | [veracode.com](https://www.veracode.com/products/binary-static-analysis-sast) | Only source code analyzer providing analysis and convenient tools to automatically confirm vulnerabilities   |EN | |
| **Veracode Static Analysis** | [veracode.com](https://www.veracode.com/products/binary-static-analysis-sast) | Scan code at each development stage with IDE, Pipeline, and Policy scans   |EN | |

### DAST (Динамічні аналізатори апплікацій)

*Динамічний аналізатор коду - інструмент, що повідомляє про вразливість програми, орієнтуючись на відповіді сервера по завданим запитам.*

**DAST in details**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **Awesome DAST** | [github.com/analysis-tools-dev](https://github.com/analysis-tools-dev/dynamic-analysis/) | DAST tools for all programming languages  |EN | |

**Open-source**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **Arachni** | [github.com/Arachni](https://github.com/Arachni/arachni) | Ruby framework aimed towards helping penetration testers and administrators evaluate the security of web applications  |EN | |
| **OWASP ZAP** | [github.com/zaproxy](https://github.com/zaproxy/zaproxy) | Automatically find security vulnerabilities in your web applications  |EN | |
| **w3af** | [github.com/andresriancho](https://github.com/andresriancho/w3af) | Open source web application security scanner  |EN | |
| **Nikto** | [github.com/sullo](https://github.com/sullo/nikto) | Web server scanner   |EN | |
| **N.E.R.V.E** | [github.com/PaytmLabs](https://github.com/PaytmLabs/nerve) | Vulnerability scanner tailored to find low-hanging fruit level vulnerabilities   |EN | |
| **Nuclei** | [github.com/projectdiscovery](https://github.com/projectdiscovery/nuclei) | Scanning for a variety of protocols, including TCP, DNS, HTTP, SSL, File, Whois, Websocket, Headless    |EN | |
| **Automatic API Attack Tool** | [github.com/imperva](https://github.com/imperva/automatic-api-attack-tool) | API attack tool  |EN | |
| **Wapiti** | [github.com/wapiti-scanner](https://github.com/wapiti-scanner/wapiti) | Web vulnerability scanner written in Python   |EN | |
| **Vega** | [github.com/subgraph](https://github.com/subgraph/Vega) | Web vulnerability scanner written in Java   |EN | |

**Paid (enterprise)**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **PortSwigger Burp Suite** | [portswigger.net](https://portswigger.net/burp) | The enterprise-enabled dynamic web vulnerability scanner  |EN | |
| **NetSparker** | [nvicti.com](https://www.invicti.com/) | Application security testing for enterprise  |EN | |
| **Acunetix** | [acunetix.com](https://www.acunetix.com/) | Automate application security testing   |EN | |
| **WebInspect** | [microfocus.com](https://www.microfocus.com/en-us/cyberres/application-security/webinspect) | Automated dynamic testing solution that provides comprehensive vulnerability detection  |EN | |
| **PT AI** | [ptsecurity.com](https://www.ptsecurity.com/ww-en/products/ai/) | Source code analyzer providing high-quality analysis and convenient tools to automatically confirm vulnerabilities  |EN | |
| **Veracode** | [veracode.com](https://www.veracode.com/products/dynamic-analysis-dast) | Dynamic testing tool Crashtest Security showing a growing focus in DAST  |EN | |
| **Tenable Web App Scanning** | [tenable.com](https://www.tenable.com/products/tenable-io/web-application-scanning) | Simple, Scalable and Automated Vulnerability Scanning for Web Applications  |EN | |

### Secrets search

*Інструменти для пошуку чутливої інформації.*

**Open-source**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **git-secrets** | [github.com/awslabs](https://github.com/awslabs/git-secrets) | Prevents you from committing passwords and other sensitive information to a git repository  |EN | |
| **Gitrob** | [github.com/michenriksen](https://github.com/michenriksen/gitrob) | Find potentially sensitive files pushed to public repositories on Github  |EN | |
| **Gitleaks** | [github.com/gitleaks](https://github.com/gitleaks/gitleaks) | SAST tool for detecting and preventing hardcoded secrets like passwords, api keys, and tokens in git repos  |EN | |
| **TruffleHog** | [github.com/trufflesecurity](https://github.com/trufflesecurity/trufflehog) | Tool for detecting and preventing secrets in GitHub Repo/S3 bucket  |EN | |
| **TruffleHog** | [github.com/trufflesecurity](https://github.com/trufflesecurity/trufflehog) | Tool for detecting and preventing secrets in GitHub Repo/S3 bucket  |EN | |
| **Talisman** | [github.com/thoughtworks](https://github.com/thoughtworks/talisman) | Tool that installs a hook to your repository to ensure that potential secrets or sensitive information  |EN | |
| **Slack Watchman** | [github.com/PaperMtn](https://github.com/PaperMtn/slack-watchman) | Monitoring and enumerating Slack for exposed secrets  |EN | |
| **GitLab Watchman** | [github.com/PaperMtn](https://github.com/PaperMtn/gitlab-watchman) | Application that uses the GitLab API to detect exposed secrets and personal data  |EN | |
| **Rusty Hog** | [github.com/newrelic](https://github.com/newrelic/rusty-hog) | Set of scanners that use regular expressions to try and detect the presence of sensitive information, such as API keys, passwords, and personal information  |EN | |
| **Rusty Hog** | [github.com/newrelic](https://github.com/newrelic/rusty-hog) | Set of scanners that use regular expressions to try and detect the presence of sensitive information, such as API keys, passwords, and personal information  |EN | |
| **detect-secrets** | [github.com/Yelp](https://github.com/Yelp/detect-secrets) | Aptly named module for detecting secrets within a code base  |EN | |
| **repo-supervisor** | [github.com/auth0](https://github.com/auth0/repo-supervisor) | Tool that helps you to detect secrets and passwords in your code  |EN | |

**Paid (enterprise)**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **GitGuardian** | [gitguardian.com](https://www.gitguardian.com/) | Scan and fix hardcoded secrets in source code, CI/CD pipelines, and developer productivity tools  |EN | |
| **SpectralOps** | [spectralops.io](https://spectralops.io/) | Monitor, classify, and protect your code, assets, and infrastructure for exposed API keys, tokens, credentials, and high-risk security misconfigurations  |EN | |

### Аналізатори сторонніх компонентів (SCA)

*Аналізатор сторонніх компонентів - інструмент, що здійснює пошук вразливостей у сторонніх open-source компонентах, які підключені до проекту*

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **OWASP Composition Analysis** | [owasp.org](https://owasp.org/www-community/Component_Analysis) | OWASP Tools Listing  |EN | |

**Open-source**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **Dependency check** | [github.com/jeremylong](https://github.com/jeremylong/DependencyCheck) | SCA tool that attempts to detect publicly disclosed vulnerabilities contained within a project's dependencies  |EN | |
| **Dependency Track** | [dependencytrack.org](https://dependencytrack.org/) | Continuous SBOM Analysis Platform  |EN | |
| **Nexus Vulnerability Scanner** | [sonatype.com](https://www.sonatype.com/products/vulnerability-scanner) | Tool to find out if your software has any open source security vulnerabilities  |EN | |
| **ClearlyDefined** | [clearlydefined.io](https://clearlydefined.io/?sortDesc=true&sort=releaseDate) | Search and check SCA in one platform  |EN | |
| **Renovate** | [mend.io](https://www.mend.io/renovate/) | Scans your software, discovers dependencies, automatically checks to see if an updated version exists, and helps you by submitting automated pull requests  |EN | |

**Paid (enterprise)**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **Sonatype Nexus IQ** | [sonatype.com](https://www.sonatype.com/products/intelligence) | Open Source Components Analyzed  |EN | |
| **Veracode SCA** | [veracode.com](https://www.veracode.com/products/software-composition-analysis) | Strong Performer in SCA Wave  |EN | |
| **Snyk Open Source** | [snyk.io](https://snyk.io/product/open-source-security-management/) | Tool provides advanced software composition analysis (SCA) backed by industry-leading security and application intelligence  |EN | |
| **WhiteSource for Developers** | [mend.io](https://www.mend.io/native-integrations-for-developers-environments/) | Keep your open source components secure and compliant throughout the development lifecycle from inside your environments  |EN | |
| **JFrog XRay** | [jfrog.com](https://jfrog.com/xray/) | End-to-End Software Supply Chain Security powered by the JFrog Platform  |EN | |
| **Black Duck** | [synopsys.com](https://www.synopsys.com/software-integrity/security-testing/software-composition-analysis.html) | Tool helps manage the security, quality, and license compliance risks that come from the use of open source and third-party code in applications and containers  |EN | |

### Тестування за принципами Behaviour Driven Development

*Фреймворки, що дозволяють описувати перевірки за методологією BDD*

**Open-source**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **BDD-Security** | [github.com/iriusrisk](https://github.com/iriusrisk/bdd-security) | Security testing framework that uses Behaviour Driven Development concepts to create self-verifying security specifications  |EN | |
| **Gauntlt** | [github.com/michenriksen](https://gauntlt/gauntlt/gauntlt) | Ruggedization framework that enables security testing that is usable by devs, ops and security  |EN | |

### Сканери Docker образів

*Інструменти, спрямовані на пошук вразливостей в образах контейнерів*

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **29 Docker security tools compared** | [sysdig.com](https://sysdig.com/blog/20-docker-security-tools/) | Alphabetical index of Docker Security tools  |EN | |
| **Awesome Container Security** | [github.com/kai5263499](https://github.com/kai5263499/awesome-container-security) | A collection of container related security resources  |EN | |
| **Awesome Docker Security** | [github.com/myugan](https://github.com/myugan/awesome-docker-security) | List of awesome resources about docker security included books, blogs, video, tools and cases  |EN | |

**Open-source**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **Clair** | [github.com/quay](https://github.com/quay/clair) | Open Source project for the static analysis of vulnerabilities in application containers  |EN | |
| **Trivy** | [github.com/aquasecurity](https://github.com/aquasecurity/trivy) | Comprehensive and versatile security scanner  |EN | |
| **Anchore** | [github.com/anchore](https://github.com/anchore/anchore-cli) | Command line interface on top of the Anchore Engine REST API  |EN | |
| **Dagda** | [github.com/eliasgranderubio](https://github.com/eliasgranderubio/dagda/) | Tool to perform static analysis of known vulnerabilities, trojans, viruses, malware & other malicious threats in docker images  |EN | |
| **whalescan** | [github.com/nccgroup](https://github.com/nccgroup/whalescan) | Vulnerability scanner for Windows containers, which performs several benchmark checks, as well as checking for CVEs/vulnerable packages on the container  |EN | |
| **grype** | [github.com/nccgroup](https://github.com/nccgroup/whalescan) | Vulnerability scanner for container images and filesystems  |EN | |
| **syft** | [github.com/anchore](https://github.com/anchore/syft) | CLI tool and Go library for generating a Software Bill of Materials (SBOM) from container images and filesystems  |EN | |

**Paid (enterprise)**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **Snyk Container** | [snyk.io](https://snyk.io/product/container-vulnerability-management/) | Container and Kubernetes security that helps developers and DevOps find, prioritize, and fix vulnerabilities throughout the SDLC   |EN | |
| **TrendMicro SmartCheck** | [trendmicro.com](https://www.trendmicro.com/en_us/business/products/hybrid-cloud/cloud-one-container-image-security.html) | Simplify security for your cloud-native applications with advanced container image scanning  |EN | |
| **WhiteSource for containers** | [mend.io](https://www.mend.io/solution-for-containers/) | Scans container images for multiple sources of risk, including open source vulnerabilities (CVEs), license policy violations, and exposed secret  |EN | |
| **Sonatype Container** | [sonatype.com](https://www.sonatype.com/products/containerl) | Run automated tests for security compliance to ensure you catch vulnerabilities early in the container development cycle  |EN | |

### Перевірка Docker / Kubernetes на відповідність

*Інструменти для перевірки Docker / Kubernetes ресурсу на відповідність CIS/PCI DSS*

**Open-source**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **Docker bench** | [github.com/docker](https://github.com/docker/docker-bench-security) | Open-source utility so the Docker community can have an easy way to self-assess their hosts and Docker containers against this benchmark  |EN | |
| **Dockle** | [github.com/goodwithtech](https://github.com/goodwithtech/dockle) | Container image linter for security, helping build the best-practice Docker Image  |EN | |
| **Kubebench** | [github.com/aquasecurity](https://github.com/aquasecurity/kube-bench) | Tool that checks whether Kubernetes is deployed securely by running the checks documented in the CIS Kubernetes Benchmark  |EN | |



### Безпека Kubernetes

*Інструменти для перевірки безпеки Kubernetes*

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **Kubernetes Security Checklist and Requirements - All in One** | [github.com/Vinum-Security](https://github.com/Vinum-Security/kubernetes-security-checklist/blob/main/README.md) | Way to make your cluster secure  |EN | |
| **Awesome Kubernetes Security** | [github.com/ksoclabs](https://github.com/ksoclabs/awesome-kubernetes-security) | A curated list of awesome Kubernetes security resources  |EN | |
| **Awesome k8s Security** | [github.com/magnologan](https://github.com/magnologan/awesome-k8s-security) | A curated list for Kubernetes (K8s) Security resources such as articles, books, tools, talks and videos  |EN | |


**Open-source**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **Kubehunter** | [github.com/aquasecurity](https://github.com/aquasecurity/kube-hunter) | Increase awareness and visibility for security issues in Kubernetes environments  |EN | |
| **KubiScan** | [github.com/cyberark](https://github.com/cyberark/KubiScan) | A tool for scanning Kubernetes cluster for risky permissions in Kubernetes's Role-based access control (RBAC) authorization model  |EN | |
| **Krane** | [github.com/appvia](https://github.com/appvia/krane) | Kubernetes RBAC static analysis tool  |EN | |
| **Statboard** | [github.com/aquasecurity](https://github.com/aquasecurity/starboard) | Security tools in the cloud native world for identifying and informing about security issues in Kubernetes  |EN | |
| **Kubeaudit** | [github.com/Shopify](https://github.com/Shopify/kubeaudit) | Command line tool and a Go package to audit Kubernetes clusters for various different security concerns  |EN | |
| **Kubesec** | [github.com/controlplaneio](https://github.com/controlplaneio/kubesec) | Security risk analysis for Kubernetes resources  |EN | |
| **audit2rbac** | [github.com/liggitt](https://github.com/liggitt/audit2rbac) | Tool takes a Kubernetes audit log and username as input, and generates RBAC role and binding objects that cover all the API requests made by that user  |EN | |
| **KubeClarity** | [github.com/openclarity](https://github.com/openclarity/kubeclarity) | Tool for detection and management of Software Bill Of Materials (SBOM) and vulnerabilities of container images and filesystems  |EN | |
| **Kubestriker** | [github.com/vchinnipilli](https://github.com/vchinnipilli/kubestriker) | Tool designed to tackle Kuberenetes cluster security issues due to misconfigurations and will help strengthen the overall IT infrastructure of any organisation  |EN | |
| **CDK - Zero Dependency Container Penetration Toolkit** | [github.com/cdk-team](https://github.com/cdk-team/CDK) | Open-sourced container penetration toolkit, designed for offering stable exploitation in different slimmed containers without any OS dependency  |EN | |

**Paid (enterprise)**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **Veracode IAST** | [veracode.com](https://www.veracode.com/products/container-security) | Integrate container security seamlessly into your existing pipeline  |EN | |


### Container Runtime

*Інструменти для слідкування за поведінкою контейнерів у Runtime*

**Open-source**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **Sysdig Falco** | [github.com/falcosecurity](https://github.com/falcosecurity/falco) | Сloud native runtime security tool for Linux operating systems  |EN | |
| **Deepfence Runtime Threat Mapper** | [github.com/deepfence](https://github.com/deepfence/ThreatMapper) | Сombination of agent-based inspection and agent-less monitoring to provide the widest possible coverage to detect threats  |EN | |
| **Stackrox** | [github.com/stackrox](https://github.com/stackrox/) | Сontainer security platform reduces the attack surface, ensures compliance, and stops attacks  |EN | |

**Paid Cloud Native Security Platform (enterprise)**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **Aqua CSP** | [aquasec.com](https://www.aquasec.com/aqua-cloud-native-security-platform/) | Accelerate secure innovation and protect your entire development lifecycle from code to cloud and back  |EN | |
| **Aqua CSPM** | [aquasec.com](https://www.aquasec.com/products/cspm/) | Identify, prioritize, and remediate the most critical cloud security risks in real-time  |EN | |
| **Prisma Cloud Compute** | [paloaltonetworks.com](https://www.paloaltonetworks.com/prisma/cloud) | Prisma Cloud secures applications from code to cloud   |EN | |
| **NeuVector** | [suse.com](https://www.suse.com/neuvector/) | Continuously scan throughout the container lifecycle   |EN | |
| **Sysdig** | [sysdig.com](https://sysdig.com/products/secure/) | Find and prioritize vulnerabilities, detect and respond to threats and anomalies and manage configurations, permissions, and compliance   |EN | |
| **Tenable.io Container Security** | [tenable.com](https://www.tenable.com/products/tenable-cs) | Apply, monitor and report on security and compliance policies across multi-cloud environments   |EN | |
| **Skyhigh** | [skyhighsecurity.com](https://www.skyhighsecurity.com/products/cloud-access-security-broker.html) | Secure corporate data in cloud applications from exfiltration to unauthorized users or devices while keeping your employees productive   |EN | |
| **TrendMicro CloudOne** | [trendmicro.com](https://www.trendmicro.com/en_us/business/products/hybrid-cloud/cloud-one-container-image-security.html) | Advanced container image scanning, policy-based admission control, and container runtime protection   |EN | |
| **Qualys Container Security** | [qualys.com](https://www.qualys.com/apps/container-security/) | Discover, track and continuously secure containers – from build to runtime   |EN | |

### Runtime Security

*Інструменти для перевірки веб-застосунків у Runtime*

**Open-source**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **RASP** | [github.com/baidu](https://github.com/baidu/openrasp) | Tool can monitor various events including database queries, file operations and network requests etc  |EN | |
| **Modsecurity** | [github.com/SpiderLabs](https://github.com/SpiderLabs/ModSecurity) | Cross platform web application firewall (WAF) engine for Apache, IIS and Nginx   |EN | |
| **Dynatrace Community Edition** | [github.com/Dynatrace](https://github.com/Dynatrace) | Analytics and automation platform powered by causal AI. It has a paid version  |EN | |

**Paid (enterprise)**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **Dynatrace Community Edition** | [dynatrace.com](https://www.dynatrace.com/) | Paid version of Dynatrace - Analytics and automation platform powered by causal AI   |EN | |
| **Datadog** | [datadoghq.com](https://www.datadoghq.com/product/application-security-management/) | Production visibility and security for your web applications and APIs   |EN | |
| **Waratek** | [waratek.com](https://waratek.com/) | The Application Security platform for enterprise Java applications and APIs  |EN | |


### IAST

*Інструменти, що поєднують практики SAST та DAST*

**Open-source**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **Contrast** | [contrastsecurity.com](https://www.contrastsecurity.com/contrast-community-edition) | Ignite innovation velocity on the only unified security platform built to get secure code moving through the entire application development pipeline (for Java & .NET apps)  |EN | |

**Paid (enterprise)**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **Checkmarx IAST** | [checkmarx.com](https://checkmarx.com/product/cxiast-interactive-code-scanning/) | Discover the runtime vulnerabilities in your applications that other solutions just can’t find  |EN | |
| **Synopsys IAST** | [synopsys.com](https://www.synopsys.com/software-integrity/security-testing/interactive-application-security-testing.html) | IAST solution with active verification and sensitive-data tracking for web-based applications  |EN | |
| **Acunetix IAST** | [acunetix.com](https://www.acunetix.com/vulnerability-scanner/acusensor-technology/) | IAST solution works with applications written in Node.js, PHP, Java (including the Spring framework), and ASP.NET  |EN | |
| **Burp IAST** | [portswigger.net](https://portswigger.net/burp/documentation/desktop/tools/infiltrator) | Tool for instrumenting target web applications in order to facilitate testing using Burp Scanner for enterprise Java & .NET applications  |EN | |

### Fuzzing

*Практика тестування програми, коли на вхід програмі подаються дані, які можуть призвести до невизначеної поведінки*

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **Awesome Fuzzing** | [github.com/cpuu](https://github.com/cpuu/awesome-fuzzing#readme) | A curated list of references to awesome Fuzzing for security testing  |EN | |
| **Fuzzing Paper Collection** | [github.com/0xricksanchez](https://github.com/0xricksanchez/paper_collection) | Academic papers related to fuzzing, binary analysis, IoT security, and general exploitation  |EN | |
| **Fuzzing Papper** | [github.com/wcventure](https://github.com/wcventure/FuzzingPaper) | This website is only used for collecting and grouping the related paper  |EN | |
| **OSS-Fuzz від Google** | [github.com/google](https://github.com/google/oss-fuzz) | OSS-Fuzz aims to make common open source software more secure and stable by combining modern fuzzing techniques with scalable, distributed execution  |EN | |

**Open-source**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **AFL++** | [github.com/AFLplusplus](https://github.com/AFLplusplus/AFLplusplus) | AFL++ is a superior fork to Google's AFL - more speed, more and better mutations, more and better instrumentation, custom module support  |EN | |
| **Syzkaller** | [github.com/google](https://github.com/google/syzkaller) | A coverage-guided fuzzer  |EN | |
| **restler-fuzzer** | [github.com/microsoft](https://github.com/microsoft/restler-fuzzer) | REST API fuzzing tool for automatically testing cloud services through their REST APIs and finding security and reliability bugs in these services  |EN | |
| **Skipfish** | [github.com/spinkham](https://github.com/spinkham/skipfish) | An active web application security reconnaissance tool  |EN | |
| **LibFuzzer** | [llvm.org](https://llvm.org/docs/LibFuzzer.html) | LibFuzzer is an in-process, coverage-guided, evolutionary fuzzing engine  |EN | |

## MAST

*Інструменти для перевірки мобільних застосунків*

**Open-source**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **MobSF** | [github.com/MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) | Automated, all-in-one mobile application (Android/iOS/Windows) pen-testing, malware analysis and security assessment framework capable of performing static and dynamic analysis  |EN | |
| **Drozer** | [github.com/WithSecureLabs](https://github.com/WithSecureLabs/drozer) | Tools to help you use, share and understand public Android exploits  |EN | |

**Paid (enterprise)**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **Appknox** | [appknox.com](https://www.appknox.com/) | Automated mobile app security checks  |EN | |


## Vulnerability Management

*Інструменти що збирають та агрегують результати перевірки сторонніх інструментів*

**Open-source**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **DefectDojo** | [github.com/DefectDojo](https://github.com/DefectDojo/django-DefectDojo) | Security orchestration and vulnerability management platform  |EN | |
| **Secure code Box** | [github.com/secureCodeBox](https://github.com/secureCodeBox/secureCodeBox) | Kubernetes based, modularized toolchain for continuous security scans of your software project  |EN | |
| **Faraday** | [github.com/infobyte](https://github.com/infobyte/faraday) | Open source vulnerability manager  |EN | |
| **Archery** | [archerysec.github.io](https://archerysec.github.io/archerysec/) | Continuous integration/continuous delivery (CI/CD) toolchains to specify testing, and control the release of a given build based on results  |EN | |

**Paid (enterprise)**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **ThreatFix** | [coalfire.com](https://www.coalfire.com/services/offensive-security/application-security/threadfix) | Over 40 different security and development tools and integrations helping you to track vulnerabilities from discovery to resolution  |EN | |
| **Cisco Vulnerability Management** | [cisco.com](https://www.cisco.com/site/us/en/products/security/vulnerability-management/index.html) | Contextual insight and threat intelligence needed to intercept the next exploit and respond with precision  |EN | |

## Application Security Orchestration and Correlation (ASOC)

*Інструменти що оркеструють перевірки сторонніх інструментів*

**Open-source**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **Orchestron** | [github.com/we45](https://github.com/we45/orchestron-community) | Application vulnerability management and correlation Tool  |EN | |

**Paid (enterprise)**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **Kondukto** | [kondukto.io](https://kondukto.io/) | Security testing tool, automated vulnerability remediation workflows and managsng risks  |EN | |

## Compliance-as-code

*Практика представлення вимог безпеки через декларативний опис у вигляді коду з подальшою безпрерервною оцінкою на відповідність*

**Open-source**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **Chef InSpec** | [github.com/inspec](https://github.com/inspec/inspec) | Open-source testing framework for infrastructure for specifying compliance, security and policy requirements  |EN | |
| **Compliance Masonry** | [github.com/opencontrol](https://github.com/opencontrol/compliance-masonry) | Сommand-line interface (CLI) that allows users to construct certification documentation using the OpenControl Schema  |EN | |

## IAC Security

*Практика тестування декларативного опису шнфраструктури через конфігураційний файл на відповідність до вимог безпеки*

**Open-source**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **Cfn Nag** | [github.com/stelligent](https://github.com/stelligent/cfn_nag) | Open-source tool looks for patterns in CloudFormation templates that may indicate insecure infrastructures  |EN | |
| **Checkov** | [github.com/bridgecrewio](https://github.com/bridgecrewio/checkov) | Static code analysis tool for infrastructure as code (IaC) and also a software composition analysis (SCA) tool for images and open source packages  |EN | |
| **Terrascan** | [github.com/tenable](https://github.com/tenable/terrascan) | Open-source static code analyzer for Infrastructure as Code  |EN | |
| **Tfsec** | [github.com/aquasecurity](https://github.com/aquasecurity/tfsec) | Static analysis of your terraform code to spot potential misconfigurations  |EN | |
| **kics** | [kics.io](https://www.kics.io/#) | Open source solution for static code analysis of Infrastructure as Code  |EN | |
| **ScoutSuite** | [github.com/nccgroup](https://github.com/nccgroup/ScoutSuite) | Open source multi-cloud security-auditing tool, which enables security posture assessment of cloud environments  |EN | |

#### Kubernetes YAML validating

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **Kubeval** | [github.com/instrumenta](https://github.com/instrumenta/kubeval) | Tool for validating a Kubernetes YAML or JSON configuration file  |EN | |
| **Kube-score** | [github.com/zegl](https://github.com/zegl/kube-score) |  Tool that performs static code analysis of your Kubernetes object definitions  |EN | |
| **Config-lint** | [github.com/stelligent](https://github.com/stelligent/config-lint) | A command line tool to validate configuration files using rules specified in YAML  |EN | |
| **Copper** | [github.com/cloud66-oss](https://github.com/cloud66-oss/copper) | Useful tool with Kubernetes configuration files to enforce best practices, apply policies and compliance requirements  |EN | |
| **Conftest** | [github.com/open-policy-agent](https://github.com/open-policy-agent/conftest) | Open source tool helps you write tests against structured configuration data  |EN | |
| **Polaris** | [github.com/FairwindsOps](https://github.com/FairwindsOps/polaris#cli) | Open source policy engine for Kubernetes  |EN | |

#### Порівняння інструментів

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **tool-compare** | [github.com/iacsecurity](https://github.com/iacsecurity/tool-compare) |  The goal of this repository is to help compare the different options so that users can choose the tool that best fits their own needs  |EN | |
| **compares tools to validate and score Kubernetes YAML files** | [earnk8s.io](https://learnk8s.io/validating-kubernetes-yaml) | The article compares six static tools to validate and score Kubernetes YAML files for best practices and compliance  |EN | |


#### Порівняння інструментів

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **tool-compare** | [github.com/iacsecurity](https://github.com/iacsecurity/tool-compare) |  The goal of this repository is to help compare the different options so that users can choose the tool that best fits their own needs  |EN | |
| **compares tools to validate and score Kubernetes YAML files** | [earnk8s.io](https://learnk8s.io/validating-kubernetes-yaml) | The article compares six static tools to validate and score Kubernetes YAML files for best practices and compliance  |EN | |


#### Порівняння інструментів

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **tool-compare** | [github.com/iacsecurity](https://github.com/iacsecurity/tool-compare) |  The goal of this repository is to help compare the different options so that users can choose the tool that best fits their own needs  |EN | |
| **compares tools to validate and score Kubernetes YAML files** | [earnk8s.io](https://learnk8s.io/validating-kubernetes-yaml) | The article compares six static tools to validate and score Kubernetes YAML files for best practices and compliance  |EN | |
