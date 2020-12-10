# baulk-bucket

Nocalhost baulk private bucket


## Usage


## 使用方法

编辑 `baulk.json` 添加 nocalhost 源，下面是一个示例：

```json
{
    "bucket": [
        {
            "description": "Baulk default bucket",
            "name": "Baulk",
            "url": "https://github.com/baulk/bucket",
            "weights": 100
        },
        {
            "description": "Nocalhost private bucket",
            "name": "Nocalhost",
            "url": "https://github.com/nocalhost/baulk-bucket",
            "weights": 200
        }
    ],
    "channel": "insider"
}
```

```pwsh
baulk u -V
baulk i nocalhost -V
```