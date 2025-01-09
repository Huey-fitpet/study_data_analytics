| Column | Data Type | 설명 | 분석가 의견 |
|--------|-----------|------|------------|
| Income | float64 | 수입 | 왜도가 양수 오른쪽 치우침 |
| Age | int64 | 나이 | 중간중간 특정나이대가 비어있으나 전체적으로 고루분포됨 |
| Dependents | int64 | 부양가족 수 | 고루분포 0~4 까지|
| Occupation | object | 직업 | 4분류 |
| City_Tier | object | 도시 등급 | 3분류 |
| Rent | float64 | 임대료 |  왜도가 양수 오른쪽 치우침 |
| Loan_Repayment | float64 | 대출 상환금 |  왜도가 양수 오른쪽 치우침 |
| Insurance | float64 | 보험료 |  왜도가 양수 오른쪽 치우침 |
| Groceries | float64 | 식료품비 |  왜도가 양수 오른쪽 치우침 |
| Transport | float64 | 교통비 |  왜도가 양수 오른쪽 치우침 |
| Eating_Out | float64 | 외식비 |  왜도가 양수 오른쪽 치우침 |
| Entertainment | float64 | 오락비 |  왜도가 양수 오른쪽 치우침 |
| Utilities | float64 | 공과금 |  왜도가 양수 오른쪽 치우침 |
| Healthcare | float64 | 의료비 |  왜도가 양수 오른쪽 치우침 |
| Education | float64 | 교육비 |  왜도가 양수 오른쪽 치우침 |
| Miscellaneous | float64 | 기타 지출 |  왜도가 양수 오른쪽 치우침 |
| Desired_Savings_Percentage | float64 | 목표 저축률 | 10%,15%,25%의 계단형|
| Desired_Savings | float64 | 목표 저축액 |  왜도가 양수 오른쪽 치우침 |
| Disposable_Income | float64 | 가처분 소득 |  왜도가 양수 오른쪽 치우침 |
| Potential_Savings_Groceries | float64 | 식료품 잠재 절약액 |  왜도가 양수 오른쪽 치우침 |
| Potential_Savings_Transport | float64 | 교통비 잠재 절약액 |  왜도가 양수 오른쪽 치우침 |
| Potential_Savings_Eating_Out | float64 | 외식비 잠재 절약액 |  왜도가 양수 오른쪽 치우침 |
| Potential_Savings_Entertainment | float64 | 오락비 잠재 절약액 |  왜도가 양수 오른쪽 치우침 |
| Potential_Savings_Utilities | float64 | 공과금 잠재 절약액 |  왜도가 양수 오른쪽 치우침 |
| Potential_Savings_Healthcare | float64 | 의료비 잠재 절약액 |  왜도가 양수 오른쪽 치우침 |
| Potential_Savings_Education | float64 | 교육비 잠재 절약액 |  왜도가 양수 오른쪽 치우침 |
| Potential_Savings_Miscellaneous | float64 | 기타 지출 잠재 절약액 |  왜도가 양수 오른쪽 치우침 |
데이터가 전체적으로 결측치가 없으나 연속형 데이터의 경우 0과 가까운쪽에 몰려 있고 오른쪽 테일이 길게 생기는 형태의 데이터로 구성되어 있다. (오른쪽 치우침. 왜도가 양수)
아마, 어떠한 격차 같은 것을 볼 수 있을 것이라고 예상된다.