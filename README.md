# FreeD TV直播源配置

一个集合了多种直播源配置的电视盒子应用配置仓库。

## 项目简介

本项目整合了适用于 TVBox 和 FreeDTV 的直播源配置，包括多个主流直播平台的源地址和解析配置。

## 目录结构

```
freed/
├── TVBox/               # TVBox 配置文件
│   ├── meow.json        # 主配置源
│   ├── meow_uncensored.json
│   └── meowcf.json
│
└── tv/                  # FreeDTV 直播源
    ├── Bilibili.json    # B站直播源
    ├── Bilibili.txt
    ├── douyu.json       # 斗鱼直播源
    ├── douyu.txt
    ├── huya.json        # 虎牙直播源
    ├── huya.txt
    ├── live.txt         # 直播频道列表
    ├── public.json      # 公共源
    ├── searchUrl.json   # 搜索地址
    ├── searchUrl2.json
    ├── sourceNavigation.json
    ├── vipParse.json    # VIP解析配置
    └── webPlugNavigation.json
```

## 配置源

### TVBox 配置
- **meow.json** - 主配置源
- **meow_uncensored.json** - 未删减版配置
- **meowcf.json** - CF版本配置

### 直播平台支持
- 哔哩哔哩 (Bilibili)
- 斗鱼直播 (Douyu)
- 虎牙直播 (Huya)
- 公共直播源

## 使用说明

### TVBox 使用方法
1. 打开 TVBox 应用
2. 配置数据源地址
3. 切换数据源即可使用

### FreeDTV 使用方法
1. 安装 FreeDTV 应用
2. 导入对应配置文件
3. 开始观看直播

## 注意事项

- 部分直播源可能需要 VIP 解析
- 请遵守相关直播平台的使用协议
- 定期更新配置以获取最佳体验

## 许可证

本项目仅供学习交流使用，请勿用于商业用途。