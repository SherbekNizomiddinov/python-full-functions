# python-full-functions

                                               # Built in functionlar

print() #Bu string ko'rinishidagi o'zagruvchilarni chiqarish funksiyasidir

input() #Bu biron bir o'zgaruvchini kiritish funksiyasidir

print(*"Salom") #Bunda biz birgina *chani qo'yishimiz orqali yozuvlarni orasini ochib yozishimiz mumkin

pow() #Bu funksiya sonlari darajasini hisoblab beradi 

print(1,2,3, sep="") # sep="" funksiyasi bu sonlarni orasiga biron bir malumotni kirgizb beradi (Bu faqat sonlarga ishlaydi)

print(1.32,23,43, end="") # end="" funsksiyasi sonlarni ohiriga biron bir malumotni kirgizb beradi

a = int(input("a = ")) #bunda biz input funksiyasini oldiga biz kiritgan qiymat qanaqa turga o'girib berishini ko'rsatadi

# sub_string funksiyasi biz kiritgan matn yoki malumot ichida biz qidirmoqchi bo'lgan funksiya bor yo'qligini tekshirib beradi

text = "salom dunyo,nima gap" #bunda biz biron bir o'zgaruvchi kiritb olamiz 

word1 = text[6:11] #Va nechinchi indexdagi so'zni olmoqchi bo'lsak indexni raqamini :nuqta bu qancha malumot olishini 11 desak 11qatorgacha oladi

print(word1) #va bunda olgan malumotimizni chiqaradi yani "dunyo" so'zini

#                                   Aperatorlar to'plami

#                                     Assigment - Arifmetik aperator

# Qo'shish (+)
# Ayirish (-)
# Ko'paytirish (*)
# Bo'lish (/)
# Qoldiqli bo'lish (%)
# Butun bo'lish (//)
# Darajaga ko'tarish (**)

#                                     Logical aperator

# and (va) 
# or(yoki) 
# not(hechqaysi) va matiqiy aperator bilan bir xil aperator yani ikkovi ham Ture False qiymat qaytaradi 

#                                     Identity aperator

# is (ikkali aperator bir hilmi)
# is not (ikkala aperator bir hil emasmi !?)

#                                     Membership aperator

# in (bormi & yo'qmi) elementlar ichidan bormi yoki yo'qmi degan javob qaytaradi yani ichida bo'lsa True agar bo'lmasa False qaytaradi
# not in (yo'qmi) elementlar orasidan biz qidirgan element yo'qmi deb qidirib ko'ramiz yani biz qidirgan element yo'q bo'lsa True bor bo'lsa False chiqaradi                     


#                                   Primitive - Data type
# integer (Butun), float (Qoldiqli son) bool (True False) string (Mantli) 
# 
#                                   Non - Primitive - Data type
# 
# List (Tartibli va o'zgaruvchan ro'yhat) 
# tuple (Tartiblangan o'zgarmas ro'yhat)
# set (Tartibsiz va takrorlanmas element to'plami)
# dict (kalit-qiymat juftliklari (key-valuedan tashkil topgan)) 

#                                   String metodlari 

# Modificatsion metodi 

# replace() kiritgan matningizni biror bir narsaga o'zgartrmoqchi bo'lsayiz ishlatasiz
# upper() bu metod kiritgan matningizni hammasini katta harfda yozib beradi 
# lower() bu moetdo kiritgan matningizni hammasini kichik harfda qilib beradi 
# capitalize() bu metod matningizni faqat boshidagini katta hatrfda qilib beradi 
# center() bu funksiya biz malumotimizni qayergacha surmoqchi bo'lsek ishlatamiz
# title() har bir o'zgaruvchini bosh harfini katta qilib beradi
# leftjust() bu elementlarni chapga surib beradi
# rightjust() bu elementlarni o'ng tarafga surib beradi

# Check (tekshirish) metodlari

# count() bu biz kiritgan element necha marta qatnashganligini sanaydi
# endwith() bu funksiya biz kiritgan malumotni qanaqa turda ekanligini aniqlab beradi
# startwith() biz kiritgan faylimiz yoki matnimiz rostdan ham shu nom bilan boshlanyaptimi yo'qmi shu bilib beradi


# len() bu elementlarni nechta ekanligini aniqlab beradi 
# endwith() bu funksiya biz kiritgan malumotni qanaqa turda ekanligini aniqlab beradi 
# lower() bu funksiya biz kiritgan malumotni barchasini kichik harfda yozib beradi
# upper() bu funksiya biz kiritgan malumotni barchasini katta harfda yozib beradi                                  
# find() bir qidirmoqchi bo'lgan so'zimiz rostdan ham o'sha matnda bormi yo'qmi shu aniqlab beradi !! agar bo'lsa u nechinchi indexda joylashganligini aniqlab beradi
# isalpha() haqiqatda harf yoki harfmasligini aniqlab beradi
# isdigit() haqiqatda son yoki sonmasligini aniqlab beradi 
# isspace() bo'sh qator bor yo'qligini aniqlab beradi

# Search (qidirish) metodlari 

# index() bu nechinchi indexlagini aniqlab beradi
# count() matnimiz necha marta qatnashganligini aniqlab beradi 
# find() biron bir so'z qidirmoqchi bo'lsak haqiqatda shu matn ichida bormi yo'qmi shuni aniqlab beradi 

#                                   String slicing

# Masalan bir matn kiritsak 
text = "Salom Dunyo" # bunda biz matn kiritb olamiz
# va bunda quyidagicha shart beramiz :
edit_text = text[2::] # agar 2 qilsak bu 3-indexdan : bu nechinchi indexgacha degani agar 5gacha qilsak 2-indexdan 5-indexgacha oladi agar shuni [2::] qilsak bu 3-indexdan ohirgacha matnimizni qirqib oladi

print(edit_text) # va natijada biz (lom Dunyo) so'zini olamiz. Bu stringni slicing qilish edi

#                                   Control Flow

# sonlarni 2lik 8lik 16lik sanoq sistemalarida chiqarish

num1 = 0b0101011010 # bunda biz num o'zgaruvchisiga 2lik sanoq sistemasidagi sonlarni yozamiz 
num2 = 0o1234566712 # bunda biz num o'zgaruvchisiga 8lik sanoq sistemasidagi sonlarni yozamiz
num3 = 0x1234321abc # bunda biz num o'zgaruvchisiga 16lik sanoq sistemasidagi sonlarni yozamiz
# va natija huddi o'shandan chiqishi uchun (#) reshotka belgisini qo'yib keyin harfni qo'yib chiqarishimz kerak aks holda :
print(f"{num1:b}") # shunchaki o'zini chiqarishimiz uchun (b) harfini qo'ysak kifoya
print(f"{num2:o}") # shunchaki o'zini chiqarishimiz uchun (o) harfini qo'ysak kifoya
print(f"{num3:x}") # shunchaki o'zini chiqarishimiz uchun (x) harfini qo'ysak kifoya
# agar printda shu harflarni olib tashlab chiqarsak shunchaki 10likdagi qiymatini chiqarib beradi

num = 348.000 # bunda biz float turidagi son kiritib olamiz

print(f"{num:.2f}") # va natijani chiqarishda shunchaki (.2f) qiladigan bo'lsak nuqtadan keyin faqat 2ta sonni qabul qil degani

#                                   While loop

# Bu bizning while loopimizning ishlatilishimiz
i = 0 # i o'zgaruvchisini 0 dan boshlab olamizda
while i < 10: # 10 gacha chiqargin deymiz va bunda 10 ni qabul qilmaydida 1-dan 9 gacha chiqaradi
    print(i) # va bunda printga i ni bersak pastga qarab chiqaradi 
    i += 1 # i += 1 bu har bittasiga 1 qo'shib keyingi songa o'tadi degani 

#                                   For loop Metodlari 

# capitalize() bu funksiya har qanday so'zni bosh harfini katta qilib yozib beradi 
# lower() bu funksiya biz kiritgan malumotni barchasini kichik harfda yozib beradi 
# upper() bu funksiya biz kiritgan malumotni barchasini katta harfda yozib beradi 
# center() bu funksiya biz malumotimizni qayergacha surmoqchi bo'lsek ishlatamiz
# count() funksiyasi biz kiritgan malumot necha marta kelganini aniqlab beradi 
# endwith() bu funksiya biz kiritgan malumotni qanaqa turda ekanligini aniqlab beradi 
# find() biz qidirmoqchi bo'lgan malumot nechinchi indexda ekanligini tekshirb beradi 
# in qidirayotgan matningiz mavjud yoki yo'qligini aniqlab beradi 
# is teng yoki teng emasligini aniqlab beradi 
# or yoki bunisi yoki bunisi 
# len() bu elementlarni nechta ekanligini aniqlab beradi 
# split() bu so'zimiz nechta sondan iboratligini aniqlab beradi 
# title() har bir o'zgaruvchini bosh harfini katta qilib beradi 
# (i + 1) bunda biz kiritgan raqamimzgacha va o'zini ham oladi masalan 1dan 100gacha son kiritsak 100ni o'zini ham qabul qiladi

#                                   Matematik kutuxona chaqirish
# pi, sin, cos, sqrt
import math # bunda biz math degan kutubxonani chaqirib oldik

print(math.sin(a)) # va natijada a ni sinusini chiqarib oldik
# kutubxona chaqirishda yana bir narsani yozsak bo'ladi masalan :
# from math as matematika qilib as orqali nomini o'zgartrsak bo'ladi

# sin bu misollarni sinus ko'rinishini chiqarib beradi 
# cos bu misollarni kosinus qiymatini chiqarib beradi 
# sqrt bu sonlarni ildizini chiqarib beradi
# time() bu funsiya kampyuterimiz yoki dasturimiz qancha vaqt ishlaganini ko'rsatadi yani qancha sekund 
# now() bu funksiya kamyuterimizdagi hozrgi vaqtni chiqarib beradi
# strftime() bu funksiya soat minutlarni string ko'rinishida chiqarib beradi 

#                                   Data typelar

# getsizeof() bu o'zgaruvchini hotiradan qancha joy olishini aniqlab beradi
# 

#                                   List Methods

# List bu har hil turdagi elementlarni qabul qiluvchi ro'yhatdir

# id() o'zgaruvchilarni hotiradagi manzilini ko'rsatadi 
# items() o'zgaruvchilarni kalit juftliklari key-value qaytaradi
# append() listning ohiriga element qo'shib beradi
# insert #nechinchi indexga element qo'shmoqchi bo'lsek shunga qo'shib qolganlarini o'nga qarab suradi
# extend listdagi har bitta elementni alohida qilib chiqarb beradi
# remove() bu listdagi elementni o'chiradi nomi bo'yicha 
# del bu listdagi elementi indexsi bo'yicha o'chiradi 
# pop() bu ham listdagi elementni indexsi bo'yicha o'chiradi lekin nimani o'chirganni bizga qaytaradi 
# clear() bu indexdagi barcha elementlarni tozalab tashlaydi 
# copy() bu listdagi elementlardan nusxa ko'chiradi va butunlay boshqa qiymat qaytaradi
# count() listdagi element necha marta qatnashganligini aniqlab beradi 
# index() listdagi element nechinchi indexda ekanligini aniqlab beradi
# reverse() bu listdagi elementlarni teskari chiqarb beradi 
# [::-1] bu elementlarni teskari tartbda chiqarb beradi
# sort() bu elementlarni o'sish ketma-ketligida tartblab beradi
# sort(reverse = True) qiladigan bo'lsek elementlarni kamayish tartibida tartblab beradi

#                              List Built-in funcsional

# all() hamma elementlar True bo'lsa ishlaydi 
# any() orasidan bitta rost bo'lib qoladigan bo'lsa ham ishlaydi 
# enumerate() bu listdagi har bitta elementni alohida qiymatga taminlab chiqarb beradi
# list() listga biron bir element taminlasak uni har birini alohida qilib chiqarb beradi 
# min() listni ichidagi eng kichik elementni topib beradi 
# max() listni ichidagi eng katta elementni topib beradi 
# sorted() bu listni ichidagi elementlarni tartblab beradi 
# sum() listdagi elementlarni yig'indisini chiqarib beradi 
# chr(65) bu aski tableda qaysi harfdaligini chiqarb beradi 
# ord('a') bu aski tableda nechinchi raqamda ekanligini chiqarib beradi
# "".join.() bu elementi string ko'rinishiga keltrb beradi 

#                               Tuple Built-in funcsional

# Tupl bu har xil qiymatlarni qabul qiluvchi o'zgarmas ro'yxat 


# count() bu tupldagi elementlar necha marta qatnashganligini bilish uchun
# index() bu tupldagi elementlar nechinchi indexda ekanligini turganligini aniqlab beradi 

#                                   Set and Dict

# set() or s = {} Non-primitive data type va uni ichidagi elementlar random ko'rinishida saqlanib ichiga tuplni ham qabul qiladi 
# add() orqali setga element qo'shamiz
#                                   Set Built-in funcsional

# all() hamma qiymatlari True bo'ladigan bo'lsa ishlaydi
# any() bitta element rost bo'lib qolsa ham ishlaydi
# enumerate() qator pastga qilib sanaydi misol uchun qavs ichiga start=10 qiladigan bo'lsak (10, 0) deb boshlab sanab ketadi
# len() nechta element borlgini aniqlab beradi 
# max() bu eng katta element qaysiligini aniqlab beradi 
# min() bu eng kichik element qaysiligini aniqlab beradi 
# sorted() bergan setimizni tartiblab yangi list qaytaradi 
# sum() elementlar yig'indisini chiqaring 

#                                   Set and Dict Metodlari

# union() bu element ikta listda bo'lsa ham bir biriga qo'shib chiqaradi 
# aperator bo'yicha | mana shundan foydalanadi
# intersection() bu ikkalasida ham qatnashgan elementni chiqaradi 
# aperator bo'yicha & mana shundan foydalanadi 
# difference() bu faqat bittasida bo'lsa ishlaydi 
# aperator bo'yicha - mana shundan foydalaniladi
# symetric_difference() bu ikkalasida ham borlarini qabul qilmaydi 
# aperator orqali ^ mana shunday foydalaniladi 
# update() bu eski qiymatlarni o'chirb biz yaratgan yangi qiymatni chiqarb beradi 
# remove() bu elementni o'chiradi lekin error qaytaradi 
# dicard() bu ham elementni o'chiradi lekin error qaytarmaydi
# pprint() bu dictionaryni chiroyli qilib chiqarb beradi 
# all() hamma elementlar True bo'lsa ishlaydi 
# any() bitta element rost bo'lib qolsa ham ishlaydi 
# len() nechta element borlgini aniqlab beradi 
# sorted() bergan dictionaryni tartiblab yangi list qaytaradi 
# clear() dictionaryni bo'sh qiladi yani hamma elementlarni o'chiradi 
# copy() bu dictionaryni nusxa ko'chiradi va butunlay boshqa qiymat qaytaradi 
# fromkeys() bu dictionaryga qiymatlarni boshqa qiymatlarni o'zgartirishga yordam beradi 
# get() bu dictionaryda qiymatni topib beradi 
# items() bu dictionaryni ichidagi elementlarni tartiblab yangi list qaytaradi 
# pop() bu dictionaryda elementni o'chiradi lekin qaytaradi 
# popitem() bu dictionaryda elementni o'chiradi va o'chirgan elementni tartiblab yangi tuple qaytaradi 
# setdefault() bu dictionaryda elementni topib beradi, agar element topilmasa boshqa qiymat qo'shadi 
# update() bu dictionaryga qiymatlarni o'zgartirishga yordam beradi 
# values() bu dictionaryni ichidagi qiymatlarni tartiblab yangi list qaytaradi 

#                             Set - and - Dict

# union()

set_one = {1, 2, 3} # bunda biz set onega elementlar berib olamiz 1, 2, 3
set_two = {3, 4, 5} # bunda ham set twoga elementlar berib olamiz 3, 4, 5
my_set = set_one | set_two # va bunda bir biriga solishtrb ko'radi agar bitta element ikkisida ham qatnashgan bo'lsa unda 
print(my_set) # natijaga (1, 2, 3, 4, 5) qilib ikkisida ham qatnashgan elementni tashlab ketib tartiblab chiqarib beradi 

# intersections()

set_one = {1, 2, 3} # bunda biz set onega elementlar berib olamiz 1, 2, 3
set_two = {3, 4, 5} # bunda biz set onega elementlar berib olamiz 3, 4, 5
my_set = set_one & set_two # va bunda biz bir-biri bilan solishtrb olamiz 
print(my_set) # va bunda biz ikkisda ham qatnashgan elementni natijaga chiqaramiz yani (3)

# difference()

set_one = {1, 2, 3} # bunda biz set onega element berib olamiz 1, 2, 3
set_two = {3, 4, 5} # bunda biz set twoga element berib olamiz 3, 4, 5
my_set = set_one - set_two # va bunda biz ikkisida bo'lgan elementni qidirib olamiz yani birida bo'lgan element ikkinchisida bo'lmasa 
print(my_set) # natijaga birinchisida bo'lgan elementni yani (1, 2) chiqaramiz

# symettric_difference

set_one = {1, 2, 3} # bunda biz set onega element berib olamiz 1, 2, 3
set_two = {3, 4, 5} # bunda biz set twoga element berib olamiz 3, 4, 5
my_set = set_one ^ set_two # va bunda biz ikkisida bo'lgan elementni solishtrb olamiz va 
print(my_set) # natijaga ikkisida ham qatnashgan elementni qabul qilmaydi 

#                                  Reckursif - funcsiya 

# Reckursif funksiya 2 xil bo'ladi returnli va returnsiz : qiymat qaytarsa ham qaytarmasa ham (def) kalit so'zi bilan boshlanadi
def add_numbers(a, b): # bunda biz add_numbers funksiyasiga a va b o'zgaruvchisini yaratib olamiz
    result = a + b # va result o'zgaruvchisiga a va bni bir-biriga qo'shib olamiz
    return result # va bizga qaytarsin returnni deb aytamiz
add_numbers(b=3, a=7) # va bu named parametrs deyiladi.

# Parametrlar 2 xil hususiyatga ega required & optional
def add_numbers(a, b=7): # Bunda biz ham required ham optional parametr yasadik 
    print(a, b)
add_numbers(5)

# *args bu sonlarni va string qiymatlarni qabul qiladi
def add_numbers(a, b, *args): # Bu yerda biz (*args) nomli funksiyani chaqirib olamiz 
    print(args) # va printda argsni chiqar deb bersak 
add_numbers(2, 3, 4,5, 52, "Salom Dunyo", 23432,) # va bu yerda bizga a=2, b=3, qilib qolgan barcha elementlarni args funksiyasiga taminlab yuboradi

# **kwargs bu o'zgaruvchilarga qiymat taminlab yaratamiz va ularni dictuaniry ko'rinishida chiqarib beradi
def add_numbers(**kwargs):
    print(kwargs)
add_numbers(a=1, b=3, s="Salom") # bunda natijada {'a': 1, 'b': 3, 's': 'Salom'} deb chiqarib beradi

# rekursif va iterativ funksiyalar

# rekursif funksiya bu o'zini - o'zi takrorlaydi
# iterativ funksiya bu for while loopidan foydalaniladi

# rekursif funksiyaga bir misol

def func(count): # bunda biz parametrga countni berib olamiz
    if count <= 10: # va shart beramiz agar countimiz <= 10dan bo'ladigan bo'lsa bunda bizga:
        print("ok") # 10 marta 'ok'ni chiqar deymiz va:
        func(count + 1) # countga + 1 qilamiz sababi o'ziga o'zini qo'shib 10 marta chiqaradi

#                                  Lambda funksiyasi 

# lambda funksiyasiga bir misol

a = lambda x: x + 2 # bunda biz lambda funskiyasini a o'zgaruvchisiga taminlab olamiz va:
# x o'zgaruvchisini olib unga biz kiritgan songa 2ni qo'shsin deb olamiz
print(a(5)) # natijada biz printga a o'zgaruvchisini berib 2ga 5ni qo'shsin deb aytib olamiz

#                                  Lambda funsksiyalari :

# High-order funksiyalar

# map()
# filter()

# map()ga misol yani darajasini aniqlash

numbers = [1, 2, 3, 4] #bunda biz list ro'yhat sifatida elementlar kiritib olamiz 
squared = list(map(lambda x: x**2, numbers)) # va bunda map funksiyasini qo'llab unga x o'zgaruvchi taminlaymizda **2 qilib darajani hisoblaymiz:
print(squared)  # Natija: [1, 4, 9, 16] va natijada har bir sonni darajasini hisoblab beradi

# filter() ga misol 
# juft sonlar bilan

numbers = [1, 2, 3, 4, 5]
even_numbers = list(filter(lambda x: x % 2 == 0, numbers))
print(even_numbers)  # Natija: [2, 4]

# toq sonlar bilan 

numbers = [1, 2, 3, 4, 5]
even_numbers = list(filter(lambda x: x % 2 != 0, numbers))
print(even_numbers)  # Natija: [1, 3, 5]

# open() fayllarni o'qish uchun yordam beradi 
# read() faylni o'qish uchun yordam beradi 
# loads() json formatida o'qilgan matnini dictionary qiymatlari qaytaradi 
# filter() funksiyasi orqali elementlarni filter qilish uchun yordam beradi

#                                      Opjeckt programming language(OOP)

# Class:
# Properties: & Methods
# Clasni ichidagi har bir funksiyani metod deb ataymiz
# __init__ obyektlarni yaratib beruvchi metod 
# __init__(self, ...) self bu standart parametr 
# __name bunaqa ko'rinish o'zgartrb bo'lmas deyiladi

# Inhertence(Meros qoldirish) yani bu degani otasida bo'lgan qobilyat bolasiga ham o'tadi

# Afzalliklari :  
# Kodning qayta foydalanish imkoniyati (Bir xil kodni bir necha marta yozish shart emas)
# Modullik va strukturaviy yondashuv (Katta loyihalarda kodni tartibga solish osonlashadi)
# Kengaytirish imkoniyati (Yangi sinflar yaratish va mavjud funksiyalarni kengaytirish osonlashadi)

# Encapsulation (Meros olish)

# Public (O'zgartrb bo'ladigan doimiy)
# Protecdec (Otasidagi qobilyatni bolasida o'zgartrsa bo'ladi lekin o'zgartrmaslik tavsiya etiladi)
# Private (To'g'ridan to'gri atributlarni o'zgartrb bo'lmaydi)

# Abstraction(Bu foydalanuvchiga ichki hususiyatini ko'rsatmay tashqi qobilyatini ko'rsatadi)


# Getter(bu private atributining qiymatini )

#                                     SQL


#  sudo mysql -u root -p - Bu databazaga kirish uchun
# quit - chiqib ketish
# CREATE DATABASE ...; - Bu biz data baza yaratishimiz uchun
# SHOW DATABASES; - Mening data bersimdagi malumotlarni ko'rsatadi 
# SHOW TABLES; - Bu yaratgan jadvalimizni chiqarib beradi
# DROP DATABASES ...; - Bu biz yaratgan databasalarni o'chiradi
# DROP TABLE ...; - Biz yaratgan jadvalni o'chiradi  
# use ... - deb biz foydalanmoqchi bo'lgan databazamizni ichiga kirib olamiz 
# Ctrl + L - Databazadagi malumotlarni clear qilib tozalaydi 
# AUTO_INCREMENT PRIMARY KEY - Bu avtomatik o'zi raqam yoki Id beradi 
# CREATE TABLE ... - Bu databazamiz ichiga jadval yaratish uchun 
# DESCRIBE ...; - Jadval haqida malumotni chiqarib beradi 
# INSERT INTO ...(name, age, ...) - deb biz yaratgan jadvalga ism familya shularni kiritishimiz uchun 
# VALUES ("Ali", "32" ...) - Bunda biz jadvaldagi malumotlarni to'ldirib olamiz
# SELECT * FROM ...; - Bunda biz jadvaldagi kiritgan malumotlarimizni chiqarib beradi.
# SELECT id, first_name yoki ... FROM ... - 
# SELECT * FROM ... WHERE ... <= ... - bunda biz jadvalizmdan eng kattasini topamiz

# Barchasi bo'yicha o'zgartirish
# UPDATE ...
# salary = salary - salary * 0.1
# WHERE id = ...; 

# Qaysi qatorni chiqarmoqchi bo'lsa 
# SELECT DISTINCT qator_nomi FROM table_nomi;

# Jami mahsulotlari yig'indisini chiqarish
# SELECT SUM(price) FROM table_nomi;

# Bittasi bo'yicha o'zgaritirsh
# UPDATE ...
# salary = salary - salary * 0.1;

# Jadvalga qator qo'shish
# ALTER TABLE ...
# ADD COLUMN ...nimani qo'shmoqchi bo'lsayiz yozasiz

# Jadvaldagi har bir mahsulotni har bittasini necha marta qatnashganini bilish
# SELECT qator_nomi COUNT(*) FROM table_nomi GROUP BY qator_nomi;

# Jadvaldagi qatorni o'chirish  
# ALTER TABLE ...
# DROP COLUMN ...nimani o'chirmoqchi bo'lsayiz yozasiz

# Jadvalni nomini o'zgartirish
# ALTER TABLE eski_nomi RENAME yangi_nomi; 

# Jadval ichidagi COLUMNni nomini o'zgartirish
# ALTER TABLE table_nomi RENAME COLUMN eski_nomi TO yangi_nomi;

# Biron bir malumot necha marta qatnashganligini bilish
# SELECT DISTING qator_nomi COUNT(*) FROM table_nomi GROUP BY;

# jadvaldagi malumot nechtaligini aniqlash uchun
# SELECT qator_nomi LENGTH(qator_nomi) * FROM jadval_nomi;

# SELECT MIN(qator_nomi), MAX(qator_nomi) FROM table_nomi;

#                                 PIP (package - manager)   

# python3 -m  venv ... virtual muhtni nomini beramiz 
# ls -a qilib o'rnatgan muhitimizni ko'rib olamiz
# source ... bin/activate qilib uni ishga tushurib olamiz 
# pip freeze biz o'rnatgan muhtlarni ko'rib olamiz 

#                                  SQLni Pythonga ulash

# 1-bo'lib sqlni pythonga ulashimiz uchun biz o'zimizga virtual muhut yaratib olishimiz kerak yani u muhut :
# (python3 -m venv .venv & .env) yoki umuman boshqa nom ham yozib ochsangiz bo'ladi 
# va bu muhtni yaratib olganimizdan keyin buni ishga tushurish quyidagicha bo'ladi :
# (source/bin/activate) bu linux va macOSlar uchun :
# windowslar uchun esa : (source/Scripts/activate) deb yoziladi
# Virtual muhutni ochib bo'lgandan so'ng o'sha muhut yaratilgan papkani ichiga kirib :
# (pip install...) qilib nima kerak bo'lsa o'sha kutubxonani o'rnatib olamiz yani bizga :
# (pip install mysql-connector-python) kutubxonasi kerak va bu kutubxona bilan SQLni pythonga ulashimiz mumkin
# va bu o'rnatilgan kutubxonalarni ro'yhatini ko'rish uchun (pip freeze) qilib ko'ramiz
# Shunga o'xshash barcha kutubxona va kodlarni (Pypi.org) saytidan olamiz
# Misol uchun biz bitta kutubxona yuklab oldik va uni versiyasini aniqlashimiz kerak va uni qayerdan bilamiz !? albatta requarimnets.txt faylidan bilamiz...
# Agar mobodo bu faylda bo'lmaydigan bo'lsa oddiy txt faylda bo'ladi va boshqalar bizni ham o'rnatgan kutubxonamizni versiyasini aniqlashlari uchun biz ham shu faylni ichiga joylaymiz
# Va bu faylga to'gridan to'gri terminaldan yozmoqchi bo'lsak (pip freeze > requariments) qilsak bo'lgani pip freezedan chiqgan malumot to'gri txt fayliga yoziladi