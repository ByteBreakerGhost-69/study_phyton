 print("helldo maulana let's learn python")
    
      # algoritma adalah langkah-langkah logis dan terstruktur untuk menyelesaikan suatu masalah
    
      #|========================================================================================================================================|#
      ###          cara kerja progam python dan bytecode          ### ===> nomor 1
      #|========================================================================================================================================|#
    
      print("|======= bismillah =======|")
      print("hello world")    #  hasilnya hello world
    
      # <== ini adalah commend (dipakai untuk menandai isi progam)
    
      a = 10
      b = 20
      print(a)  # hasilnya 10 
      print(b)
      """ada apa dengan mu"""   # {'''.......'''} ini juga di sebut commend {commend multilain} 
      
      #|=============================================================================================================================================|#
      ###          mengenal variabel          ### ===> nomor 2
      #|=============================================================================================================================================|#
      
      print("|======= bismillah === nomor 2 =======|")
      x = 10
      #x  <=== adalah varibel
      #10 <=== adalah veliu
      #=  <=== adalah devinisi..
      
      # variabel adalah tempat menyimpan data
      
      a = 10          # maka a nilainya 10
      panjang = 1000  # hasilnya 10 # maka panjangnay 1000
      
      print(a)
      # pemanggilan pertama
      a = 1
      b = 6
      saya = 0
      print(" nilai a = ", a)   # hasilnya nilai z = i
      print(" nilai b = ", b)   # hasilnya nilai a = 6
      print(" nilai saya = ", saya)   # hasilnya nilai kamu = 0
      
      # penamaan dikasih _
      nilai_y = 5   # tidak buleh ada spasi di samping itu 'nilai_y' harus  
      # di kasih andeskor tidak buleh di spasi dan juga tidak buleh menaruh
      # angka di depan
      
      #pemanggilan kedua
      a = 90
      print(" nilai a = ", a )
      print(" nilai a = ", a)
      
      # asaimen indairek
      b = 98
      print(" nilai b = ", a)   # beda ternyata tidak apa apa
      #|==============================================================================================================================================|#
      ###          tipe data          ###   ===> nomor 3
      #|==============================================================================================================================================|#
      
      print("|======= bismillah === nomor 3 =======|")
      #tipe data apa saja yang ada di python
      
      # yang pertama tipe data angka satuan { integer } ===> yang tidak ada komanya
      data_integer = 1
      print("type(data_integer")  #  hasilnya <class 'int'>
      print("data : ", data_integer, ", bertipe : ", type(data_integer))  # hasilnya data: 1 , bertipe : <class 'int'>
      
      # asal mula yang ada di bawah ada diatas 
      
      data_integer = 1
      print("data : ", data_integer)   #hasil data : 1
      print(" -bertipe : ", type(data_integer))
      
      # yang kedua tipe data decimal {float} ===> angka dengan koma
      data_float = 1.5
      print("data : ", data_float)
      print(" -bertipe : ", type(data_float))
      
      # yang ketiga tipe data kumpulan karakter { string }
      data_string = " the intelligen python"
      print("data : ", data_string)
      print(" -bertipe : ", type(data_string))
      
      # yang keempat tipe data biner ===> true/false { boolean/bool }
      data_bool = True
      print("data : ", data_bool)
      print(" -bertipe : ", type(data_bool))
      
      # tipe data khusus ada dua jenis
      # yang pertama bilangan complex
      data_complex = complex(5,6)
      print("data : ", data_complex)
      print(" -bertipe : ", type(data_complex))
      
      # yang kedua type data dari bahasa c
      
      from ctypes import c_double # import dari bahasa c
      
      
      #|=============================================================================================================================================|#
      ###          casting type data          ###   ===> nomor 4  ===> merubah dari satu type ke type lain
      #|=============================================================================================================================================|#
      # tipe tipe data yang ditahu ada 4 ===> int,float,string,bool
      
      print("|======= bismillah nomor 4 =======|")
      print("|===== int =====") #====================================================#
      data_int = 5
      print("data = ", data_int, ",type =", type(data_int))   # data type = <class'int'>
      
      data_float  = float(data_int) # ini akan di bulatkan ke bawah
      data_str    = str(data_int) # ini harus angka
      data_bool   = bool(data_int) # akan false jika nilai integer = 0          
      print("data = ", data_float, ",type =", type(data_float))
      print("data = ", data_str, ",type =", type(data_str))
      print("data = ", data_bool, ",type =", type(data_bool))
      
      print("|===== fload =====") #==================================================#
      data_float = 9.5
      print("data = ", data_float, ",type =", type(data_float))     # data type = <class'float'>
      
      data_int    = int(data_float) # ini akan di bulatkan ke bawah
      data_str    = str(data_float) # ini harus angka
      data_bool   = bool(data_float) # akan false jika nilai integer = 0
      print("data = ", data_int, ",type =", type(data_int))
      print("data = ", data_str, ",type =", type(data_str))
      print("data = ", data_bool, ",type =", type(data_bool))
      
      print("|===== bool =====|") #==================================================#
      data_bool = True
      print("data = ", data_bool, ",type =", type(data_bool))   # data type <class'bool'>
      
      data_int    = int(data_bool) # ini akan di bulatkan ke bawah
      data_str    = str(data_bool) # ini harus angka
      data_float  = float(data_bool) # akan false jika nilai integer = 0
      print("data = ", data_int, ",type =", type(data_int))
      print("data = ", data_str, ",type =", type(data_str))
      print("data = ", data_float, ",type =", type(data_float))
      
      print("|===== string =====|") #===================================================#
      data_str = "10";  #harus angka tidak buleh huruf
      print("data = ", data_str, ",type =", type(data_str))   # data type <class'str'>
      
      data_int    = int(data_str) # ini akan di bulatkan ke bawah
      data_float = float(data_str) # ini harus angka 
      data_bool  = bool(data_str) # akan false jika nilai integer = 0
      print("data = ", data_int, ",type =", type(data_int))
      print("data = ", data_float, ",type =", type(data_float))
      print("data = ", data_bool, ",type =", type(data_bool))
      #|=============================================================================================================================================|#
      #####          mengambil input data dari user          #####     ===> nomor 5
      #|=============================================================================================================================================|#
      
      print("|======= bismillah === nomor 5 =======")
      print("===== ### =====")
      
      data = input("masukan nama ")   # nanti di suruh masukan data [ masukan data ... ] ex: data yang kan aku masukan adalah 10
                                      # maka hasilnya [ masukan data 10 ]
      
      # fungsi dari input(...) yakni akan selalu mengembalikan nilai dalam bentuk string( teks ), meskipun user memasukkan angka
      
      print("data = ",data ,",type =",type(data))     # digunakan untuk menunjukan type [ type = <class 'str'> ]
      
      # jika ingin mengambil integer, maka:
      data_int = int(input("masukan data "))  # tidak buleh berupa nama atau yang menyamainya, harus angka
      # ^^^ fungsi input (...) tetap mengembalikan string, tetapi kemudian int(...) mengoversi string tersebut menjadi integer [ bilangan bulat ]
      
      print("data = ",data_int,",type =",type(data_int))    # digunakan untuk menunjukan type [ type = <class 'int> ]
      
      # kesimpulannya di atas ===>  1.[ data = input("masukan data") ] dengan 2.[ data_int = int(input("masukan data")) ]
      #itu beda kalau yang nomor 1. itu buleh berupa nama dan yang menyamainya, dan variabel tapi kalau yang nomor 2. itu harus berupa variabel
      
      
      # bagaimana dengan booleaan
      data_bool = bool(int(input("masukan nilai boolean:")))   # hasilnya nanti true atau false 
                                                                # jika menaruk angka 0 maka hasilnya false selain itu true
      
      print("data = ",data_bool,",type =",type(data_bool))  # digunakan untuk menunjukan type [ type = <class 'bool'> ]
      #|===========================================================================================================================================|#
      #####          operasi aritmatika          #####   ===>  nomor 6
      #|===========================================================================================================================================|#
      
      print("|======= bismillah === nomor 6 =======")
      a = 10
      b = 3
      
      # operasi pertambah +
      hasil = a + b
      print(a,'+',b,'=',hasil)
      
      # operasi pengurangan -
      hasil = a - b
      print(a,'-',b,'=',hasil)
      
      # operasi perkali *
      
      hasil = a * b
      print(a,'*',b,'=',hasil)
      
      # operasi pembagian /
      hasil = a / b
      print(a,'/',b,'=',hasil)
      
      #operasi eksponen (pangkat) **
      hasil = a ** b
      print(a,'**',b,'=',hasil)
      
      #operasi modulus (sisa pembagian) %
      hasil = a % b
      print(a,'%',b,'=',hasil)
      
      #operasi floor division //
      hasil = a // b
      print(a,'//',b,'=',hasil)
      
      #prioritas oprasi, oprational precedence
      
      '''
          prioritas operasi:
      
          1.( )
          2.eksponen **
          3.perkalian dan temannya * // ** / % 
          4.penjumlahan dan pengirangan + -
      '''    
      
      x = 3
      y = 2
      z = 4
      
      hasil = x ** y * z + x / y - y % z // x
      print(x ,'**', y, '*' ,z ,'+' ,x ,'/' ,y ,'-' ,y ,'%' ,z ,'//' ,x,'=',hasil )
      
      hasil = x + y * z 
      print( x,'+', y,'*', z,'=', hasil)
      #kurung akan mengambil langkah paling pertama
      hasil = (x + y) * z 
      print( '(',x,'+',y,') *', z,'=', hasil)
      #|===========================================================================================================================================|#
      #####          latihan perhitungan sederhana          #####   ===> nomor 7
      #|===========================================================================================================================================|#
      
      print("|======= bismillah === nomor 7 =======|")
      # latihan konversi satuan temperatur
      
      # progam konversi celcius ke satuan lain
      
      print("\nprogam konversi temperatur\n")
      
      celcius = float(input('masukan suhu dalam celcius: '))
      print("suhu adalah", celcius,"celcius")
      
      # reamur
      reamur = (4/5) * celcius
      print("suhu dalam reamur adalah", reamur,"reamur")
      
      #fahrenhait
      fahrenhait = (9/5) * celcius + 32
      print("suhu dalam fahrenhait adalah", fahrenhait,"fahrenhait")
      
      #kelvin
      kelvin = celcius + 273
      print("suhu dalam kelvin adalah", kelvin,"kelvin")
      
      # progam konversi fahrenhait ke kelvin
      fahrenheit = float(input("Masukan Suhu Fahrenheit : "))
      celcius    = (5/9) * (fahrenheit - 32)
      kelvin     = (celcius + 273)
      print("Suhu dalam Kelvin : ", kelvin)   # hasil   ===> aku masukan 3 hasil 256.888
      
      #progam konversi kelvin ke fahrenhait
      kelvin     = float(input("Masukan Suhu Dalam kelvin : "))
      celcius    = kelvin - 273
      fahrenheit = ((9/5) * celcius) + 32
      print("suhu dalam fahrenheit : ", fahrenheit)   # hasil ===> aku masukan 3 hasil -454.0
      0
      #|===========================================================================================================================================|#
      #####          operasi logika atau boolean          #####   ===> nomor 8
      #|===========================================================================================================================================|#
      
      print("|====== bismillah === nomor 8 ======|")
      # NOT,OR ,AND , XOR
      
      print("|======= or =======|")
      a = True
      c = a or b
      print('data a = ', a)              #   ===> True
      print('-------------------NOT')    #   ===>  -------------NOT
      print('data C = ', c)              #   ===> False
      
      print("|======= not =======|")
      a = True
      b = False
      c = a or b
      print(a,'not',b,'=',c)
      
      # or =====> JIKA SALAH SATU TRUE, MAKA TRUE
      print('|====== OR =======|')   
      a = False                         
      b = False                         
      c = a or b                        
      print(a,'OR',b,'=',c)             # False or False = False
      a = False                         
      b = True                          
      c = a or b                        
      print(a,'OR',b,'=',c)             # False or Trye = True
      a = True                          
      b = False                         
      c = a or b                        
      print(a,' OR',b,'=',c)             # True OR False = True
      a = True                          
      b = True                          
      c = a or b                        
      print(a,' OR',b,'=',c)             # True or True = True
      
      # AND    =====> akan True jika keduanya False = False, True = True
      print('|====== AND =======|')   
      a = False                         
      b = False                         
      c = a and b                        
      print(a,'AND',b,'=',c)             # False AND False = True
      a = False                         
      b = True                          
      c = a and b                        
      print(a,'AND',b,'=',c)             # False AND True = False
      a = True                          
      b = False                         
      c = a and b                        
      print(a,' AND',b,'=',c)             # True AND False = False
      a = True                          
      b = True                          
      c = a and b                        
      print(a,' AND',b,'=',c)             # True AND True = True
      
      # XOR    =====>  akan true jika salah satu true, sisanya false
      print('|====== XOR =======|')   
      a = False                         
      b = False                         
      c = a ^ b                        
      print(a,'XOR',b,'=',c)             # False XOR False = False
      a = False                         
      b = True                          
      c = a ^ b                        
      print(a,'XOR',b,'=',c)             # False XOR True = True
      a = True                          
      b = False                         
      c = a ^ b                        
      print(a,' XOR',b,'=',c)             # True XOR False = True
      a = True                          
      b = True                          
      c = a ^ b                        
      print(a,' XOR',b,'=',c)             # True XOR True = False

