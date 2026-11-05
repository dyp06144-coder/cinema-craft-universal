# 原文件到通用中文版的映射

## 版本与来源

原导出：46个文本文件，导出于2026-11-05。原风格库版本：`18e0b276406a1ea1568f5a1562f43bc31e46bc75`。中文通用改编版本：`1.0.0-zh`。

原风格规范按27个页面切分，同一风格跨页；先依原始manifest重建59个完整风格，再按风格编写独立中文制作规范。新文件有新的SHA-256，原始SHA-256仅用于来源追溯，不冒充中文校验值。详见 `style-manifest.json`。

## 改编规则

- 删除“必须在Lumina”“只能使用原生Question”“缺少原生编辑器不得用本地工具”等宿主排他规则；保留真实能力验证、授权、版本和完整成果审核。
- 固定模型、quality/image-area开关、30秒路由和服务商音频阈值改为检查当前工具schema；具体视觉布局及声音检查继续保留。
- 合并重复运行时条款，保留有界修复、接受状态未知不重提、仅失效实际依赖、静音不等于去配乐、无字幕不等于不剪辑等核心约束。
- 风格规范按中文执行需求重组，保留各自媒介与动作/镜头/颜色/版式/声音/数值重点、典型手法、错误检查、变化空间和提示词。移除未随包提供的demo工程操作命令，以实际可用工具路线代替；不是逐句对照翻译或可直接运行的原demo副本。
- 保留必要机器标识、颜色值、原始哈希、标题及法律声明原文。旧使用说明的51种说法不延续；实际为59种。

## 46个原始文件的去向

下列新参考文件路径相对于本目录；根入口及配置按标注位置。

| 原始文件 | 通用版对应位置 |
|---|---|
| `SKILL.md` | `../SKILL.md` |
| `agents/openai.yaml` | `../agents/openai.yaml` |
| `references/artifact-first.md` | `runtime-control.md`、`story-visual-development.md` |
| `references/audio-postproduction.md` | `audio-postproduction.md` |
| `references/canvas-tables.md` | `production.md`、`artifact-contracts.md` |
| `references/characters-voices.md` | `characters-assets.md`、`audio-postproduction.md` |
| `references/image-settings.md` | `characters-assets.md`、`host-adapters.md` |
| `references/language-policy.md` | `../SKILL.md`、`runtime-control.md` |
| `references/moodboard-visuals.md` | `story-visual-development.md`、`characters-assets.md` |
| `references/postproduction-options.md` | `audio-postproduction.md` |
| `references/production-requests.md` | `production.md`、`runtime-control.md` |
| `references/production-workflow.md` | `../SKILL.md`、`audio-postproduction.md`、`runtime-control.md` |
| `references/props-assets.md` | `characters-assets.md` |
| `references/reference-media.md` | `story-visual-development.md` |
| `references/runtime-control.md` | `runtime-control.md` |
| `references/speech-inputs.md` | `production.md`、`characters-assets.md` |
| `references/story-development.md` | `story-visual-development.md`、`../THIRD_PARTY_NOTICES.txt` |
| `references/style-index.md` | `style-index.md` |
| `references/style-manifest.json` | `style-manifest.json` |
| `references/style-specs-01.md` | `styles/（按风格重新拆分；对应片段见 style-manifest.json）` |
| `references/style-specs-02.md` | `styles/（按风格重新拆分；对应片段见 style-manifest.json）` |
| `references/style-specs-03.md` | `styles/（按风格重新拆分；对应片段见 style-manifest.json）` |
| `references/style-specs-04.md` | `styles/（按风格重新拆分；对应片段见 style-manifest.json）` |
| `references/style-specs-05.md` | `styles/（按风格重新拆分；对应片段见 style-manifest.json）` |
| `references/style-specs-06.md` | `styles/（按风格重新拆分；对应片段见 style-manifest.json）` |
| `references/style-specs-07.md` | `styles/（按风格重新拆分；对应片段见 style-manifest.json）` |
| `references/style-specs-08.md` | `styles/（按风格重新拆分；对应片段见 style-manifest.json）` |
| `references/style-specs-09.md` | `styles/（按风格重新拆分；对应片段见 style-manifest.json）` |
| `references/style-specs-10.md` | `styles/（按风格重新拆分；对应片段见 style-manifest.json）` |
| `references/style-specs-11.md` | `styles/（按风格重新拆分；对应片段见 style-manifest.json）` |
| `references/style-specs-12.md` | `styles/（按风格重新拆分；对应片段见 style-manifest.json）` |
| `references/style-specs-13.md` | `styles/（按风格重新拆分；对应片段见 style-manifest.json）` |
| `references/style-specs-14.md` | `styles/（按风格重新拆分；对应片段见 style-manifest.json）` |
| `references/style-specs-15.md` | `styles/（按风格重新拆分；对应片段见 style-manifest.json）` |
| `references/style-specs-16.md` | `styles/（按风格重新拆分；对应片段见 style-manifest.json）` |
| `references/style-specs-17.md` | `styles/（按风格重新拆分；对应片段见 style-manifest.json）` |
| `references/style-specs-18.md` | `styles/（按风格重新拆分；对应片段见 style-manifest.json）` |
| `references/style-specs-19.md` | `styles/（按风格重新拆分；对应片段见 style-manifest.json）` |
| `references/style-specs-20.md` | `styles/（按风格重新拆分；对应片段见 style-manifest.json）` |
| `references/style-specs-21.md` | `styles/（按风格重新拆分；对应片段见 style-manifest.json）` |
| `references/style-specs-22.md` | `styles/（按风格重新拆分；对应片段见 style-manifest.json）` |
| `references/style-specs-23.md` | `styles/（按风格重新拆分；对应片段见 style-manifest.json）` |
| `references/style-specs-24.md` | `styles/（按风格重新拆分；对应片段见 style-manifest.json）` |
| `references/style-specs-25.md` | `styles/（按风格重新拆分；对应片段见 style-manifest.json）` |
| `references/style-specs-26.md` | `styles/（按风格重新拆分；对应片段见 style-manifest.json）` |
| `references/style-specs-27.md` | `styles/（按风格重新拆分；对应片段见 style-manifest.json）` |

## 未打包的资源

原风格规范引用的样片、DEMO.md、demo/、渲染引擎、字体文件、照片、音乐和其他外部素材未随原页面导出，因此也不被本包宣称提供。引用是资料线索，不能用文件名冒充已存在资源。相关署名/许可见 `../THIRD_PARTY_NOTICES.txt`。
