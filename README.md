# 🐾 Monitor Pet

바탕화면 위에서 살아 움직이는 데스크탑 캐릭터 펫 프로그램입니다.

## 🛠️ 사용 기술
- C# / WPF
- Win32 API (SetWindowsHookEx, GetCursorPos)

## ✨ 기능
- 바탕화면 위 투명 창에 캐릭터가 자유롭게 돌아다님
- 키보드 입력 감지 → 타이핑 중 작업 애니메이션 재생
- 마우스가 가까이 오면 경계 애니메이션 → 5초 후 뛰어넘기
- 카카오톡 알림 감지 → 반응 애니메이션 재생
- 물 마시기 버튼으로 수분 보충 가능
- idle, run, jump, work, guard, drinkwater 등 다양한 상태

## 📥 실행 방법
1. 아래 Releases에서 zip 파일 다운로드
2. 압축 풀기
3. `MyDesktopPet.exe` 실행
4. SmartScreen 경고 뜨면 "추가 정보" → "실행" 클릭
