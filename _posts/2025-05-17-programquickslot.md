---
layout: single
title: "Program Quickslot - 원하는 프로그램을 단축키 한 번으로 실행하고 정돈하세요!(출시 대기)"
date: 2025-05-17
permalink: /products/programquickslot/
categories: [products]
tags: [MS Store, 단축키 실행, 자동 배치, 생산성, 유틸리티]
sidebar:
  nav: "products"
classes: wide
---

## 🔹 제품 개요

**Program Quickslot**은 자주 사용하는 프로그램들을 미리 등록한 단축키로 한 번에 실행하고, **화면 위치와 크기까지 자동으로 정렬**해주는 Windows 유틸리티입니다.  
개발, 방송, 사무 등 복잡한 작업 환경을 단 몇 초 만에 세팅하여, **반복적인 수동 작업에서 사용자를 해방**시켜줍니다.

---

## 🔧 기능 소개

| 기능 | 설명 |
|------|------|
| 단축키 지정 실행 | Ctrl + Shift + F1~F12에 프로그램을 등록해 단축키만으로 실행 |
| 다중 앱 자동 배치 | 각 프로그램을 설정한 위치와 크기로 자동 정렬 |
| 작업 공간 저장 | 자주 사용하는 앱 조합을 하나의 세트로 관리 가능 |
| 유연한 사용처 | 개발, 스트리밍, 사무 등 다양한 작업 환경에 활용 가능 |

---

## 🛠️ 기술 스택

- **언어**: C++
- **프레임워크**: MFC (Microsoft Foundation Classes)
- **사용 기술**:
  - Win32 API (ShellExecute, FindWindow, MoveWindow 등으로 창 제어)
  - GDI를 활용한 UI 구성

---

## 🚀 배포 방식

- **배포 플랫폼**: Microsoft Store
- **설치 방식**: MSI (Visual Studio의 Setup 프로젝트로 패키징)
- **운영 체제 요구사항**: Windows 10 이상

👉 [Microsoft Store에서 설치하기(출시 대기)](-)

---

## 📈 개발 후기

Program Quickslot은 **반복적인 작업 환경 세팅**을 간소화하고자 시작한 프로젝트입니다.

- **아이디어의 출발**  
  매번 수동으로 앱을 실행하고 정렬하는 과정이 비효율적이라는 문제의식에서 출발했습니다.

- **기술적 도전**  
  각 프로그램이 실행된 직후 윈도우 핸들을 안정적으로 찾기 위해, 프로세스 지연 및 폴링 방식 제어 로직을 구현했습니다.  
  창 위치를 정밀하게 조정하기 위해 Win32 API 기반 수동 배치 구현도 필요했습니다.

- **배포 과정**  
  Visual Studio의 Setup 프로젝트를 활용해 MSI 설치 파일을 구성했고,  
  Microsoft Store에 등록하면서 **제품 제거 시 잔여 파일 삭제** 요건과 **코드 서명** 이슈를 해결했습니다.

이번 프로젝트를 통해 **MFC UI 설계, Windows 설치 패키징, 배포 정책 대응**까지 폭넓게 경험할 수 있었고,  
소프트웨어가 사용자에게 실질적 가치를 주기 위해 고려해야 할 요소들을 배우는 계기가 되었습니다.

---

> 피드백 및 제보는 언제든 환영합니다:  
📮 [개발자 이메일: iarnmango@gmail.com](mailto://iarnmango@gmail.com)

---

## 개인정보 처리 방침

Program Quickslot은 사용자의 개인정보를 수집하거나 저장하지 않습니다.
이 애플리케이션은 인터넷에 연결하지 않으며, 사용자의 이름, 이메일, 위치 정보, 기기 정보 등 어떠한 개인정보도 수집하지 않습니다.

앱 내 설정(단축키, 프로그램 경로, 창 위치 등)은 오직 사용자 컴퓨터의 로컬 환경에만 저장되며, 외부 서버로 전송되지 않습니다.

개인정보와 관련된 문의사항이 있으실 경우 아래 이메일로 연락 주시기 바랍니다.  
이메일: iarnmango@gmail.com

## Privacy Policy

Program Quickslot does not collect or store any personal information.
This application does not connect to the internet and does not gather any personally identifiable data such as your name, email address, location, or device information.

All settings (such as shortcuts, program paths, and window positions) are stored locally on your device and are never transmitted to any server.

If you have any questions regarding privacy, please contact us at:  
Email: iarnmango@gmail.com

---
