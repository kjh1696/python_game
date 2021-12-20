import random #랜덤한 숫자를 만들기 위해서 random을 import한다.
import os

chance = 10
number = random.randint(1,99)

# os.system("cls") linux에서는 "cls"명령어가 작동하지 않는다.

print("1부터 99까지의 숫자를 10번 안에 맞춰 보세요")

def input_check(msg, casting = int):
	while True:
		try:
			user_input = casting(input("몇 일까요?))
			return user_input
		except:
			continue
		
	

while(1):
	user_input = input_check("몇 일까요?)
	chance -= 1
	
	if(chance == 0):
		print("모든 기회를 다 사용했습니다.")
		print("정답은 {}였습니다.".format(number))
		break
		
	if(number == user_input):
		print("정답")
		break
	else:
		print("틀렸습니다")
		if(user_input > number):
			print("입력한 숫자보다 더 작습니다.")
		else:
			print("입력한 숫자보다 더 큽니다.")
