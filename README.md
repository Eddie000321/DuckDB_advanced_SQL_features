# DuckDB 기반 고급 SQL 연습

## 개요
이 저장소는 CMU 15-445/645 Intro to Database Systems (Fall 2025) 과제 중 SQL 연습 문제를 따라 하며 DuckDB 기능을 익히기 위한 개인 실습 공간입니다. 학습 목적의 개인 프로젝트이며, 모든 문제 설명과 자료의 저작권은 카네기 멜론 대학교(Carnegie Mellon University)에 있습니다.

## 과제 출처
- 과제 설명 및 공식 자료: https://15445.courses.cs.cmu.edu/fall2025/assignments.html
- 위 링크에서 제공되는 공개 자료를 참고하며, 원본 과제 PDF는 저장소에 포함하지 않고 로컬에서만 참고합니다.

## 저장소 구성
- `q1_sample.duckdb.sql` ~ `q6_upsert.duckdb.sql`: 각 문제에 대한 DuckDB SQL 스크립트
- `lahman-cmudb2025.db`: 과제에서 제공된 Lahman 데이터베이스 스냅샷
- (로컬 전용) 과제 설명 PDF는 공개 저장소에 추가하지 않습니다.

## 실행 방법
1. DuckDB CLI 설치 후 프로젝트 루트에서 명령을 실행합니다.
2. 예시: `duckdb -c ".read q1_sample.duckdb.sql"`
3. 필요 시 SQL 스크립트 내 주석을 참고하거나 직접 쿼리를 수정하며 실습합니다.

## 참고 및 저작권 고지
- 모든 문제 설명과 데이터셋은 CMU 15-445/645 강의에서 제공된 자료입니다.
- 본 저장소는 교육용 개인 연습 공간으로, 결과물과 풀이 공유 시 강의 정책을 준수합니다.
