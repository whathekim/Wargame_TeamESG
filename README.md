# 🧠 TeamESG Wargame

> Team ESG가 제작한 CTF 스타일 웹 기반 워게임 프로젝트입니다.  
> 현실 기반 시나리오로 보안 취약점을 학습할 수 있도록 구성되어 있습니다.

![Wargame_TeamESG_gif](Wargame_TeamESG.gif)

---

## 🎯 프로젝트 소개

**TeamESG_Wargame**은 실제 웹 공격 시나리오를 반영한 CTF 스타일 학습 플랫폼입니다.  
사용자는 다양한 인증 우회, 파라미터 조작, 디렉토리 트래버설 등의 기법을 실습하며,  
보안 사고에 대응할 수 있는 실전 역량을 기를 수 있습니다.

이 프로젝트는 정보보안 입문자 및 CTF 준비자를 위한 훈련 환경으로 활용됩니다.

---

## 🧰 주요 문제 및 취약점

| 번호 | 문제 이름                              | 핵심 취약점                          |
|------|----------------------------------------|--------------------------------------|
| 01   | 접근 노드에 접속                        | 페이지 소스 확인                     |
| 02   | ESG 멤버 로그 추적 시스템               | 파라미터 조작                        |
| 03   | ESG 유저 파일                           | IDOR (수평 권한 상승)                |
| 04   | ESG 인증 포털                           | SQL Injection                        |
| 05   | 계정 UID 탈취                          | 디렉토리 트래버설                    |
| 06   | ESG 내부 문서 확인                     | User-Agent 기반 인증 우회           |
| 07   | 프로그램을 이용한 조작                  | HTTP Method Manipulation            |
| 08   | ESG 전용 입구를 찾아라                  | Brute Force Attack                  |
| 09   | 내부 접근 제한 시스템                   | HTTP Header 기반 인증 우회          |
| 10   | ESG 금고 탈취                          | URL Encoding을 통한 접근 우회       |

---

## 📝 워크스루 문서

문제별 상세 풀이가 포함된 워크스루 문서는 아래 링크에서 확인할 수 있습니다:  
👉 [Walkthrough 다운로드 (pdf 파일)](https://github.com/whathekim/Wargame_TeamESG/blob/main/ESG%20Walkthrough%20%EC%A1%B0%EB%B2%94%EA%B7%BC.pdf)

---

## 📄 라이선스

본 프로젝트는 **KOREAIT** 보안 실습 과정에서 제작되었습니다.

---
