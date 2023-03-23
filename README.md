# python123
# ilk projeler
# if-elif-else kullanımı

defkullanıcı_adı ="yazılım"
defparolanız = "1234"

kullanıcı_adı = input("kullanıcı adınız:")
parola = input("parolanız:")



if ((defkullanıcı_adı==kullanıcı_adı)and (parola==defparolanız)):
        print("hesabınıza hoşgeldiniz")
elif ((defkullanıcı_adı!=kullanıcı_adı)and (parola==defparolanız )):
        print("Üzgünüz, kullanıcı adı yanlıştı. Lütfen bilgilerinizi dikkatlice kontrol edin. ")
elif ((defkullanıcı_adı==kullanıcı_adı)and (parola!=defkullanıcı_adı)):
        print("Üzgünüz, şifren yanlıştı. Lütfen şifreni dikkatlice kontrol et.")
else:
        print("bilgiler yanlış\nlütfen tekrar deneyiniz ")
...

# HESAP MAKİNESİ

print("""**********************************
Hesap Makinesi Programı

işlemler;

+
-
*
/
***********************************""")





a = int(input("birinci sayı:"))
b = int(input("ikinci sayı:"))

işlem = input("işlem giriniz")

if işlem == "+":
    print("{} ile {} in toplamı eşittir {}".format(a,b,a+b))

elif işlem == "-":
    print("{} ile {} in eksisi eşittir {}".format(a,b,a-b))

elif işlem == "*":
    print("{} ile {} in bolmesi eşittir {}".format(a,b,a*b))

elif işlem == "/":
    print("{} ile {} in çarpımı  eşittir {}".format(a,b,a/b))

else:
    print("doğru işlem giriniz")


.....
