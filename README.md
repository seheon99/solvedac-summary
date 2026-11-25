# solvedac-summary

# 사용 방법

```yml
- uses: actions/checkout@v5
- uses: seheon99/solvedac-summary@84d86b3137f6b45e52dcb1d60528ef28bbde411f
  with:
    username: YOUR_BAEKJOON_HANDLE_HERE
    client-id: YOUR_SOLVEDAC_CLIENT_ID
    client-secret: ${{ secrets.SOLVEDAC_API_KEY }}
```

### 예시

https://github.com/seheon99/baekjoon/blob/ed8cc93065b4abee6b9ff894a332400e04c3c176/.github/workflows/update-readme-md.yaml
