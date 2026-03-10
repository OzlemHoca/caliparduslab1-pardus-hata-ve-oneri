# Pardus ARM – Donanım Uyumluluk Bildirim Önerisi

## Açıklama

Pardus ARM sürümü, ARM mimarili cihazlarda çalışabilen bir işletim sistemi olarak geliştirilmektedir. Ancak bazı durumlarda kullanıcılar kullandıkları donanım bileşenlerinin sistem tarafından tam olarak desteklenip desteklenmediğini anlamakta zorlanabilmektedir.

## Yeniden Üretme Adımları

1. Pardus ARM tabanlı bir sistem başlatılır.
2. Sistem donanım bileşenleri incelenir.
3. Donanım uyumluluk bilgileri değerlendirilir.

## Beklenen Davranış

Kullanıcıların sistemde bulunan donanım bileşenlerinin uyumluluk durumunu kolayca görebilmesi beklenmektedir.

## Gerçek Durum

Donanım uyumluluğu hakkında bilgi edinmek için genellikle terminal komutları veya teknik araçlar kullanılması gerekebilmektedir.

## Etki

Yeni kullanıcılar donanım uyumluluğunu değerlendirmekte zorlanabilir ve sistem kurulumu sırasında belirsizlik yaşayabilir.

## Önerilen Çözüm

- Sistem ayarlarında donanım uyumluluk ekranı oluşturulması
- Desteklenen ve kısmi desteklenen donanımların gösterilmesi
- Donanım sürücü durumu hakkında bilgilendirme yapılması
