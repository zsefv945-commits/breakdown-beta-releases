# INDEPENDENT_RESTORE_ENTRYPOINT — breakdown-beta-releases
**2026-11-03, GitHub-only first-stage audit.** Existing history preserved; documentation is not authorization for development.

## Purpose
BreakDown 공개 베타 배포 아티팩트와 한국어·영어 랜딩

## Baseline and independent checkout
- Repository: https://github.com/zsefv945-commits/breakdown-beta-releases (permission required).
- **Observed `main` SHA:** `9200e2b4bf20ba8ae70c49aa758ccfcb533967b2` (not necessarily last fully verified product).
- Documentation-only branch: `docs/independent-restore-20261103`; intentionally unmerged.
- `git clone git@github.com:zsefv945-commits/breakdown-beta-releases.git`
- `cd breakdown-beta-releases`
- `git checkout 9200e2b4bf20ba8ae70c49aa758ccfcb533967b2`
- Read existing README and history/decision/railway/handoff, then inspect other refs *without merging*.

## Exact existing reference paths
- main README.md
- landing/public-beta-001
- Release v0.1.0-beta.1 (ZIP SHA-256 is recorded in original release/handoff)

## Next **potential** restore check, not performed
출시 릴리스 자산과 기록된 ZIP SHA-256 확인; 실제 로컬 ZIP 실행은 별도 환경에서만.

## Gaps and safety
배포 ZIP이 다운로드 가능하다는 사실과 개별 원본 소스 재구성은 별개. 서명/배포 권리·비밀키 확인 없이 재공개 금지.

Independent environment gates: A Git checkout/files **NOT_EXECUTED**, B runtime **NOT_TESTED**, C dependency installation **NOT_TESTED**, D original test run **NOT_TESTED**, E offline core smoke **NOT_TESTED**, F source/output SHA check **NOT_TESTED**, G actual failure ledger **PARTIAL**. All repository SHA/branch lookups above are GitHub **metadata-only** checks.

Preserve main and operational data; no new workflow, no external publish, no paid/live API calls, no human gate bypass, no automatic merge. Historical test evidence != independent reconstruction. Actions artifacts can expire. Record any absent original as `SOURCE_MISSING` only after searching all relevant refs, not simply default main.
