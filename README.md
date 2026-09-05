# postgres-dba-lab

PostgreSQL DBA 실습 저장소입니다.

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
```

- `01-query-performance`: 쿼리 성능 분석 및 튜닝
- `02-mvcc-vacuum`: MVCC와 VACUUM
- `03-lock-deadlock`: 잠금과 교착 상태
- `04-backup-pitr`: 백업과 시점 복구
- `scripts/`: 실습용 스크립트
- `docs/`: 실습 기록과 참고 문서

현재는 기본 폴더 구조만 준비되어 있습니다. `docker-compose.yml`에 PostgreSQL 서비스를 정의한 뒤 실습 환경을 실행하세요.
