# 세종 AX Workshop — Gemini Enterprise 사용자 기본 교육

법무법인(유) 세종 비IT 직군 대상 **사용자 기본 교육(90분: 이론 45분 + 실습 45분)** 웹 자료입니다.

| 페이지 | 설명 |
|---|---|
| [`index.html`](index.html) | Gemini Enterprise 활용 교재 (슬라이드 111장, 검색 · 발표 모드) |
| [`SEJONG_index.html`](SEJONG_index.html) | 실습 가이드북 (90분 시간표, 프롬프트 복사, 직무별 템플릿) |
| [`data_pack.zip`](data_pack.zip) | 실습용 가상 데이터팩 7종 |
| [`admin/`](admin/) | **관리자 교육** (90분): GE 관리자 기본 설정, 모니터링, 부서·팀별 통계, 크레딧, Antigravity·Agent, ChatGPT Agent 이전 진단, 운영 체크리스트 (실제 콘솔 화면 포함) |
| [`admin/slides.html`](admin/slides.html) | (선택) 관리자 교육 발표용 슬라이드 |
| [`admin/deploy.html`](admin/deploy.html) | 웹 게시 방법 (GitHub Pages 설정, 커밋·푸시, 문제 해결) |

- 실습 데이터는 모두 교육용 **가상 데이터**이며 실제 의뢰인·사건·법인 규정과 무관합니다.
- 에이전트 설계 · 노코드 에이전트 · 멀티에이전트는 이후 **사용자 활용 교육**에서 다룹니다.

Prepared by MegazoneSoft

## 웹에 올리는 방법

```
cd "C:\Megazone\교육 자료\sejong\sejong_lab_upload"
git add .
git commit -m "변경 내용 한 줄"
git push origin main
```

- 최초 1회: 저장소 **Settings › Pages › Build and deployment** → Source **Deploy from a branch**, Branch **main / (root)** → **Save**
- 확인: **Actions** 탭의 *pages build and deployment* 완료 후 `https://rmadudtjr1.github.io/sejong_lab/admin/`
- GitHub Pages 사이트는 저장소가 비공개여도 인터넷에 공개됩니다. 의뢰인·내부 정보는 올리지 마십시오.
- 자세한 순서와 문제 해결: [`admin/deploy.html`](admin/deploy.html)
