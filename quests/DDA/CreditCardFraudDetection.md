| Column          | Data Type | 설명       | 분석가 의견                               |
| --------------- | --------- | ---------- | ----------------------------------------|
| TransactionID   | int64     | 고유식별자 |                                           |
| TransactionDate | object    | 결재 일자  |                                           |
| Amount          | float64   | 결재 금액  | 결재 금액이 고루 분포 되어 있다.              |
| MerchantID      | int64     | 상점 ID    | 상점 ID 도 전 구간에 걸쳐 고루 분포 되어 있다. |
| TransactionType | object    | 결재 유형  | refund = 50131 건, purchase = 49869       |
| Location        | object    | 결재 지역  | 각 지역별로 고르게 분포 되어 있다.            |
| IsFraud         | int64     | 사기 여부  | 사기 1, 정상 0 , 사기 1000건, 정상 99000건   |


데이터의 결측치와 이상치가 없으며, 데이터의 분포가 전체적으로 고루 분포 되어 있는 특징이 있다.