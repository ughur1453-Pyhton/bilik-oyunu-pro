print("="*40)
print("🎮 BİLİK OYUNU 🎮")
print("="*40)
basla = input("Oyuna başlamaq üçün ENTER basın...")
print("🎮 Səviyyə seçin:")
print("1️⃣ Asan")
print("2️⃣ Orta")
print("3️⃣ Çətin")
seviyye = input("Cavabınızı yazın 1 , 2, 3 : ").strip().lower()

while seviyye not in ["1", "2", "3"]:
    print("Xaiş olunur səviyyənizi düzgün secin(1,2,3)")
    seviyye = input("Cavabınızı yazın (1,2,3): ").strip().lower()
print("Salam bilik oyununa xoş gəlmisiniz.Sizə bu oyunda 10 dənə sual veriləcək.Hər düz bildiyiniz sual üçün 10 bal veriləcək. Axirda nəticənizi 100 üzərindən görə bilərsiniz")
ad = input("Adınınızı yazın: ")
n = 0
print(f"{ad} hazirsaniz baslayaq")
if seviyye == "1" :
    sual1=("1.Suyun kimyəvi formulu nədir?") 
    print(sual1)
    print("a)H2O2 b)CO2 c)H2O d)ClO e)NaO2")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="c":
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab H2O idi")
    sual2=("2.Azərbaycanın paytaxtı hansıdır?")
    print(sual2)
    print("a)Istanbul b)Bakı c)New York d)Madrid e)Naftalan")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="b":
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab Bakı idi")
    sual3 = ("3.Bir ildə neçə ay var?")   
    print(sual3)
    print("a)12 b)18 c)21 d)5 e)10")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="a" :
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab 12 idi")
    sual4 = ("4.Su hansı temperaturda donar? (°C)")  
    print(sual4)
    print("a)-5 b)3 c)-1 d)1 e)0")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="e" :
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab 0 idi")    
    sual5 = ("5.Futbolda bir komanda neçə oyunçu ilə oynayır?")   
    print(sual5)
    print("a)7 b)10 c)20 d)11 e)5")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="d" :
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab 11 idi")
    sual6 = ("6.Günəş sistemində neçə planet var?") 
    print(sual6)
    print("a)5 b)15 c)8 d)6 e)9")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="c" :
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab 8 idi")
    sual7 = ("7.Azərbaycan dilində neçə sait var?") 
    print(sual7)
    print("a)4 b)9 c)6 d)10 e)8")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="b" :
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab 9 idi")
    sual8 = ("8.Dünyanın ən uzun çayı hansıdır?")
    print(sual8)
    print("a)Amazon b)Missisipi c)Konqo d)Lena e)Nil")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="e" :
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab Nil idi")
    sual9 = ("9.Dünyanın ən böyük okeanı hansıdır?")
    print(sual9)
    print("a)Sakit okean b)Hind okeanı c)Şimal Buzlu okeanı d) Cənub okeanı e)Atlantik okean ")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="a" :
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab Sakit okean idi")
    sual10 = ("10.Günəş sistemində ən böyük planet hansıdır?") 
    print(sual10)
    print("a)Yer b)Mars c)Uran d)Yupiter e)Neptun")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="d" :
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab Yupiter idi")
elif  seviyye == "2" :
    sual1 =("1.Azərbaycanın müstəqilliyi hansı ildə bərpa olunub?")
    print(sual1)
    print("a)1994 b)1992 c)1991 d)1980 e)1990")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="c" :
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab 1991 idi")
    sual2 = ("2.İşıq sürəti təxminən neçə km/s-dir?") 
    print(sual2)
    print("a)125000 km/s b)200000 km/s c)250000 km/s d)100000 km/s e)300000 km/s")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="e" :
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab 300000 km/s idi")
    sual3 = ("3.İnsan beyninin əsas hissələrinin sayı neçədir?")   
    print(sual3)
    print("a)3 b)1 c)2 d)7 e)5")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="a" :
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab 3 idi")
    sual4 = ("“4.Romeo və Cülyetta” əsərinin müəllifi kimdir?")    
    print(sual4)
    print("a)Nizami Gəncəvi b)Viktor Hüqo c)Fyodor Dostoyevski d)William Shakespeare e)Lev Tolstoy")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="d" :
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab William Shakespeare idi")
    sual5 = ("5.Periodik cədvəldə hidrogenin atom nömrəsi neçədir?") 
    print(sual5)
    print("a)5 b)3 c)12 d)4 e)1")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="e" :
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab 1 idi")
    sual6 = ("6.Dünyada ən çox danışılan dil hansıdır(ana dili kimi)?")  
    print(sual6)
    print("a)İspanyol b)Çin c)İngilis d)Fransizca e)İtalyanca")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="b" :
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab Çin idi")
    sual7 = ("7.Bir saatda neçə saniyə var?")    
    print(sual7)
    print("a)3600 b)2400 c)5200 d)1700 e)10800")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="a" :
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab 3600 idi")
    sual8 = ("8.Qan hansı orqanda təmizlənir?")  
    print(sual8)
    print("a)ürək b)ciyər c)böyrək d)beyin e)ağ ciyər")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="c" :
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab böyrək idi")
    sual9 = ("9.İnsan bədənində neçə sümük var?")    
    print(sual9)
    print("a)103 b)412 c)564 d)123 e)206")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="e" :
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab 206 idi")
    sual10 = ("10.Kim “Nisbilik nəzəriyyəsi”ni irəli sürmüşdür?")    
    print(sual10)
    print("a)Nikola Tesla b)Albert Ensteyn c) Robert Oppenheimer d)Carl Sagan e)Ibn Sina")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="b" :
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab Albert Ensteyn idi")
elif seviyye == "3" :
    sual1 = ("1.İnsan bədənində ən böyük daxili orqan hansıdır?")
    print(sual1)
    print("a)qaraciyər b)ağciyər c)beyin d)böyrək e)ürək")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="a" :
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab qaraciyər idi")
    sual2 = ("2.Dünya üzrə ən yüksək dağ zirvəsi hansıdır?") 
    print(sual2)
    print("a)K2 b)Kanchenjunga c)Everest d)Makalu e)Manaslu")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="c" :
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab Everest idi")
    sual3 = ("3.Azərbaycanın ilk prezidenti kim olub?")
    print(sual3)
    print("a)İlham Əliyev b)Ayaz Mütəllibov c)Heydər Əliyev d)Əbülfəz Elçibəy e)İsa Qəmbər")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="b" :
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab Ayaz Mütəllibov idi")
    sual4 = ("4.1 mol maddədə neçə zərrəcik olur?") 
    print(sual4)
    print("a)60.2*10²³ b)6.01*10²³ c)60.1*10²³ d)5.04*10²³ e)6.02*10²³")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="e" :
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab 6.02*10²³ idi")
    sual5 = ("5.Beynəlxalq vahidlər sistemində (SI) qüvvə vahidi nədir?")  
    print(sual5)
    print("a)paskal b)metr c)Kilovolt d)kiloqram e)Nyuton")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="e" :
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab Nyuton idi")
    sual6 = ("6.Dünyanın ən dərin okean nöqtəsi haradır?")    
    print(sual6)
    print("a)Tonga b)Mariana c)Filipin d)Porto Riko e)Kuril-Kamçatka")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="b" :
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab Mariana idi")
    sual7 = ("7.Fotosintez zamanı bitkilər hansı qazı qəbul edir?") 
    print(sual7)
    print("a)O2 b)H2 c)CO2 d)CO e)N2O")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="c" :
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab CO2 idi")
    sual8 = ("8.Azərbaycanın BMT-yə üzv olduğu il hansıdır?")  
    print(sual8)
    print("a)1990 b)1880 c)1995 d)2001 e)1992")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="e" :
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab 1992 idi")
    sual9 = ("9.İnsan DNT-sində neçə xromosom olur?")
    print(sual9)
    print("a)55 b)48 c)52 d)46 e)50")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="d" :
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab 46 idi")
    sual10 = ("10.Python proqramlaşdırma dilinin yaradıcısı kimdir?") 
    print(sual10)
    print("a)Jensen Huang b)Nadir Nəcəfli c)Bill Qeyts d)Guido van Rossum e)Marco Van Basten")
    cavab = input("cavabinizi bura qeyd edin : ").strip().lower()
    while cavab not in ["a", "b", "c", "d", "e"]:
        print("❗ Zəhmət olmasa 5 variantdan birini seçin (a, b, c, d, e)")
        cavab = input("Cavabınızı yazın (a/b/c/d/e): ").strip().lower()
    if cavab =="d" :
        print("cavabiniz duzdur")
        n = n + 10
    else:
        print("sizin cavabiniz sehvdir. Cavab Guido van Rossum idi")
print("\n🎯 OYUN BİTDİ 🎯")
print(f"{ad} Topladığınız bal: {n}/100")

if n == 100:
    print("🏆 Əfsanəsən!")
elif n >= 70:
    print("👏 Çox yaxşı nəticə!")
elif n >= 40:
    print("👍 Orta səviyyə")
else:
    print("📘 Bir az da oxu 😉")        
