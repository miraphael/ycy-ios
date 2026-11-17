# ycy-ios（CI 跳板仓库）

这个仓库只用来给 **Codemagic** 提供构建入口，真正的源码在
[miraphael/huimandao](https://github.com/miraphael/huimandao)。

构建时会把 huimandao 的 `ios/` 工程 clone 下来编译，产物是未签名的
`绘漫岛-unsigned.ipa`。

配置见 `codemagic.yaml` 里的 `build-huimandao` workflow。
