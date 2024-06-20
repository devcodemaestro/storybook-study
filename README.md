<p align="center">
  <a href="https://www.chromatic.com/">
    <img alt="Chromatic" src="https://avatars2.githubusercontent.com/u/24584319?s=200&v=4" width="60" />
  </a>
</p>

<h1 align="center">
  Chromatic의 스토리북 리액트 템플릿 소개
</h1>

이 템플릿은 빠르게 시작하고 실행하는 데 필요한 기본 React 및 스토리북 구성 파일과 함께 제공됩니다.

## 🚅 Quick start

1.  **애플리케이션을 만듭니다.**

    이 템플릿을 얻으려면 [degit](https://github.com/Rich-Harris/degit) 을 사용합니다.

    ```shell
    # 템플릿 복제하기
    npx degit chromaui/intro-storybook-react-template taskbox
    ```

1.  **종속 요소를 설치합니다.**

    새 사이트의 디렉토리로 이동하여 필요한 종속성을 설치합니다.

    ```shell
    # 디렉토리로 이동
    cd taskbox/

    # 종속성 설치
    yarn
    ```

1.  **소스코드를 열고 편집을 시작합니다!**

    선택한 코드 편집기에서 `taskbox` 디렉토리를 열고 첫 번째 컴포넌트를 빌드합니다!

1.  **스토리 찾아보기!**
    `yarn storybook`을 실행하여 `http://localhost:6006`에서 컴포넌트들의 스토리를 확인하세요.

## 🔎 What's inside?

이 템플릿에 포함된 최상위 파일과 디렉터리를 간략히 살펴보세요.

    .
    ├── .storybook
    ├── node_modules
    ├── public
    ├── src
    ├── .eslintrc.cjs
    ├── .gitignore
    ├── .index.html
    ├── LICENSE
    ├── package.json
    ├── yarn.lock
    ├── vite.config.js
    └── README.md

1.  **`.storybook`**: 이 디렉터리에는 스토리북의 [configuration](https://storybook.js.org/docs/react/configure/overview) 파일이 들어 있습니다..

2.  **`node_modules`**: 이 디렉터리에는 프로젝트가 의존하는 모든 코드 모듈(npm 패키지)이 포함되어 있습니다.

3.  **`public`**: 이 디렉터리에는 사이트의 개발 및 프로덕션 빌드가 포함됩니다.

4.  **`src`**: 이 디렉토리에는 애플리케이션에 표시되는 것과 관련된 모든 코드가 포함됩니다.

5.  **`.eslintrc.cjs`**: 이 파일은 ECMAScript/JavaScript 코드에서 발견되는 패턴을 식별하고 보고하는 도구인 [ESLint](https://eslint.org/)의 구성 파일입니다.

6.  **`.gitignore`**: 이 파일은 프로젝트 개발 과정에서 추적하거나 유지 관리해서는 안 되는 파일을 git에 알려줍니다.

7.  **`.index.html`**: 개발 또는 프로덕션 빌드를 생성할 때 제공되는 HTML 페이지입니다.

8.  **`LICENSE`**: 템플릿은 MIT 라이선스에 따라 라이선스가 부여됩니다.

9.  **`package.json`**: 일반적으로 프로젝트별 메타데이터(예: 프로젝트 이름, 작성자 등 기타 정보)를 포함하는 Node.js 프로젝트의 표준 매니페스트 파일입니다. npm은 이 파일을 기반으로 프로젝트에 필요한 패키지를 파악합니다.

10. **`yarn.lock`**: 이 파일은 프로젝트에 설치된 npm 종속 요소의 정확한 버전을 기반으로 자동으로 생성되는 파일입니다. **(수동으로 변경하지 마세요).**

11. **`vite.config.js`**: 최신 웹 프로젝트에 더 빠르고 간결한 개발 환경을 제공하는 것을 목표로 하는 빌드 도구인 [Vite](https://vitejs.dev/)의 설정 파일입니다.

12. **`README.md`**: 프로젝트에 대한 유용한 참조 정보가 포함된 텍스트 파일입니다.

## Contribute

템플릿에 문제가 발생하면 이 템플릿의 리포지토리에서 문제를 제기하는 것이 좋습니다.

## Learning Storybook

1. [Learn Storybook](https://storybook.js.org/tutorials/intro-to-storybook/react/en/get-started/)에서 입문 튜토리얼을 읽어보세요..
2. [Design Systems for Developers](https://storybook.js.org/tutorials/design-systems-for-developers/) 튜토리얼에서 컴포넌트 라이브러리를 디자인 시스템으로 변환하는 방법을 알아보세요..
3. [Storybook](https://storybook.js.org/) 공식 문서를 참조하세요..
