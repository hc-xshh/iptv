# IPTV

> iptv-org/iptv 的浅克隆。全球 IPTV 直播源合集，包含按国家/分类整理的 M3U 播放列表。

**本项目为 clone（上游：iptv-org/iptv）。仅供参考引用，不做修改。**

## Usage

```bash
# 查找可用的中文电视台
grep -r "CCTV\|卫视" streams/

# 查看特定国家的频道列表
cat streams/cn.m3u
```

## Structure

```
streams/        # M3U 播放列表（按国家/分类）
scripts/        # 维护脚本
tests/          # 测试
```

## Notes

- 浅克隆（只保留了最新 commit），如需完整历史需重新 clone
- 数据为静态参考，不参与自动化 pipeline
- 上游更新频繁，需要时可 `git pull`
