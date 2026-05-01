# oneul-cross-data

`오늘의 크로스` 모바일 앱이 fetch하는 데이터 미러.

## 갱신 주기

매일 KST 16:30 (장마감 16:00 + 30분 여유), 월~금
GitHub Actions로 자동 갱신 — 워크플로우는 [`oneul_cross`](https://github.com/singongjineung/oneul_cross) 레포에 있음.

## 엔드포인트

`https://singongjineung.github.io/oneul-cross-data/signals.json`

## 데이터 출처

[FinanceDataReader](https://github.com/financedata-org/FinanceDataReader) (KRX 공시 기반)

## 면책

투자 정보 제공 목적으로만 사용되며, 매수/매도 추천이 아닙니다.
