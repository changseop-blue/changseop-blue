<img align="right" src="./assets/profile-character.png" width="160" alt="Changseop Lee character" />

# Changseop Lee (이창섭)

**Junior Security Analyst · Blue Team / SOC**

로그와 네트워크 트래픽에서 공격의 흔적을 찾고,
증거를 기반으로 위협을 분석하는 보안 분석가를 목표로 합니다.

![Profile Views](https://komarev.com/ghpvc/?username=changseop-blue&style=flat-square&color=blue&label=PROFILE+VIEWS)
![Followers](https://img.shields.io/github/followers/changseop-blue?style=flat-square&logo=github&label=FOLLOWERS)
![Stars](https://img.shields.io/github/stars/changseop-blue?style=flat-square&logo=github&label=STARS)

![Role](https://img.shields.io/badge/Role-Blue_Team_%2F_SOC-004386?style=flat-square)
![Region](https://img.shields.io/badge/Region-Korea-555555?style=flat-square)
![Goal](https://img.shields.io/badge/Goal-Entry--level_SOC_Analyst-2ea44f?style=flat-square)

**Contact** `leechangseop71@gmail.com`

<br clear="right">

---

## About Me

Blue Team / SOC 분야를 목표로 학습 중인 Junior Security Analyst입니다.
Linux 보안 로그와 네트워크 패킷을 읽고, 이벤트가 정상인지 비정상인지 판단하는 연습을 해 왔습니다.

**SOC에서 할 수 있는 일**

- Snort/Suricata 탐지 이벤트를 확인하고 룰 단위로 원인을 설명
- Wireshark로 pcap을 분석해 공격 흐름과 증거 정리
- Linux 인증·시스템 로그에서 Source IP와 시간대 기준으로 의심 이벤트 선별
- 분석 과정을 Evidence → Analysis → Conclusion 구조로 문서화

> "왜 이 이벤트를 위협으로 판단했는가?"
> 이 질문에 로그와 네트워크 증거로 답할 수 있는 분석가가 목표입니다.

---

## Security Analysis Workflow

```text
Alert Detection
      ↓
Evidence Collection
      ↓
Log & Network Traffic Analysis
      ↓
Event Correlation
      ↓
Attack Timeline Analysis
      ↓
Threat Classification
      ↓
Incident Response
      ↓
Documentation & Detection Improvement
```

| 단계 | 의미 |
|---|---|
| Alert Detection | SIEM·IDS가 보낸 경고를 확인 |
| Evidence Collection | 관련 로그와 패킷을 수집 |
| Log & Traffic Analysis | 로그와 트래픽에서 의심 행위 확인 |
| Event Correlation | 여러 이벤트를 하나의 흐름으로 연결 |
| Attack Timeline Analysis | 시간순으로 공격 과정 재구성 |
| Threat Classification | 공격 유형과 위험도 판단 |
| Incident Response | 차단·격리 등 대응 방안 정리 |
| Documentation & Detection Improvement | 보고서 작성, 탐지 룰 개선 |

> 위 흐름은 학습 중인 분석 절차이며 실무 경험이 아닙니다.
> 실습은 모두 가상 랩 환경에서 진행했습니다.

---

## Currently

**완료한 실습**

- [x] Ubuntu 기반 Snort 2.9.x IDS/IPS 구성 및 룰 작성
- [x] Suricata → Logstash → Elasticsearch → Kibana 로그 파이프라인 구성
- [x] pfSense Firewall 기본 구성 (WAN/LAN, NAT, 규칙)
- [x] Wireshark 기반 pcap 패킷 분석
- [x] DVWA 대상 Burp Suite / OWASP ZAP 웹 취약점 실습

**진행 중인 학습**

- [ ] Linux 인증 로그(`auth.log`, `secure`) 분석 정리
- [ ] Wazuh 기반 SIEM 환경 학습 <!-- 설치·이벤트 증빙 확인 후 [x] -->
- [ ] SSH Brute Force 시나리오 재현·탐지 <!-- 증빙 확인 후 [x] -->
- [ ] Python 로그 파싱 학습 (python-security-basics)

**자격 및 시험**

- [ ] 정보보안산업기사 과정평가형 외부평가 재응시 준비
- [ ] 정보보안기사 학습 <!-- 실제 학습 중일 때만 유지 -->
- [ ] 리눅스마스터 2급 학습 <!-- 실제 학습 중일 때만 유지 -->

---

## Tech Stack

![Hands-on](https://img.shields.io/badge/Level-Hands--on_직접_설치·실습-2ea44f?style=flat-square)
![Familiar](https://img.shields.io/badge/Level-Familiar_기본_개념·사용법-0969da?style=flat-square)
![Learning](https://img.shields.io/badge/Level-Learning_학습_중-d29922?style=flat-square)

**Operating Systems**

![Ubuntu](https://img.shields.io/badge/Ubuntu-Hands--on-2ea44f?style=flat-square&logo=ubuntu&logoColor=white)
![Rocky Linux](https://img.shields.io/badge/Rocky_Linux-Hands--on-2ea44f?style=flat-square&logo=rockylinux&logoColor=white)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-Hands--on-2ea44f?style=flat-square&logo=kalilinux&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-Hands--on-2ea44f?style=flat-square&logo=windows&logoColor=white)

**SIEM & Security Monitoring**

![Elastic Stack](https://img.shields.io/badge/Elastic_Stack-Hands--on-2ea44f?style=flat-square&logo=elastic&logoColor=white)
![Kibana](https://img.shields.io/badge/Kibana-Hands--on-2ea44f?style=flat-square&logo=kibana&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-Learning-d29922?style=flat-square)

**IDS / IPS**

![Snort](https://img.shields.io/badge/Snort_2.9.x-Hands--on-2ea44f?style=flat-square)
![Suricata](https://img.shields.io/badge/Suricata-Hands--on-2ea44f?style=flat-square)

**Network & Web Security**

![Wireshark](https://img.shields.io/badge/Wireshark-Hands--on-2ea44f?style=flat-square&logo=wireshark&logoColor=white)
![pfSense](https://img.shields.io/badge/pfSense-Hands--on-2ea44f?style=flat-square&logo=pfsense&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-Familiar-0969da?style=flat-square&logo=burpsuite&logoColor=white)
![OWASP ZAP](https://img.shields.io/badge/OWASP_ZAP-Familiar-0969da?style=flat-square&logo=owasp&logoColor=white)

**Programming & Infrastructure**

![Python](https://img.shields.io/badge/Python-Learning-d29922?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-Familiar-0969da?style=flat-square&logo=gnubash&logoColor=white)
![VMware](https://img.shields.io/badge/VMware-Hands--on-2ea44f?style=flat-square&logo=vmware&logoColor=white)
![Git](https://img.shields.io/badge/Git-Hands--on-2ea44f?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Hands--on-2ea44f?style=flat-square&logo=github&logoColor=white)

---

## Core Security Skills

| 분야 | 할 수 있는 일 |
|---|---|
| SIEM | 보안 이벤트를 수집하고 Kibana 대시보드에서 확인 |
| Log Analysis | Linux 인증·시스템 로그에서 로그인 성공/실패 확인 |
| Network Security | TCP/IP 트래픽의 흐름과 이상 징후 분석 |
| IDS / IPS | Snort/Suricata 탐지 이벤트와 룰의 관계 설명 |
| Packet Analysis | Wireshark로 프로토콜별 패킷 추적 |
| Web Security | DVWA로 웹 취약점 재현 및 점검 |
| Incident Analysis | 이벤트를 시간순으로 정리하는 방법 학습 |
| System Security | Linux 계정, 권한, 서비스, 로그 점검 |
| Automation | Python·Bash 기초 |

---

## Featured Security Projects

> 각 프로젝트의 증거(스크린샷, 설정 파일, 로그)는 저장소에 정리합니다.
> `[확인 필요]`는 증빙 확인 후 갱신 예정입니다.

### Project 01. Wazuh SOC Security Monitoring Lab

![Status](https://img.shields.io/badge/Status-Learning-d29922?style=flat-square)
![Wazuh](https://img.shields.io/badge/Wazuh-555555?style=flat-square)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)

<details>
<summary>상세 보기</summary>

| 항목 | 내용 |
|---|---|
| Overview | Ubuntu 기반 Wazuh 보안 모니터링 환경 학습 |
| Objective | Linux 인증 로그를 수집하고 인증 실패 이벤트를 대시보드에서 확인 |
| Lab Environment | VMware, Ubuntu (Wazuh Manager), Linux agent `[확인 필요]` |
| Tools | Wazuh, Linux auth log |
| Implementation | 설치 및 agent 등록 `[확인 필요]` |
| Analysis | 인증 실패 이벤트의 Source IP·Timestamp 확인 `[확인 필요]` |
| Troubleshooting | `[확인 필요]` |
| Evidence | `[확인 필요]` |
| Current Status | 학습 중 |
| What I Learned | `[실제 학습 내용으로 작성]` |

</details>

### Project 02. Snort / Suricata IDS & ELK Lab

![Status](https://img.shields.io/badge/Status-Hands--on-2ea44f?style=flat-square)
![Snort](https://img.shields.io/badge/Snort_2.9.x-316192?style=flat-square)
![Suricata](https://img.shields.io/badge/Suricata-EF4444?style=flat-square)
![Elastic](https://img.shields.io/badge/Elastic_Stack-005571?style=flat-square&logo=elastic&logoColor=white)

<details>
<summary>상세 보기</summary>

| 항목 | 내용 |
|---|---|
| Overview | IDS 탐지 환경과 Suricata 로그 시각화 파이프라인 구성 |
| Objective | 네트워크 트래픽과 IDS 이벤트의 관계 이해 |
| Lab Environment | VMware, Ubuntu (IDS), Ubuntu Server 24.04 (ELK), Kali Linux (공격 호스트) |
| Tools | Snort 2.9.x, Suricata, Logstash, Elasticsearch, Kibana |
| Implementation | Snort 룰 작성 / Suricata EVE JSON → Logstash → Elasticsearch → Kibana |
| Analysis | 탐지 이벤트와 원본 트래픽 대조 `[사례 추가 필요]` |
| Troubleshooting | Ubuntu 24.04 apt sources 경로 변경 이슈, index pattern 설정 오류 |
| Evidence | `[확인 필요]` |
| Current Status | 기본 환경 구성 완료 |
| What I Learned | IDS 이벤트는 수집과 정규화가 되어야 분석이 가능하다는 점 |

</details>

### Project 03. pfSense Firewall Lab

![Status](https://img.shields.io/badge/Status-Hands--on-2ea44f?style=flat-square)
![pfSense](https://img.shields.io/badge/pfSense-D64000?style=flat-square&logo=pfsense&logoColor=white)
![VMware](https://img.shields.io/badge/VMware-607078?style=flat-square&logo=vmware&logoColor=white)

<details>
<summary>상세 보기</summary>

| 항목 | 내용 |
|---|---|
| Overview | VMware 가상 네트워크에서 pfSense 방화벽 구성 |
| Objective | WAN/LAN 구조와 접근 제어 이해 |
| Lab Environment | VMware Workstation, pfSense, Rocky Linux, Windows 10 (내부 호스트) |
| Tools | pfSense, Wireshark |
| Implementation | WAN/LAN 구성, Firewall Rule, NAT |
| Analysis | 허용/차단 트래픽 비교 |
| Troubleshooting | `[확인 필요]` |
| Evidence | `[확인 필요]` |
| Current Status | 기본 구성 및 테스트 완료 |
| What I Learned | 규칙 순서와 방향(In/Out)이 정책 결과를 결정한다는 점 |

🔗 [Repository](https://github.com/changseop-blue/pfsense-portfolio) `[링크 확인 필요]`

</details>

### Project 04. Linux Security Log Analysis

![Status](https://img.shields.io/badge/Status-Learning-d29922?style=flat-square)
![Linux](https://img.shields.io/badge/Linux-Logs-FCC624?style=flat-square&logo=linux&logoColor=black)

<details>
<summary>상세 보기</summary>

| 항목 | 내용 |
|---|---|
| Overview | Linux 인증 로그 분석 학습 |
| Objective | 로그인 성공/실패 패턴과 Source IP 식별 |
| Lab Environment | Rocky Linux / Ubuntu `[확인 필요]` |
| Tools | `auth.log`, `secure`, grep, awk |
| Implementation | `[확인 필요]` |
| Analysis | 반복 인증 실패 패턴 확인 `[확인 필요]` |
| Troubleshooting | `[확인 필요]` |
| Evidence | `[확인 필요]` |
| Current Status | 학습 중 |
| What I Learned | `[실제 학습 내용으로 작성]` |

</details>

---

## Home Security Lab

<p align="center">
  <img src="./assets/home-lab-diagram.svg" alt="Home Security Lab architecture diagram" width="720" />
</p>

<!-- 실제 구축한 VM과 연결만 포함하는지 확인 후 사용. 미구축 장비는 제거.
     이미지가 계속 깨지면 이 블록 전체를 삭제. -->

---

## Education & Certifications

![정보보안산업기사](https://img.shields.io/badge/정보보안산업기사-재응시_준비-f0883e?style=flat-square)
![정보보안기사](https://img.shields.io/badge/정보보안기사-학습_중-d29922?style=flat-square)

| 기관 / 자격 | 과정 | 상태 |
|---|---|---|
| 코리아IT아카데미 | 정보보안산업기사 과정평가형 | 수료 |
| 학점은행제 | 정보보안학 학사 | 진행 중 |
| 정보보안산업기사 | 외부평가 | 재응시 준비 (미취득) |
| 정보보안기사 | 정보보안 이론·실무 | 학습 중 `[확인 필요]` |
| 리눅스마스터 2급 | Linux 시스템 운영 | 학습 중 `[확인 필요]` |

**Career Goal**

```text
Junior Security Analyst → SOC / Security Monitoring → Incident Response & Threat Analysis
```

---

## GitHub Activity

[![Repositories](https://img.shields.io/badge/Repositories-View-181717?style=flat-square&logo=github)](https://github.com/changseop-blue?tab=repositories)
[![Starred](https://img.shields.io/badge/Starred-View-181717?style=flat-square&logo=github)](https://github.com/changseop-blue?tab=stars)
![Last Commit](https://img.shields.io/github/last-commit/changseop-blue/changseop-blue?style=flat-square&label=LAST%20COMMIT)
![Public Repos](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2Fchangseop-blue&query=%24.public_repos&label=PUBLIC%20REPOS&style=flat-square&color=004386)

---

## Security Philosophy

> **"Alert는 시작이고, Evidence가 판단을 만든다."**

무슨 일이 발생했는가 → 왜 발생했는가 → 공격인가 → 어떻게 대응할 것인가.
이 네 질문에 로그와 패킷이라는 객관적 증거로 답하는 분석가가 되겠습니다.
