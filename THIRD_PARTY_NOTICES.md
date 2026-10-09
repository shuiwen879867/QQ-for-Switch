# 第三方许可说明

本仓库只附许可文本和项目图标；不是应用或各依赖的完整对应源码。各组件实际许可保持有效，“24 小时删除”建议不改变这些权利。

| 组件 | 许可 |
| --- | --- |
| 本项目前端及原创几何图标 | MIT |
| libnx、stb_image、二维码生成器 | 各自 MIT 等随附声明 |
| SILK SDK | Skype BSD 风格许可，不授予专利许可 |
| OpenCORE AMR | Apache-2.0 |
| FreeType、HarfBuzz、libpng、zlib、bzip2、newlib | 对应 `licenses/` 文件 |
| FFmpeg 7.1 (Switch 构建) | 实际配置 --enable-gpl，库报告 GPL version 2 or later；见 licenses/FFmpeg-GPL-2.0.txt |
| dav1d 1.5.0 | BSD-2-Clause；见 licenses/dav1d-BSD-2-Clause.txt |
| Unicorn / QEMU | GPL/LGPL 等实际组件许可；附主要许可文本，不声称完成对应源码要求 |

当前 NRO 内嵌腾讯原始 `libfekit.so`，该组件不由本项目开源许可授权。此仓库不包含该库的源码、提取表、私有适配或协议测试向量。附许可文本不能替代各二进制组件的授权及适用的完整对应源码、构建材料等要求。

FFmpeg 的实际链接包含 libavformat、libavcodec、libswscale、libswresample 和 libavutil。许可判断依据本地已链接的构建配置及库声明；部分组件的 LGPL 许可不能覆盖启用 GPL 的构建。完整对应源码或必要的构建/重链接材料未在本仓库提供，许可告知不等同于已满足该条件。

Twemoji 14.0.2 graphics, Copyright Twitter, Inc. and contributors, CC-BY-4.0. Source: https://github.com/twitter/twemoji/tree/v14.0.2 . The embedded glyphs are resized and color-quantized to 32px; the graphics license is in licenses/Twemoji-CC-BY-4.0.txt. QQ face graphics come from Tencent public qzonestyle.gtimg.cn CDN; identifiers use the original QQ QSid/EMCode mapping. These proprietary graphics are not covered by the Twemoji license.
