# 우리 팀 Farewell Playlist

GitHub Pages에 바로 올릴 수 있도록 정리한 버전입니다.

## 파일 구조

```text
저장소 루트/
├─ index.html
├─ .nojekyll
├─ photos/
│  ├─ team-1.jpg
│  ├─ team-2.jpg
│  ├─ team-3.jpg
│  ├─ team-4.jpg
│  ├─ choi-arim.jpg
│  ├─ choi-sunghyun.jpg
│  ├─ kim-eunseo.jpg
│  ├─ kwon-minje.jpg
│  ├─ jeon-suhyun.jpg
│  └─ park-seungwon.jpg
└─ music/
   ├─ choi-arim-youth.mp3
   ├─ choi-sunghyun-how-lucky-am-i.mp3
   ├─ kim-eunseo-nobody-else.mp3
   ├─ kwon-minje-kaiju-no-hanauta.mp3
   ├─ jeon-suhyun-dancin-krono-remix.mp3
   └─ park-seungwon-in-the-stars.mp3
```

## GitHub에 올리는 방법

1. GitHub에서 새 저장소를 만듭니다.
2. 이 폴더 안의 파일과 폴더를 저장소 루트에 그대로 업로드합니다.
3. `photos` 폴더에는 jpg 사진 파일을, `music` 폴더에는 mp3 음악 파일을 넣습니다.
4. 저장소의 **Settings → Pages**로 이동합니다.
5. **Build and deployment → Source**를 `Deploy from a branch`로 설정합니다.
6. Branch를 `main`, 폴더를 `/root`로 선택한 뒤 저장합니다.
7. 잠시 후 표시되는 GitHub Pages 주소로 접속합니다.

## 주의할 점

- GitHub Pages는 저장소 루트의 `index.html`을 첫 화면으로 인식합니다.
- HTML 안의 파일명과 실제 업로드한 파일명이 1글자라도 다르면 사진/음악이 나오지 않습니다.
- 음악은 브라우저 정책상 사용자가 재생 버튼을 눌러야 재생됩니다.
- 상업 음원은 저작권 문제가 생길 수 있으니 공개 저장소에 올릴 때 주의하세요.
