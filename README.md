# 🍱 오늘 점심 어디가?

Claude AI가 네이버를 실시간 검색해서 주변 실제 맛집을 추천해주는 웹앱이에요.

## 사용 방법

1. [오늘 점심 어디가?](https://YOUR_GITHUB_USERNAME.github.io/lunch-recommender) 접속
2. Anthropic API 키 입력 (브라우저에만 저장, 외부 전송 없음)
3. 위치·음식 종류·거리·예산 설정
4. 🎲 AI 점심 추천받기!

## API 키 발급

- [console.anthropic.com](https://console.anthropic.com) 에서 무료로 발급 가능
- 키는 본인 브라우저에만 저장되며 서버로 전송되지 않아요

## GitHub Pages 배포

이 저장소를 fork 하고 Settings → Pages → Source: Deploy from branch (main) 선택하면 자동 배포돼요.

## 기술 스택

- 순수 HTML/CSS/JS (의존성 없음)
- Anthropic Claude API (web_search 도구)
- GitHub Pages 호스팅
