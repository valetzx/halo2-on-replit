# halo2-on-replit

将 halo2 博客部署在 Replit 平台

## 您需要添加以下环境变量

```
HALO_WORK_DIR=${PWD}/.halo2
```

```
halo.external-url=你的replit网页
```
## 默认账号为 `admin` 密码为 `P@88w0rd`

## 更多内容请查看官方问文档：https://halo.run/

## 当前版本为 2.4 如果没有重大更新将不维护本仓库

## 使用方法：

新建一个 Java 项目，在控制台中输入以下代码后回车。Replit 最好是使用教育空间！

```
git clone https://github.com/valetzx/halo2-on-replit tmp && mv -b tmp/* ./ && mv -b tmp/.[^.]* ./ && rm -rf *~ && rm -rf tmp
```