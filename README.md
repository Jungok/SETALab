# SETALab
# AuLoRa

오로라 사용을 위해서는 온라인 라이센스 구매가 필요합니다. 

  2018년 오로라 온라인 라이센스 사용료
	
  1개월 : 30만원  1년 : 300만원
	
  Contact :  www.setalab.com help@setalab.com
  
AuLoRa 1.1 버전 업데이트 
1. 인증 서버 변경
2. 로그 레벨 변경 API 추가 :
    SrvSetLogMode(loglevel); // 0 : all, 1: correct data ony, 2 : correc data + MIC error
3. Down FCnt 설정 API 추가:
   SrvSetParam("DOWNFCOUNT",		"005A"); // 0x005A
4. Log file save 기능 추가
5. Mac Command Hexa 처리 오류 수정
