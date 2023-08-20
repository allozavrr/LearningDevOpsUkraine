# LearningDevOpsUkraine - DevSecOps

**Доброго всім дня.**

**Це невеличкий конспект з допомоги тим, хто хоче вивчати DevSecOps у 2023 році.**

**Усі посилання зібрані в одній доці**

*Перелік не є закінченим. Доповнення і зауваження дуже вітаються.*

*Також дякую телеграм-спільноті https://t.me/DevOpsMarathon та її очільнику - @edemus.*

**[Never give up!](https://www.youtube.com/watch?v=GC5E8ie2pdM&ab_channel=TinaTurner)**


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
| *Pentration Testing, Beginners To Expert!** | [github.com/xalgord](https://github.com/xalgord/Massive-Web-Application-Penetration-Testing-Bug-Bounty-Notes)  | Web Application Penetration Testing for everyone  |EN | |
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

### Анализатори сторонніх компонентів (SCA)

*Анализатор сторонніх компонентів - інструмент, що здійснює пошук вразливостей у сторонніх open-source компонентах, які підключені до проекту*

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **OWASP Composition Analysis** | [owasp.org](https://owasp.org/www-community/Component_Analysis) | OWASP Tools Listing  |EN | |

**Open-source**

| Name | URL | Description | Language | 
| :---------- | :---------- | :---------- | :----------: |
| **Dependency check** | [github.com/jeremylong](https://github.com/jeremylong/DependencyCheck) | SCA tool that attempts to detect publicly disclosed vulnerabilities contained within a project's dependencies  |EN | |