- [x] Convert to npm package.
  - Relies heaviy on prettier anyways for common use cases.
- [ ] Update CI example in readme to use install-tools
- [ ] Handler `answer` in install functions
- [ ] Hide installer output unless failed
- [ ] pre-commit should run a check on partially-staged files after a
      successful fix run of fully-staged files.
- [x] Add missing test coverage:
  - [x] css
  - [x] dash
  - [x] html
  - [x] jsx
  - [x] ksh
  - [x] lua
  - [x] luau
  - [x] mksh
  - [x] package.json
  - [x] pug
  - [x] Cargo.toml
  - [x] sass
  - [x] tsx
  - [x] xml
  - [ ] graphql
  - [ ] test that syntax errors cause check failure
  - [ ] test that syntax errors cause fix failure
  - [ ] Perhaps some method for ensuring all supported file types are tested?
  - [ ] Syntax error behavior for each file type
- [ ] Additional tools:
  - tslint
  - eslint
  - stylelint
  - cpplint
  - infer (facebook)
- [ ] Install script should allow installing different "profiles" for different languages.
  - Auto-detect?
- [ ] Replace `eval echo` for args creation with safer templating