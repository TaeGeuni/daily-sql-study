# Daily SQL Study

매일매일 꾸준히 LeetCode와 HackerRank의 SQL 문제를 풀고 학습한 내용을 기록하는 저장소입니다. 

## 학습 목표 (Motivation)
- 1일 1쿼리: 하루 한 문제 이상 SQL 문제를 해결하고 TIL(Today I Learned) 작성하기
- 성능 최적화(Tuning) 감각 향상: 단순히 결과를 내는 쿼리를 넘어, PostgreSQL의 `EXPLAIN`을 활용해 실행 계획과 인덱스를 고려하는 엔지니어링 사고방식 기르기

## 사용 환경 (Tech Stack)
- RDBMS: PostgreSQL
- IDE / Tools: Visual Studio Code (SQLTools Extension)

## 저장소 구조 (Directory Structure)

문제 출처와 난이도별로 디렉토리를 분리하여 관리합니다.

```text
📦 daily-sql-study
 ┣ 📂 LeetCode
 ┃ ┣ 📂 Easy
 ┃ ┃ ┣ 📜 175_Combine_Two_Tables.sql
 ┃ ┃ ┗ 📜 175_Combine_Two_Tables.md
 ┃ ┣ 📂 Medium
 ┃ ┗ 📂 Hard
 ┣ 📂 HackerRank
 ┃ ┣ 📂 Basic
 ┃ ┣ 📂 Intermediate
 ┃ ┗ 📂 Advanced
 ┗ 📜 README.md
 ```

## 파일 작성 규칙 (Convention)
각 문제에 대해 다음 두 가지 파일을 작성합니다.

1. 문제이름.sql: 정답으로 통과한 SQL 쿼리문
2. 문제이름.md: 문제의 핵심 요구사항, 접근 방식(JOIN, 서브쿼리 등), 쿼리 성능 분석 및 새롭게 배운 점(TIL) 정리

## 커밋 메시지 규칙 (Commit Convention)
- `[플랫폼] 난이도 - 문제명` 형식으로 작성합니다.

- 예시:
    - `feat: [LeetCode] Easy - 175. Combine Two Tables`
    - `docs: [HackerRank] Basic - Revising the Select Query I 풀이 추가`