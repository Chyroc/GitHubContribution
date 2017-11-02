# MyContribution

Crawl all merged pull request and show on `README.md`

## Basic

### Dependencies

 - Python 3.5+
 - request (only in sync mode)

```bash
pip3 install request
```
 - aiohttp (only in async mode)

```bash
pip3 install aiohttp
```

### How to use

Fork this repository and 

```bash
# 密码模式
python3 contribution.py

# token模式
python3 contribution.py -t <github token>
```

Default mode is `ASYNC`, if error happened, you can try slower `--sync` mode.

Use `--help` to see full options and usage.

## Contributions(245 merged)

* [**littlecodersh/trip**(★57)](https://github.com/littlecodersh/trip) - [Fix/lack import](https://github.com/littlecodersh/trip/pulls/2)
* [**schollz/progressbar**(★111)](https://github.com/schollz/progressbar) - [fix remove Duration.Round to compatible with version less than go1.9](https://github.com/schollz/progressbar/pulls/3)
* [**airyland/vux**(★9895)](https://github.com/airyland/vux) - [fix docs use i18n link err](https://github.com/airyland/vux/pulls/2130)
* [**dudustin/Java**(★3)](https://github.com/dudustin/Java) - [添加了git忽略文件](https://github.com/dudustin/Java/pulls/1)
