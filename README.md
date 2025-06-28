# Lovely Seal Swimming

Unity WebGL로 제작한 귀여운 물개 수영 애니메이션/게임입니다.

[![Netlify Status](https://api.netlify.com/api/v1/badges/965d072c-2508-4509-9c55-0e9c8539021a/deploy-status)](https://app.netlify.com/sites/lovelysealswimming/deploys)

---

## 데모

👉 [실행하러 가기](https://lovelysealswimming.netlify.app)

---

## 구성

- `Build/`, `TemplateData/`, `index.html` : Unity WebGL 빌드 파일
- `Seal5.unitypackage` : Unity 에셋 패키지

---

## 로컬 실행 방법

Unity WebGL은 보안(CORS) 문제로 파일을 직접 열어 실행할 수 없으므로, 다음과 같이 실행합니다.

### Python HTTP Server

```bash
python -m http.server 8000
