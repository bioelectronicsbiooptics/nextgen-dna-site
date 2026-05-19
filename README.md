# NextGen DNA Site

`nextgen-dna.com`용 GitHub Pages 정적 사이트입니다.

## 파일

- `index.html`: 사이트 본문
- `CNAME`: GitHub Pages custom domain 파일
- `CNAME_TEMPLATE.txt`: 다른 도메인으로 복제할 때 참고

## 도메인

`CNAME` 안에는 도메인 한 줄만 둡니다: `nextgen-dna.com`.

## 수정할 곳

`index.html`에서 다음 문구를 실제 회사/연구실 정보로 바꾸면 됩니다.

- `NextGen DNA`
- `hello@nextgen-dna.com`
- 서비스 문구
- 주소/기관명

## 로컬 미리 보기

```bash
cd /Users/young/Desktop/site_setup_guide_ng_gene/nextgen-dna-site
python3 -m http.server 8080
```

브라우저에서 `http://localhost:8080`을 열면 됩니다.

## 배포

이미 GitHub repo와 연결되어 있습니다.

```bash
git remote -v
```

수정 후 반영:

```bash
git add .
git commit -m "Update NextGen DNA site"
git push origin main
```
