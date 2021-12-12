`create-nuxt-app`을 이용해 자동으로 프로젝트를 생성할 수 있다.

```bash
# yarn
yarn create nuxt-app <project-name>

# npm
npm init nuxt-app <project-name>

# npx
npx create-nuxt-app <project-name>
```

`yarn create nuxt-app my-nuxt-project`{{execute}}를 실행하고 아래를 순서대로 입력한다.

- Project name: <kbd>enter</kbd>
- Programming language: `TypeScript` 선택
- Package manager: `Yarn` 선택
- UI framework: `Windi CSS` 선택
- Nuxt.js modules: `PWA`, `Content` 선택
- Linting tools: `ESLint`, `Prettier`, `Lint staged files`, `StyleLint`, `Commitlint` 선택
- Testing framework: `Jest` 선택
- Rendering mode: `Universal` 선택
- Deployment target: `Static` 선택
- Development tools: `jsconfig.json` 선택
- Continuous integration: `None` 선택
- Version control system: `Git` 선택

프로젝트 폴더로 이동한다. `cd my-nuxt-project`{{execute}}

`yarn dev`를 실행하면 nuxt를 개발환경에서 실행한다.

`Port 3000` 탭을 선택하여 실행을 확인한다.


