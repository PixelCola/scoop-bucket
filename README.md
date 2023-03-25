# Scoop

## Install scoop
```powershell
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser

irm get.scoop.sh | iex
```

## Add bucket
```powershell
scoop bucket add apps https://github.com/sncwt/scoop-bucket

scoop bucket add dorado https://github.com/chawyehsu/dorado
```

## Search apps
[scoop.sh](https://scoop.sh/#/apps?s=0&d=1&o=true)

## Install apps
```powershell
scoop insal <bucket>/<app_name>
```


## Basic usage
*Wiki*
- [Scoop Wiki](https://github.com/ScoopInstaller/Scoop/wiki)

*How to create bucket*
- https://www.simaek.com/archives/88/
- https://zhuanlan.zhihu.com/p/413985471
