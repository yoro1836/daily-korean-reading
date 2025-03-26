# Daily Korean Reading

매일 새로운 비문학 독해 학습지를 생성하는 웹 애플리케이션입니다.

## 기능

- Google Gemini AI를 활용한 비문학 지문 자동 생성
- 다양한 유형의 문제 제공:
  - 지문 내용 일치/불일치 확인 문제
  - 각 문단의 중심문장 찾기
  - 전체 내용 요약하기
- 학생 정보 입력 기능
- A4 용지에 최적화된 인쇄 레이아웃
- 문제와 정답 페이지 자동 생성

## 사용 방법

1. [Google AI Studio](https://makersuite.google.com/app/apikey)에서 API 키 발급
2. 웹 페이지에서 발급받은 API 키 입력
3. "새로운 지문" 버튼을 클릭하여 학습지 생성
4. 학생 정보 입력 후 "인쇄하기" 버튼으로 출력

## 로컬에서 실행하기

1. 저장소 클론:
   ```bash
   git clone https://github.com/jkf87/daily-korean-reading.git
   cd daily-korean-reading
   ```

2. 웹 서버로 실행:
   - Python의 경우:
     ```bash
     python -m http.server 8000
     ```
   - Node.js의 경우:
     ```bash
     npx http-server
     ```

3. 브라우저에서 `http://localhost:8000` 접속

## 기술 스택

- HTML5
- CSS3
- Vanilla JavaScript
- Google Gemini API

## 라이선스

MIT License 