Metro Ağ Yönetimi
Bu proje, bir metro ağındaki istasyonlar ve hatlar arasındaki bağlantıları modellemek ve analiz etmek için geliştirilmiştir. Proje, en az aktarmalı rotayı bulmak için BFS (Breadth-First Search) algoritmasını, en hızlı rotayı bulmak için ise A* algoritmasını kullanır.

Özellikler
İstasyonlar ve Hatlar: Metro ağındaki istasyonları ve hatları modellemek için Istasyon ve MetroAgi sınıfları kullanılmıştır.

Bağlantılar: İstasyonlar arasındaki bağlantılar (yolculuk süresi ile birlikte) eklenebilir.

En Az Aktarmalı Rota: Başlangıç ve hedef istasyonları arasında en az aktarmayı gerektiren rotayı bulur (BFS algoritması kullanılır).

En Hızlı Rota: Başlangıç ve hedef istasyonları arasında en hızlı rotayı (toplam yolculuk süresi en kısa olan rota) bulur (A* algoritması kullanılır).

Kullanım
1. Metro Ağının Oluşturulması
Öncelikle bir MetroAgi nesnesi oluşturun ve metro ağındaki istasyonları ekleyin.

2. İstasyonlar ve Bağlantılar Ekleyin
İstasyonlar, her biri bir Istasyon nesnesi olarak eklenir. İstasyonlar, belirli hatlarda yer alabilir ve birbirleriyle bağlantı kurabilirler.

3. Rotaları Hesaplayın
En Az Aktarmalı Rota: en_az_aktarma_bul(baslangic_id, hedef_id) fonksiyonu, iki istasyon arasında en az aktarma ile ulaşılacak rotayı döndürür.

En Hızlı Rota: en_hizli_rota_bul(baslangic_id, hedef_id) fonksiyonu, iki istasyon arasında en hızlı rotayı (en kısa süreyi) döndürür.

Kurulum
Python 3.x yüklü olmalıdır.

Projeyi klonlayın veya indirin.

Uygulamayı başlatmak için Python dosyasını çalıştırın.
