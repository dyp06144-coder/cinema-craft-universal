# Cinema Craft 通用电影制作 Skill · 中文版

面向画布与通用 Agent 的电影制作技能，包含剧本、完整分镜、角色与道具、声音一致性、镜头制作和后期交付，以及 **59种独立中文风格规范**。

适用于 Codex、Claude Code 以及能够读取提示词/知识资料的豆包等 Agent。技能按真实工具能力执行：没有媒体工具也能交付前期方案，有图像、语音、视频及剪辑工具时可继续制作。它不附带生成模型、API凭据或媒体资产。

## 下载与开始

- [下载中文版 Skill 压缩包](Cinema-Craft-通用中文版.zip)
- [技能入口](SKILL.md)
- [详细使用说明](使用说明.md)
- [59种风格索引](references/style-index.md)

下载ZIP并解压，将完整 `cinema-craft-universal` 文件夹放到宿主支持的技能目录。Codex项目可用 `.agents/skills/`，Claude Code项目可用 `.claude/skills/`；其他产品按实际文件/知识库能力接入。没有目录技能入口时使用 [通用调度提示词](agents/universal-prompt.md)。

## 示例请求

> 使用 cinema-craft-universal，把雨夜修表铺的创意做成40秒中文短片。现在只做前期，不调用付费媒体工具。先交付完整剧本与九列初步分镜，标明估时；确认后再按可用工具继续制作。

## 内容结构

```text
SKILL.md
agents/              可选界面元数据与通用提示词
references/          工作流、成果规范、来源映射与索引
  styles/            59份独立中文风格规范
使用说明.md
THIRD_PARTY_NOTICES.txt
package-manifest.json
```

本版经过平台无关改造与中文重编，不是原资料的逐行对照翻译。文件与来源校验、75处本地引用及六种文本/调度场景已验证；未在所有产品与付费媒体接口上实测整片生成。实际能力与权限由宿主提供。

## 开源许可

本仓库的新增内容采用 [MIT License](LICENSE)。改编资料的必要版权与许可声明集中保留于 [第三方许可文件](THIRD_PARTY_NOTICES.txt)。示例媒体、外部素材与服务不随技能提供。
