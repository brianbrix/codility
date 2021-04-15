# you can write to stdout for debugging purposes, e.g.
# print("this is a debug message")

def solution(N, K, A, B, C):
    # write your code in Python 3.6
    if 1<=len(A) == len(B)==len(C)<=200000:
        if 1 <= N <=100000:
            ls1={}
            for m in range(1, N+1):
                ls1[m]=[]
                for x in range(len(C)):
                    if A[x]<=B[x]:
                        for y in range(A[x], B[x]+1):
                            if y == m:
                                ls1[m].append(C[x])
                ls2 = len([x for x in ls1.values() if x == list(range(1, K+1))])
            return ls2
