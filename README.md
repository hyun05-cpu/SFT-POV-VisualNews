# SFT Cinematic POV — GitHub Pages

## 콘셉트
사용자가 실제로 바다에 들어가 터널까지 이동하는 1인칭 시점입니다.

1. 수면 위에서 시작
2. 수면을 통과하며 기포/빛 변화
3. 물속에서 수면을 올려다봄
4. 실제 어군 사진 + 3D 물고기를 통과
5. 멀리 SFT 등장
6. 콘크리트 외벽/리브/케이블로 접근
7. 터널 입구 진입
8. 터널 내부 1인칭 주행
9. 반대편으로 빠져나와 전체 구조 확인

## GitHub Pages 업로드
새 저장소를 만들거나 기존 비주얼뉴스 저장소를 사용할 수 있습니다.

권장 새 저장소 이름:
`SFT-POV-VisualNews`

저장소 루트 구조:
```
SFT-POV-VisualNews/
├─ index.html
├─ cms-embed.html
└─ README.md
```

1. GitHub → New repository → `SFT-POV-VisualNews`
2. Add file → Upload files
3. `index.html`, `README.md` 업로드
4. Settings → Pages
5. Deploy from a branch
6. Branch `main`, Folder `/(root)`
7. 배포 후 주소 예시:
   `https://hyun05-cpu.github.io/SFT-POV-VisualNews/`
8. `cms-embed.html` 안의 `YOUR-ID`, `YOUR-REPO`를 실제 값으로 수정
9. 기사 CMS에는 `cms-embed.html` 코드만 삽입

## 참고
- Three.js는 CDN에서 로드합니다.
- 수면/수중/어군 사진은 Wikimedia Commons URL을 사용합니다.
- SFT는 실제 완공 구조물이 아니라 기사 이해를 위한 3D 개념 시각화입니다.
