---
layout: post
title:  "BOJ 2738"
date:   2025-11-11 15:55:29 +0900
categories: jekyll update
---
This section is BOJ programming review
BOJ python 2738 

Q : 2-demensional matrix sum
A : 

N, M = map(int, input().split())

arr1 = [list(map(int, input().split())) for _ in range(N)]

arr2 = [list(map(int, input().split())) for _ in range(N)]

arr3 = [[0 for _ in range(M)] for _ in range(N)]

for i in range(N):
	for j in range(M):
		arr3[i][j] = arr1[i][j] + arr2[i][j]

for i in arr3:
	print(*i)


Check out the problem : [BOJ 2738]

[BOJ 2738]: https://www.acmicpc.net/problem/2738
