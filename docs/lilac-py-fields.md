# `lilac.py` 文件说明

## 打包流程
* `pre_build`: 打包前执行的函数。
* `post_build`: 打包成功后执行的函数。
* `post_build_always`: 打包最后执行的函数，不论成功与否。可选。

## 辅助信息
* `makechrootpkg_args`: 传递给 `makechrootpkg` 的额外参数。可选。

## 提供的信息
* `_G.oldver`: 旧版本号。可能为 `None`。
* `_G.newver`: 新版本号。可能为 `None`。
* `lilac.yaml` 中的信息（如 `depends`、`maintainers`，已进行基本的解析）
