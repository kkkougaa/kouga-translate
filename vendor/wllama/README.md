# wllama (vendored)

브라우저 안 번역(PLaMo 3 Translate)을 돌리는 [wllama](https://github.com/ngxson/wllama) — llama.cpp 의 WebAssembly 판. MIT License (LICENSE).

npm 에 나온 `@wllama/wllama@3.8.1` 은 PLaMo 3 의 모델 구조는 알지만 토크나이저(`plamo3`)를 몰라서 모델을 못 올린다
(`unknown tokenizer: 'plamo3'`). 그래서 그보다 새 llama.cpp 로 빌드된 wllama 개발판을 받아 여기 둔다.

- 받은 곳: https://github.ngxson.com/wllama/esm/index.js, https://github.ngxson.com/wllama/esm/wasm/wllama.wasm (2026-11-05)
- sha256
  - `index.js` ae78882006d36eea6b55d75bc8577143d37f397151dd6f68344ea1c53bd23b25
  - `wasm/wllama.wasm` f5283730528f46ad68101c29714c014e8648344ee50a11d81e06693d4375ae66
- npm 에 PLaMo 3 를 아는 판이 나오면 그걸로 바꿔도 된다.
