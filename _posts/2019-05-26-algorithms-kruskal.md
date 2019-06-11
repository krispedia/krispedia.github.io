---
layout: post
title: "[Algorithms] Kruskal 알고리즘 "
comments: true
description: "kruskal"
tag : [Algorithms]
---

### Kruskal 알고리즘에 대해 알아봅시다. 

#### Kruskal 동작 기본개념<br>
   1.에지들을 오름차순으로 정렬한다.<br>
   2.아직 확인 하지 않은 에지들 중에서 가장 낮은 weight값을 가진 에지를 확인한다. <br>
   3.확인하는 에지가 사이클을 만들지 않으면 MST(최소 비용 신장 트리)에 추가한다.<br>
   4.n-1개의 에지가 선택되면 종료한다.<br>

##### MST-KRUSKAL

##### MAKE-SET(v)
각 노드를 하나의 집합으로 생성하는 함수

##### FIND-SET(v)
해당 v가 어느 집합에 들어 있는지 확인하는 함수

##### UNION(u,v)
두 노드를 하나의 집합으로 합치는 함수 