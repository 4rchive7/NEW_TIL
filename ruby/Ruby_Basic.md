# Ruby



## 0.개요

 	0. 루비는 모든 것이 객체이다.
 	1.  모든것이 객체
 	2. Ruby on Rails



## 1. puts vs print

> 3.times {print "hello"} # => hellohellohello

> 3.times {puts"hello"} # = hello\nhello\nhello\n

> puts vs p => p는 inspect까지 다 보임



## 2. puts vs p

> array = [1,2,3]  => [1, 2, 3] 

> puts array

> 1

> 2

> 3

> p array

> [1, 2, 3]



ex2)

```
a= "hello"

 => "hello" 

 p a

"hello"

 => "hello" 



```



## 3. 변수 선언법

다른 것은 다 자바랑 같지만 변수 선언시 여러 단어를 써야하는 경우 _로 구분한다.



## 4.pry

```
[3] pry(main)> class Integer
[3] pry(main)*   def dollar
[3] pry(main)*     self*1100
[3] pry(main)*   end  
[3] pry(main)* end  
=> :dollar
[4] pry(main)> 5.dollar
=> 5500
[5] pry(main)> 
```



## 5.  inline statement

```
# if
puts "a=0" if a == 0   # 0 출력 됨
puts "a=0" if a == 1   # 0 출력 안됨 // if 만족시 앞에 실행

# while
c = 2
result = c +=2 while c < 50
puts result #50

puts "hi" if 0 #hi
#0이 true


#===   => 다 실행되고 종료된다고 하네;;
```



## 6. case

```
case name
	when "taeik" then puts "hi taeik!"                                                   when "tak" then puts "hi tak"                                                         else puts "hi"  
end  
```

