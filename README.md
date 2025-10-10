# classwork
 a=int(input("введите число"))
if a>=0:
     print("число положительное:")
 elif a<0:
     print("число отрицательное:")

     a=int(input("введите свой возраст:"))
 if a<0 or a>120:
     print("возраст не коректен")
 else:
     print("возраст коректен")

     a = int(input("Введите первое число: "))
b = int(input("Введите второе число: "))
 if a > b:
     print("требуется нормализация")
 for i in range(a, b + 1):
     if i % 2 != 0:
         print(i, end=" ")

         
hours=int(input("введите часы:"))
minutes=int(input(("введите минуты")))
 seconds=int(input("введите секунды"))
 if hours<=0 or hours>24 and  minutes<=0 or minutes>60 and seconds<=0 or seconds>60:
     print("число некоректно")
 else:
     print(hours,":",minutes,":",seconds)


a=int(input("введите число"))
b=int(input("введите число"))
 if a>b:
     print(a)
 else:
     print(b)



     a=int(input("введите число"))
 if a %5==0:
     print("число кратно ")
 else:
     print("число не кратно")


     a=(input("введите название планеты:"))
 if a==("земля") or a==("Земля"):
     print("привет землянин")
 else:
     print("привет инопланетянин")
