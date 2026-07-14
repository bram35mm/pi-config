# Pi 配置

Bram35mm 的 pi 编码助手配置。

## 新机器初始化

```bash
# 1. 克隆配置
git clone git@github.com:bram35mm/pi-config.git ~/.pi

# 2. 安装第三方扩展包
pi install npm:pi-mcp-adapter
pi install npm:@tintinweb/pi-subagents
pi install npm:pi-btw
pi install npm:pi-web-access

# 3. 重新登录认证（生成新的 auth.json）
pi
```
