# 스케치

각 층의 설계 그림을 원본과 이미지 두 형태로 보관한다.

| 파일 | 용도 |
|---|---|
| `layer-N.excalidraw` | 원본. JSON이므로 git diff로 층별 변화를 추적할 수 있고, 편집이 가능하다 |
| `layer-N.png` | GitHub 웹에서 바로 보기 위한 이미지. Excalidraw 내보내기에서 **"장면 포함(Embed scene)"** 을 켜서 저장하면 이 PNG를 다시 Excalidraw에 끌어다 놓았을 때 편집 상태로 열린다 |

정리된 결론은 각 층 문서(`docs/NN-layerN.md`)에 Mermaid로 남긴다.
스케치는 **결론에 이르기까지의 사고 과정**을 남기는 것이 목적이므로, 중간에 버린 그림도 지우지 않는다.

작도 도구: https://excalidraw.com (무료, 로그인 불필요)
