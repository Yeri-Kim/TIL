정리 안된 문서

light sail
쉽게 간단하게 사용하는 vps
디지털오션과 거의 동일.
콘솔 깨끗함. 정보 보기 좋음
ec2복잡.

개인블로그 해보기 좋음.(750시간 무료)

제약
인스턴스 20개
고정아이피 5개
dns영역 3개 관리.

인스턴스 타입변경 불가 (5달러->10달러 업그레이드 불가)
업그레이드 하려면 스냅샷 찍어서 옮겨야함. - 백업 받은거로 새 인스턴스 만들면 똑같은 타입으로 만들어져서 cli 사용해야함(커맨드라인으로) 
하드디스크 추가, 용량변경 불가
정기적인 스냅샷 생성 안 해줌

ssh 접속도 쉬움(키 다운 노필요)

iam 권한 lightsail: *
사용가능한 지역 -> 한국 안 됨.

ec2가 어느 면에서 나을 수도 있겠는데?
(1년 선결제)

ssh key. 키 관리 편함

스냅샷 생성 자동화 할 수도 있는데 cli 이용해서 하면 됨. 스크립트 짜면 됨

궁금할만한것
ssh, http포트가 기본으로 열려있음(https는 추가하면 됨)
lightsail는 개발자가 크게 관심은 없는 듯 함(개발자가 ec2가 다 사용할 줄 아니까)
lightsail 리소스는 aws 콘솔의 c2 인스턴스, elastic ip, 볼륨, 스냅샷에서 안 보임
ebs못붙임

선택 ec2 vs lightsail
ec2 트랙픽 많지 않으면 ec2가 유리할 수 있음 (트래픽 100mb이상이면 라이트세일이 낫다)
ec2 잘 쓸 줄 알면 계속 쓰면 됨
ec2가 복잡해서 디지털오션 같은 vps 사용중이었다면 lighsail
블로그, 개인용도의 서버 lightsail이 낫다.(편하다)
cli 사용할때 외우기 힘든 인스턴스 id가 짜증 나면 lightsail
