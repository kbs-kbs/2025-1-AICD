# 2025-1-AICD
2025학년도 1학기 인공지능캡스톤디자인

# 아이디어 제안서 구성
## 표지
- 인공지능캡스톤디자인 프로젝트 아이디어 제안서
- 팀 식스센스
- 학번 김보성

## 주제 및 개요
- AI 기반 폴더 트리 생성/파일 분류 + 요약 리마인더 데스크톱 앱
- 수집한 사이트나 문서를 나중에 볼 파일을 자동으로 분류해주고 학습을 미뤄둔 파일의 내용을 요약해서 상기시켜주는 정보 재고관리 앱
- 
- 


## 목차
1. 배경 및 목적
2. 시장 분석
3. 시스템 기능
4. 유사 서비스와의 차별성 (포지셔닝)
5. 사용 기술 및 개발 도구
6. 기대 효과

## 배경 및 목적
**배경**
- 개인은 생산하기 위해 정보를 수집하여 지식으로 만들고 자신의 상황에 맞게 활용하여야 함
- 정보 과잉은 확신보다 의심을 가지게 하여 정보의 소화를 방해함
- 현대인의 정보-지식 변환에 시간이 걸리다 보니 개인이 가진 정보의 재고가 늘어남 -> 파일 정리 필요
- 개인의 상황이 변화함에 따라 수집한 정보가 필요없어지는 경우도 생김 (정보의 부패) -> 일정 기간 이내 소진 필요
- 하지만 파일을 생성할 때 곧바로 알맞은 폴더로 옮겨놓거나, 주기적으로 예전 파일을 하나씩 열어보는 작업은 번거로움

**목표**
- 정보의 재고관리를 돕기 위해 파일을 대신 정리해주고, 주기적으로 파일 내용을 대신 읽고 알려주는 리마인더 기능을 포함한 데스크톱 앱 개발   

**기대 효과**
- 개인의 생산성 증대   

## 시장 분석
**목표 사용자** 타겟
- 다양한 것을 학습해야하는 학생
- 학제간 연구를 하는 연구가
- 프로젝트를 하는 직장인
- 프로덕트를 만들어야하는 사업가

**사용자 수요 요약** 니즈
- 학습량이 많은 직군


## 시스템 기능
**주요 기능 구성도**

**사용자 시나리오**
- 배경화면이 아이콘으로 꽉 차있는 사람
- 나중에 정리하려고 한 폴더에 모아 놓아야지
- 나중에 읽어야지 스크랩 하고 시간이 지나고 보면 더이상 쓸모없는 파일
- 폴더 이름을 뭘로 하지?

## 유사 서비스와의 차별성 (포지셔닝)

|서비스|기능|공통점|차이점|
|---|---|---|---|
|TagSpaces|태깅 기반 파일 정리|로컬 우선|Web Clipper를 통한 스크랩 기능, 자동 분류/요약 리마인더 기능 없음|
|Obsidian + (Templater, Reminder 등 플러그인)|로컬 우선, 문서 요약, 리마인더|확장성이 높음, 자동 분류 기능 없음/요약 기능과 리마인더 기능 따로|
|Local File Organizer|||
|본 제품|||

## 사용 기술 및 개발 도구
파이썬 러스트

K-means를 활용한 문서 군집 분석을 통해 폴더 트리를 만들고 koBart를 통해 오래된 문서를 요약하여 주기적으로 알림을 보냄

## 기대 효과
- 파일 정리 시간을 대폭 절감하여 업무 효율성 향상
- 불필요한 파일을 쉽게 정리할 수 있어 저장 공간 관리 용이

ai로 팩트체크를 할 수 있을까?
거짓된 정보가 퍼져있다면 빅데이터로 처리할 수 없음
딥리서치가 필요

암기력이 높으면 많은 정보를 수용해서 바로 배치학습
낮으면 배치사이즈 작음
기존 지식으로 진위를 가려 지식을 늘리는것
진위를 가리는 것이 곧 이해이자 공부
학습률을 높이는 것은 진위를 별로 가리지 않겠다는 의미
