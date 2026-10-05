# draft-kit-module

SKE Draft-Kit의 「기능 모듈」 중 앱에서 내려받아 쓰는 모듈 파일을 올려 두는 저장소입니다.
GitHub Pages(`https://cpk7778.github.io/draft-kit-module/`)로 서비스하며, 앱은 `manifest.json`을 읽어
파일을 내려받고 sha256을 확인한 뒤 브라우저 캐시에 저장합니다.

| 모듈 | 버전 | 파일 | 라이선스 |
|---|---|---|---|
| coolprop | 6.6.0 | `coolprop/6.6.0/coolprop.js`, `coolprop.wasm` | MIT (CoolProp) |
| pglite | 0.5.4 | `pglite/0.5.4/pglite.wasm`, `pglite.data`, `initdb.wasm` | Apache-2.0 (PGlite) |

파일을 바꿀 때는 새 버전 폴더를 만들고 `manifest.json`의 version·sha256·size를 같이 갱신합니다.
