# Xinwu

- 即時影像
  - 兩支即時影像
    - 北門-出入車輛可直接放行
      - 需要車牌辨識嗎?
    - 南門-出入車輛須經過判斷
      - 要進入
        - 場內的車位數>0 && 車位數-1
        - 車牌辨識為白名單 或 預約名單
      - 出
        - 場內車位數+1


- 車牌查詢
  - 區間查詢
    - 起始日期 , 結束日期(default=當日)
  - 車號查詢 
    - 可只提供部分車號
  - 進出狀態查詢 
    - (全部 進 出)


- 車流總數管理
  - 剩餘車位數量 
    - 修改 車位總數 (管理者權限)


- 入場車牌申請登記
  - 新增 白名單
  - 新增 預約名單
  - 修改 預約名單的預約時間



- 帳號密碼登入
  - 新增 使用者 (管理者權限)
  - 新增 管理者
  - 重新取得新token
  - 忘記密碼

  
- 雷達測速 (管理者權限)
  - 未超過速限
    - 不記錄資料
  - 紀錄 超過速限車輛
    - 時間 , 車號 , 車速
  - 修改 場內速限



- 燈號控制
- LED字幕機控制