# `hankook-exchange-rs`

## `Reboot` Notice

(`2022-07-04`) 한국투자증권에서 [Rest, WebSocket API](https://apiportal.koreainvestment.com/intro) 를 새로 출시함에 따라, 해당 레파지토리를 다시 리부팅합니다.
원 레포 계정의 2FA 가 어디로 사라진 것 같은데, 새로 찾는 것 보다는 그냥 Fork 해서 새로 생성하는게 좋을 것 같아, 새로운 계정에 새로운 레파지토리로 생성하여 [Rust](https://www.rust-lang.org/) 언어로 클라이언트를'
작성하여 새로이 개발할 예정입니다. 사이드 프로젝트로 간간히 할 예정이어서, 언제 쯤 개발이 끝날지는 모르겠고, 새로운 언어로 시도해보는 것이다 보니 공부하는 데 시간이 많이 걸릴 것 같습니다.

생각하고 있는 Architecture 은 ZeroMQ 를 사용해서 내부적인 메시징을 구현하고, 향후에 다른 Exchange 가 연결될 가능성이 높은 만큼 [FIX(Financial Information eXchange)](https://en.wikipedia.org/wiki/Financial_Information_eXchange) 프로토콜을 사용하여 내부적으로 시세 데이터 및 주문 데이터를 내부에서는 통일해서 사용할 수 있도록 구현해볼 예정입니다.

## LICENSE

* [`Apache 2.0 License`](https://www.apache.org/licenses/LICENSE-2.0.txt)를 따른다면, 누구든지 Contribution 가능하고, 사용할 수 있습니다.