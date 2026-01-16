# 기여 가이드

[English](CONTRIBUTING.md)

NPB 히스토리컬 데이터베이스에 관심을 가져주셔서 감사합니다!

## 기여 방법

### 1. 이슈 제출 (쉬움)

GitHub Issues를 통해 제보:
- **Nickname** - 선수 별명 제보
- **Pitch Repertoire** - 투수 구종 제보
- **Stat Correction** - 스탯 오류 신고
- **Missing Player** - 누락된 선수 신고
- **Feature Request** - 기능 제안

코딩 필요 없음! 템플릿만 작성하시면 됩니다.

### 2. Pull Request (파일 기여)

로고, 유니폼, 구장 등 파일을 직접 기여하고 싶을 때.

#### 방법 A: 웹 업로드 (Git 필요 없음)

1. 레포지토리 우측 상단 "Fork" 클릭
2. 본인 Fork에서 파일 추가할 폴더로 이동
3. "Add file" → "Upload files" 클릭
4. 파일 드래그 앤 드롭
5. "Commit changes" 클릭
6. "Contribute" → "Open pull request" 클릭
7. Pull Request 제출

#### 방법 B: Git 사용

##### 1단계: Fork

레포지토리 페이지 우측 상단의 "Fork" 버튼 클릭.

##### 2단계: Clone

```bash
git clone https://github.com/내계정/OOTP_NPB_Historical.git
cd OOTP_NPB_Historical
```

##### 3단계: 파일 추가

적절한 폴더에 파일 추가:

| 콘텐츠 | 폴더 | 포맷 |
|--------|------|------|
| 팀 로고 | `logos/` | PNG 150x150 |
| 저지 | `uniforms/jerseys/` | PNG |
| 바지 | `uniforms/pants/` | PNG |
| 모자 | `uniforms/ballcap/` | PNG |
| 양말 | `uniforms/socks/` | PNG |
| 구장 | `ballparks/` | - |
| 스케줄 | `schedules/` | - |
| 페이스젠 | `fg_files/` | - |

##### 4단계: Commit & Push

```bash
git add .
git commit -m "Add [기여 내용 설명]"
git push
```

##### 5단계: Pull Request 생성

1. GitHub에서 본인 Fork로 이동
2. "Contribute" → "Open pull request" 클릭
3. 변경 내용 설명 작성
4. Pull Request 제출

## 파일 이름 규칙

OOTP에 등록된 팀명을 사용하세요 (실제 기업명 X).

### 로고
```
팀명_시작연도-종료연도_hex1_hex2.png
```
예시:
- `tokyo_giants_1961-1974_F97709_000000.png`
- `tokyo_giants_1975-1992_F97709_000000.png`
- `osaka_tigers_1961-1999_FFE100_000000.png`

### 유니폼
```
타입_팀명_시작연도-종료연도.png (홈)
타입_팀명_away_시작연도-종료연도.png (원정)
타입_팀명_alt_시작연도-종료연도.png (대체)
```
타입: `jerseys`, `pants`, `caps`, `socks`

예시:
- `jerseys_Tokyo_Giants_1975-1992.png`
- `jerseys_Tokyo_Giants_away_1975-1992.png`
- `pants_Tokyo_Giants_1975-1992.png`
- `caps_Tokyo_Giants_away_1975-1992.png`

## 질문이 있으신가요?

**Feature Request** 템플릿으로 이슈를 열어주세요.
