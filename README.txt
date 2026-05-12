Baccarat Pattern Matcher V7.4.4 - Auto Hit/Miss Log

수정 내용:
- 추천 성과 요약이 자동으로 작동하도록 수정
- 추천 결과가 나온 상태에서 다음 실전 입력을 누르면 자동 판정
  예:
  추천 Banker → 다음 입력 Banker = 적중
  추천 Banker → 다음 입력 Player = 미적중
- 최대 연속 적중 / 최대 연속 미적중 / 전체 적중률 자동 집계
- recLogs를 localStorage와 JSON 내보내기에 저장
- 되돌리기 시 마지막 실전 입력과 마지막 추천성과 로그도 함께 되돌림

주의:
- Tie 추천은 성과 집계에서 제외
- 추천이 없는 관망 상태에서 입력한 결과도 성과 집계에서 제외
