# Changelog

## [0.0.1](https://github.com/manojkumar010/IntelliSearch/compare/v0.2.0...v0.0.1) (2024-01-22)


### Features

* add mistral + chatml prompts ([#1426](https://github.com/manojkumar010/IntelliSearch/issues/1426)) ([e326126](https://github.com/manojkumar010/IntelliSearch/commit/e326126d0d4cd7e46a79f080c442c86f6dd4d24b))
* **API:** Ingest plain text ([#1417](https://github.com/manojkumar010/IntelliSearch/issues/1417)) ([6eeb95e](https://github.com/manojkumar010/IntelliSearch/commit/6eeb95ec7f17a618aaa47f5034ee5bccae02b667))
* Disable Gradio Analytics ([#1165](https://github.com/manojkumar010/IntelliSearch/issues/1165)) ([6583dc8](https://github.com/manojkumar010/IntelliSearch/commit/6583dc84c082773443fc3973b1cdf8095fa3fec3))
* Drop loguru and use builtin `logging` ([#1133](https://github.com/manojkumar010/IntelliSearch/issues/1133)) ([64c5ae2](https://github.com/manojkumar010/IntelliSearch/commit/64c5ae214a9520151c9c2d52ece535867d799367))
* enable resume download for hf_hub_download ([#1249](https://github.com/manojkumar010/IntelliSearch/issues/1249)) ([4197ada](https://github.com/manojkumar010/IntelliSearch/commit/4197ada6267c822f32c1d7ba2be6e7ce145a3404))
* Get answers using preferred number of chunks ([cf709a6](https://github.com/manojkumar010/IntelliSearch/commit/cf709a6b7a951fc333ef5a089b24179ca660469b))
* **llm:** Add openailike llm mode ([#1447](https://github.com/manojkumar010/IntelliSearch/issues/1447)) ([2d27a9f](https://github.com/manojkumar010/IntelliSearch/commit/2d27a9f956d672cb1fe715cf0acdd35c37f378a5)), closes [#1424](https://github.com/manojkumar010/IntelliSearch/issues/1424)
* **llm:** drop default_system_prompt ([#1385](https://github.com/manojkumar010/IntelliSearch/issues/1385)) ([a3ed14c](https://github.com/manojkumar010/IntelliSearch/commit/a3ed14c58f77351dbd5f8f2d7868d1642a44f017))
* move torch and transformers to local group ([#1172](https://github.com/manojkumar010/IntelliSearch/issues/1172)) ([0d677e1](https://github.com/manojkumar010/IntelliSearch/commit/0d677e10b970aec222ec04837d0f08f1631b6d4a))
* Qdrant support ([#1228](https://github.com/manojkumar010/IntelliSearch/issues/1228)) ([03d1ae6](https://github.com/manojkumar010/IntelliSearch/commit/03d1ae6d70dffdd2411f0d4e92f65080fff5a6e2))
* Release GitHub action ([#1078](https://github.com/manojkumar010/IntelliSearch/issues/1078)) ([b745091](https://github.com/manojkumar010/IntelliSearch/commit/b7450911b25b0b70528fd4b620cffb90766e3448))
* **settings:** Configurable context_window and tokenizer ([#1437](https://github.com/manojkumar010/IntelliSearch/issues/1437)) ([4780540](https://github.com/manojkumar010/IntelliSearch/commit/47805408703c23f0fd5cab52338142c1886b450b))
* **settings:** Update default model to TheBloke/Mistral-7B-Instruct-v0.2-GGUF ([#1415](https://github.com/manojkumar010/IntelliSearch/issues/1415)) ([8ec7cf4](https://github.com/manojkumar010/IntelliSearch/commit/8ec7cf49f40701a4f2156c48eb2fad9fe6220629))
* **ui:** add LLM mode to UI ([#1080](https://github.com/manojkumar010/IntelliSearch/issues/1080)) ([d249a17](https://github.com/manojkumar010/IntelliSearch/commit/d249a17c330abd122e4988d35d94bcc2df980700))
* **ui:** Allows User to Set System Prompt via "Additional Options" in Chat Interface ([#1353](https://github.com/manojkumar010/IntelliSearch/issues/1353)) ([145f3ec](https://github.com/manojkumar010/IntelliSearch/commit/145f3ec9f41c4def5abf4065a06fb0786e2d992a))
* **ui:** make chat area stretch to fill the screen ([#1397](https://github.com/manojkumar010/IntelliSearch/issues/1397)) ([c71ae7c](https://github.com/manojkumar010/IntelliSearch/commit/c71ae7cee92463bbc5ea9c434eab9f99166e1363))


### Bug Fixes

* 294 (tested) ([4cda348](https://github.com/manojkumar010/IntelliSearch/commit/4cda348cf87f56ff237e376b03732b1b47a99215))
* Add `TARGET_SOURCE_CHUNKS` to `example.env` ([2027ac5](https://github.com/manojkumar010/IntelliSearch/commit/2027ac563b6606199563632191b65f5105af8ebe))
* Adding an LLM param to fix broken generator from llamacpp ([#1519](https://github.com/manojkumar010/IntelliSearch/issues/1519)) ([869233f](https://github.com/manojkumar010/IntelliSearch/commit/869233f0e4f03dc23e5fae43cf7cb55350afdee9))
* chromadb max batch size ([#1087](https://github.com/manojkumar010/IntelliSearch/issues/1087)) ([f5a9bf4](https://github.com/manojkumar010/IntelliSearch/commit/f5a9bf4e374b2d4c76438cf8a97cccf222ec8e6f))
* **deploy:** fix local and external dockerfiles ([fde2b94](https://github.com/manojkumar010/IntelliSearch/commit/fde2b942bc03688701ed563be6d7d597c75e4e4e))
* Disable Chroma Telemetry ([8c6a81a](https://github.com/manojkumar010/IntelliSearch/commit/8c6a81a07fc9c800d53f62a33f5ae3b5247a22a6))
* Docker and sagemaker setup ([#1118](https://github.com/manojkumar010/IntelliSearch/issues/1118)) ([895588b](https://github.com/manojkumar010/IntelliSearch/commit/895588b82a06c2bc71a9e22fb840c7f6442a3b5b))
* **docker:** docker broken copy ([#1419](https://github.com/manojkumar010/IntelliSearch/issues/1419)) ([059f358](https://github.com/manojkumar010/IntelliSearch/commit/059f35840adbc3fb93d847d6decf6da32d08670c))
* **docs:** Update quickstart doc and set version in pyproject.toml to 0.2.0 ([0a89d76](https://github.com/manojkumar010/IntelliSearch/commit/0a89d76cc5ed4371ffe8068858f23dfbb5e8cc37))
* fix pytorch version to avoid wheel bug ([#1123](https://github.com/manojkumar010/IntelliSearch/issues/1123)) ([24cfddd](https://github.com/manojkumar010/IntelliSearch/commit/24cfddd60f74aadd2dade4c63f6012a2489938a1))
* make docs more visible ([#1081](https://github.com/manojkumar010/IntelliSearch/issues/1081)) ([aa4bb17](https://github.com/manojkumar010/IntelliSearch/commit/aa4bb17a2e6a797b450fa11a45e0b0528b8efecf))
* minor bug in chat stream output - python error being serialized ([#1449](https://github.com/manojkumar010/IntelliSearch/issues/1449)) ([6191bcd](https://github.com/manojkumar010/IntelliSearch/commit/6191bcdbd6e92b6f4d5995967dc196c9348c5954))
* Remove global state ([#1216](https://github.com/manojkumar010/IntelliSearch/issues/1216)) ([022bd71](https://github.com/manojkumar010/IntelliSearch/commit/022bd718e3dfc197027b1e24fb97e5525b186db4))
* sagemaker config and chat methods ([#1142](https://github.com/manojkumar010/IntelliSearch/issues/1142)) ([a517a58](https://github.com/manojkumar010/IntelliSearch/commit/a517a588c4927aa5c5c2a93e4f82a58f0599d251))
* **settings:** correct yaml multiline string ([#1403](https://github.com/manojkumar010/IntelliSearch/issues/1403)) ([2564f8d](https://github.com/manojkumar010/IntelliSearch/commit/2564f8d2bb8c4332a6a0ab6d722a2ac15006b85f))
* **tests:** load the test settings only when running tests ([d3acd85](https://github.com/manojkumar010/IntelliSearch/commit/d3acd85fe34030f8cfd7daf50b30c534087bdf2b))
* typo in README.md ([#1091](https://github.com/manojkumar010/IntelliSearch/issues/1091)) ([ba23443](https://github.com/manojkumar010/IntelliSearch/commit/ba23443a70d323cd4f9a242b33fd9dce1bacd2db))
* Windows 11 failing to auto-delete tmp file ([#1260](https://github.com/manojkumar010/IntelliSearch/issues/1260)) ([0d52002](https://github.com/manojkumar010/IntelliSearch/commit/0d520026a3d5b08a9b8487be992d3095b21e710c))
* Windows permission error on ingest service tmp files ([#1280](https://github.com/manojkumar010/IntelliSearch/issues/1280)) ([f1cbff0](https://github.com/manojkumar010/IntelliSearch/commit/f1cbff0fb7059432d9e71473cbdd039032dab60d))


### Miscellaneous Chores

* Initial version ([490d93f](https://github.com/manojkumar010/IntelliSearch/commit/490d93fdc1977443c92f6c42e57a1c585aa59430))

## [0.2.0](https://github.com/imartinez/privateGPT/compare/v0.1.0...v0.2.0) (2023-12-10)


### Features

* **llm:** drop default_system_prompt ([#1385](https://github.com/imartinez/privateGPT/issues/1385)) ([a3ed14c](https://github.com/imartinez/privateGPT/commit/a3ed14c58f77351dbd5f8f2d7868d1642a44f017))
* **ui:** Allows User to Set System Prompt via "Additional Options" in Chat Interface ([#1353](https://github.com/imartinez/privateGPT/issues/1353)) ([145f3ec](https://github.com/imartinez/privateGPT/commit/145f3ec9f41c4def5abf4065a06fb0786e2d992a))

## [0.1.0](https://github.com/imartinez/privateGPT/compare/v0.0.2...v0.1.0) (2023-11-30)


### Features

* Disable Gradio Analytics ([#1165](https://github.com/imartinez/privateGPT/issues/1165)) ([6583dc8](https://github.com/imartinez/privateGPT/commit/6583dc84c082773443fc3973b1cdf8095fa3fec3))
* Drop loguru and use builtin `logging` ([#1133](https://github.com/imartinez/privateGPT/issues/1133)) ([64c5ae2](https://github.com/imartinez/privateGPT/commit/64c5ae214a9520151c9c2d52ece535867d799367))
* enable resume download for hf_hub_download ([#1249](https://github.com/imartinez/privateGPT/issues/1249)) ([4197ada](https://github.com/imartinez/privateGPT/commit/4197ada6267c822f32c1d7ba2be6e7ce145a3404))
* move torch and transformers to local group ([#1172](https://github.com/imartinez/privateGPT/issues/1172)) ([0d677e1](https://github.com/imartinez/privateGPT/commit/0d677e10b970aec222ec04837d0f08f1631b6d4a))
* Qdrant support ([#1228](https://github.com/imartinez/privateGPT/issues/1228)) ([03d1ae6](https://github.com/imartinez/privateGPT/commit/03d1ae6d70dffdd2411f0d4e92f65080fff5a6e2))


### Bug Fixes

* Docker and sagemaker setup ([#1118](https://github.com/imartinez/privateGPT/issues/1118)) ([895588b](https://github.com/imartinez/privateGPT/commit/895588b82a06c2bc71a9e22fb840c7f6442a3b5b))
* fix pytorch version to avoid wheel bug ([#1123](https://github.com/imartinez/privateGPT/issues/1123)) ([24cfddd](https://github.com/imartinez/privateGPT/commit/24cfddd60f74aadd2dade4c63f6012a2489938a1))
* Remove global state ([#1216](https://github.com/imartinez/privateGPT/issues/1216)) ([022bd71](https://github.com/imartinez/privateGPT/commit/022bd718e3dfc197027b1e24fb97e5525b186db4))
* sagemaker config and chat methods ([#1142](https://github.com/imartinez/privateGPT/issues/1142)) ([a517a58](https://github.com/imartinez/privateGPT/commit/a517a588c4927aa5c5c2a93e4f82a58f0599d251))
* typo in README.md ([#1091](https://github.com/imartinez/privateGPT/issues/1091)) ([ba23443](https://github.com/imartinez/privateGPT/commit/ba23443a70d323cd4f9a242b33fd9dce1bacd2db))
* Windows 11 failing to auto-delete tmp file ([#1260](https://github.com/imartinez/privateGPT/issues/1260)) ([0d52002](https://github.com/imartinez/privateGPT/commit/0d520026a3d5b08a9b8487be992d3095b21e710c))
* Windows permission error on ingest service tmp files ([#1280](https://github.com/imartinez/privateGPT/issues/1280)) ([f1cbff0](https://github.com/imartinez/privateGPT/commit/f1cbff0fb7059432d9e71473cbdd039032dab60d))

## [0.0.2](https://github.com/imartinez/privateGPT/compare/v0.0.1...v0.0.2) (2023-10-20)


### Bug Fixes

* chromadb max batch size ([#1087](https://github.com/imartinez/privateGPT/issues/1087)) ([f5a9bf4](https://github.com/imartinez/privateGPT/commit/f5a9bf4e374b2d4c76438cf8a97cccf222ec8e6f))

## 0.0.1 (2023-10-20)

### Miscellaneous Chores

* Initial version ([490d93f](https://github.com/imartinez/privateGPT/commit/490d93fdc1977443c92f6c42e57a1c585aa59430))
