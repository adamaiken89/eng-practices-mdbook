# Google 工程實踐 (Google Engineering Practices Documentation) - MDBOOK VERSION <!-- omit in toc -->

## 正體中文翻譯 <!-- omit in toc -->

本書正體中文翻譯由 [Will 保哥](https://blog.miniasp.com/) 完成，原文取自 [Google Engineering Practices Documentation](https://github.com/google/eng-practices)。若有任何問題，歡迎造訪 [Will 保哥的技術交流中心](https://www.facebook.com/will.fans) 與我聯繫！

## 授權 (License) <!-- omit in toc -->

該專案中的文件根據 [CC-By 3.0 授權](LICENSE)進行授權，該授權鼓勵您分享這些文件。有關詳細資訊，請參閱<https://creativecommons.org/licenses/by/3.0/>。

The documents in this project are licensed under the [CC-By 3.0 License](LICENSE), which encourages you to share these documents. See <https://creativecommons.org/licenses/by/3.0/> for more details.

<a rel="license" href="https://creativecommons.org/licenses/by/3.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/3.0/88x31.png" /></a>

---

This is a modified version for mdbook use

**Table of Contents**
- [1. Preparation](#1-preparation)
- [2. Run locally](#2-run-locally)
- [3. Export to EPUB](#3-export-to-epub)

## 1. Preparation

```bash
brew install mdbook // Read on browser
cargo install mdbook-epub // Read on e-reader
```

## 2. Run locally

```bash
mdbook serve
```

## 3. Export to EPUB

```bash
mdbook-epub -s true
```