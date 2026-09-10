# Clash DeFi 域名规则

在 [defi.yaml](defi.yaml) 中维护需要走“区块链”分组的域名。

点击文件右上角的编辑按钮，按现有格式增加或删除一行，然后提交修改。

```yaml
payload:
  - '+.uniswap.org'
  - '+.aave.com'
```

`+.example.com` 匹配该域名及全部子域名。只填写域名，不填写 `https://`、路径或端口。

现有 Clash 订阅每小时检查一次规则更新，不需要重新发布完整配置。GitHub Raw 可能短暂缓存；需要立即生效时可在 Clash 中手动更新规则提供器。

原始规则地址：

https://raw.githubusercontent.com/feelgood3000/clash-defi-rules/main/defi.yaml

仓库仅存放公开域名，不要加入节点密码、机场订阅令牌或私人订阅链接。此清单用于分流，不保证网站可访问。
