# NPB 히스토리컬 데이터베이스 (OOTP용)

[English](README.md)

OOTP Baseball용 NPB (일본프로야구) 히스토리컬 데이터베이스입니다.

## 수록 범위

- **연도**: 1936-2025
- **리그**: 센트럴 리그, 퍼시픽 리그
- **2군**: 니군 리그 (이스턴/웨스턴) 2008-2025

## 파일 구조

### stats/
- `historical_database.odb` - 메인 NPB 데이터베이스
- `historical_lineups.odb` - 경기 라인업
- `historical_minor_database.odb` - 2군 데이터
- `historical_transactions.odb` - 트랜잭션 기록
- 기타 CSV 파일들 (팀, 선수, 로스터 등)

### 기타 폴더
- `logos/` - 팀 로고
- `ballparks/` - 구장 파일
- `uniforms/` - 유니폼 파일 (모자, 저지, 바지, 양말)
- `schedules/` - 스케줄 파일
- `fg_files/` - 페이스젠 파일
- `tools/` - 툴 (스케줄러 등)

## 설치 방법

1. 파일 다운로드
2. OOTP 설치 폴더에 배치

## 기여하기

오류를 발견했거나 별명을 추가하고 싶으신가요?

- **Issues** 탭에서 요청을 제출해주세요
- 사용 가능한 템플릿:
  - **Nickname** - 선수 별명 제보
  - **Pitch Repertoire** - 투수 구종 제보
  - **Stat Correction** - 스탯 오류 신고
  - **Missing Player** - 누락된 선수 신고
  - **Feature Request** - 기능 제안

## 라이선스

이 프로젝트는 OOTP Baseball 개인 사용 목적입니다.
