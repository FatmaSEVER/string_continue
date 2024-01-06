# string_continue

message ='Hello There. My name is Fatma SEVER'

message = message.upper() # upper metodu tüm karakterleri büyük harfle yazar.

message = message.lower() # lower metodu tüm karakterleri küçük harfle yazar.

message = message.title()  # title metodu tüm kelimelerin ilk harfini büyük yazdırır.

message = message.capitalize()  # capitalize metodu sadece ilk harfi büyük yazar.

message = message.strip()  # strip metodu varsa, cümlenin başındaki ve sonundaki boşlukları siler.

message = message.split('.') # Nokta itibariyle cümleleri böler.

print(message[1]) 


message = message.split()

message = ' ---  '.join(message)

print(message)
