# qtae-blog-images

이 저장소는 [dailymusings.github.io](https://dailymusings.github.io) 블로그에서 사용하는 이미지 파일들을 관리하기 위해 만들어졌습니다.  
모든 블로그 게시글에 포함된 이미지들은 이 저장소에 업로드되며, GitHub Pages를 통해 정적 자산으로 제공됩니다.

## 이미지 업로드 방식

본 저장소는 [Obsidian](https://obsidian.md)에서 작성한 블로그 글을 기반으로 이미지 업로드가 자동화되어 있습니다.  
자동 업로드를 위해 아래 플러그인을 사용합니다:

- 🔌 [`obsidian-image-upload-toolkit`](https://github.com/addozhang/obsidian-image-upload-toolkit)
  - Obsidian에서 복사한 이미지를 클립보드에서 자동으로 저장하고 GitHub 저장소로 업로드
  - GitHub 토큰 기반 인증으로 안전한 커밋/푸시 지원
  - 업로드된 이미지의 URL을 자동으로 마크다운에 삽입

## 사용 목적

- 블로그 글과 이미지를 분리하여 관리함으로써 저장소 구조를 깔끔하게 유지
- 이미지 요청 속도 향상 (CDN 기반 GitHub Pages)
- 블로그 마크다운 파일과의 버전 충돌 방지

---

> 이 저장소는 단독 실행 목적이 아닌, 블로그 운영을 위한 이미지 저장 전용 공간입니다.
