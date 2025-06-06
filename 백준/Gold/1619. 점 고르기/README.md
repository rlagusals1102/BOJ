# [Gold II] 점 고르기 - 1619 

[문제 링크](https://www.acmicpc.net/problem/1619) 

### 성능 요약

메모리: 34128 KB, 시간: 560 ms

### 분류

브루트포스 알고리즘, 기하학

### 문제 설명

<p>2차원 평면 위에 N개의 점들이 찍혀 있다. 우리는 아래의 조건을 만족하도록 몇 개의 점을 고르려고 한다.</p>

<ol>
	<li>적어도 세 점 이상은 골라야 한다.</li>
	<li>고른 점들 중에서 어떤 두 점을 임의로 선택해도, 선택한 두 점을 잇는 직선을 만들었을 때 이 직선을 통과하는 다른 점이 적어도 한 개 이상은 있어야 한다.</li>
	<li>최대한 많은 점을 골라야 한다.</li>
</ol>

<p>모든 점의 좌표가 주어졌을 때, 조건을 만족하도록 점을 골라 주는 프로램을 작성하시오.</p>

### 입력 

 <p>첫째 줄에 점의 개수 N(3 ≤ N ≤ 1,000)이 주어진다. 이어서 둘째 줄부터 N개의 줄에 걸쳐 점의 x좌표와 y좌표를 나타내는 두 정수가 순서대로 주어진다. 주어지는 모든 좌표는 절댓값이 20,000을 넘지 않는 정수이다. 주어지는 모든 점은 서로 다르다.</p>

### 출력 

 <p>첫째 줄에 고른 점들의 최대 개수를 출력한다. 점들을 고르는 것이 불가능한 경우 -1을 출력한다.</p>

