# pr-assets

PR 본문에 넣는 스크린샷 전용 공개 저장소. 코드 저장소가 private 이라 raw URL 이 PR 에서 렌더되지 않아서 따로 둔다.
공개 페이지 스크린샷만 올리고 admin 화면은 올리지 않는다.

경로: `<repo>/<branch>/<route>-<width>.png` (master|branch 좌우 합성)
참조: `https://raw.githubusercontent.com/hyeoniverse/pr-assets/main/<repo>/<branch>/<file>`

## 프로젝트별 브랜치
여러 프로젝트가 같이 쓰므로 새 이미지는 프로젝트(코드 저장소) 이름의 브랜치에 올린다. main 의 기존 이미지는 이미 머지된 PR 이 참조하므로 그대로 둔다.

- 경로: `<PR 번호>/<내용>-<폭>.png`
- 참조: `https://raw.githubusercontent.com/hyeoniverse/pr-assets/<프로젝트>/<PR 번호>/<file>`
- 예: `web-portfolio-hyeoniverse` 브랜치
