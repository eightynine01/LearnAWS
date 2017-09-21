AWS 네트워킹 및 컴퓨팅 서비스 - VPC, EC2
===
Amazon VPC (Virtual Private Cloud)
---
VPC는 Virtual Private Cloud의 약자로 아마존 클라우드 내에서 private ip를 사용하는 일종의 가상 private network 망을 만들어줄 수 있게 해주는 서비스이다.
Amazon VPC 는 AWS 클라우드 내의 분리된 공간으로, 안전한 사설형 클라우드라고 할 수 있습니다. 사용자는 이
공간 내에서 가상 네트워크 구성을 정의해 AWS 서비스를 사용할 수 있습니다. VPC 를 생성하면 사용자는 VPC 의
인스턴스가 사용할 사설 IP 주소를 직접 제공할 수 있습니다. 이 주소를 CIDR(Classless Inter-Domain Routing) 블록
형태로 지정합니다(예: 10.0.0.0/16). 또한, /28 (16 IP 주소)과 /16 (65,536 IP 주소) 사이에서 네트워크의 블록 크기를
지정할 수도 있습니다..

https://d0.awsstatic.com/International/ko_KR/whitepapers/Extend%20your%20IT%20infrastructure%20with%20Amaon%20VPC.pdf


EC2
---
Amazon Elastic Compute Cloud(Amazon EC2)는 Amazon Web Services(AWS) 클라우드에서 확장식 컴퓨팅을 제공합니다. Amazon EC2를 사용하면 하드웨어에 선투자할 필요가 없어 더 빠르게 애플리케이션을 개발하고 배포할 수 있습니다. Amazon EC2를 통해 원하는 만큼 가상 서버를 구축하고 보안 및 네트워크 구성과 스토리지 관리가 가능합니다. Amazon EC2는 요건이나 갑작스러운 인기 증대 등 변동사항에 따라 확장하거나 축소할 수 있어 트래픽 예측 필요성이 줄어듭니다.
EC2 가상 컴퓨팅 서비스 
Server라는 용어 대신 Instance라고 표현하며 자유롭게 크기 조절이 가능하고 리소스에 대한 제어가 완벽하다, 기존에 새로운 서버를 구축하는데 몇일의 시간이 걸렸다면
인스턴스를 확보하고 사용하는데까지 걸리는 시간을 몇 분으로 단축시켰다. 99.99%의 가용성을 확보하였으며 장애가 날 경우 EBS 스냅샷을 이용하여 복구가 가능하다.

http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/concepts.html
