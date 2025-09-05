# idle_hippo_music_resource

## 遊戲中的音樂需要下載

### flow

1. app 開啟時 loading 通過 HTTP 讀取該 repo 中的 version.json
2. 如果與 app 中的 collect_version 低於 version.json 版本就會下載該 repo 中的 collect.json
3. 如果與 app 中的 collect_version 大於等於 version.json 則直接進入遊戲主頁

## 音樂來源於 StockTune

- Echoes Of The Void: https://stocktune.com/free-music/echoes-of-the-void-291665-172428
- Viking Warriors' Final Charge: https://stocktune.com/free-music/viking-warriors-final-charge-271433-161293
- Racing Pulse Beats: https://stocktune.com/free-music/racing-pulse-beats-285807-168514
