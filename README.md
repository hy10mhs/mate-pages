# mate-pages

Mate 앱 관련 **정적 페이지**(GitHub Pages). App Store / Play Console에 넣을 **개인정보 처리방침 URL** 용.

## 페이지

| 경로 | 설명 |
| --- | --- |
| [docs/privacy-policy.html](docs/privacy-policy.html) | 개인정보 처리방침 (스토어에 넣을 주소는 아래 설정 후) |

## GitHub Pages 설정

1. GitHub에서 이 저장소 → **Settings** → **Pages**
2. **Build and deployment** → Source: **Deploy from a branch**
3. Branch: **main** (또는 기본 브랜치), Folder: **/docs**
4. 저장 후 몇 분 뒤 공개 URL 확인 (예: `https://<user>.github.io/mate-pages/`)

**App Store Connect에 넣을 URL 예:**

`https://<user>.github.io/mate-pages/privacy-policy.html`

(조직/사용자명과 저장소 이름에 맞게 바꿈.)

## 커스텀 도메인 (선택)

`r-mate.click` 등을 쓰려면 Pages 설정에 Custom domain 추가 후, DNS에 GitHub 안내(CNAME/A) 반영.

## trier 저장소와의 관계

원본 앱 저장소(`trier`)의 `mate_app/legal/privacy-policy.html` 과 동일한 내용을 유지하려면, 수정 시 **둘 다** 맞추거나 한쪽만 정본으로 두고 복사하세요.
