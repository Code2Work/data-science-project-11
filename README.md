# Data Science Python Project 11 — Pandas ile Veri Analizi

### Proje Kurulumu
Projeyi öncelikle forklayın ve clone edin.
Proje sayımız ilerledikçe proje yönetimimizi kolaylaştırmak adına projelerimizi belli klasör kalıplarında saklamak iyi bir alışkanlıktır.
Örnek bir Lokasyon: Code2Work/DataScience/data-project-11.

### Proje Kurulumu Komutlar
Aşağıdaki komutları sırasıyla çalıştırınız.
* `python -m venv venv`
* `venv\Scripts\activate` (Windows) — macOS / Linux için: `source venv/bin/activate`
* `pip install -r requirements.txt` => Tüm bağımlılıkları kurar
* `python watch.py` => Tüm testleri çalıştırır

## Bonus
* Eğer daha detaylı bir şekilde testlerin içerisine bakmak isterseniz:
* `pytest tests/test_question.py -s -v`

### Projeye Başlamadan Önce
* Bu bir **Python** projesidir. Veritabanı kurulumuna, SQL sorgusuna ya da herhangi bir bağlantı ayarına **gerek yoktur**.
* Çalışırken sadece `tasks/task_manager.py` dosyasında çalışacağız. Bu dosyanın dışındaki kodları değiştirmeyiniz!
* Her fonksiyonun ne yapması gerektiği `tasks/task_manager.py` içindeki yorum satırlarında açıklanmıştır. Fonksiyonların içini doldurunuz.
* Projede kullanılan veri seti repo içinde `files/cyberpunk_characters.csv` yolundadır; ayrıca bir dosya indirmenize gerek yoktur.
* Testleri çalıştırarak doğru sonuç alıp almadığınızı adım adım kontrol edebilirsiniz.

# Questions
* Senaryo:
    Cyberpunk 2077 evrenindeki karakterlerin istatistiklerini içeren bir CSV dosyası elinde.
    Pandas ile bu veriyi okuyup filtreleyecek, sıralayacak, normalize edecek ve özet istatistikler çıkaracaksın.
* `tasks/task_manager.py` dosyasının içerisindeki fonksiyonların içerisini doldurmaya çalışın.
