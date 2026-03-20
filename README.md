# Python-Pytorch-
2026 3.20( 2학년 python 공부도중) 구의 부피와 겉넓이 구하는 프로그램 만들기(성공)
import math
r = int(input("구의 반지름을 입력해주세요: "))
print("= 구의 부피는 {}입니다." .format(4/3 * math.pi * (r**3)))
print("= 구의 겉넓이는 {}입니다.".format(4 * math.pi * (r**2)))

혁펜하임 Pytorch기초--> torch.tensor()와 텐서의 기본연산
numpy의 np.array() == pytorch의 torch.tensor()
import torch
a = torch.tensor([1,2,3,4])
print(a) --> tensor([1,2,3,4])
print(type(a)) --> <class 'torch.tensor'>
print(a.dtype) --> torch.int64
print(a.shape) --> torch.size([4])












