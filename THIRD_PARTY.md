# 运行依赖

本包不附带剪映程序库、商业字体、音效或私人视频。以下媒体依赖由 Windows 准备步骤安装，使用各项目自身许可证：

- [PyAV](https://github.com/PyAV-Org/PyAV)，16.0.1：本地媒体解码、原始时间戳与抽帧。
- [Pillow](https://github.com/python-pillow/Pillow)，12.0.0：波形、拼图与透明图形层。
- [faster-whisper](https://github.com/SYSTRAN/faster-whisper)，1.2.1：本地语音识别；模型单独下载。

Windows 草稿接口随包保留 [aoguai/pyJianYingDraft](https://github.com/aoguai/pyJianYingDraft/tree/69cee12ae3f7442416df16acdf368ae574764811) 固定版本 `69cee12ae3f7442416df16acdf368ae574764811` 的两个未修改源文件 `draft_codec.py`、`draft_crypto.py`，位于 `scripts/vendor/jianying_codec/`，同目录保留原 Apache-2.0 许可证及来源说明。它们通过用户已安装剪映的程序库工作；不需要另装完整的 pyJianYingDraft。本包的剪辑计划与审美判断独立保留。

上游宣称的支持范围不等于本包已经完成相同范围的验证；以兼容说明和当前电脑短段结果为准。
