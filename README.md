# Machine-Learning1901266

 Machine1
 //////////////////////////////////////////
a=3
b=10.3
c=a+b
print(c)
13.3

 Machine2
 ////////////////////////////////////
 인자가없는함수 
 //////////////////////////////////////
  def greet():
    print( 'hello world')
    
    def add(a,b):
  c=a+b
  return c
  
  def multplay(a,b):
  c=a*b
  return c
  
   def greet2(name):
    print('반갑습니다', name)
    print(name,'님은 파이썬의 세계로 오셨습니다')
  inputname= '박양후'
greet2(inputname)
반갑습니다 박양후
박양후 님은 파이썬의 세계로 오셨습니다
//////////////////////////////////////
main 함수
//////////////////////////////
def adder(num1,num2):
  sum=sum1+num2
  return sum
  def main():
    pirnt(adder(5,3))
    main()
  print('덧셈 결과: ', num1 + num2)
  adder (10,5)
  sum
/////////////////////////////////////
Eval 함수의활용
//////////////////////////////////////
result=eval(input("뭐든 넣어요:"))
result
뭐든 넣어요:51848496+8484
51856980


def ret():
    
    return 12
result=eval(input("뭐든 넣어요:"))
print(result)
뭐든 넣어요:12
12
/////////////////////////////////////////////////
 Machine3
////////////////////////////////////////////////


sum=0
for i in range(1,11):
  sum=sum+i



import random
  number_of_trals=5000000
  number0fhits=0


  for i in range(number_of_trials):
    x=random,random()*2 - 1
    y=random,random()*2 - 1

if x * x + y * y <= 1:
  number_of_trials+=1
  pi= 4* number0fhits/number_of_trials
  print("PI는",pi,"입니다")
///////////////////////////////





