# 009. True or False
지금까지 우리는 지구 멸망의 날을 알아 내는 법을 배웠습니다. 문제는 이게 어떻게 작동되는 지만 알지 왜 이렇게 작동되는 지에 대해서는 모릅니다. 여행을 하려면 고장난 물건 정도는 뚝딱 고쳐야하지 않겠어요? 그래서 "왜" 이렇게 작동되는 지에 대해 배워봅시다.

```python
print(10 > 10) #False
print(10 == 10) #True

print(bool(1)) #True
print(bool(0)) #False
print(bool(100)) #True
```

먼저 첫번째 print문은 10이 10보다 클 리는 없으니 당연히 거짓입니다. python에서는 이를 False라고 하죠! 밑의 print문에서 10은 10과 같으니 참이고, python에서는 이를 True라 합니다.

밑에 print문과 bool()이라는 이상한 함수가 있습니다. 전혀 겁먹을 이유 없어요. bool은 인자로 들어온 것이 참인지 거짓인 지 판별해서 결과를 돌려주는 함수랍니다. python 내에서의 합의는 0은 거짓, 즉 False이고 0이 아닌 것은 모두 True라고 판별하기로 합의했어요. 그래서 0만 False라 출력하고, 이외에는 True라 출력하는 것이에요.