# Seal Swimming

직접 그린 그래픽과 Unity를 활용해 제작한 **수영 게임**입니다.

바다에 쓰레기를 버리지 말자는 취지로 빠르게 디자인 및 구현했습니다.

게임에 사용된 **배경, 캐릭터, 장애물, UI 요소까지 모두 직접 그림으로 하나씩 제작**해 구현했으며, Unity WebGL 빌드를 통해 웹에서도 실행할 수 있도록 완성했습니다.

## 게임 설명

1. 터치로 **범고래와 북극곰을 피하세요!**
2. 빙하와 바다의 쓰레기는 부딪혀도 되지만 피하는 것이 좋습니다.
3. **피할 때마다 +1점**이 올라갑니다.
4. 화면 밖으로 나가면 게임이 종료됩니다.

## 데모

[Netlify에서 실행하기!](https://lovelysealswimming.netlify.app)

## 폴더 구성

- `Build/`, `TemplateData/`, `index.html` : Unity WebGL 빌드 결과물
- `Seal5.unitypackage` : Unity 프로젝트 에셋 패키지

## 기술 스택

- **Unity**
  - 씬 구성, 애니메이션(Animation), 프리팹(Prefab), UI, Physics2D 시스템 활용
  - WebGL 빌드를 통한 웹 배포
- **C#**
  - 플레이어 이동, 장애물 스폰 및 움직임, 충돌 처리, 점수 로직
- **Photoshop/Clip Studio (또는 기타 툴)**
  - 배경, 캐릭터(물개, 범고래, 북극곰), 장애물(빙하, 쓰레기) 직접 제작
- **HTML/CSS/JavaScript**
  - Unity WebGL 빌드 실행 및 기본 뷰어 구성
- **Netlify**
  - 웹 배포

## 배포

본 프로젝트는 Netlify에 연동되며, 버전관리는 따로 이루어지고 있지 않습니다. 고도화 작업 필요시 진행됩니다.

## 라이선스

MIT License
