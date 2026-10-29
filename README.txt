Toilet Go Busan — YULIM Infotech

파일
- index.html: 다국어 모바일 웹앱
- yulim_logo.png: 사용자가 제공한 YULIM Infotech 공식 로고

GitHub Pages 배포
1. 저장소를 열고 Add file > Upload files를 선택합니다.
2. index.html과 yulim_logo.png 두 파일을 함께 업로드합니다. 저장소 루트(root)에 둡니다.
3. Commit changes를 누릅니다.
4. Settings > Pages에서 배포 설정이 완료되어 있는지 확인합니다.

현재 기능
- 한국어, 영어, 중국어 간체/번체, 일본어
- 브라우저 위치 권한 기반 주변 화장실 검색
- 검색 반경 1/3/5/10km
- 공개된 OpenStreetMap 데이터를 통한 화장실 목록 조회
- 접근성/기저귀 교환대/무료 정보 필터 (태그가 등록된 시설만 표시)
- Google Maps 길찾기와 OpenStreetMap 상세 링크

주의
- 위치 검색은 HTTPS에서 동작해야 합니다.
- 검색 시 브라우저가 사용자의 좌표를 OpenStreetMap Overpass API에 전송합니다. 앱 자체에는 위치 기록을 저장하지 않습니다.
- 외부 데이터 제공자에 따라 검색이 느리거나 일시적으로 실패할 수 있습니다.
- 지도 데이터가 실제 운영 상태, 이용 가능 시간, 편의시설을 완벽하게 반영하지 않을 수 있습니다.
- 공개 전에는 실제 기기에서 테스트하고 개인정보 안내 및 데이터 사용 조건을 검토하세요.
