# 【X-UI WARP分流】

将 JSON 模板填入 X-Ray 配置中，确保 WARP SOCKS5 出站代理已正确设置。

## 前提条件

1.VPS 上运行：

```Bash
wget -N https://gitlab.com/fscarmen/warp/-/raw/main/menu.sh && bash menu.sh [option] [lisence/url/token]
```

默认创建的 SOCKS5 出站为 127.0.0.1:40000。

2.安装 X-UI 面板
