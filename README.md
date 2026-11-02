# 치즈 슬링샷 (Cheese Slingshot)

고양이 바구니에 치즈를 쏘아 쥐를 잡는 미니 게임입니다.
단일 HTML 파일로 동작하며, GitHub Pages에서 바로 플레이할 수 있습니다.

## 플레이 방법

- **드래그 & 릴리스**: 바구니 뒤로 당겨서 치즈를 발사합니다.
- **목표**: 날아오는 치즈로 쥐를 모두 제거하면 승리, lives가 0이 되면 게임 오버.
- 게임 오버 팝업에는 최종 점수가 강조 표시됩니다.

## 실행

`index.html`을 브라우저로 열면 됩니다. 별도 빌드 과정이 없습니다.

## 배포

GitHub Actions 워크플로(`.github/workflows/deploy.yml`)가 master 브랜치 push 시
리포 루트의 정적 파일을 GitHub Pages로 자동 배포합니다.
