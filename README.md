# roadmate-ondevice

Roadmate 端侧大模型运行时（需求1976）。动态下载，不进 APK（APK 体积零增量）。

- `ondevice/bridge.dex` — LiteRT-LM + gson + Java 桥（OnDeviceOcrEngine）预 dex（d8，min-api 24）。
- `ondevice/arm64-v8a/liblitertlm_jni.so` — LiteRT-LM 大运行时（arm64-v8a，vivo 真机）。
- `ondevice/SHA256SUMS` — 下载校验。

模型（Xiaomi-OCR-0 int8，1.31GB）在 HuggingFace：litert-community/Xiaomi-OCR-0（Apache-2.0）。
许可：litertlm / gson 均 Apache-2.0，可再分发。
