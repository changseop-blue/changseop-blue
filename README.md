제공해주신 이미지와 내용을 보면, GitHub 프로필 README(`changseop-blue/changseop-blue`)를 작성 중이신 상태이며 상단 배너(Profile Views, Followers, Stars 등) 영역의 마크다운 링크에 `YOUR GITHUB USERNAME`이라는 플레이스홀더가 그대로 남아 있거나 일부 이미지 배지 경로가 비어 있는 부분이 있습니다.

해당 부분을 실제 사용자 아이디인 `changseop-blue`에 맞게 모두 교정하고, 기술 스택(Tech Stack) 섹션에서 아이콘이나 뱃지가 빠져 허전하게 보이던 부분을 직관적이고 깔끔한 배지 형태로 채워 넣은 **완성형 마크다운 코드**를 정리해 드립니다.

---

### 📋 수정된 전체 `README.md` 코드

아래 코드를 복사하여 GitHub 편집기 창에 그대로 붙여넣으시면 됩니다.

```markdown
# 👋 Changseop Lee

### 🛡️ Junior Security Analyst · Blue Team / SOC

<p align="left">
  <img src="https://komarev.com/ghpvc/?username=changseop-blue&style=for-the-badge&color=blue&label=PROFILE+VIEWS" />
  <a href="https://github.com/changseop-blue">
    <img src="https://img.shields.io/github/followers/changseop-blue?style=for-the-badge&logo=github&label=Followers" />
  </a>
  <a href="https://github.com/changseop-blue?tab=repositories">
    <img src="https://img.shields.io/github/stars/changseop-blue?affiliations=OWNER%2CCOLLABORATOR&style=for-the-badge&logo=github&label=Stars" />
  </a>
</p>

---

## 🔐 About Me

🧑‍💻 **Blue Team / SOC 분야를 목표로 성장하고 있는 주니어 보안 분석가입니다.**

Linux / Windows 환경에서 발생하는 **로그, 보안 이벤트, 네트워크 트래픽을 분석하고 공격 흔적을 식별하는 실습**을 중심으로 보안 운영 역량을 쌓고 있습니다.

특히 단순히 "공격이 발생했다"고 판단하기보다,

> **Evidence → Analysis → Detection → Response**

의 흐름으로 객관적인 증거를 기반으로 보안 이벤트를 분석하는 것을 중요하게 생각합니다.

### 🎯 Security Philosophy

```text
Logs
  ↓
Indicators
  ↓
Investigation
  ↓
Root Cause
  ↓
Response
  ↓
Documentation

```

**추측보다 증거를 우선하고, 분석 결과를 기록으로 남기는 Security Analyst**를 목표로 합니다.

---

# 📊 GitHub Statistics

---

# 🔥 Contribution Streak

---

# 🏆 GitHub Achievements

---

# 📈 Contribution Activity

---

# 🧭 Security Focus

## 📡 Log Analysis

* Linux / Windows Security Log Analysis
* Authentication Event Analysis
* SSH Login / Failed Login Analysis
* Suspicious IP Identification
* IOC Identification
* Attack Timeline Analysis
* Privilege Escalation Indicators

---

## 🚨 SIEM & Detection

* Wazuh Security Monitoring
* Elastic Stack / ELK
* Security Event Monitoring
* SSH Brute Force Detection
* Custom Detection Rule 작성 및 테스트
* File Integrity Monitoring
* Alert Triage
* Security Event Classification

---

## 🖥️ System Security

* Linux Security Configuration
* User / Group / Permission Management
* SELinux
* Firewalld
* iptables
* Apache / Nginx
* Linux Security Logs

---

## 🌐 Network Security

* TCP / UDP Traffic Analysis
* HTTP / HTTPS
* DNS Traffic Analysis
* Wireshark
* Snort
* Suricata
* pfSense
* Firewall Rules
* NAT
* Network Segmentation

---

## 🔍 Web Security

* OWASP Top 10
* DVWA
* WebGoat
* bWAPP / Bee-Box
* Burp Suite
* OWASP ZAP
* SQL Injection
* XSS
* Command Injection
* File Inclusion
* Authentication Vulnerabilities

---

# 🛠️ Tech Stack

### 💻 Operating Systems

### 🚨 SIEM / Security Monitoring

### 🌐 Network / Firewall

### 🔐 Web Security

### 💻 Development / Infrastructure

---

# 🎓 Certifications

| Status | Certification | Details |
| --- | --- | --- |
| ⏳ | **정보보안산업기사** | 과정평가형 외부평가 준비 |
| 📘 | **정보보안기사** | 학습 및 준비 |
| 📘 | **리눅스마스터 2급** | 학습 중 |

---

# 🚀 Currently Working On

## 01. 🛡️ SIEM & Detection Engineering

### Wazuh Security Monitoring Lab

* Linux Security Log 수집
* SSH Brute Force Detection
* Authentication Failure Analysis
* Custom Detection Rule
* FIM 이벤트 분석
* Alert Triage
* Incident Response Simulation

---

## 02. 🔎 Security Log Analysis

Linux 환경에서 발생하는 보안 로그를 기반으로 공격 흔적을 분석합니다.

```text
Authentication Log
        ↓
Failed / Successful Login
        ↓
Suspicious Source IP
        ↓
IOC Identification
        ↓
Attack Timeline
        ↓
Incident Analysis

```

주요 분석 대상:

* `/var/log/auth.log`
* `/var/log/secure`
* SSH Authentication
* Failed Login
* Successful Login
* Privilege Escalation Indicators
* Suspicious IP

---

## 03. 🔥 Network Security Lab

### pfSense Network Security Lab

VMware 기반 가상 네트워크 환경에서 네트워크 보안 구성을 실습합니다.

```text
Internet
   │
   ▼
[ pfSense ]
   │
   ├── WAN
   │
   └── LAN
       │
       ├── Linux Server
       ├── Security Monitoring
       └── Client

```

주요 실습:

* WAN / LAN Segmentation
* Firewall Rules
* NAT
* Access Control
* Network Monitoring
* Security Event Analysis

---

## 04. 🌐 Web Security Lab

웹 애플리케이션 취약점을 직접 재현하고 원인과 대응 방법을 분석합니다.

### Practice Environment

* DVWA
* WebGoat
* Bee-Box
* Burp Suite
* OWASP ZAP

### Vulnerability

* SQL Injection
* Cross-Site Scripting
* Command Injection
* File Inclusion
* Authentication Issues

---

# 📂 Featured Security Projects

## 🛡️ Wazuh Security Monitoring Lab

> Linux 환경의 보안 이벤트를 Wazuh로 수집하고 탐지하는 Security Monitoring 프로젝트

### Key Features

* SSH Brute Force Detection
* Authentication Failure Detection
* Custom Detection Rules
* File Integrity Monitoring
* Alert Investigation
* Incident Documentation

**Workflow**

```text
Attack
 ↓
Log Collection
 ↓
Detection
 ↓
Alert Triage
 ↓
Investigation
 ↓
Response
 ↓
Incident Report

```

---

## 🔥 pfSense Network Security Lab

> VMware 기반 가상 네트워크 환경에서 방화벽과 네트워크 보안 환경을 구축한 프로젝트

### Key Features

* WAN / LAN Segmentation
* Firewall Policy
* NAT
* Access Control
* Network Monitoring
* Traffic Analysis

---

## 🔍 Linux Security Log Analysis

> Linux Security Log를 기반으로 비정상적인 접근과 공격 흔적을 분석하는 프로젝트

### Analysis

* Authentication Logs
* SSH Login
* Failed Login
* Successful Login
* Suspicious IP
* IOC
* Attack Timeline
* Privilege Escalation Indicators

---

# 📝 Incident Documentation

보안 실습 결과를 단순한 화면 캡처로 끝내지 않고 **Incident Report 형태로 기록**합니다.

```text
01. Incident Summary
        ↓
02. Evidence Collection
        ↓
03. IOC Identification
        ↓
04. Timeline Analysis
        ↓
05. Root Cause Analysis
        ↓
06. Impact Assessment
        ↓
07. Response
        ↓
08. Mitigation
        ↓
09. Lessons Learned

```

### Documentation Principles

* Evidence-based Analysis
* Reproducible Investigation
* Clear Timeline
* IOC Documentation
* Root Cause Analysis
* Response Procedure
* Lessons Learned

---

# 📚 Security Learning

현재 다음 영역을 중심으로 학습하고 있습니다.

* **Security Operations:** SOC, SIEM, Security Monitoring, Alert Triage, Incident Response, Log Analysis
* **System Security:** Linux Security, Windows Security, Authentication, Access Control, System Hardening
* **Network Security:** TCP/IP, Network Traffic Analysis, Firewall, IDS / IPS, Packet Analysis
* **Application Security:** OWASP Top 10, Secure Coding, SAST, DAST, Web Vulnerability Analysis

---

# 🎯 Career Goal

## Junior Security Analyst

### Target Roles

* SOC Analyst
* Security Monitoring
* Security Operations
* Blue Team
* Junior Security Analyst

### Long-Term Goal

```text
Junior Security Analyst
        ↓
SOC Analyst
        ↓
Security Monitoring / Detection
        ↓
Incident Response
        ↓
Threat Detection & Analysis

```

보안 이벤트를 정확하게 탐지하고, **근거를 바탕으로 분석 → 대응 → 기록**할 수 있는 Security Analyst로 성장하는 것을 목표로 합니다.

---

# 💡 Security Mindset

> **"증거는 거짓말하지 않는다."**

> **Trust nothing. Verify everything.**

화려한 추측보다 **하나의 로그와 하나의 네트워크 이벤트가 더 정확한 판단의 근거**가 될 수 있다고 생각합니다.

```text
Stay Calm
    ↓
Follow the Evidence
    ↓
Analyze
    ↓
Respond
    ↓
Document

```

---

**Detect → Analyze → Respond → Document**

