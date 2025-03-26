# MCP 工具数据仓库

这个仓库包含了所有 MCP (Model Control Protocol) 工具的元数据和文档。

## 目录结构

```
.
├── tools/                # 工具目录
│   ├── index.json       # 工具索引文件
│   └── [tool-id]/       # 每个工具的目录
│       ├── meta.json    # 工具元数据
│       └── README.md    # 工具文档
```

## 数据格式

### tools/index.json

包含所有工具的分类信息和工具 ID 列表。

### tools/[tool-id]/meta.json

包含单个工具的详细信息，包括：
- 基本信息（ID、标题、描述等）
- 安装说明
- 配置选项
- 依赖关系

## 贡献指南

1. Fork 这个仓库
2. 创建你的工具分支
3. 提交你的更改
4. 创建 Pull Request