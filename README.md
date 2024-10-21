# **Harmonify (RVC No UI)**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1X8YR4Ruv7zzY8YAMPTfC7hkxqT_d4Q5d)



## **Credits**
[Eempostor](https://discordapp.com/users/818050831034613771) - Made everything work together, Notebook creator

[Applio](https://github.com/IAHispano/Applio-RVC-Fork) by [IAHispano](https://github.com/IAHispano) - The repo this colab is based on

[CNChTu](https://github.com/CNChTu) - [FCPE](https://github.com/CNChTu/FCPE) F0 method

[So Vits SVC](https://github.com/svc-develop-team/so-vits-svc) - [FCPE](https://github.com/CNChTu/FCPE) F0 method script

[ChatGPT](https://chat.openai.com/) - Helper

[Phind](https://www.phind.com/) - Helper



## **Changelogs**
9/3/2024 | Huge changes
- Pitch extraction `fcpe` now uses the `torchfcpe` library. You can still use the previous version with `fcpe_legacy`
- `MIN_PITCH` and `MAX_PITCH` now accepts pitch notations
- Fixed error when running inference without a GPU (GPU is still recommended as its way faster and more stable)
- Fixed error when running `hybrid` with `pm`, `dio`, and `harvest`
- Overhaulled the directory structure and some code

14/1/2024 | Fixes
- Fixed `Cannot retrieve the public link of the file` issue while downloading models from google drive

10/1/2024 | Fixes
- Fixed `Cannot retrieve the public link of the file` issue on installation

12/12/2023 | Small adjustments
- Moved `DOWNLOAD` and `SAVE_TO_DRIVE` option on inference cell into a new cell
