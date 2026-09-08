# 시간강사 주휴수당·급여 자동계산기

학교 시간강사 수업확인표 캡처 이미지를 이용해
주휴수당, 근무수당, 급식비, 고용보험, 실지급액을 계산하는 웹 도구입니다.

## 주요 기능
- 수업확인표 캡처 자동 인식
- '계' 행 숫자를 수업시간으로 반영
- 점심식사 체크에 따른 급식비 공제
- 주차별 주휴수당 발생 여부 및 실제 계산식 표시
- 시간단가 / 급식비 단가 수정
- 엑셀용 한 줄 복사 / CSV 저장
- 클립보드 붙여넣기 자동 선명화
- 캡처 인식 후 이미지 메모리 제거

## GitHub Pages 배포
1. GitHub에서 새 Public repository를 만듭니다.
   예: `time-lecturer-pay`
2. 이 폴더의 파일을 모두 repository 최상단에 업로드합니다.
   - index.html
   - icon.png
   - .nojekyll
3. GitHub 저장소에서 `Settings` → `Pages`로 이동합니다.
4. `Build and deployment`에서
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/(root)`
   로 선택하고 저장합니다.
5. 잠시 후 아래 형식의 주소가 생성됩니다.
   `https://내아이디.github.io/time-lecturer-pay/`

## 사용 환경
- Chrome 또는 Microsoft Edge 권장
- OCR 기능 사용 시 인터넷 연결 필요
- 별도 설치 불필요

## 주의
본 도구는 급여업무를 돕기 위한 실무 보조 계산기입니다.
최종 지급 전 실제 근로계약서, 개근 여부 및 소속 교육청/기관의 최신 지침을 확인하세요.
