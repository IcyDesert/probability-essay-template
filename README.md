# 2024 秋概率论与数理统计期末论文 LaTeX 模板

## 仓库说明

- `main.tex` 主文件，进行 LaTeX 写作
- `db.bib` 参考文献文件

## 注意事项

1. 所有图片放在 `./figure` 文件夹下
2. 编译时需要按照 xe->bib->xe->xe  的顺序进行，即编译四次；如果使用 VS Code，示例配置如下

```json
"latex-workshop.latex.recipes": [
{
    "name": "xe->bib->xe->xe",
    "tools": [
        "xelatex",
        "bibtex",
        "xelatex",
        "xelatex"
    ]
},
]
```
