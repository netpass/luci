# RosyWrt luci feed

## Description

This is the RosyWrt "luci"-feed based on [LuCI](https://github.com/openwrt/luci) Project from [OpenWrt](https://github.com/openwrt/openwrt). It contains [luci-theme-rosy](https://github.com/rosywrt/luci-theme-rosy).

## Usage

This feed is enabled by default. Your feeds.conf.default (or feeds.conf) should contain a line like:
```
src-git luci https://github.com/rosywrt/luci.git
```

To install all its package definitions, run:
```
./scripts/feeds update luci
./scripts/feeds install -a -p luci
```

## Contact RosyWrt
* Bug Report : https://github.com/rosywrt/luci/issues

* QQ Gourp : 428742246

## License

See [LICENSE](LICENSE) file.

## References
* API [documentation](http://htmlpreview.github.io/?http://raw.githubusercontent.com/openwrt/luci/master/documentation/api/index.html).

* Development [Wiki](https://github.com/openwrt/luci/wiki).

* [Package Guidelines](CONTRIBUTING.md)  file.
