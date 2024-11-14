#include <Wire.h>
#include <LiquidCrystal_I2C.h>

// LCD ekran adresini ve boyutunu tanımlayın
LiquidCrystal_I2C lcd(0x27, 16, 2); // 0x27, kullanılan I2C modülüne göre değişebilir

void setup() {
  // LCD'yi başlat
  lcd.begin();
  
  // Arka ışığı aç
  lcd.backlight();

  // Ekranda mesaj yazdır
  lcd.setCursor(0, 0); // İlk satır, ilk sütun
  lcd.print("Merhaba!");

  lcd.setCursor(0, 1); // İkinci satır, ilk sütun
  lcd.print("Ben Astro :)");
}

void loop() {
  // Döngü içinde işlem yapılmayacak
}
