# solvedac-summary

# 사용 방법

```yml
- uses: actions/checkout@v5
- uses: seheon99/solvedac-summary@84d86b3137f6b45e52dcb1d60528ef28bbde411f
  with:
    username: YOUR_SOLVEDAC_HANDLE
    color: light # 또는 dark (기본값 light)
```

README의 `<!-- START AUTO-UPDATE -->`와 `<!-- END AUTO-UPDATE -->` 사이를 [solvedac-cards](https://github.com/seheon99/solvedac-cards) 카드(프로필, 레이팅 요약, 레이팅 변화, 스트릭, 태그, 난이도 분포)로 채웁니다. solved.ac API 키는 필요 없습니다.

### 예시

https://github.com/seheon99/baekjoon/blob/ed8cc93065b4abee6b9ff894a332400e04c3c176/.github/workflows/update-readme-md.yaml
