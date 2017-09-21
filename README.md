AWS 네트워킹 및 컴퓨팅 서비스 - VPC, EC2
===
Amazon Virtual Private Cloud (VPC)
---
VPC는 Virtual Private Cloud의 약자로 아마존 클라우드 내에서 private ip를 사용하는 일종의 가상 private network 망을 만들어줄 수 있게 해주는 서비스이다.
Amazon VPC 는 AWS 클라우드 내의 분리된 공간으로, 안전한 사설형 클라우드라고 할 수 있습니다. 사용자는 이
공간 내에서 가상 네트워크 구성을 정의해 AWS 서비스를 사용할 수 있습니다. VPC 를 생성하면 사용자는 VPC 의
인스턴스가 사용할 사설 IP 주소를 직접 제공할 수 있습니다. 이 주소를 CIDR(Classless Inter-Domain Routing) 블록
형태로 지정합니다(예: 10.0.0.0/16). 또한, /28 (16 IP 주소)과 /16 (65,536 IP 주소) 사이에서 네트워크의 블록 크기를
지정할 수도 있습니다.

https://d0.awsstatic.com/International/ko_KR/whitepapers/Extend%20your%20IT%20infrastructure%20with%20Amaon%20VPC.pdf


Amazon Elastic Compute Cloud (EC2)
---
Amazon Elastic Compute Cloud(Amazon EC2)는 Amazon Web Services(AWS) 클라우드에서 확장식 컴퓨팅을 제공합니다. Amazon EC2를 사용하면 하드웨어에 선투자할 필요가 없어 더 빠르게 애플리케이션을 개발하고 배포할 수 있습니다. Amazon EC2를 통해 원하는 만큼 가상 서버를 구축하고 보안 및 네트워크 구성과 스토리지 관리가 가능합니다. Amazon EC2는 요건이나 갑작스러운 인기 증대 등 변동사항에 따라 확장하거나 축소할 수 있어 트래픽 예측 필요성이 줄어듭니다.

http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/concepts.html

AWS 스토리지 서비스 - EBS, S3
===

Amazon Elastic Block Store (EBS)
---
Amazon Elastic Block Store(EBS)는 AWS 클라우드의 Amazon EC2 인스턴스에 사용할 영구 블록 스토리지 볼륨을 제공합니다. 각 Amazon EBS 볼륨은 가용 영역 내에 자동으로 복제되어 구성요소 장애로부터 보호하고, 고가용성 및 내구성을 제공합니다.

http://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/EBSVolumes.html

Amazon Simple Storage Service (S3)
---
AWS S3 (Simple Stoage Service)는 파일을 저장하기 위한 스토리지이다. 일반적인 파일시스템의 개념과는 약간 다르고, 파일 이름을 대표하는 key와 파일 자체로 구분되는 Object Storage이다. 용량 저장할 수 있는 파일의 크기는 개당 1byte~5TB이고, 총 저장 용량에는 제한이 없다. 디렉토리와 비슷한 개념으로, bucket이라는 개념을 가지고 있다.


http://docs.aws.amazon.com/ko_kr/AmazonS3/latest/dev/Welcome.html
http://bcho.tistory.com/778
