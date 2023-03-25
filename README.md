# Scoop

## 安装 scoop
```powershell
# 典型安装，非管理员
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
irm get.scoop.sh | iex

# 高级安装
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
irm get.scoop.sh -outfile 'install.ps1'
# 查看命令
.\install.ps1 -?
# 例子：自定义安装目录
.\install.ps1 -ScoopDir 'D:\Applications\Scoop' -ScoopGlobalDir 'F:\GlobalScoopApps' -NoProxy
```

## 添加 bucket
```powershell
scoop bucket add apps https://github.com/sncwt/scoop-bucket
```

## 搜索应用
[scoop.sh](https://scoop.sh/#/apps?s=0&d=1&o=true)

## 安装应用
```powershell
scoop insal <bucket>/<app_name>
```

## 此仓库部分应用引用列表
> 非官方认证的 bucket
1. [clash-verge](https://github.com/chawyehsu/dorado/blob/811aed9e00a2ec0ba6e49b09d7a36c2a37eb935d/bucket/clash-verge.json)


## Scoop wiki
- [Scoop Wiki](https://github.com/ScoopInstaller/Scoop/wiki)

