# host : 레디스 서버 호스트
# password : 레디스 서버 로그인 패스워드
# max-actice : pool 에 할당될 수 있는 커넥션 최대수(음수로 사용시 무제한)
# max-idle : pool의 idle 커넥션 최대수(음수로 사용시 무제한)
# max-wait : pool이 바닥났을 때 예외발생 전에 커넥션 할당 차단의 최대 시간 (단위: 밀리세컨드, 음수는 무제한 차단)
# min-idle : pool에서 관리하는 idle 커넥션 최소 수(양수일 때만 유효)
# sentinel.master : 레디스 서버 이름
# sentinel.nodes : 호스트: 포트 쌍 목록(콤마로 구분)
# timeout : 커넥션 타임아웃(단위: 밀리세컨드)