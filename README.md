# Immortalwrt-mt798x for Redmi ax6000 & BananaPi R3 mini

### 固件发布:
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/hiyoi/Actions-OpenWrt?style=for-the-badge&label=固件下载)](https://github.com/hiyoi/Actions-OpenWrt/releases/latest)

#### 固件源码来源
- hanwckf-[hanwckf/immortalwrt-mt798x](https://github.com/hanwckf/immortalwrt-mt798x).
```bash
git clone -b openwrt-21.02 --single-branch https://github.com/hanwckf/immortalwrt-mt798x
```

## Redmi AX6000 不死uboot
- [hanwckf大佬uboot地址](https://github.com/hanwckf/bl-mt798x/releases/latest)
- [红米ax6000刷不死uboot](https://blog.w2aa.ga/post/ax6000-uboot.html).

## Redmi AX6000 不死ubootmod
- [红米ax6000刷不死ubootmod](https://www.right.com.cn/forum/thread-8272071-1-2.html).

## .config获取
- 默认使用 [hanwckf/immortalwrt-mt798x 的config](https://github.com/hanwckf/immortalwrt-mt798x/blob/openwrt-21.02/defconfig/mt7986-ax6000.config)
- 去掉了额外主题，luci-app-ssr-plus

### 固件初始配置
- 默认管理IP:`192.168.5.1` 
- 用户名:`root`
- 密码:`设置首次登录后台密码为空（进入openwrt后自行修改密码）`
