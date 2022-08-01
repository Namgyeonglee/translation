# High-level Overview
## What is the Cosmos SDK
[Cosmos SDK](https://github.com/cosmos/cosmos-sdk)는 Cosmos Hub와 같은 다중 자산 공개 지분 증명(Proof-of-Stake,PoS) 블록체인 및 허가된 권한 증명(Proof-of-Authority,PoA) 블록체인을 구축하기 위한 오픈 소스 프레임워크입니다. Cosmos SDK로 만들어진 블록체인은 일반적으로 애플리케이션별 블록체인으로 지칭됩니다.

Cosmos SDK의 목표는 개발자가 처음부터 쉽게, 다른 블록체인과 네이티브하게 상호 운용할 수 있는 맞춤형 블록체인을 만들 수 있도록 하는 것입니다. 저희는 Cosmos SDK가 [Tendermint](https://github.com/tendermint/tendermint) 위에 안전한 블록체인 애플리케이션을 구축하기 위한 npm과 같은 프레임워크라 생각합니다. SDK 기반 블록체인은 대부분 오픈 소스이며 모든 개발자가 쉽게 사용할 수 있는 구성 가능한 [모듈](https://docs.cosmos.network/v0.46/building-modules/intro.html)로 구축됩니다. 누구나 Cosmos SDK용 모듈을 만들 수 있으며, 이미 구축된 모듈을 블록체인 애플리케이션으로 가져오는 것만큼이나 간편하게 통합할 수 있습니다. 또한 Cosmos SDK는 개발자가 모듈 간의 상호 작용의 보안에 대해 더 나은 이유를 제시할 수 있는 기능 기반 시스템입니다. 기능에 대해 자세히 알아보려면 [Object-Capability Model](https://docs.cosmos.network/v0.46/core/ocap.html)를 확인해보세요.

## What are Application-Specific Blockchains

오늘날 블록체인 세계의 한 가지 개발 패러다임은 이더리움과 같은 가상 머신 블록체인의 개발 패러다임으로, 개발은 일반적으로 스마트 계약의 집합으로 기존 블록체인 위에 분산형 애플리케이션을 구축하는 것을 중심으로 이루어집니다. 스마트 계약은 단일 사용 애플리케이션(예: ICO)과 같은 일부 사용 사례에 매우 좋을 수 있지만 복잡한 분산형 플랫폼을 구축하기에는 부족한 경우가 많습니다. 보다 일반적으로 스마트 계약은 유연성, 주권 및 성능 측면에서 제한적일 수 있습니다.

애플리케이션별 블록체인은 가상 머신 블록체인과 근본적으로 다른 개발 패러다임을 제공합니다. 애플리케이션별 블록체인은 단일 애플리케이션을 작동하도록 맞춤화된 블록체인으로, 개발자는 애플리케이션이 최적으로 실행되기 위해 필요한 설계 결정을 자유롭게 내릴 수 있습니다. 그들은 또한 더 나은 주권, 보안 및 성능을 제공할 수 있습니다.

[애플리케이션별 블록체인](https://www.notion.so/Cosmos-SDK-namgyeongl-701aa8fd134f43cb826bd3f859f53e9a)에 대해 자세히 알아보세요.

## Why the Cosmos SDK

Cosmos SDK는 오늘날 맞춤형 애플리케이션별 블록체인을 구축하기 위한 가장 진보된 프레임워크입니다. 다음은 Cosmos SDK로 분산 애플리케이션을 구축하는 것을 고려해야 하는 몇 가지 이유입니다.

- Cosmos SDK에서 사용할 수 있는 기본 합의 엔진은 [Tendermint Core](https://github.com/tendermint/tendermint) 입니다. Tendermint는 현존하는 가장 성숙한 BFT 합의 엔진입니다. 업계 전반에 걸쳐 널리 사용 되고 있으며, 지분 증명(Proof-of-Stake) 시스템 구축을 위한 골드 표준 합의 엔진으로 간주됩니다.
- Cosmos SDK는 오픈 소스이며 구성 가능한 모듈로 블록체인을 쉽게 구축할 수 있도록 설계되었습니다. 오픈 소스 Cosmos SDK 모듈 생태계가 커지면서 이를 활용한 복잡한 분산형 플랫폼 구축이 점점 쉬워질 전망입니다.
- Cosmos SDK는 기능 기반 보안에서 영감을 받았으며, 수년간 블록체인 상태 머신과 씨름하면서 정보를 얻었습니다. 이로 인해 Cosmos SDK는 블록체인을 구축하기에 매우 안전한 환경이 되었습니다.
- 가장 중요한 것은 Cosmos SDK가 이미 많은 애플리케이션별 블록체인을 구축하는 데 사용되고 있다는 점입니다. 그 중에서도 [Cosmos Hub](https://hub.cosmos.network/), [IRIS Hub](https://irisnet.org/), [Binance Chain](https://docs.binance.org/), [Terra](https://terra.money/) 또는 [Kava](https://www.kava.io/)가 있습니다. 이외에도 [더 많은 것](https://www.notion.so/Cosmos-SDK-namgyeongl-701aa8fd134f43cb826bd3f859f53e9a)들이 Cosmos SDK를 기반으로 만들어지고 있습니다.

## Getting started with the Cosmos SDK

- [architecture of a Cosmos SDK application](https://docs.cosmos.network/v0.46/intro/sdk-app-architecture.html) 에 대해 더 알아보기
- [Cosmos SDK Tutorial](https://www.notion.so/Cosmos-SDK-namgyeongl-701aa8fd134f43cb826bd3f859f53e9a)을 사용하여 애플리케이션별 블록체인을 처음부터 구축하는 방법 알아보기
