# sonlar =list( range(11,101,2))
# kubi = []
# for i in sonlar:
#   i=i**3
#   kubi.append(i)
# print(kubi)
# kinolar = []
# print("5 ta sevimli kinoingiz qaysilar?")
# for k in range(5):
#     kinolar.append(input(f"{k+1}-kino:"))
# print(kinolar)   
# odamlar = []
# soni = int(input("Bugun nechta odam bilan uchrashdingiz?"))
# for n in range(soni):
#   uchrashgan = input(f"{n+1}-uchrashgan odamingiz kim edi:")
#   odamlar.append(uchrashgan)
# print(odamlar)
# cars = ['toyota', 'mazda', 'hyundai', 'gm', 'kia']
# for car in cars:
#   if car =='gm':
#     print(car.upper())
#   else:
#     print(car.title())
# log_ism = str(input('Ismingizni kiritin:  '))
# if log_ism.lower() =='admin':
#   print(f'Xush kelibsiz, Admin. Foydalanuvchilar royxatini korasizmi?')
# else:
#   print ('Hush kulibsz')
# a= int (input('a ni kiritin '))
# b = int (input('b ni kiritin'))
# if a==b :
#   print('sonlar teng')
# else:
#   print('teng emas')
# a= float(input("son kiritin"))
# if a<0:
#   print("manfiy son")
# else:
#   print(f"musbat son {a**(1/2)}")
# a =float(input('Juft son kirirtin'))
# if a%2:
#   print("bu juft son emas")
# else:
#   print("rahmat")
# yosh =int(input())
# if yosh<4 or yosh>60 :
#   print("bepul")
# elif yosh<18 :
#   print("100 somon")
# else:
#   print("200 somon")
# mahsulotlar = ["anor", "olma","banan","tarvuz","mandarin"]
# yuq_mahsulotlar = ["un","shaftolu","qovun","choy"]
# a=[]
# for n in range(5):
#   a.append(input(f"savatga {n+1} mahsulot kiritin"))
# for mahsulot in a:
#   if mahsulot in mahsulotlar:
#     # print(f"bu mahsulot dukonda bor {mahsulot}")
#   elif mahsulot in yuq_mahsulotlar:
#     print(f"bu mahsulot dukondda yuq {mahsulot}")
# foydanuvchilar =["anvar","bonu","yanvar","saddam","gufron"]
# yangi =[]
# yangi.append(input("login ni kiritin: "))
# for foydalanuvchi in yangi:
#   if foydalanuvchi in foydanuvchilar:
#     print(f"bu login {foydalanuvchi} band")
#   else:
#     print(f"xush kelibsz {foydalanuvchi}")
son =int(input("istalgan son kiritin"))
for n in range(2, 11):
  if not (son%n):
    print (f"{son} bu raqamga {n} bulinadi ")
