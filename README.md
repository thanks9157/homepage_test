# homepage_test

간단한 정적 홈페이지입니다. 빌드 과정 없이 HTML, CSS, JavaScript 파일로 구성되어 있습니다.

## 파일 구성

- `index.html` — 페이지 구조와 내용
- `style.css` — 디자인 (라이트/다크 모드 자동 대응, 모바일 대응)
- `script.js` — 간단한 동작 (푸터 연도 자동 갱신)

## 미리보기

브라우저에서 `index.html` 파일을 열면 바로 확인할 수 있습니다.

로컬 서버로 확인하려면:

```bash
python3 -m http.server 8000
```

그 다음 http://localhost:8000 에 접속하세요.

## 내용 수정하기

- 이름, 소개, 프로젝트, 이메일은 `index.html`에서 직접 고치면 됩니다.
- 색상은 `style.css` 상단의 `:root` 변수에서 바꿀 수 있습니다.
