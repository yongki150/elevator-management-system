<div align="center">

# Elevator management system

</div>

- [Elevator management system](#elevator-management-system)
  - [소개](#소개)
  - [진행사항](#진행사항)
  - [화면](#화면)
  - [사용법](#사용법)

## 소개

다수의 엘리베이터를 기다리는 일상 생활에서, 어떤 엘리베이터가 최적의 비용으로 스케쥴링되어 승객을 운반하는지 궁금하여 구현하게 되었습니다.

예로, 다음과 같은 상황이 있었습니다.

```
필자가 5층인 상황에서 
엘리베이터 A는 3층에 가만히 있고, 
엘리베이터 B는 10층에서 내려오는 상황에서
엘리베이터 A와 필자 간의 거리가 가까움에도, 엘리베이터 B로만 운행이 된 것을 확인했습니다.
```

## [진행사항](https://github.com/yongki150/elevator-management-system/wiki)

링크를 확인해주세요.

## 화면

```bash
##############################################################
'남은 작업: 5' [
  Passenger { currentFloor: 3, targetFloor: 9, direction: 1 },
  Passenger { currentFloor: 3, targetFloor: 9, direction: 1 },
  Passenger { currentFloor: 4, targetFloor: 6, direction: 1 },
  Passenger { currentFloor: 5, targetFloor: 2, direction: -1 },
  Passenger { currentFloor: 7, targetFloor: 4, direction: -1 }
]
##############################################################
[UP  ]:  1층 | 남은 거리: 6 | 남은 작업수: 5 | 남은 승객수: 0
[UP  ]:  2층 | 남은 거리: 5 | 남은 작업수: 5 | 남은 승객수: 0
[IN  ]:  3층 | 남은 거리: 4 | 남은 작업수: 5 | 남은 승객수: 2
[IN  ]:  4층 | 남은 거리: 3 | 남은 작업수: 5 | 남은 승객수: 3
[UP  ]:  5층 | 남은 거리: 2 | 남은 작업수: 5 | 남은 승객수: 3
[OUT ]:  6층 | 남은 거리: 1 | 남은 작업수: 4 | 남은 승객수: 2
[UP  ]:  7층 | 남은 거리: 0 | 남은 작업수: 4 | 남은 승객수: 2
[UP  ]:  8층 | 남은 거리: 5 | 남은 작업수: 4 | 남은 승객수: 2
[OUT ]:  9층 | 남은 거리: 4 | 남은 작업수: 2 | 남은 승객수: 0
[UP  ]: 10층 | 남은 거리: 3 | 남은 작업수: 2 | 남은 승객수: 0
[UP  ]: 11층 | 남은 거리: 2 | 남은 작업수: 2 | 남은 승객수: 0
[UP  ]: 12층 | 남은 거리: 1 | 남은 작업수: 2 | 남은 승객수: 0
[UP  ]: 13층 | 남은 거리: 0 | 남은 작업수: 2 | 남은 승객수: 0
[DOWN]: 12층 | 남은 거리: 2 | 남은 작업수: 2 | 남은 승객수: 0
[DOWN]: 11층 | 남은 거리: 1 | 남은 작업수: 2 | 남은 승객수: 0
[DOWN]: 10층 | 남은 거리: 0 | 남은 작업수: 2 | 남은 승객수: 0
[DOWN]:  9층 | 남은 거리: 2 | 남은 작업수: 2 | 남은 승객수: 0
[DOWN]:  8층 | 남은 거리: 1 | 남은 작업수: 2 | 남은 승객수: 0
[IN  ]:  7층 | 남은 거리: 0 | 남은 작업수: 2 | 남은 승객수: 1
[DOWN]:  6층 | 남은 거리: 2 | 남은 작업수: 2 | 남은 승객수: 1
[IN  ]:  5층 | 남은 거리: 1 | 남은 작업수: 2 | 남은 승객수: 2
[OUT ]:  4층 | 남은 거리: 0 | 남은 작업수: 1 | 남은 승객수: 1
[DOWN]:  3층 | 남은 거리: 2 | 남은 작업수: 1 | 남은 승객수: 1
[OUT ]:  2층 | 남은 거리: 1 | 남은 작업수: 0 | 남은 승객수: 0
##############################################################
'남은 작업: 0' []
##############################################################
```

## 사용법

Download [Node.js](https://nodejs.org/ko/download/).

```bash
node src/index.js
```