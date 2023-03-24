# Scoop

## Install scoop
*For Admin*
```powershell
irm get.scoop.sh -outfile 'install.ps1'
.\install.ps1 -RunAsAdmin [-OtherParameters ...]
# I don't care about other parameters and want a one-line command
iex "& {$(irm get.scoop.sh)} -RunAsAdmin"
```

## Add this bucket
```powershell
scoop bucket add apps https://github.com/sncwt/scoop-bucket
```

## Basic usage
*Wiki*
- [Scoop Wiki](https://github.com/ScoopInstaller/Scoop/wiki)

*How to create bucket*
- https://www.simaek.com/archives/88/
- https://zhuanlan.zhihu.com/p/413985471

## Apps
*Reference*
- [Main](https://github.com/ScoopInstaller/Main)
- [Extras](https://github.com/ScoopInstaller/Extras)
- [Nonportable](https://github.com/ScoopInstaller/Nonportable)
- [dorado](https://github.com/chawyehsu/dorado)
- [scoop-apps](https://github.com/kkzzhizhou/scoop-apps)
