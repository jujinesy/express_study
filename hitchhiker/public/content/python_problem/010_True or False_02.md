# 010. True or False
자! 그럼 if문에서 참과 거짓이 어떻게 작동되는 지 알 수 있습니다. 아까 지구 멸망 코드를 들고와 보죠.

```python
dooms_day = 19791012

if dooms_day < 19791012 : #False
	print("MORE BEEEERR!")
elif dooms_day > 19791012  : #False
	print("Hitchhiking")
else :
	print("BOOM!") #Truuuuuuueeeeeee
```

여기서 if문 내에서는 dooms_day가 19791012보다 작은 게 아니므로 이 값은 False가 반환이 됩니다. if문은 True일 때 if문 내의 코드를 실행하고, False일 때는 if문 내의 코드를 실행하지 않습니다. 그러므로 맥주를 더이상 마시지 않아도 괜찮죠.

elif문도 if문과 마찬가지 입니다. 여기서는 조건에서 False가 반환이 되어 elif문 내의 코드가 실행되지 않습니다.

else문은 관대한 친구입니다. if문과 elif문에서 작동되지 않은 이들을 모아 참, 거짓을 따지지 않고 실행시켜 줍니다. 여기서는 "BOOM!"이네요. 어찌 되었든 간에 지구 멸망의 날은 피할 수 없게 되었습니다.
