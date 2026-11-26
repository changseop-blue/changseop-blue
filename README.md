<img align="right" src="https://raw.githubusercontent.com/changseop-blue/changseop-blue/main/assets/profile-character.png" width="160" alt="Changseop Lee character" />

# Changseop Lee (이창섭)

**Junior Security Analyst · Blue Team / SOC**

로그와 네트워크 트래픽에서 공격의 흔적을 찾고,
증거를 기반으로 위협을 분석하는 보안 분석가를 목표로 합니다.

![Profile Views](https://komarev.com/ghpvc/?username=changseop-blue&style=flat-square&color=blue&label=PROFILE+VIEWS)
![Followers](https://img.shields.io/github/followers/changseop-blue?style=flat-square&logo=github&label=FOLLOWERS)
![Stars](https://img.shields.io/github/stars/changseop-blue?style=flat-square&logo=github&label=STARS)

![Blue Team](https://img.shields.io/badge/Role-Blue_Team_%2F_SOC-004386?style=flat-square)
![Location](https://img.shields.io/badge/Region-Korea-555555?style=flat-square)
![Status](https://img.shields.io/badge/Status-Open_to_Entry--level_SOC-2ea44f?style=flat-square)

**Contact** `leechangseop71@gmail.com`

<br clear="right">

---

## About Me

Blue Team / SOC 분야를 목표로 학습 중인 Junior Security Analyst입니다.
Linux 보안 로그와 네트워크 패킷을 읽고, 이벤트가 정상인지 비정상인지 판단하는 연습을 해 왔습니다.

**SOC에서 할 수 있는 일**

- IDS(Snort, Suricata) 탐지 이벤트를 확인하고 룰 단위로 원인을 설명
- Wireshark/tshark로 pcap을 분석해 공격 흐름과 증거 정리
- Linux 인증·시스템 로그에서 Source IP와 시간대 기준으로 의심 이벤트 선별
- 분석 과정을 Evidence → Analysis → Conclusion 구조로 문서화

> "Alert는 시작이고, Evidence가 판단을 만든다."

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

> 위 흐름은 학습 중인 분석 절차이며, 실무 경험이 아닙니다.
> 현재 실습은 가상 랩 환경에서 진행했습니다.

---

## Currently

**완료한 실습**

- [x] Ubuntu 기반 Snort 2.9.x IDS/IPS 구성 및 룰 작성
- [x] Suricata → Logstash → Elasticsearch → Kibana 로그 파이프라인 구성
- [x] pfSense Firewall 기본 구성 (WAN/LAN, NAT, 규칙)
- [x] Wireshark 기반 pcap 패킷 분석 및 보고서 작성
- [x] DVWA 대상 Burp Suite / OWASP ZAP 웹 취약점 실습
- [x] Next.js 포트폴리오 사이트 구축 및 직접 호스팅

**진행 중인 학습**

- [ ] Linux 인증 로그(`auth.log`, `secure`) 분석 정리
- [ ] Wazuh 기반 SIEM 환경 학습 <!-- 증빙 확인 후 [x]로 변경 -->
- [ ] SSH Brute Force 시나리오 재현·탐지 <!-- 증빙 확인 후 변경 -->
- [ ] Python 로그 파싱 및 보안 자동화 학습 (python-security-basics)

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
![Logstash](https://img.shields.io/badge/Logstash-Hands--on-2ea44f?style=flat-square&logo=logstash&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-Learning-d29922?style=flat-square)

**Network Security**

![Wireshark](https://img.shields.io/badge/Wireshark-Hands--on-2ea44f?style=flat-square&logo=wireshark&logoColor=white)
![pfSense](https://img.shields.io/badge/pfSense-Hands--on-2ea44f?style=flat-square&logo=pfsense&logoColor=white)
![TCP/IP](https://img.shields.io/badge/TCP%2FIP-Familiar-0969da?style=flat-square)

**IDS / IPS**

![Snort](https://img.shields.io/badge/Snort_2.9.x-Hands--on-2ea44f?style=flat-square)
![Suricata](https://img.shields.io/badge/Suricata-Hands--on-2ea44f?style=flat-square)

**Web Security**

![Burp Suite](https://img.shields.io/badge/Burp_Suite-Familiar-0969da?style=flat-square&logo=burpsuite&logoColor=white)
![OWASP ZAP](https://img.shields.io/badge/OWASP_ZAP-Familiar-0969da?style=flat-square&logo=owasp&logoColor=white)

**Programming & Scripting**

![Python](https://img.shields.io/badge/Python-Learning-d29922?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-Familiar-0969da?style=flat-square&logo=gnubash&logoColor=white)

**Infrastructure & Development**

![VMware](https://img.shields.io/badge/VMware-Hands--on-2ea44f?style=flat-square&logo=vmware&logoColor=white)
![Git](https://img.shields.io/badge/Git-Hands--on-2ea44f?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Hands--on-2ea44f?style=flat-square&logo=github&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-Hands--on-2ea44f?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-Hands--on-2ea44f?style=flat-square&logo=typescript&logoColor=white)

---

## Core Security Skills

| 분야 | 할 수 있는 일 |
|---|---|
| SIEM | 보안 이벤트를 수집하고 Kibana 대시보드에서 확인 |
| Log Analysis | Linux 인증·시스템 로그에서 로그인 성공/실패 확인 |
| Network Security | TCP/IP 트래픽의 흐름과 이상 징후 분석 |
| IDS / IPS | Snort/Suricata 탐지 이벤트와 룰의 관계 설명 |
| Packet Analysis | Wireshark로 프로토콜별 패킷 추적, 인증 정보·파일 전송 흔적 확인 |
| Web Security | DVWA로 SQL Injection 등 웹 취약점 재현 및 점검 |
| Incident Analysis | 이벤트를 시간순으로 정리하는 방법 학습 |
| System Security | Linux 계정, 권한, 서비스, 로그 점검 |
| Automation | Python·Bash 기초, 로그 파싱 학습 |

---

## Featured Security Projects

> 각 프로젝트의 상세 증거(스크린샷, 설정 파일, 로그)는 해당 저장소에 정리합니다.
> `[확인 필요]`로 표시된 항목은 증빙 확인 후 갱신 예정입니다.

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
| Evidence | `[확인 필요]` 스크린샷 / 설정 파일 |
| Current Status | 학습 중 |
| What I Learned | `[실제 학습 내용으로 작성]` |

</details>

### Project 02. Suricata IDS & Network Security Lab

![Status](https://img.shields.io/badge/Status-Hands--on-2ea44f?style=flat-square)
![Suricata](https://img.shields.io/badge/Suricata-EF4444?style=flat-square)
![Elastic](https://img.shields.io/badge/Elastic_Stack-005571?style=flat-square&logo=elastic&logoColor=white)
![Kali](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)

<details>
<summary>상세
