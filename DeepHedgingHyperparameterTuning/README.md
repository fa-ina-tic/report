# Deep Hedging

[데이터 출처](https://www.data.go.kr/data/15094808/openapi.do)

시장에 참여하는 투자자들은 옵션의 가격을 효율적으로 계산하는 것과, 포트폴리오의 위험성을 최소한으로 하는 방법에 대한 궁금증에 필연적으로 직면하게 된다. 옵션의 가격을 효율적으로 계 산해야 투자의 성공률을 높일 수 있고, 포트폴리오의 위험성을 효과적으로 제거해야 악영향에 의 해 손해를 보는 상황에서 손해를 최소화할 수 있기 때문이다.

포트폴리오의 위험성을 제거하는 전략으로 폭넓게 쓰이는 것이 Hedging이다. Hedging은 여러 방법으로 포트폴리오에서 위험성을 제거하는 전략이다. Option을 통해 Hedging하는 방식을. Option을 이용한 Hedging은 통계적, 수학적인 공식을 활용하는 전통적인 방식인 Greek Hedging, Delta Hedging이 존재하였으나, 컴퓨터 공학의 발전으로 새로운 Hedging 전략이 등 장하게 되었다. 3세대 Hedging으로도 불리는 Deep Hedging은 AI가 데이터를 기반으로 파생 상 품의 위험성과 가격 책정을 하는 Hedging이다.

3세대 Hedging과 기존 Hedging의 가장 큰 차이점은 3세대 Hedging은 입력 변수들의 관계를 통 해 Option값을 책정하는 중간 계산 과정에만 사용되는 것이 아니라, 입력 변수들의 관계를 가중 치를 통해 조정하고, 이를 통해 가장 최적의 Hedging 결과를 내는 방법을 알아낸다. 즉 어떤 Option Pricing 공식을 주입하여 이용하는 것이 아니라, Option Pricing을 하는 최적의 공식 자체를 만들어내고, 이를 활용하는 것이 3세대 Hedging이라는 것이다.

이 프로젝트에서는 2세대, 3세대 Hedging인 Delta Hedging과 Deep Hedging을 KOSPI의 시가총액이 가장 큰 기업 9개를 대상으로 실제로 진행해본다. 진행 결과를 통해 Insight를 얻어보고, Deep Hedging의 성능을 높일 방법에 대해 논의해보겠다.

