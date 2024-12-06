## 项目简介

Rime输入法配置文件，使用[雾凇拼音](https://github.com/iDvel/rime-ice)方案。

## 目录结构

```markdown
├── base                         # 雾凇拼音默认配置
└── custom                       # 自定义配置
    ├── macos    
    │   ├── default.custom.yaml  # 系统配置
    │   └── squirrel.custom.yaml # 样式配置
    └── windows  
        ├── default.custom.yaml  # 系统配置
        └── weasel.custom.yaml   # 样式配置
```

## 使用

1.克隆仓库到本地

2.将base目录中的内容，复制到`用户文件夹`内

3.在custom目录中选择对应的操作系统，将里面的配置复制到`用户文件夹`内

4.重新部署