# synology-dsm-ip-block

개인 Synology NAS에 인가받지 않은 접근을 시도한 IP 목록입니다.
주기적으로 추가하거나 업데이트합니다.

* 적용 방법
  * 시놀로지 DSM 로그인 → 제어판 → 보안 → 보호 → 허용/차단 목록으로 이동합니다.
  * 차단 목록 탭에서 생성 버튼 옆의 ▼을 클릭 후 IP 주소 목록 가져오기를 클릭합니다.
  * 파일 → 찾아보기에서 다운로드 받은 nas_ip_block_YYYYMMDD.txt 파일을 선택합니다.
    * "차단 목록과 허용 목록에 있는 기존 IP 주소를 덮어씁니다."를 체크할 경우 기존 등록된 IP 내역과 동일한 IP가 있으면 덮어씁니다.
  * 차단된 IP 주소 목록의 내용을 보고 확인 버튼을 누릅니다.
  * 완료.
---
A list of IPs that attempted unauthorized access to my personal Synology NAS.
Added or updated periodically.

* How to apply
   * Go to Synology DSM Login → Control Panel → Security → Protection → Allow/Block List.
   * On the Block List tab, click ▼ next to the Create button and then click Get IP Address List.
   * From File → Browse, select the downloaded nas_ip_block_YYYYMMDD.txt file.
     * If you check "Overwrite the existing IP addresses in the block list and allow list", if there is an IP address identical to the existing registered IP address, it will be overwritten.
   * View the list of blocked IP addresses and click the OK button.
   * complete.