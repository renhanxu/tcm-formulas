# TCM Formulas (中医方剂库)

Traditional Chinese Medicine formulas and prescriptions database.

## 结构

```
├── data/
│   ├── formulas.json   # 方剂数据
│   ├── combinations.json # 配伍禁忌
│   └── index.json      # 版本信息
└── categories/
    ├── tonics/         # 补剂
    ├── cooling/        # 清热
    └── warming/        # 温阳
```

## API 调用

```typescript
const formulas = await fetch('https://cdn.jsdelivr.net/gh/renhanxu/tcm-formulas@main/data/formulas.json')
```

## 许可证

MIT License
