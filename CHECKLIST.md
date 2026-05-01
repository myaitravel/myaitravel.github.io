# 배포 전 체크리스트

## 폴더 구조
```
E:\Projects\
├── 앱이름\          ← 개발/수정용 (로컬만, GitHub 올리기 X)
│   └── index.html   (내가 쓰는 원본 - 개인정보 포함 가능)
│
└── 앱이름-public\   ← 배포용 (GitHub에 올리는 것)
    └── index.html   (개인정보 제거된 버전)
```

## 배포 전 확인 사항
- [ ] 개인 북마크 / 링크 제거
- [ ] API 키 제거
- [ ] 비밀번호 제거
- [ ] 개인 사이트 링크 제거
- [ ] 개인정보가 담긴 데이터 제거
- [ ] LICENSE 파일 추가 (MIT)
- [ ] index.html 맨 위 라이선스 주석 추가

## 라이선스 주석 템플릿
```html
<!--
  앱이름
  Copyright (c) 2026 myaitravel
  MIT License - https://opensource.org/licenses/MIT
-->
```

## LICENSE 파일
- GitHub 레포에 `LICENSE` 파일 업로드
- 내용은 MIT License 템플릿 그대로 사용
- `Copyright (c) 2026 myaitravel` 확인

## 배포 순서
1. 로컬에서 개발/수정
2. 배포용 폴더에 복사
3. 개인정보 제거 확인 (체크리스트)
4. LICENSE 파일 추가
5. GitHub 레포에 업로드
6. GitHub Pages 활성화 확인
