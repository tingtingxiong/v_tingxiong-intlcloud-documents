Tencent Cloud CLB(Cloud Load Balancer)의 사용을 환영합니다. CLB는 VIP를 설정하여 클라이언트의 요청을 지정한 방식에 따라 지역 내 연결된 멀티 백 엔드 CVM에 배치합니다.

CLB는 그와 바인딩한 멀티 CVM을 한 개의 사용 가용한 클라우드 서비스 풀로 구성합니다. 그러면 CLB 서비스는 클라우드 서비스 풀에서 CVM의 상태 검사를 진행하게 되고, 이상 상태인 CVM을 자동으로 격리시켜 단일 CVM의 SSO 문제를 해결하는 동시에 응용프로그램의 전체 서비스 능력을 향상시킵니다. 더불어 서비스가 DDOS 공격을 받으면, CLB는 300 Gb 이상의 피크값 트래픽을 방어할 수 있습니다.

Tencent Cloud CLB는 여러 기기를 동시에 지원하는 솔루션으로 CVM과 함께 사용해야 합니다.

