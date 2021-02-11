https://drive.google.com/file/d/1SKUrzVhxre5CcuE_envSDwmNik9MRASp/view

Burdaki dosyayı indiriyoruz ve Arduinonun "libraries" dosyasını içine atıyoruz hedefteki dosyaları değiştiriyoruz.
libraries konumu
C:\Users\username\Documents\Arduino\libraries yani belgelerim veyada
C:\Users\KULLANICIADI\Documents\ArduinoData\packages\digistump\hardware\avr\1.6.7\libraries

Konumunda olması gerekiyor hedefteki dosyaları değiştirdiğiz zaman qwerty destekli yani türkçe klavye destekli yapmak için yapmanız gereken tek bir şey kalıyor kodlarınızın  başına #define kbd_tr_tr kodunu eklemek 

Örnek:

#define kbd_tr_tr           
#include "DigiKeyboard.h"
void setup() {
}

void loop() {



Converter için:

BadUSB hakkında bolca payload bulabilirsiniz ancak Digispark ve benzeri Arduino aygıtlarında kodlar farklı şekildedir ama onunda basit bir çözümü var 
Github da paylaşılmış bir Converter var  https://cedarctic.github.io/digiQuack/
