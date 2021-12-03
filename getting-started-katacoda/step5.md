# Create First Scenario

## Git 저장소 clone

이미 katacoda 프로필에 git 저장소가 설치되어 있다면 해당 저장소를 clone 한다.

> 계정은 본인 계정으로 변경이 필요하다.

`git clone https://github.com/go2zo/katacoda-scenarios-example.git`{{execute}}

`cd katacoda-scenarios-example`

## 시나리오 생성

시나리오 생성을 위한 명령은 `katacoda scenarios:create`{{execute}}이다.

몇가지 항목을 입력하여 시나리오를 생성한다.

- Friendly URL: 시나리오 폴더명. 소문자여야 하며 공백불가.

- Title: 프로필에 표시되는 시나리오명.

- Description(Optional): 프로필의 시나리오 카드에 표시.

- Difficulty level: intro에 표시되는 난이도.

- Extimated time: intro에 표시되는 예상시간.

- Number of steps: 초기 step 개수. 향후 추가 가능.

- Image: Environment imageID를 선택한다. [Supported Environment](https://www.katacoda.community/essentials/environments.html)에서 확인 가능.

- Layout: 실행화면에 표시되는 창의 레이아웃을 선택한다. [Supported Layouts](https://www.katacoda.community/essentials/layouts.html)에서 확인 가능.

## 시나리오 배포

시나리오를 작성하고 배포 전에 `katacoda scenarios:validate`{{execute}}로 검증을 진행한다.

`Scenario is valid`라고 뜨면 에러가 없이 잘 작성된 것이다.

아래와 같이 실행해서 remote 저장소에 push한다. (하지만 인증문제로 push는 실패할 것이다.)

```sh
git add .

git commit -m "Create new scenario"

git push -u origin main
```{{execute}}

## Example

보다 자세한 내용은 아래의 katacoda example을 확인한다.

- Live scenario: <https://katacoda.com/scenario-examples/scenarios/create-scenario-101>

- Source: <https://github.com/katacoda/scenario-examples/tree/main/create-scenario-101>
