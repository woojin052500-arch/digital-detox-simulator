# 디지털 금욕 실험 · 사고실험 시뮬레이터

인스타그램을 하루 참을 때마다 보상이 커지는 규칙을 직접 돌려보는 단일 HTML 도구입니다.

- 조건(첫날 보상금·증가 배수·유혹 강도·실패 처리·기간)을 바꾸면 그래프, 표, 네 단계 분석이 함께 다시 계산됩니다.
- '오늘의 선택'에서 참기/열기 버튼을 눌러 날짜별 심리 저울 변화를 체험할 수 있습니다.
- 외부 라이브러리 없이 index.html 하나로 동작합니다.

https://woojin052500-arch.github.io/digital-detox-simulator/

## 배포 방법

GitHub Pages가 `gh-pages` 브랜치를 바라보고 있습니다. 내용을 고칠 때는 `main`에 커밋한 뒤 같은 커밋을 `gh-pages`로도 올려야 사이트에 반영됩니다.

    git push origin main
    git push origin main:gh-pages

연결된 GitHub 앱에 Pages 관리 권한이 없어 Settings에서 소스를 `main`으로 바꾸는 대신, `gh-pages` 브랜치 자동 퍼블리시로 운영합니다.
