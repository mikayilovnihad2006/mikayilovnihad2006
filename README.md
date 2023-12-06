#include <stdio.h>

int main() {
    int bolunen, bolen, bolum, kalan;

    // Kullanıcıdan tam sayıları al
    printf("Bolunen sayiyi girin: ");
    scanf("%d", &bolunen);

    printf("Bolen sayiyi girin: ");
    scanf("%d", &bolen);

    // Bölme işlemi
    bolum = bolunen / bolen;
    kalan = bolunen % bolen;

    // Sonuçları ekrana yazdır
    printf("Bolum: %d\n", bolum);
    printf("Kalan: %d\n", kalan);

    return 0;
}
