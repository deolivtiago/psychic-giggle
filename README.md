## Nodejs project example

- chore: add npm

      yarn init -y
      npm init -y

      git init

- chore: add commit linter

      yarn add -D git-commit-msg-linter
      npm i -D git-commit-msg-linter

- chore: add typescript

      yarn add -D typescript @types/node ts-node
      npm i -D typescript @types/node ts-node

      yarn tsc --init --outDir dist --target es2020
      npx tsc --init --outdir dist --target es2020

- chore: add eslint

      yarn add -D eslint
      npm i -D eslint

      yarn eslint --init
      npx eslint --init

  - vscode plugin required

- chore: add jest

      yarn add -D jest @types/jest ts-jest
      npm i -D jest @types/jest ts-jest

      yarn jest --init
      npx jest --init
