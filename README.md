# 荣格八维认知功能知识库

一套系统化的荣格认知功能理论参考资料，基于 Hugo + Hextra 主题构建，部署于 Cloudflare Pages。

**在线访问**：[mbti-docs.pages.dev](https://mbti-docs.pages.dev)

## 内容概览

| 模块 | 篇数 | 内容 |
|------|:----:|------|
| 总论与基础框架 | 3 | 理论全景、与 MBTI 的关系、Socionics 对比 |
| 八维功能深度解析 | 8 | Se·Si·Ne·Ni·Te·Ti·Fe·Fi 逐一拆解 |
| 功能位置 | 8 | 主导·辅助·第三·劣势 + 四个影子功能位 |
| 功能轴 | 4 | Te-Fi·Ti-Fe·Se-Ni·Si-Ne |
| 16 型人格画像 | 16 | 每种类型的完整功能栈分析 |
| 动态机制 | 4 | Loop·Grip·生命周期·协作 |
| 实际应用 | 6 | 人际关系·成长·职业·教育·心理健康·领导力 |
| 学术视角 | 4 | 历史·神经科学·Socionics·跨体系整合 |
| 工具与索引 | 2 | 速查手册·FAQ 与推荐资源 |

共 **55 篇**深度文章，约 **80 万字**。

## 技术栈

- **静态站点生成**：[Hugo](https://gohugo.io/) v0.160.1 Extended
- **主题**：[Hextra](https://github.com/imfing/hextra)
- **部署**：[Cloudflare Pages](https://pages.cloudflare.com/)

## 本地开发

```bash
# 克隆（含主题子模块）
git clone --recurse-submodules https://github.com/ZenzZwei/mbti-site.git
cd mbti-site

# 启动本地服务器
hugo server --disableFastRender
```

访问 `http://localhost:1313/`

## 许可证

[Apache License 2.0](LICENSE)
