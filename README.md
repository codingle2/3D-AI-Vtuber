# 3D-AI-Vtuber
| 항목    | 설명                                                       |
| ----- | -------------------------------------------------------- |
| 모델    | **Gemini 2.0 Flash (text)** + **Gemini 2.5 TTS (audio)** |
| 캐릭터   | `강가온` - 강원대학교 가상 홍보대사 (정해진 페르소나 기반)                      |
| 입력    | 사용자 질문                                                   |
| 출력    | JSON 형식 응답 (reason, content, expression, gesture)        |
| 음성 출력 | Gemini TTS API → PCM 오디오 → PyAudio로 실시간 재생               |
| 로깅    | `chat_log.txt` + `chat_log.json`에 텍스트 로그 및 구조화 저장        |
| 보완    | JSON 파싱 실패 시 오류 출력 및 생 raw 응답 확인 가능                      |

25.07.22 update
