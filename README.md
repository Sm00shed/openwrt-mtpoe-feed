# openwrt-mtpoe-feed

OpenWrt package feed for mtpoe-ctrl (MikroTik PoE controller).

## Description

This feed provides the mtpoe-ctrl package for OpenWrt.
Target device: MikroTik RB5009UPr+S+IN

## Usage

Add to feeds.conf.default:

    src-git mtpoe https://github.com/Sm00shed/openwrt-mtpoe-feed.git

Then:

    ./scripts/feeds update mtpoe
    ./scripts/feeds install mtpoe-ctrl

## Credits

- [adron-s](https://github.com/adron-s) - Original author of mtpoe_ctrl, relicensed to GPL-2.0
- [prudy](https://github.com/prudy) - RB5009UPr adaptations
- [Nerdleben](https://github.com/Sm00shed) - Initiated relicensing to GPL-2.0, feed repo, testing

## Source

https://github.com/adron-s/mtpoe_ctrl

## License

GPL-2.0
