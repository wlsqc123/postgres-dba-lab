# postgres-dba-lab

PostgreSQL DBA 실습 저장소입니다.

단순 암기보다 **문제 → 예측 → 실험 → 상태 변화 관찰 → 원리 이해 → 인출 복습** 순서로 학습합니다.

## Study Method

- [DBA 학습 방법과 루틴](docs/STUDY_METHOD.md)
- [일일 학습 기록 템플릿](docs/STUDY_TEMPLATE.md)

핵심 원칙:

```text
많이 읽기 < 많이 떠올리기
예쁜 정리 < 짧은 압축
정상 동작 < 장애 재현
명령어 암기 < 내부 상태 이해
완독 < 문제 해결
```

권장 복습 주기: `D+1 → D+3 → D+7 → D+14 → D+30`

## Repository Structure

```text
postgres-dba-lab/
├─ README.md
├─ docker-compose.yml
├─ labs/
│  ├─ 01-query-performance/
│  ├─ 02-mvcc-vacuum/
│  ├─ 03-lock-deadlock/
│  └─ 04-backup-pitr/
├─ scripts/
└─ docs/
   ├─ STUDY_METHOD.md
   └─ STUDY_TEMPLATE.md
```

- `01-query-performance`: 쿼리 성능 분석 및 튜닝
- `02-mvcc-vacuum`: MVCC와 VACUUM
- `03-lock-deadlock`: 잠금과 교착 상태
- `04-backup-pitr`: 백업과 시점 복구
- `scripts/`: 실습용 스크립트
- `docs/`: 학습 방법, 실습 기록, 참고 문서

현재는 기본 실습 구조를 준비한 단계입니다. 이후 각 주제를 실제 장애/성능 시나리오 중심으로 확장합니다.
