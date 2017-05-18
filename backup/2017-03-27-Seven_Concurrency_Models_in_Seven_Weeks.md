---
layout: post
title: 7가지 동시성 모델
author: 폴 부처 (지은이), 임백준 (옮긴이)
tags: book
---

## 1
부산에서 개발을 하면서 거대한 프로그램을 다루는 일이 없어서 뜸했지만, 로그 데이터 수집 및 분석을 하게 되면서 동시성 모델에 고민이 많았다. RabbitMQ를 사용해서 손쉽게 해결하긴 했지만, 동시성 모델에 대한 약간의 목마름이 있었다.

알라딘에서 책을 고르는 중에 이런 책이 있다는 것을 알고 곧바로 구매해서 읽기 시작했고 많은 도움을 받았다. 당장 코드를 써먹을 순 없었지만 기본 개념과 나에게 필요한 다양한 자료를 소개하고 있어기 때문에 긴 시간을 두고 읽었다.

----

> [...] 어느 순간 스레드와 잠금장치를 이용한 코드의 정확성을 확신할 수 없게 되면서 새로운 방법론에 대한 열망을 품게 되었다. 그 무렵에 잠금장치가 없는 자료구조, 소프트웨어 트랜잭션 메모리, 그리고 액터 모델이 주목을 받기 시작했다.
