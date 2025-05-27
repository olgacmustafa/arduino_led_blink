
---

### 📄 `README_TR.md` (Türkçe Versiyon)

```markdown
# Arduino LED Yakma Projesi

Bu, bir LED'i dijital 8 numaralı pin üzerinden yakmak için yapılmış basit bir Arduino projesidir. Arduino kartında dijital çıkış pininin nasıl kontrol edileceğini gösterir.

## Kullanılan Bileşenler
- Arduino Uno (veya uyumlu bir kart)
- 1 adet LED
- 1 adet 220 ohm direnç
- Breadboard ve jumper kablolar

## Devre Şeması
LED’in uzun bacağı (anot), 220 ohm direnç üzerinden 8 numaralı pine bağlanır. Kısa bacağı (katot) ise GND’ye bağlanır.

## Kod
```cpp
void setup() {
  pinMode(8, OUTPUT);
}

void loop() {
  digitalWrite(8, HIGH); // LED’i yak
}
