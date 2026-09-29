# haruharu-apply

`apply.haruharu.co.kr` 인스타 바이오 랜딩. 서울/광주 버튼 → join 신청폼으로 보냄.

- Cloudflare Pages 프로젝트 `haruharu`
- `main` 에 push 하면 자동 배포 (Actions `deploy`). 1분 안쪽
- 파일은 `index.html` + `img/` 가 전부. 빌드 없음
- 잘못 올라가면 → Cloudflare 대시보드 `haruharu` → Deployments 에서 이전 배포 Rollback, 또는 `git revert` 후 push
