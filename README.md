# trading

tensorflow 2.12.0


kis_devlp.yaml 파일은 한국투자증권 api (https://apiportal.koreainvestment.com/login)에서 key를 발급받아서 만들어야함.

일봉, 분봉 주가데이터를 받아 강화학습 알고리즘을 학습하고 모의투자 환경에서 해외 주식 트레이딩을 진행하는 것을 목표로 함.

문제점

1.1분정도의 간격을 두고 데이터를 받야야하지만 중간중간 실행이 지연되서 데이터를 연속되게 받아오지 못함

2.학습알고리즘 개선 필요

3.손절,익절 구현 필요


참고문헌

한국투자증권 open-trading-api
https://github.com/koreainvestment/open-trading-api

© Dr. Yves J. Hilpisch | The Python Quants GmbH | November 2020
Artificial Intelligence in Finance
https://github.com/yhilpisch/py4fi2nd

youtube-jocoding
https://github.com/youtube-jocoding/koreainvestment-autotrade

