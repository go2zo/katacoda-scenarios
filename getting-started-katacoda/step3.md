Katacoda CLI는 scenario, course등을 간편하게 생성/설정하도록 지원한다. 실제 katacoda 파일들은 json, md로 되어있으므로 CLI 없이 작성이 가능하다.

## Prerequisite

`npm`이 설치되어 있어야 한다.
현재 실행중인 katacoda 시나리오는 nodejs 기반이므로 npm이 설치되어 있다.
실제 환경에서 진행할 때는 nodejs를 설치하여야 한다.

> **Note:** homebrew, chocolatey에서는 지원하지 않는다.

## Install

CLI 설치를 위해 `npm install katacoda-cli --global`{{execute}}를 실행한다.

설치가 정상적으로 되었는지 확인하려면 `katacoda version`{{execute}}를 실행하고,

`katacoda commands`{{execute}}로 명령어 목록을 확인할 수 있다.
