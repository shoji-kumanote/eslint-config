Linter configuration for our work.

- Based on eslint-config-airbnb.

## Install

```sh
npm install --save-dev \
    git+https://github.com/shoji-kumanote/eslint-config.git \
    @typescript-eslint/eslint-plugin@^5.5.0 \
    @typescript-eslint/parser@^5.5.0 \
    eslint@^8.3.0 \
    eslint-config-airbnb-base@^15.0.0 \
    eslint-config-prettier@^8.3.0 \
    eslint-plugin-import@^2.25.3 \
    prettier@^2.5.0 \
    typescript@^4.5.2
```

or

```sh
yarn add -D \
    git+https://github.com/shoji-kumanote/eslint-config.git \
    @typescript-eslint/eslint-plugin@^5.5.0 \
    @typescript-eslint/parser@^5.5.0 \
    eslint@^8.3.0 \
    eslint-config-airbnb-base@^15.0.0 \
    eslint-config-prettier@^8.3.0 \
    eslint-plugin-import@^2.25.3 \
    prettier@^2.5.0 \
    typescript@^4.5.2
```

## Usage

```
# .eslintrc.yml
extends:
  - '@kumanote/eslint-config'
