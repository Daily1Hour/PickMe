# 면접 기록 서비스 PICK ME

> 기존의 문서 서비스에서 면접에 특화된 새로운 기록 플랫폼  
> 기존 채용 플랫폼에서 서류 전형 기록 → 면접 기록 서비스에서 면접 전형 기록

## 팀 소개

|          [김아영](https://github.com/Cameist)           |             [김영진](https://github.com/yxxngjxn)              |             [안진수](https://github.com/Awlstn)              | [정원철](https://github.com/NarciSource)                      |
| :-----------------------------------------------------: | :------------------------------------------------------------: | :----------------------------------------------------------: | ------------------------------------------------------------- |
| ![A0](https://avatars.githubusercontent.com/u/86555254) | ![Youngjin](https://avatars.githubusercontent.com/u/141807721) | ![Jinsoo](https://avatars.githubusercontent.com/u/116646091) | ![Woncheol](https://avatars.githubusercontent.com/u/26417221) |

## 프로젝트 소개

### 프론트엔드 프로젝트

#### [PickMe-MFA-Root](https://github.com/Daily1Hour/PickMe-MFA-Root); 마이크로 프론트엔드 통합

- Single-SPA 응용 프로그램을 시작하는 프론트엔드의 루트 프로젝트

#### [PickMe-Style-Guide](https://github.com/Daily1Hour/PickMe-Style-Guide); 스타일 가이드

- Module Federation을 활용한 컴포넌트 동적 제공
- Storybook을 활용한 컴포넌트 문서화

#### [PickMe-Nav-Application](https://github.com/Daily1Hour/PickMe-Nav-Application); 네비게이션 마이크로 프론트엔드

- 웹사이트 공통 네비게이션 공간 렌더링

#### [PickMe-Auth-Parcel](https://github.com/Daily1Hour/PickMe-Auth-Parcel); 사용자 관리 마이크로 꾸러미 조각

- Amazon Cognito를 이용한 사용자 관리
- Parcel 컴포넌트로 구성하여 동적 모듈 호출 기능

#### [PickMe-Record-Application](https://github.com/Daily1Hour/PickMe-Record-Application); 기록 서비스 마이크로 프론트엔드

#### [PickMe-Review-Application](https://github.com/Daily1Hour/PickMe-Review-Application); 면접 회고 마이크로 프론트엔드

#### [PickMe-Report-Application](https://github.com/Daily1Hour/PickMe-Report-Application); 기업 분석 마이크로 프론트엔드

- 사용자가 기업 분석을 할 수 있도록 기록 서비스를 제공

#### [PickMe-Calendar-Application](https://github.com/Daily1Hour/PickMe-Calendar-Application); 캘린더 마이크로 프론트엔드

- 면접 일정 관리와 알림 기능을 제공

#### [PickMe-Chat-Application](https://github.com/Daily1Hour/PickMe-Chat-Application); 채팅 마이크로 프론트엔드

- 사용자간 실시간 채팅

### 백엔드 프로젝트

#### [PickMe-Record-Service](https://github.com/Daily1Hour/PickMe-Records-Service); 기록 마이크로 서비스

#### [PickMe-Review-Service](https://github.com/Daily1Hour/PickMe-Review-Service); 회고 마이크로 서비스

#### [PickMe-Report-Service](https://github.com/Daily1Hour/PickMe-Report-Service); 공고 분석 마이크로 서비스

#### [PickMe-Calendar-Service](https://github.com/Daily1Hour/PickMe-Calendar-Service); 캘린더 마이크로 서비스

#### [PickMe-Reminder-Service](https://github.com/Daily1Hour/PickMe-Reminder-Service); 알림 서비스

- API를 통해 알림 시간을 관리하고, 스케쥴러가 매시간 알림을 발송하는 서비스

#### [PickMe-Chat-Service](https://github.com/Daily1Hour/PickMe-Chat-Service); 채팅 서비스

## 기술 스택

### 프론트엔드

프레임워크
[![Single-SPA](https://img.shields.io/badge/Single_SPA-f5bcd3.svg?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA2MDAgODExLjIxIj48c2NyaXB0IHhtbG5zPSIiIGlkPSJjdXN0b20tdXNlcmFnZW50LXN0cmluZy1wYWdlLXNjcmlwdCIvPjxkZWZzPjxzdHlsZT4uY2xzLTF7ZmlsbDojZWU2ODlmO308L3N0eWxlPjwvZGVmcz48ZyBpZD0iTGF5ZXJfMiIgZGF0YS1uYW1lPSJMYXllciAyIj48ZyBpZD0iTGF5ZXJfMS0yIiBkYXRhLW5hbWU9IkxheWVyIDEiPjxwYXRoIGNsYXNzPSJjbHMtMSIgZD0iTTEwOC41NCwyMDAuMzMsNTI4LjQyLDQ3MC40Miw0NDkuMjcsNTgzLjg0LDU5LjM5LDM4Ni4yMmw0OS4xNS0xODUuODlNNzcuNCwxMjAuMTIsMCw0MTIuODZsNDY1LjYxLDIzNkw2MDAsNDU2LjI4LDc3LjQsMTIwLjEyWiIvPjxwb2x5Z29uIGNsYXNzPSJjbHMtMSIgcG9pbnRzPSIyODQuODQgNTU2LjM0IDQ2NS42IDY0OC44NSAxNTQuNjkgODExLjIxIDI4NC44NCA1NTYuMzQiLz48cG9seWdvbiBjbGFzcz0iY2xzLTEiIHBvaW50cz0iNDAxLjA2IDMyOC44NSA3Ny40IDEyMC4xMiA1NjkuMDkgMCA0MDEuMDYgMzI4Ljg1Ii8+PC9nPjwvZz48L3N2Zz4=&style=flat-square&logoColor)](https://single-spa.js.org/)
[![Module Federation](https://img.shields.io/badge/Module_Federation-bfeaf9.svg?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGZpbGw9Im5vbmUiIHZpZXdCb3g9IjAgMCAxNTkgMTUyIj4KICA8cGF0aCBzdHJva2U9IiMxMDhDQjkiIHN0cm9rZS1taXRlcmxpbWl0PSIxMCIgc3Ryb2tlLXdpZHRoPSIzLjIiIGQ9Ik05Ni4zIDEyLjcgNzkgMy4ybS0xNyA5LjYgMTctOS42bTE3LjMgMTM2LjFMNzkgMTQ4LjhtLTE3LTkuNiAxNy4xIDkuNk0zMi43IDI5LjYgMTYgMzkuOG0tLjMgMTkuNi4yLTE5LjZtLjEgMC0xMy44LThtMTQwLjQgNjAuOS0uMyAxOS42bS0xNi45IDEwLjEgMTYuOS0xMC4xbTAgMCAxMy43IDcuOU0xNS43IDkzbC40IDE5LjVNMzMgMTIyLjZsLTE3LTEwbTAtLjEtMTMuNiA4bTEyMi45LTkxLjEgMTYuOCAxMC4ybS4zIDE5LjYtLjMtMTkuNm0wIDAgMTMuNy04Ii8+CiAgPHBhdGggZmlsbD0iIzk1ODlFQyIgZD0iTTk2LjUgNDMuMyA3OSAzMy4zbC0xNy41IDEwTDc5IDUzLjRsMTcuNS0xMFoiLz4KICA8cGF0aCBmaWxsPSIjMUMyMTM1IiBkPSJNNzkgMzIuOCA2MS4yIDQzLjF2MjAuNkw3OSA3NC4xbDE4LTEwLjRWNDMuMUw3OSAzMi44Wm0xNi44IDEwLjVMNzkgNTNsLTE2LjctOS43TDc5IDMzLjdsMTYuOCA5LjZabS0zMy45LjcgMTYuNyA5LjZWNzNMNjIgNjMuM1Y0NFptMTcuNSAyOVY1My41TDk2LjEgNDR2MTkuM2wtMTYuNyA5LjZaIi8+CiAgPHBhdGggZmlsbD0iIzk1ODlFQyIgZD0iTTU5LjggMTA3LjRWODcuMkw0Mi40IDc3djIwLjJsMTcuNCAxMFoiLz4KICA8cGF0aCBmaWxsPSIjMUMyMTM1IiBkPSJNNTkuOCA2Ni42IDQyIDc2Ljl2MjAuNmwxNy44IDEwLjMgMTgtMTAuM1Y3Ni45bC0xOC0xMC4zWk03Ni42IDc3bC0xNi44IDkuNkw0My4xIDc3bDE2LjctOS43TDc2LjYgNzdabS0zMy45LjcgMTYuOCA5LjZ2MTkuM0w0Mi43IDk3Vjc3LjhabTE3LjUgMjguOVY4Ny40TDc3IDc3LjhWOTdsLTE2LjcgOS43WiIvPgogIDxwYXRoIGZpbGw9IiM5NTg5RUMiIGQ9Ik05OC4yIDEwNy40Vjg3LjJMMTE1LjcgNzd2MjAuMmwtMTcuNSAxMFoiLz4KICA8cGF0aCBmaWxsPSIjMUMyMTM1IiBkPSJNOTguMiA2Ni42IDgwLjMgNzYuOXYyMC42bDE4IDEwLjNMMTE2IDk3LjVWNzYuOUw5OC4yIDY2LjZaTTExNSA3N2wtMTYuNyA5LjZMODEuNiA3N2wxNi43LTkuN0wxMTUgNzdabS0zMy44LjcgMTYuNyA5LjZ2MTkuM0w4MS4yIDk3Vjc3LjhabTE3LjUgMjguOVY4Ny40bDE2LjctOS42Vjk3bC0xNi43IDkuNloiLz4KICA8cGF0aCBmaWxsPSIjOTU4OUVDIiBkPSJtMTE1LjcgNTQuOC0xNy41LTEwLTE3LjUgMTBMOTguMiA2NWwxNy41LTEwWiIvPgogIDxwYXRoIGZpbGw9IiM5NTg5RUMiIGQ9Ik05OC4yIDg1LjFWNjVsMTcuNS0xMHYyMEw5OC4yIDg1LjFaIi8+CiAgPHBhdGggZmlsbD0iIzFDMjEzNSIgZD0iTTk4LjIgNDQuMyA4MC4zIDU0LjZ2MjAuNmwxOCAxMC40TDExNiA3NS4yVjU0LjZMOTguMiA0NC4zWk0xMTUgNTQuOGwtMTYuNyA5LjctMTYuNy05LjcgMTYuNy05LjYgMTYuNyA5LjZabS0zMy44LjcgMTYuNyA5Ljd2MTkuM2wtMTYuNy05LjdWNTUuNVptMTcuNSAyOVY2NS4ybDE2LjctOS43djE5LjNsLTE2LjcgOS43WiIvPgogIDxwYXRoIGZpbGw9IiM5NTg5RUMiIGQ9Im03Ny4zIDU0LjgtMTcuNS0xMC0xNy40IDEwTDU5LjggNjVsMTcuNS0xMFpNNTkuOCA4NS4xVjY1TDQyLjQgNTV2MjBsMTcuNCAxMC4xWiIvPgogIDxwYXRoIGZpbGw9IiMxQzIxMzUiIGQ9Ik01OS44IDQ0LjMgNDIgNTQuNnYyMC42bDE3LjggMTAuNCAxOC0xMC40VjU0LjZsLTE4LTEwLjNabTE2LjggMTAuNS0xNi44IDkuNy0xNi43LTkuNyAxNi43LTkuNiAxNi44IDkuNlptLTMzLjkuNyAxNi44IDkuN3YxOS4zbC0xNi44LTkuN1Y1NS41Wm0xNy41IDI5VjY1LjJMNzcgNTUuNXYxOS4zbC0xNi43IDkuN1oiLz4KICA8cGF0aCBmaWxsPSIjOTU4OUVDIiBkPSJNNzkgMTE4LjVWOTguM2wtMTcuNS0xMHYyMC4xbDE3LjUgMTBabTAgMFY5OC4zbDE3LjUtMTB2MjAuMWwtMTcuNSAxMFoiLz4KICA8cGF0aCBmaWxsPSIjMUMyMTM1IiBkPSJNNzkgNzcuNyA2MS4yIDg4djIwLjZMNzkgMTE5bDE4LTEwLjRWODhMNzkgNzcuN1ptMTYuOCAxMC41TDc5IDk4bC0xNi43LTkuN0w3OSA3OC42bDE2LjggOS42Wm0tMzMuOS43IDE2LjcgOS42djE5LjNMNjIgMTA4LjJWODguOVptMTcuNSAyOVY5OC40TDk2LjEgODl2MTkuM2wtMTYuNyA5LjZaIi8+CiAgPHBhdGggZmlsbD0iIzcxQkVEQiIgZD0iTTEzNC41IDQzLjIgODAgMTEuNnYyMEwxMTcuMyA1M2wxNy4yLTEwWm0tOTMuNyAxMCAzNy41LTIxLjdWMTEuNkwyMy41IDQzLjJsMTcuMyAxMFptNzcuMiAxLjN2NDMuM2wxNy4zIDEwVjQ0LjRsLTE3LjMgMTBabS03Ny44LjEtMTcuMy0xMHY2M2wxNy4zLTEwdi00M1pNMjMuNyAxMDlsNTQuNiAzMS40di0yMEw0MSA5OWwtMTcuMyAxMFptNTYuMiAxMS41djIwbDU0LjUtMzEuNUwxMTcgOTlsLTM3IDIxLjVaIi8+CiAgPHBhdGggZmlsbD0iIzk1ODlFQyIgZD0iTTk2LjUgNjYuNCA3OSA1Ni4zbC0xNy41IDEwTDc5IDc2LjVsMTcuNS0xMFoiLz4KICA8cGF0aCBmaWxsPSIjOTU4OUVDIiBkPSJNNzkgOTYuNlY3Ni40bC0xNy41LTEwdjIwLjFMNzkgOTYuNlptMCAwVjc2LjRsMTcuNS0xMHYyMC4xTDc5IDk2LjZaIi8+CiAgPHBhdGggZmlsbD0iIzFDMjEzNSIgZD0iTTc5IDU1LjggNjEuMiA2Ni4xdjIwLjdMNzkgOTdsMTgtMTAuMlY2Nkw3OSA1NS44Wm0xNi44IDEwLjZMNzkgNzZsLTE2LjctOS42TDc5IDU2LjdsMTYuOCA5LjdabS0zMy45LjYgMTYuNyA5LjdWOTZMNjIgODYuM1Y2N1ptMTcuNSAyOVY3Ni43TDk2LjEgNjd2MTkuM0w3OS40IDk2WiIvPgo8L3N2Zz4K&style=flat-square&logoColor)](https://module-federation.io/)

언어
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
[![EJS](https://img.shields.io/badge/EJS-B4CA65?style=flat-square&logo=ejs&logoColor=a91e50)](https://ejs.co/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://ejs.co/)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://ejs.co/)

SPA
[![Vuejs](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)](https://vuejs.org/)
[![React](https://img.shields.io/badge/React-191B1F?style=flat-square&logo=React&logoColor=61DAFB)](https://reactjs.org)
[![Svelte](https://img.shields.io/badge/Svelte-FF3E00?style=flat-square&logo=svelte&logoColor=white)](https://svelte.dev/)

유틸리티 라이브러리
[![Pinia](https://img.shields.io/badge/🍍_Pinia-FFD859?style=flat-square&logoColor=white)](https://pinia.vuejs.org/)
[![Vue-Query](https://img.shields.io/badge/Vue_Query-FF4955.svg?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyMTQiIGhlaWdodD0iMjE0IiBzdHlsZT0ic2hhcGUtcmVuZGVyaW5nOmdlb21ldHJpY1ByZWNpc2lvbjt0ZXh0LXJlbmRlcmluZzpnZW9tZXRyaWNQcmVjaXNpb247aW1hZ2UtcmVuZGVyaW5nOm9wdGltaXplUXVhbGl0eTtmaWxsLXJ1bGU6ZXZlbm9kZDtjbGlwLXJ1bGU6ZXZlbm9kZCI+PHBhdGggc3R5bGU9Im9wYWNpdHk6Ljk1MyIgZmlsbD0iIzA3MmM0YiIgZD0iTS0uNSAxMy41YzI4LjY2OS0uMTY3IDU3LjMzNSAwIDg2IC41QTE3ODMuODk0IDE3ODMuODk0IDAgMCAxIDEwNiA0OC41IDU5NS4yNDUgNTk1LjI0NSAwIDAgMCAxMjYuNSAxNGMyOC45OTgtLjUgNTcuOTk4LS42NjcgODctLjV2MmEyNDQ4MS4xNTQgMjQ0ODEuMTU0IDAgMCAwLTEwNy41IDE4NEE4NzAxNzguMDU4IDg3MDE3OC4wNTggMCAwIDAtLjUgMTYuNXYtM3oiLz48cGF0aCBzdHlsZT0ib3BhY2l0eToxIiBmaWxsPSIjNjYzNDRlIiBkPSJNMTMyLjUgMjQuNWMyMC44MzctMS4zMjggNDEuODM3LTEuMzI4IDYzIDAtLjEyNC42MDctLjQ1Ny45NC0xIDFhOTYxLjYzNiA5NjEuNjM2IDAgMCAwLTYyLTF6Ii8+PHBhdGggc3R5bGU9Im9wYWNpdHk6MSIgZmlsbD0iI2ZiNDA1MyIgZD0iTTEzMi41IDI0LjVjMjAuODQtLjMzIDQxLjUwNy4wMDMgNjIgMWEyMDYxMy4yNzIgMjA2MTMuMjcyIDAgMCAxLTg4LjUgMTUzbC04OC41LTE1M2E2NDEuMjIzIDY0MS4yMjMgMCAwIDEgNjItLjVBMjk3MS40OTEgMjk3MS40OTEgMCAwIDEgMTA2IDY5LjVhNzYxLjI5IDc2MS4yOSAwIDAgMCAyNi41LTQ1eiIvPjxwYXRoIHN0eWxlPSJvcGFjaXR5OjEiIGZpbGw9IiMwYjJkNGIiIGQ9Ik0zOC41IDM3LjVjMTEuMTYtMS4xNiAyMi40OTItMS4zMjYgMzQtLjVBNDkxMC4wNiA0OTEwLjA2IDAgMCAwIDEwNiA5NC41bDMzLjUtNTdhMTQ1LjAwNCAxNDUuMDA0IDAgMCAxIDM0IDAgMTAwMDAuNTY0IDEwMDAwLjU2NCAwIDAgMS02Ny41IDExNiA5NzExLjM1NiA5NzExLjM1NiAwIDAgMC02Ny41LTExNnoiLz48cGF0aCBzdHlsZT0ib3BhY2l0eToxIiBmaWxsPSIjZjZkMzRjIiBkPSJNNTYuNSA0Ni41YzMuNjA2LS4yOSA3LjEwNi4wNDQgMTAuNSAxYTMzMzIuMTgzIDMzMzIuMTgzIDAgMCAwIDM5IDY3IDMzMzYuMDE5IDMzMzYuMDE5IDAgMCAwIDM5LTY3YzMuNzQ0LTEuMTI2IDcuNTc3LTEuMjkzIDExLjUtLjVMMTA2IDEzMy41YTI4MTAuOTcgMjgxMC45NyAwIDAgMS00OS41LTg3eiIvPjwvc3ZnPg==&style=flat-square)](https://tanstack.com/query/latest/docs/framework/vue/overview)
[![VeeValidate](https://img.shields.io/badge/VeeValidate-065f46.svg?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHZpZXdCb3g9JzAgMCA2ODcuMzYgNTk1LjI4MDA1Jz48cGF0aCBkPSdtNTcyLjQgMC01Ny40OSA5OS41Ni0xNzEuMjMgMjk2LjU5TDE3Mi40NSA5OS41NmgxMTguMDJsNTMuMjEgOTIuMTQgNTMuMjEtOTIuMTRMNDU0LjM2IDBIMGwzNDMuNjggNTk1LjI4TDY4Ny4zNiAwWicgZmlsbD0nIzA2ZDc3Yic+PC9wYXRoPjwvc3ZnPgo=&style=flat-square)](https://vee-validate.logaretm.com/v4/)  
[![Zustand](https://img.shields.io/badge/🐻_Zustand-F56D2E?style=flat-square&logoColor=white)](https://zustand-demo.pmnd.rs/)
[![Jotai](https://img.shields.io/badge/👻_Jotai-dbeafe?style=flat-square&logoColor=white)](https://jotai.org/)
[![React Router](https://img.shields.io/badge/React_Router-CA4245?style=flat-square&logo=react-router&logoColor=white)](https://reactrouter.com/)
[![React Query](https://img.shields.io/badge/React%20Query-FF4154?style=flat-square&logo=reactquery&logoColor=fff)](https://tanstack.com/query/latest/docs/framework/react/overview)
[![React Hook Form](https://img.shields.io/badge/React%20Hook%20Form-EC5990?style=flat-square&logo=reacthookform&logoColor=fff)](https://react-hook-form.com/)

라이브러리
[![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white)](https://socket.io/)
[![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white)](https://zod.dev/)

UI 라이브러리
[![Chakra UI](https://img.shields.io/badge/Chakra_UI-319795?style=flat-square&logo=chakraui&logoColor=white)](https://www.chakra-ui.com/)
[![Quasar](https://img.shields.io/badge/Quasar-050A14?style=flat-square&logo=quasar&logoColor=white)](https://quasar.dev/)
[![SMUI](https://img.shields.io/badge/Svelte_Material_UI-007FFF?style=flat-square&logo=mui&logoColor=white)](https://sveltematerialui.com/)

외부 라이브러리
[![OneSignal](https://img.shields.io/badge/OneSignal-E54B4D.svg?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSI1NiIgaGVpZ2h0PSI1NiIgZmlsbD0ibm9uZSIgdmlld0JveD0iMCAwIDU2IDU2Ij4NCiAgPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTI3Ljk0OCAwQzEyLjQ5OC4wMy0uMDg2IDEyLjc0NSAwIDI4LjIzM2EyOC4xMSAyOC4xMSAwIDAgMCA3LjI3NCAxOC43MTMgMjcuOTc4IDI3Ljk3OCAwIDAgMCAxNy44ODMgOS4wNTIuMzIxLjMyMSAwIDAgMCAuMzU1LS4zMjJWMjguMDcyaC0yLjE3NmEuMzIyLjMyMiAwIDAgMS0uMzIyLS4zMjN2LTQuMzU2YS4zMjMuMzIzIDAgMCAxIC4zMjItLjMyMmg2LjgzYS4zMjEuMzIxIDAgMCAxIC4zMjIuMzIydjMyLjI4M2EuMzIzLjMyMyAwIDAgMCAuMzU0LjMyMiAyNy45OCAyNy45OCAwIDAgMCAxOC40MTYtOS42NTcgMjguMTE2IDI4LjExNiAwIDAgMCA2LjcwNC0xOS43MjEgMjguMTAyIDI4LjEwMiAwIDAgMC04LjctMTguOTIyQTI3Ljk2NSAyNy45NjUgMCAwIDAgMjcuOTQ3IDBabTcuOTU4IDQ5Ljc0NWEuMzIuMzIgMCAwIDEtLjM5NC0uMTU2LjMyMy4zMjMgMCAwIDEtLjAzNS0uMTQ5di00LjYwN2EuNDg1LjQ4NSAwIDAgMSAuMjc2LS40MzggMTguMDU2IDE4LjA1NiAwIDAgMCA4LjUwNS04LjQ4NyAxOC4xMiAxOC4xMiAwIDAgMCAxLjMwOC0xMS45NTkgMTguMDg0IDE4LjA4NCAwIDAgMC02LjQ2Ny0xMC4xMzQgMTguMDA1IDE4LjAwNSAwIDAgMC0xMS4zNzgtMy44MjJjLTkuNTc5LjE0Ny0xNy40MzkgNy44OS0xNy43NDMgMTcuNDlhMTguMTM1IDE4LjEzNSAwIDAgMCAyLjYyNiA5Ljk5IDE4LjA3IDE4LjA3IDAgMCAwIDcuNjUgNi45MjIuNDgzLjQ4MyAwIDAgMSAuMjc3LjQzOHY0LjYwN2EuMzI1LjMyNSAwIDAgMS0uMjc4LjMyLjMyMS4zMjEgMCAwIDEtLjE1Mi0uMDE1IDIzLjA2MiAyMy4wNjIgMCAwIDEtMTEuMDE1LTguNTQzQTIzLjE1MiAyMy4xNTIgMCAwIDEgNC45OSAyNy44NTlDNS4xIDE1LjMyNyAxNS4zMTUgNS4wOTMgMjcuODIxIDVjMTIuNzc2LS4xMDMgMjMuMTk1IDEwLjI4NyAyMy4xOTUgMjMuMDcgMCA5Ljk0Mi02LjI5OSAxOC40MzUtMTUuMTEgMjEuNjc0WiI+PC9wYXRoPg0KPC9zdmc+&style=flat-square&logoColor)](https://onesignal.com/)
[![Editorjs](https://img.shields.io/badge/+_Editor.js-1CADFE?style=flat-square&logoColor=white)](https://editorjs.io/)

빌드
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)](https://ko.vite.dev)
[![Webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=flat-square&logo=webpack&logoColor=blue)](https://webpack.kr/)

개발 도구
[![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)](https://www.postman.com/)
[![Steiger](https://img.shields.io/badge/FSD_Steiger-211b1d.svg?logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz4KPHN2ZyB2ZXJzaW9uPSIxLjEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgd2lkdGg9IjIwMCIgaGVpZ2h0PSIyMDAiPgo8cGF0aCBkPSJNMCAwIEMyOC4zOCAwIDU2Ljc2IDAgODYgMCBDODYgMy42MyA4NiA3LjI2IDg2IDExIEM1Ny42MiAxMSAyOS4yNCAxMSAwIDExIEMwIDcuMzcgMCAzLjc0IDAgMCBaICIgZmlsbD0iI0VCRUFFQSIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoNTcsMTAyKSIvPgo8cGF0aCBkPSJNMCAwIEMyOC4zOCAwIDU2Ljc2IDAgODYgMCBDODYgMy42MyA4NiA3LjI2IDg2IDExIEM1Ny42MiAxMSAyOS4yNCAxMSAwIDExIEMwIDcuMzcgMCAzLjc0IDAgMCBaICIgZmlsbD0iI0VCRUFFQSIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoNTcsODcpIi8+CjxwYXRoIGQ9Ik0wIDAgQzI4LjM4IDAgNTYuNzYgMCA4NiAwIEM4NiAzLjYzIDg2IDcuMjYgODYgMTEgQzU3LjYyIDExIDI5LjI0IDExIDAgMTEgQzAgNy4zNyAwIDMuNzQgMCAwIFogIiBmaWxsPSIjRUJFQUVBIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSg1Nyw1NykiLz4KPHBhdGggZD0iTTAgMCBDMjguMzggMCA1Ni43NiAwIDg2IDAgQzg2IDMuNjMgODYgNy4yNiA4NiAxMSBDNTcuNjIgMTEgMjkuMjQgMTEgMCAxMSBDMCA3LjM3IDAgMy43NCAwIDAgWiAiIGZpbGw9IiNFQkVBRUEiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDU3LDQyKSIvPgo8cGF0aCBkPSJNMCAwIEMxMy41MyAwIDI3LjA2IDAgNDEgMCBDNDEgMy42MyA0MSA3LjI2IDQxIDExIEMyNy40NyAxMSAxMy45NCAxMSAwIDExIEMwIDcuMzcgMCAzLjc0IDAgMCBaICIgZmlsbD0iI0U5RThFOCIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoNTcsMTQ3KSIvPgo8cGF0aCBkPSJNMCAwIEMxMy41MyAwIDI3LjA2IDAgNDEgMCBDNDEgMy42MyA0MSA3LjI2IDQxIDExIEMyNy40NyAxMSAxMy45NCAxMSAwIDExIEMwIDcuMzcgMCAzLjc0IDAgMCBaICIgZmlsbD0iI0U5RThFOCIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoNTcsMTMyKSIvPgo8cGF0aCBkPSJNMCAwIEMxMy41MyAwIDI3LjA2IDAgNDEgMCBDNDEgMy42MyA0MSA3LjI2IDQxIDExIEMyNy40NyAxMSAxMy45NCAxMSAwIDExIEMwIDcuMzcgMCAzLjc0IDAgMCBaICIgZmlsbD0iI0U5RThFOCIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoNTcsMTE3KSIvPgo8cGF0aCBkPSJNMCAwIEMxMy41MyAwIDI3LjA2IDAgNDEgMCBDNDEgMy42MyA0MSA3LjI2IDQxIDExIEMyNy40NyAxMSAxMy45NCAxMSAwIDExIEMwIDcuMzcgMCAzLjc0IDAgMCBaICIgZmlsbD0iI0U5RThFOCIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoNTcsNzIpIi8+Cjwvc3ZnPgo=&style=flat-square&logoColor=black)](https://github.com/feature-sliced/steiger)
[![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white)](https://eslint.org/)
[![Prettier](https://img.shields.io/badge/Prettier-F7B93E?style=flat-square&logo=prettier&logoColor=black)](https://prettier.io/)

문서
[![Storybook](https://img.shields.io/badge/Storybook-FF4785?style=flat-square&logo=storybook&logoColor=white)](https://storybook.js.org)
[![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)](https://www.figma.com/)

### 백엔드

프레임워크
[![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)](https://nestjs.com/)
[![NodeJS](https://img.shields.io/badge/Node.js-6DA55F?style=flat-square&logo=node.js&logoColor=white)](https://nodejs.org/ko)
[![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white)](https://spring.io/)
[![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)](https://spring.io/)

언어
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white)](https://www.typescriptlang.org/)

데이터베이스
[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Amazon DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)](https://aws.amazon.com/ko/dynamodb/)
[![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)](https://redis.io/)

라이브러리
[![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white)](https://socket.io/)

컨테이너
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white)](https://www.docker.com/)

테스트툴
[![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)](https://jestjs.io/)
[![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)](https://vitest.dev/)

빌드
[![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white)](https://gradle.org/)

개발도구
[![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)](https://swagger.io/)
[![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white)](https://eslint.org/)

### 인프라

컴퓨팅
[![Amazon ECS](https://img.shields.io/badge/Amazon_ECS-FF9900?style=flat-square&logo=amazonecs&logoColor=white)](https://aws.amazon.com/ko/ecs)
[![Amazon EC2](https://img.shields.io/badge/Amazon_EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)](https://aws.amazon.com/ko/ec2)
[![AWS Amplify](https://img.shields.io/badge/AWS_Amplify-FF9900?style=flat-square&logo=awsamplify&logoColor=white)](https://ap-northeast-2.console.aws.amazon.com/amplify)

인증
[![Amazon Cognito](https://img.shields.io/badge/Amazon_Cognito-DD344C?style=flat-square&logo=amazoncognito&logoColor=white)](https://aws.amazon.com/ko/cognito/)

스토리지
[![Amazon S3](https://img.shields.io/badge/Amazon_S3-569A31?style=flat-square&logo=amazons3&logoColor=white)](https://aws.amazon.com/ko/s3)

데이터베이스
[![Amazon DynamoDB](https://img.shields.io/badge/Amazon_DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)](https://ap-northeast-2.console.aws.amazon.com/dynamodbv2/)
