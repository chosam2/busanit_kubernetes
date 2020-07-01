# 클러스터 구성 자동화

## IaC(Infrastructure As Code) 란?

### History of IaC

> 기원

용어 정의를 누가 했는지는 명확하지 않지만 `2009, Velocity Conference`에서 나오게 되었으며 Cloud 기반의 환경이 도입되면서 Pace of Change, Automation의 요구 (Change of Pace : 늘 하던 방법을 바꿈)

> Wiki

Infrastructure as code (IaC) is the process of `managing and provisioning computer` data centers through machine-readable `definition files`, rather than physical hardware configuration or interactive `configuration tools`.

The IT infrastructure managed by this comprises both physical equipment such as bare-metal servers as well as `virtual machines` and associated configuration resources. The definitions may be in a version control system. It can use either `scripts or declarative definitions`, rather than manual processes, but the term is more often used to promote declarative approaches. IaC approaches are promoted for cloud computing, which is sometimes marketed as infrastructure as a service (IaaS). IaC supports IaaS, but should not be confused with it.

> 정의

IaC가 의미하는 바를 글자 그대로 해석하자면 "IT 시스템에서 인프라스트럭쳐 상태를(사람이 직접 작업하는 순서를 늘어놓은 것이 아닌) 소프트웨어가 자동으로 실행할 수 있는 코드 형태로 기술한다" 이다.
여기서 말하는 "인프라스트럭쳐"란 좁은 의미의 `IT 인프라(서버와 네트워크 게층)`보다는 넓으며, `미들웨어 계층과 애플리케이션의 배포, 외부 서비스와 모니터링과 연결`되는 범위도 대상이 된다. IaC가 의미하는 인프라는 "시스템을 가동하기 위해 전제가 되는 주변 환경 모두"를 가리킨다.

더욱 엄밀하게는 서버와 네트워크 계층을 다루는 것을 IaC, 미들웨어와 애플리케이션 배포 등의 상위 계층을 다루는 것을 Configuration as Code로 나누는 경우도 있지만, 이것은 넓은 의미로는 Infrastructure as Code의 한 요소로 간주한다. **특히, 앤서블을 이용하는 경우에는 이런 계층들을 교차하는 작업도 원활하게 할 수 있으므로 계층을 구별해서 사용할 필요성이 줄어든다.**

> 구글 트렌드

Ansible, Terraform 사용률이 꾸준히 증가하는 추세

![Google trend](./img/google_trend.png)

## 실습 환경을 위해 사용될 도구 소개

![IaC](./img/iac.png)

## Vagrant

## Ansible