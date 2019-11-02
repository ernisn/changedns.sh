# changedns.sh
A script to set permanent DNS nameserver.

修改 DNS 并且使用 *resolvconf* 来防止 Nameserver 被自动重新覆盖而丢失 DNS 设置。

## 使用方法
```bash
wget --no-check-certificate 'https://raw.githubusercontent.com/ernisn/changedns.sh/master/changedns.sh' && bash changedns.sh
```
