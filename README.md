# THU-Tools

## thu-cloud-dl.py

方便地递归下载清华云盘的方式，纯命令行环境执行，需要预先安装 `click`、`rich`、`requests` 包。已修改为并发下载

使用方式：

```shell
>>> python thu-cloud-dl.py --help
Usage: thu-cloud-dl.py [OPTIONS] URL

  Recursively download files from the Tsinghua Cloud.

Options:
  --exclude-exts TEXT Comma-separated list of file extensions, e.g. mp4,mp3 .
  --max-workers INT Maximum number of concurrent downloads.
  --help Show this message and exit.
这段代码的 `--max-workers` 选项用来设置并发下载的最大数量，默认为5。如果网络环境允许，可以适当提高这个值以增加下载速度。

```

效果图

![CleanShot 2023-07-06 at 22.54.13@2x](README.assets/CleanShot%202023-07-06%20at%2022.54.13@2x.png)
