# LinuxWaveOrg/Deps

LinuxWave 的依赖库存放处。形态与 [LinuxWaveOrg/Bottle](https://github.com/LinuxWaveOrg/Bottle)
完全相同，只是承载的是依赖（`depsinfo_*` 那一侧）而不是软件包。

```
tag   = 依赖名
资产名 = <依赖名>@<版本>.<架构><扩展名>

https://github.com/LinuxWaveOrg/Deps/releases/download/zlib/zlib%401.3.1.amd64.tar.gz
```

来源多是 conda 的归档（`repo.continuum.io`、`conda.anaconda.org`），因此
`.tar.bz2` 与 `.conda` 是主流格式。

## 硬规则

与 Bottle 一致的四条：不改名、不替换、先校验再上传、架构写进文件名。
