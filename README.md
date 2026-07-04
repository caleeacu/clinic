# CALee Acupuncture — Clinic Site (caleeacu.com)

GitHub Pages 배포용 정적 사이트. 리서치 사이트(caleeacu.github.io)와 동일한 구조.

## 배포 방법
1. GitHub에 새 저장소 생성 (예: `caleeacu/clinic`)
2. 이 폴더 전체를 push
3. Settings → Pages → Branch: main, / (root) 선택
4. Settings → Pages → Custom domain: `caleeacu.com` 입력 (CNAME 파일 이미 포함됨)
5. GoDaddy DNS 설정:
   - A 레코드 4개: 185.199.108.153 / 109.153 / 110.153 / 111.153
   - www CNAME → caleeacu.github.io (또는 저장소 페이지 주소)

## 배포 전 확인
- [x] 전화번호: (562) 907-8640 Text/WhatsApp 반영됨
- [x] 이메일: caleeacu@gmail.com 반영됨
- [x] Square 예약 링크 연결됨
- [x] 로고 투명 배경 처리됨

## 구조
```
index.html       홈 (히어로 / 철학 / 치료분야 / 보험 / 리서치 링크)
about.html       철학 3원칙 + 이훈 원장 소개
services.html    3대 서비스 + 첫 방문 안내
contact.html     위치·시간·폼·구글맵
assets/
  clinic.css     공용 스타일 (Forest Sage + Bronze)
  clinic.js      공용 네비/푸터 주입
  images/        로고 및 클리닉 이미지
CNAME            caleeacu.com
```
