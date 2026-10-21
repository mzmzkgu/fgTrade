# fgTrade (F&amp;G 매매전략 · TQQQ)

공포탐욕지수(Fear &amp; Greed)와 VIX를 기준으로 TQQQ(나스닥 3배 레버리지 ETF)를 분할 매수·매도하는 전략의 상태 대시보드.

## 구성
- `index.html` — F&amp;G 지수, VIX, TQQQ 현재가, 환율(KRW/USD)과 함께 매수/매도 진행 상황, 매수·매도 기록을 보여주는 페이지 (Chart.js 사용)

## 동작 방식
- 공포(F&amp;G 낮음·VIX 높음) 구간에서 분할 매수, 탐욕 구간에서 분할 매도하는 역발상 전략
- 매수/매도 기록을 Google Sheets에 저장해서 관리
