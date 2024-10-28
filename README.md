# Google Drive Appdata Test

* **Slack**에 **DeepL** API를 연동해 번역봇으로 사용하기 위한 토이 프로젝트

## Overview

Nodejs를 기반으로 @slack/web-api 라이브러리를 이용해 DeepL API로 채팅을 번역하는 Slack 번역 봇 서버입니다.

## 개발 환경

* **NodeJS:** `v20.16.0` (LTS)
* **PackageManager:** `npm`

## Getting Started

### 실행

```bash
# Module Install
npm install

# Server start
npm run start
```

### 환경변수

* **SLACK_BOT_TOKEN**: *OAuth & Permissions-OAuth Tokens*의 **Bot User OAuth Token**을 입력합니다.
* **DEEPL_API_KEY**: [DeepL API Key](https://www.deepl.com/en/your-account/keys)를 입력합니다.

```plaintext
SLACK_BOT_TOKEN=
DEEPL_API_KEY=
```



## Reference

* [https://api.slack.com/](https://api.slack.com/)
* [https://www.deepl.com/en/your-account/subscription](https://www.deepl.com/en/your-account/subscription)
* [https://velog.io/@devand/%EC%8A%AC%EB%9E%99-Web-API-%EB%A5%BC-%EC%9D%B4%EC%9A%A9%ED%95%B4%EB%B3%B4%EC%9E%90-1](https://velog.io/@devand/%EC%8A%AC%EB%9E%99-Web-API-%EB%A5%BC-%EC%9D%B4%EC%9A%A9%ED%95%B4%EB%B3%B4%EC%9E%90-1)