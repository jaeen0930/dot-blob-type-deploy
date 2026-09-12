# Dot Blob Type — 웹 배포 패키지

`index.html` 한 파일이 전부입니다(외부 의존은 Google Fonts뿐). 아래 중 하나로 올리면 됩니다.

## A. GitHub Pages (무료, 영구 주소)
1. github.com에서 새 저장소 `dot-blob-type` 생성(Public)
2. `index.html` 업로드 → Commit
3. Settings → Pages → Branch: main / (root) → Save
4. 1분 뒤 `https://<아이디>.github.io/dot-blob-type/` 에서 열림

## B. Netlify Drop (가장 빠름)
1. app.netlify.com/drop 접속(무료 계정)
2. 이 폴더(`deploy/`)를 통째로 드래그
3. 바로 `https://<임의이름>.netlify.app` 주소 발급 → Site settings에서 이름 변경 가능

## C. Vercel
`vercel` CLI 또는 대시보드에서 폴더 업로드, 프레임워크 "Other".

SVG/PNG 저장 버튼은 일반 브라우저에서는 바로 다운로드되고, claude.ai 아티팩트 안에서는 확인창을 거칩니다.
