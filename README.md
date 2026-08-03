# STAY PACHIRA 랜딩페이지

이태원역 도보 2분, 5·6층 프라이빗 스테이 STAY PACHIRA의 다국어 판매 랜딩페이지입니다.

## 언어별 페이지

| 언어 | 파일 |
|---|---|
| 한국어 (기본) | `index.html` / `landing-ko.html` |
| English | `landing-en.html` |
| 日本語 | `landing-ja.html` |
| 中文 | `landing-zh.html` |
| Deutsch | `landing-de.html` |
| Français | `landing-fr.html` |
| Español | `landing-es.html` |
| العربية | `landing-ar.html` |
| Português | `landing-pt.html` |
| Русский | `landing-ru.html` |

`index.html`은 `landing-ko.html`과 동일한 내용으로, GitHub Pages 루트 주소(`/`)에 접속했을 때 한국어 페이지가 바로 보이도록 해둔 것입니다.

## GitHub Pages로 배포하는 법

이 저장소를 GitHub에 올린 뒤, 저장소 페이지에서 **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main / (root)** 을 선택하고 저장하면 됩니다.

배포가 끝나면 아래와 같은 주소로 접속할 수 있습니다 (계정명·저장소명에 맞게 바뀝니다):

```
https://<계정명>.github.io/<저장소명>/                → 한국어 (index.html)
https://<계정명>.github.io/<저장소명>/landing-en.html  → 영어
https://<계정명>.github.io/<저장소명>/landing-ja.html  → 일본어
...
```

## 참고

- 각 언어 페이지는 이미지가 base64로 파일 안에 그대로 들어있는 단일 HTML 파일이라, 별도 이미지 폴더 없이 그대로 올리면 됩니다.
- 예약 CTA는 https://litt.ly/staypachira 로 연결되어 있습니다.
- 실제 배포 도메인이 정해지면 각 파일 상단의 `hreflang`·`og:url` 값을 그 도메인으로 업데이트하는 것을 권장합니다.
