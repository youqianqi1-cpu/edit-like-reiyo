# 运行依赖

本包不附带剪映程序库、商业字体、音效或私人视频。以下媒体依赖由 Windows 准备步骤安装，使用各项目自身许可证：

- [PyAV](https://github.com/PyAV-Org/PyAV)，16.0.1：本地媒体解码、原始时间戳与抽帧。
- [Pillow](https://github.com/python-pillow/Pillow)，12.0.0：波形、拼图与透明图形层。
- [faster-whisper](https://github.com/SYSTRAN/faster-whisper)，1.2.1：本地语音识别；模型单独下载。

Windows 草稿接口随包保留 [aoguai/pyJianYingDraft](https://github.com/aoguai/pyJianYingDraft/tree/69cee12ae3f7442416df16acdf368ae574764811) 固定版本 `69cee12ae3f7442416df16acdf368ae574764811` 的两个未修改源文件 `draft_codec.py`、`draft_crypto.py`，位于 `scripts/vendor/jianying_codec/`，同目录保留原 Apache-2.0 许可证及来源说明。它们通过用户已安装剪映的程序库工作；不需要另装完整的 pyJianYingDraft。本包的剪辑计划与审美判断独立保留。

上游宣称的支持范围不等于本包已经完成相同范围的验证；以兼容说明和当前电脑短段结果为准。

## v0.1.1 随包基础资源

- 音效来自 Kenney 的 [Interface Sounds](https://kenney.nl/assets/interface-sounds)、[UI Audio](https://kenney.nl/assets/ui-audio) 和 [Digital Audio](https://kenney.nl/assets/digital-audio)。授权 CC0 1.0。所选 18 项保留来源文件名、授权原文与校验值；仅转成标准 48 kHz / 16-bit PCM WAV，未调整增益或音高。
- [思源黑体 CN Regular 2.005R](https://github.com/adobe-fonts/source-han-sans/tree/2.005R)：Adobe，SIL OFL 1.1；原字体未修改。
- [得意黑 Smiley Sans 2.0.1](https://github.com/atelier-anchor/smiley-sans/releases/tag/v2.0.1)：atelierAnchor，SIL OFL 1.1；原字体未修改。
- 授权原文位于 `edit-like-reiyo/assets/starter/licenses/`，分享资源时保持这些文件。音效的原始名称、页面与用途见 `assets/starter/catalog.json`。
- 这些是公开资源中的基础候选，不是 Reiyo 私人收藏文件；没有逐项宣称 Reiyo 已试听认可。字体与声音的各自授权不等于本 Skill 其他内容采用同一许可证。
