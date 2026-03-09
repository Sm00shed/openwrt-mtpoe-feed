OpenWrt package feed for mtpoe-ctrl (MikroTik PoE controller)

This feed provides the mtpoe-ctrl package for OpenWrt.
Target device: MikroTik RB5009UPr+S+IN

USAGE
Add to feeds.conf.default:
src-git mtpoe https://github.com/Sm00shed/openwrt-mtpoe-feed.git

Then:
./scripts/feeds update mtpoe
./scripts/feeds install mtpoe-ctrl

CREDITS
adron-s  - Original author of mtpoe_ctrl, relicensed to GPL-2.0
prudy    - RB5009UPr adaptations
Nerdleben - Initiated relicensing to GPL-2.0, feed repo, testing

SOURCE
https://github.com/adron-s/mtpoe_ctrl

LICENSE
GPL-2.0
