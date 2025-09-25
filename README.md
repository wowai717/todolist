https://www.figma.com/design/OEcigLjHqthWpC22dFDZMe/todolist?node-id=0-1&t=pT44F86sjKFE9JkM-1



## 📚 프로젝트 소개

React와 NestJS를 이용해 만드는 간단한 할 일 목록 웹 애플리케이션입니다.

## 📂 폴더 구조

-   `/client`: 프론트엔드 (React)
-   `/server`: 백엔드 (NestJS)

## 🛠️ 설치 및 실행 방법

### ✅ 사전 준비 (Prerequisites)

이 프로젝트를 실행하기 위해선 아래 프로그램들이 설치되어 있어야 합니다.

-   [Node.js](https://nodejs.org/) (LTS 버전 권장)
-   `npm` (Node.js 설치 시 자동 설치됨)
-   `@nestjs/cli`
    ```bash
    npm i -g @nestjs/cli
    ```

### ⚙️ 설치 (Installation)

1.  **프로젝트 클론**
    ```bash
    git clone 
    cd todolist
    ```
2.  **백엔드 종속성 설치**
    ```bash
    cd server
    npm install
    cd ..
    ```
3.  **프론트엔드 종속성 설치**
    ```bash
    cd client
    npm install
    cd ..
    ```

### ▶️ 실행 (Running the App)

**‼️ 중요: 백엔드와 프론트엔드 서버를 각각 실행해야 하므로, 터미널(또는 VSCode 터미널)을 2개 준비해야 합니다.**

1.  **백엔드 서버 실행**
    -   첫 번째 터미널을 열고 아래 명령어를 입력하세요.
    ```bash
    cd server
    npm run start:dev
    ```
    -   서버가 `http://localhost:3000` 에서 실행됩니다.

2.  **프론트엔드 서버 실행**
    -   **새로운 두 번째 터미널**을 열고 아래 명령어를 입력하세요.
    ```bash
    cd client
    npm start
    ```
    -   React 앱이 `http://localhost:3001` (또는 다른 포트) 에서 실행되며 자동으로 브라우저 창이 열립니다.
