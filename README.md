# Ehcoo
一个 `ehco` 配置便捷脚本

## 优点
- [x] 简单配置 `ehco` 隧道
- [x] 支持开机自启
- [x] 支持中转机器 
- [x] 支持落地机器

## 更新
### 2021年6月30日更新
- 支持添加多个中转
- 支持国内机器使用
- 修复了 `Debian` 和 `Ubuntu` 下 `systemctl` 无法守护进程以及开机自启的问题  

## 计划功能
- 判断端口是否被占用
- 流量统计(暂时可能不会实现)

## 兼容性
支持 `CentOS` `Ubuntu` `Debian` 等 `Linux` 系统的所有版本

## 使用
```shell
wget -O ehco.sh https://cdn.jsdelivr.net/gh/owogo/Ehcoo/ehco.sh && bash ehco.sh
```
## 感谢
- 感谢 [echo](https://github.com/Ehco1996/ehco) 所有开发者的贡献
- 感谢 [Jack](https://github.com/Jackxun123) 提供的 `jq` 处理 `JSON` 的方案
- 感谢 [missuo](https://github.com/missuo) 提供的原脚本的方案

## 反馈
你可以提出ISSUES。
