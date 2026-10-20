# 🎄 크리스마스 카드 메이커 (Christmas Card Maker)

내 사진과 손글씨 편지, 크리스마스 일러스트로 나만의 포토 엽서를 만들고 이미지로 저장하는 웹 애플리케이션입니다.

## 🚀 깃허브 배포 (GitHub Pages) 초간단 3단계

1. **깃허브 저장소(Repository) 생성 & 파일 업로드**:
   - GitHub(https://github.com)에서 **New repository**를 생성합니다 (예: `christmas-card`, Public 설정).
   - 압축 파일(`christmas-card-maker-github.zip`)을 다운로드하여 압축을 풀거나, 아래 파일들을 저장소의 최상위(Root)에 업로드(Push)합니다:
     - `index.html`
     - `style.css`
     - `script.js`
     - `assets/` (배경 이미지 폴더)
     - `README.md`

2. **GitHub Pages 활성화**:
   - 저장소 상단 메뉴의 **Settings** 클릭
   - 좌측 사이드바의 **Pages** 클릭
   - **Build and deployment** > **Source**: `Deploy from a branch` 선택
   - **Branch**: `main`(또는 `master`), 폴더: `/(root)` 선택 후 **Save** 클릭

3. **배포 주소 확인**:
   - 약 1~2분 뒤 상단에 표시되는 `https://<내깃허브아이디>.github.io/<저장소이름>/` 주소로 접속하면 바로 카드를 만들 수 있습니다!

## 📁 파일 구성
- `index.html`: 메인 카드 에디터 화면
- `style.css`: 산타 모자 장식, 종이 질감, 반응형 스타일시트
- `script.js`: 고해상도 캔버스 렌더러, 손글씨 편지 엔진, 사진 필터 및 스티커 엔진
- `assets/images/`: 크리스마스 일러스트 및 실사 감성 배경 이미지 (7종)
