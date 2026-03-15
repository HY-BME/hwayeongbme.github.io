---
title: "VS Code Python Debuging 시 느려지는 현상 해결"
excerpt: "Python 환경 검색 방식을 변경하거나 캐시를 초기화하여 해결"

categories:
  - Categories5
tags:
  - [tag1, tag2]

permalink: /categories5/post-name-here-5/

toc: true
toc_sticky: true

date: 2026-03-15
last_modified_at: 2026-03-15
---

## 🦥 본문

방법 1: Python Locator 설정 변경 (권장)
새로 도입된 native 방식 대신, 기존의 안정적인 js 방식으로 검색 도구를 변경하면 문제가 즉시 해결됩니다.

1. VS Code에서 설정(Settings)을 엽니다. (단축키: Ctrl + , 또는 Cmd + ,)
2. 검색창에 Python Locator를 입력합니다.
3. Python > Locator 항목을 찾아 드롭다운 메뉴에서 native를 js 로 변경합니다.
4. VS Code를 재시작합니다.

<img width="928" height="204" alt="Image" src="https://github.com/user-attachments/assets/fe5d5401-df3e-4250-b294-a6ed2e89eefc" />

&nbsp;
&nbsp;

방법 2: 파이썬 Language Server 설정 변경 (Pylance/Jedi) 

설정 방법: Ctrl + , (Mac: Cmd + ,) -> python language server 검색 -> Jedi 대신 Pylance 선택.
Jedi 비활성화: 코드 자동 완성이 너무 느리다면 설정에서 Jedi Enable을 체크 해제(False)합니다. 

<img width="494" height="117" alt="Image" src="https://github.com/user-attachments/assets/f1de45e7-09e5-43d7-a896-5232262f93e6" />
