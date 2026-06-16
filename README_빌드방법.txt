양파깡 자산관리 Android 앱 프로젝트

구성
- Android WebView 앱
- 기존 모바일 PWA 웹앱을 assets/web 안에 포함
- 삼성폰에 직접 설치 가능한 APK 빌드 가능

빌드 방법
1. PC에 Android Studio 설치
2. Android Studio 실행
3. Open 선택
4. 이 폴더(YangpaGgangAsset_Android) 선택
5. Gradle Sync 완료 대기
6. 상단 메뉴 Build > Build Bundle(s) / APK(s) > Build APK(s)
7. 생성 위치:
   app/build/outputs/apk/debug/app-debug.apk

삼성폰 설치 방법
1. app-debug.apk를 휴대폰으로 전송
2. 파일 앱에서 APK 실행
3. '알 수 없는 앱 설치 허용' 승인
4. 설치

현재 포함 기능
- 가족 구성원 필터
- 자산/부채 입력
- 기준일별 스냅샷 저장
- 과거 기준일 비교
- 카테고리 관리
- OCR 검증용 이미지 업로드
- PIN 잠금
- JSON 백업/복구

주의
- 데이터는 앱 내부 WebView localStorage에 저장됩니다.
- 휴대폰 교체/앱 삭제 전 반드시 JSON 백업을 다운로드해야 합니다.
- 실제 자동 OCR, 생체인증, 강한 DB 암호화는 다음 단계 기능입니다.
