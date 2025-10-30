# 🧠 Problem Solving (with Baekjoon & BarkingDog)

> 코딩테스트 대비를 위한 알고리즘 문제풀이 정리 저장소입니다.  
> 바킹독 알고리즘 시리즈를 기반으로 **유형별로 학습**하고,  
> **시간 제한**, **회독 기록**, **오답 복습**을 통해 실력을 체계적으로 향상시킵니다.

> 목표는 단순히 BOJ 티어를 올리는 것이 아닙니다.  
> **“반복 학습”을 통해 실전에서 통과 가능한 실력을 기르고, 실제 기업 코딩테스트 합격을 목표로 합니다.**

[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=forwarder1121)](https://solved.ac/forwarder1121/)

---

## 🎯 풀이 목표 시간

| 난이도 | 목표 시간     |
|--------|----------------|
| 실버   | ⏱️ 10분 이내  |
| 골드   | ⏱️ 30분 이내  |

> 모든 문제는 해당 시간 내에 풀이를 완료해야  
> **“오답이 성공적으로 해결되었다”고 판단합니다.**

---

## 🧩 진도표 상태 이모지 가이드

| 상태 구분         | 기호   | 설명                          |
|-------------------|--------|-------------------------------|
| 🔄 진행중         | `🔄`   | 현재 회독 중인 챕터          |
| ✅ 1회독 완료     | `✅`   | 1회독 완료                   |
| ✅✅ 2회독 완료   | `✅✅` | 2회독까지 완료               |
| 🔁 다시 복습 필요 | `🔁`   | 틀린 문제 많아서 재복습 예정 |
| 🚀 완전 숙지      | `🚀`   | 빠르게 풀이 가능, 복습 불필요 |
| ⏳ 미시작          | `⏳`   | 아직 시작하지 않음           |

### 세부 상태 이모지  
> 🥈 실버 난이도 풀이 완료 / 🥇 골드 난이도 풀이 완료 / 💎 플래티넘 난이도 풀이 완료

---

## 📌 바킹독 알고리즘 진도표

| No. | 챕터 | 주제 | 한 줄 정의 | 상태 | 1회독 | 2회독 | 3회독 |
|-----|------|------|-----------|------|-------|-------|-------|
| 01 | [0x05](https://www.acmicpc.net/workbook/view/7309) | 스택 | 지금 처리할 수 없는 것들을 보류하고, 나중에 다시 꺼내는 사고의 기술 | ✅ | 🥈🥇💎 | | |
| 02 | [0x06](https://www.acmicpc.net/workbook/view/7310) | 큐 | 들어온 순서를 그대로 존중해, 먼저 온 것을 먼저 처리 | ✅ |🚀 | | |
| 03 | [0x07](https://www.acmicpc.net/workbook/view/7311) | 덱 | 스택과 큐를 모두 일반화한(슈퍼셋) 자료구조 | ✅  | 🥈🥇💎  | | |
| 04 | [0x09](https://www.acmicpc.net/workbook/view/7313) | BFS | 동시에 퍼져나가는 물결 - connected_components,deqth 제한 bfs, multi-source bfs, frontier bfs / 완료 : 1926,2174,1679,1012,2583,2468,6593,2667,2206,7569,2573,2146,16920,3197,9328 | 🔄 | 🥈 🥇| | |
| 05 | [0x0A](https://www.acmicpc.net/workbook/view/7290) | DFS | 한 갈래를 끝까지 내려가 보는 탐험 | ⏳ | | | |
| 06 | [0x0B](https://www.acmicpc.net/workbook/view/7314) | 재귀 |  | ⏳ | | | |
| 07 | [0x0D](https://www.acmicpc.net/workbook/view/7316) | 시뮬레이션 |  | ⏳ | | | |
| 08 | [0x0C](https://www.acmicpc.net/workbook/view/7315) | 백트래킹 |  | ⏳ | | | |
| 09 | [0x11](https://www.acmicpc.net/workbook/view/7320) | 그리디 | | ⏳ | | | |
| 10 | [0x13](https://www.acmicpc.net/workbook/view/8400) | 이분 탐색 |  | ⏳ | | | |
| 11 | [0x14](https://www.acmicpc.net/workbook/view/8709) | 투 포인터 | | ⏳ | | | |
| 12 | [0x15](https://www.acmicpc.net/workbook/view/9063) | 해시 |  | ⏳ | | | |
| 13 | [0x10](https://www.acmicpc.net/workbook/view/7319) | DP | 기억의 재사용 : 1463,9095,2579,1149,11726 | 🔄 | | | |
| 14 | [0x18](https://www.acmicpc.net/workbook/view/9562) | 그래프 |  | ⏳ | | | |
| 15 | [0x19](https://www.acmicpc.net/workbook/view/9657) | 트리 | | ⏳ | | | |
| 16 | [0x1A](https://www.acmicpc.net/workbook/view/9738) | 위상 정렬 |  | ⏳ | | | |
| 17 | [0x1B](https://www.acmicpc.net/workbook/view/9907) | 최소 신장 트리 |  | ⏳ | | | |
| 18 | [0x1D](https://www.acmicpc.net/workbook/view/10433) | 다익스트라 | BFS가 동심원처럼 “한 층씩” 퍼져나간다면, 다익스트라는 지형의 고저에 따라 “거리 파동이 굴절되며” 퍼져나가는 모습 - Multi-source Dijkstra / 1753, 1504, 1261, 11779, 1238, 1916 | 🔄 | | | |
| 19 | [0x1C](https://www.acmicpc.net/workbook/view/10318) | 플로이드 - 위셜 |  | ⏳ | | | |
| 20 | [0x1E](https://www.acmicpc.net/workbook/view/12205) | KMP | | ⏳ | | | |
| 21 | [0x1F](https://www.acmicpc.net/workbook/view/12649) | 트라이  |  | ⏳ | | | |

---

## 📚 2회독 이후 추천 문제집

> 유형 학습이 어느 정도 정리되면, 실전 감각을 높이기 위해 아래 문제집들을 풀 예정입니다.

- 🔗 [삼성 SW 역량 테스트 기출 문제집](https://www.acmicpc.net/workbook/view/1152)  
  - 삼성 A형 스타일 (구현, 시뮬레이션, BFS 등)

- 🔗 [IT기업/대기업 기출 유사 문제집 (지속 업데이트)](https://www.acmicpc.net/workbook/view/8708)  
  - 카카오, 라인, SK, 현대오토에버 등 실전 스타일 문제

> 이 문제집들은 **시간 제한**을 더욱 엄격히 적용해 실전처럼 풀이할 예정입니다.

---

## 🧑‍💻 Author

> **forwarder1121**


---

### 참고
### 🧠 코테 사고법 (Thinking Patterns) 8종 정리

---

### 1️⃣ 거꾸로 생각하기 (Reverse Thinking)
> 출발점·도착점을 반대로 보면 계산이 단순해진다.  
**예시:** [BOJ 17835 면접보는 승범이네](https://www.acmicpc.net/problem/17835), [BOJ 11779 최소비용 구하기 2](https://www.acmicpc.net/problem/11779)

---

### 2️⃣ 대칭성 활용 (Symmetry)
> 절반만 계산하고 반대편은 그대로 적용한다.  
**예시:** [BOJ 1213 팰린드롬 만들기](https://www.acmicpc.net/problem/1213), [BOJ 10942 팰린드롬?](https://www.acmicpc.net/problem/10942)

---

### 3️⃣ 상태 고정 (Fix a Variable)
> 한 변수를 고정시키고 나머지를 탐색한다.  
**예시:** [BOJ 1806 부분합](https://www.acmicpc.net/problem/1806), [BOJ 2470 두 용액](https://www.acmicpc.net/problem/2470)

---

### 4️⃣ 경계값 사고 (Boundary / Parametric Thinking)
> 정답이 아니라 조건을 만족하는 **최소/최대 경계값**을 찾는다.  
**예시:** [BOJ 1654 랜선 자르기](https://www.acmicpc.net/problem/1654), [BOJ 2805 나무 자르기](https://www.acmicpc.net/problem/2805), [BOJ 1300 K번째 수](https://www.acmicpc.net/problem/1300)

---

### 5️⃣ 전환 (Transformation)
> 문제의 구조를 다른 형태로 바꿔 단순화한다.  
**예시:** [BOJ 1916 최소비용 구하기](https://www.acmicpc.net/problem/1916), [BOJ 1932 정수 삼각형](https://www.acmicpc.net/problem/1932), [BOJ 2268 구간합 세그트리](https://www.acmicpc.net/problem/2268)

---

### 6️⃣ 누적/차이 사고 (Prefix–Diff)
> 이미 계산한 값을 재활용해 중복 계산을 피한다.  
**예시:** [BOJ 11659 구간합](https://www.acmicpc.net/problem/11659), [BOJ 10986 나머지 합](https://www.acmicpc.net/problem/10986), [BOJ 2042 구간합 구하기](https://www.acmicpc.net/problem/2042)

---

### 7️⃣ 그래프적 사고 (Graph Modeling)
> 관계를 **그래프 구조로 모델링**하면 풀이가 명확해진다.  
**예시:** [BOJ 1516 게임 개발](https://www.acmicpc.net/problem/1516), [BOJ 2252 줄 세우기](https://www.acmicpc.net/problem/2252), [BOJ 2667 단지번호붙이기](https://www.acmicpc.net/problem/2667)

---

### 8️⃣ 역전 / 역추적 (Reverse Simulation)
> 결과 상태에서 거꾸로 과정을 복원한다.  
**예시:** [BOJ 11779 최소비용 구하기 2](https://www.acmicpc.net/problem/11779), [BOJ 13913 숨바꼭질 4](https://www.acmicpc.net/problem/13913), [BOJ 12852 1로 만들기 2](https://www.acmicpc.net/problem/12852)

---

📌 **요약 키워드**
거꾸로 · 대칭성 · 상태고정 · 경계값 · 전환 · 누적차이 · 그래프화 · 역추적
