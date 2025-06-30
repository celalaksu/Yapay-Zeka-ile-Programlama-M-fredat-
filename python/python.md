# Python Programlama Dili Müfredatı - Yapay Zeka Destekli Öğrenme

## Genel Öğrenme Yaklaşımı ve Öneriler

### Öğrenme Metodolojisi
Her seviyede aşağıdaki yaklaşımı benimseyin:
- **Teoriyi önce anlayın**: Kavramları tam olarak kavramadan kod yazmaya geçmeyin
- **İnteraktif pratik yapın**: Python REPL'i aktif kullanın, her yeni kavramı hemen deneyin
- **Jupyter Notebook kullanın**: Öğrenme aşamasında kod blokları halinde çalışın
- **Küçük projeler oluşturun**: Her konuyu ayrı bir .py dosyasında deneyimleyin
- **IDE'nizin özelliklerini aktif kullanın**: Tooling'i sadece text editor olarak değil, tam potansiyeliyle kullanın
- **Python documentation'ını okuyun**: Official docs'lar ve help() fonksiyonu en güvenilir kaynak
- **PEP 8 standartlarını öğrenin**: Pythonic kod yazma alışkanlığı edinin
- **Community resources'larını takip edin**: Real Python, Python.org tutorials gibi kaynakları kullanın
- **Stack Overflow ve Python forums'larında aktif olun**: Soru sorun, başkalarının sorularını okuyun
- **Kod yazarken IDE'nin IntelliSense özelliklerinden faydalanın**: Auto-completion ve inline docs'ları kullanın
- **Debugging araçlarını öğrenin ve kullanın**: Print debugging'den ziyade proper debugger ve pdb kullanın
- **Virtual environment kullanın**: Her proje için ayrı sanal ortam oluşturun

### IDE Kullanım İpuçları
- **Kısayol tuşlarını öğrenin**: Her IDE için temel kısayolları ezberleyin (Ctrl+Shift+P, F12, Ctrl+., vs.)
- **Eklentileri aktif kullanın**: Python extension, Pylint, Black formatter gibi eklentiler geliştirmeyi dramatik şekilde kolaylaştırır
- **Debugging araçlarını kullanın**: Breakpoint, step-through, variable inspection gibi özellikleri öğrenin
- **Git entegrasyonunu kullanın**: IDE içinden commit, push, merge işlemlerini yapın
- **Workspace ayarlarını optimize edin**: Her proje için uygun ayarları yapılandırın
- **Code formatting**: Black veya autopep8'i otomatik çalışacak şekilde ayarlayın
- **Linting**: Pylint, Flake8, mypy'yi IDE'ye entegre edin, uyarıları ciddiye alın
- **Type hints kullanın**: Modern Python geliştirmede tip belirtmeyi alışkanlık haline getirin

### Değerlendirme Soruları
Her seviye sonunda kendinizi test etmek için şu soruları sorun:
- "Bu konuyu hiç programlama bilmeyen birine nasıl açıklardım?"
- "Bu kavramı kullanarak küçük ama anlamlı bir program yazabilir miyim?"
- "Bu konunun daha önce öğrendiğim kavramlarla bağlantısı nedir?"
- "Gerçek dünya projelerinde bu nasıl ve ne zaman kullanılır?"
- "IDE'mde bu konuyla ilgili hangi özellikleri kullanabilirim?"
- "Bu kodu daha Pythonic hale nasıl getirebilirim?"
- "Bu konseptin performans açısından implications'ları nelerdir?"

### Proje Bazlı Öğrenme
Her seviyede şunları yapın:
- Küçük demo projeler oluşturun
- Önceki seviyelerden kavramları kombine edin
- GitHub'da kod paylaşın ve review isteyin
- Başkalarının kodlarını okuyun ve anlamaya çalışın
- Open source projelere katkıda bulunmayı hedefleyin

---

## Seviye 1: Temel Kavramlar ve Başlangıç

### 1.1 Programlama ve Python'a Giriş

#### Soru 1
```
"Programlama nedir? Hiç programlama bilmeyen birinin anlayacağı şekilde açıkla"
```

#### Soru 2
```
"Python programlama dili nedir ve neden önemlidir?"
```

#### Soru 3
```
"Python programlama dilinin diğer programlama dillerinden farkları nelerdir?"
```

#### Soru 4
```
"Python programlama dili hangi alanlarda kullanılır? Örneklerle açıkla"
```

#### Soru 5
```
"Python'un 'batteries included' felsefesi ne demektir?"
```

#### Soru 6
```
"Python interpreter nedir? Nasıl çalışır?"
```

#### Soru 7
```
"Python 2 vs Python 3 arasındaki temel farklar nelerdir? Neden Python 3 kullanmalıyım?"
```

### 1.2 Python Kurulumu ve Geliştirme Ortamı

#### 1.2.1 Windows İçin Python Kurulumu

#### Soru 8
```
"Windows'ta Python nasıl kurulur? Python.org'dan indirme ve kurulum adımları"
```

#### Soru 9
```
"Windows'ta PATH environment variable'ı nedir? Python için nasıl ayarlanır?"
```

#### Soru 10
```
"Windows'ta Python IDLE nedir? Nasıl kullanılır?"
```

#### Soru 11
```
"Windows'ta Command Prompt ve PowerShell'de Python nasıl çalıştırılır?"
```

#### Soru 12
```
"Windows'ta pip nedir? Package installation nasıl yapılır?"
```

#### 1.2.2 Linux İçin Python Kurulumu

#### Soru 13
```
"Linux'ta Python nasıl kurulur? (Ubuntu, Debian, Fedora, Arch için ayrı talimatlar)"
```

#### Soru 14
```
"Linux'ta system Python vs user Python arasındaki fark nedir?"
```

#### Soru 15
```
"Linux'ta python vs python3 command'ları arasındaki fark nedir?"
```

#### Soru 16
```
"Linux'ta pip3 ve package management nasıl çalışır?"
```

#### Soru 17
```
"Linux'ta terminal'de Python interactive shell nasıl kullanılır?"
```

#### 1.2.3 macOS İçin Python Kurulumu

#### Soru 18
```
"macOS'ta Python nasıl kurulur? (Homebrew, Python.org, pyenv ile farklı yöntemler)"
```

#### Soru 19
```
"macOS'ta system Python vs custom Python arasındaki fark nedir?"
```

#### Soru 20
```
"macOS'ta Terminal'de Python nasıl çalıştırılır?"
```

#### Soru 21
```
"macOS'ta pip ve package management nasıl çalışır?"
```

### 1.3 IDE ve Text Editor Seçimi

#### 1.3.1 Visual Studio Code ile Python

#### Soru 22
```
"VS Code'a Python extension nasıl kurulur ve yapılandırılır?"
```

#### Soru 23
```
"VS Code'da Python interpreter nasıl seçilir?"
```

#### Soru 24
```
"VS Code'da Python kodu nasıl çalıştırılır? (Run button, terminal, debug)"
```

#### Soru 25
```
"VS Code'da Python için yararlı eklentiler nelerdir? (Pylint, Black, Python Docstring Generator)"
```

#### Soru 26
```
"VS Code'da Python debugging nasıl yapılır?"
```

#### 1.3.2 PyCharm IDE

#### Soru 27
```
"PyCharm Community Edition nasıl kurulur ve yapılandırılır?"
```

#### Soru 28
```
"PyCharm'da yeni Python project nasıl oluşturulur?"
```

#### Soru 29
```
"PyCharm'da Python interpreter nasıl ayarlanır?"
```

#### Soru 30
```
"PyCharm'da debugging özellikleri nasıl kullanılır?"
```

#### 1.3.3 Jupyter Notebook

#### Soru 31
```
"Jupyter Notebook nedir? Nasıl kurulur ve çalıştırılır?"
```

#### Soru 32
```
"Jupyter Notebook'ta Python kodu nasıl yazılır ve çalıştırılır?"
```

#### Soru 33
```
"Jupyter Notebook'ta markdown cells nasıl kullanılır?"
```

#### Soru 34
```
"JupyterLab vs Classic Notebook arasındaki fark nedir?"
```

#### 1.3.4 IDLE ve Python Shell

#### Soru 35
```
"Python IDLE nedir? Temel özellikleri nelerdir?"
```

#### Soru 36
```
"Python interactive shell (REPL) nasıl kullanılır?"
```

#### Soru 37
```
"IPython nedir? Python shell'den farkları nelerdir?"
```

### 1.4 Virtual Environment ve Package Management

#### Soru 38
```
"Virtual environment nedir? Neden kullanılır?"
```

#### Soru 39
```
"venv ile virtual environment nasıl oluşturulur ve kullanılır?"
```

#### Soru 40
```
"pip nedir? Temel pip komutları nelerdir?"
```

#### Soru 41
```
"requirements.txt dosyası nedir? Nasıl oluşturulur ve kullanılır?"
```

#### Soru 42
```
"conda vs pip arasındaki fark nedir?"
```

### 1.5 İlk Python Programı

#### Soru 43
```
"İlk Python programımı nasıl yazarım ve çalıştırırım? (Tüm işletim sistemleri için pratik örnekler)"
```

#### Soru 44
```
"Python dosyası (.py) nasıl oluşturulur ve çalıştırılır?"
```

#### Soru 45
```
"print() fonksiyonu nedir ve nasıl kullanılır?"
```

#### Soru 46
```
"Python'da syntax error'ları nasıl okurum ve düzeltirim?"
```

## Seviye 2: Temel Sözdizimi ve Veri Türleri

### 2.1 Temel Sözdizimi

#### Soru 47
```
"Python'da kod yazım kuralları nelerdir? (indentation, naming conventions)"
```

#### Soru 48
```
"Python'da yorum satırları nasıl yazılır? (# ve triple quotes)"
```

#### Soru 49
```
"Python'da docstring nedir? Nasıl yazılır?"
```

#### Soru 50
```
"PEP 8 nedir? Python kod stilinin temel kuralları nelerdir?"
```

#### Soru 51
```
"Python'da indentation (girinti) neden önemlidir? Nasıl kullanılır?"
```

#### Soru 52
```
"Python'da statement vs expression arasındaki fark nedir?"
```

### 2.2 Değişkenler ve Atama

#### Soru 53
```
"Değişken nedir? Programlama bilgisi olmayan birinin anlayacağı şekilde açıkla"
```

#### Soru 54
```
"Python'da değişken nasıl tanımlanır ve kullanılır?"
```

#### Soru 55
```
"Python'da değişken isimlendirme kuralları nelerdir?"
```

#### Soru 56
```
"Python'da multiple assignment nasıl yapılır? (a, b = 1, 2)"
```

#### Soru 57
```
"Python'da değişken scope nedir? Global vs local variables"
```

#### Soru 58
```
"Python'da id() fonksiyonu nedir? Object identity nasıl çalışır?"
```

### 2.3 Temel Veri Türleri

#### Soru 59
```
"Python'da veri türü nedir? type() fonksiyonu nasıl kullanılır?"
```

#### Soru 60
```
"Python'da numeric türler nelerdir? (int, float, complex)"
```

#### Soru 61
```
"Python'da string nedir? Nasıl tanımlanır? (single, double, triple quotes)"
```

#### Soru 62
```
"Python'da boolean türü nedir? True/False değerleri"
```

#### Soru 63
```
"Python'da None değeri nedir? Ne zaman kullanılır?"
```

#### Soru 64
```
"Python'da type conversion (casting) nasıl yapılır? int(), str(), float()"
```

### 2.4 String İşlemleri

#### Soru 65
```
"Python'da string concatenation nasıl yapılır?"
```

#### Soru 66
```
"Python'da string formatting nasıl yapılır? (%, .format(), f-strings)"
```

#### Soru 67
```
"Python'da string indexing ve slicing nasıl çalışır?"
```

#### Soru 68
```
"Python'da temel string metotları nelerdir? (upper(), lower(), strip(), split())"
```

#### Soru 69
```
"Python'da escape characters nelerdir? (\n, \t, \\, \", \')"
```

#### Soru 70
```
"Python'da raw strings (r"") ne zaman kullanılır?"
```

### 2.5 Sayısal İşlemler

#### Soru 71
```
"Python'da temel aritmetik operatörler nelerdir? (+, -, *, /, //, %, **)"
```

#### Soru 72
```
"Python'da / vs // operatörü arasındaki fark nedir?"
```

#### Soru 73
```
"Python'da modulo (%) operatörü ne işe yarar?"
```

#### Soru 74
```
"Python'da üslü sayı (**) nasıl hesaplanır?"
```

#### Soru 75
```
"Python'da math modülü nedir? Temel math fonksiyonları nelerdir?"
```

## Seviye 3: Operatörler ve Karşılaştırmalar

### 3.1 Karşılaştırma Operatörleri

#### Soru 76
```
"Python'da karşılaştırma operatörleri nelerdir? (==, !=, <, >, <=, >=)"
```

#### Soru 77
```
"Python'da == vs is arasındaki fark nedir?"
```

#### Soru 78
```
"Python'da chained comparisons nasıl çalışır? (1 < x < 10)"
```

#### Soru 79
```
"Python'da in operatörü nasıl kullanılır?"
```

### 3.2 Logical Operatörleri

#### Soru 80
```
"Python'da logical operatörler nelerdir? (and, or, not)"
```

#### Soru 81
```
"Python'da truth values nedir? Hangi değerler False kabul edilir?"
```

#### Soru 82
```
"Python'da short-circuit evaluation nedir?"
```

### 3.3 Assignment Operatörleri

#### Soru 83
```
"Python'da assignment operatörleri nelerdir? (+=, -=, *=, /=)"
```

#### Soru 84
```
"Python'da walrus operator (:=) nedir? Python 3.8+"
```

## Seviye 4: Kontrol Yapıları

### 4.1 Koşullu İfadeler

#### Soru 85
```
"Koşullu ifade nedir? Günlük hayattan örneklerle açıkla"
```

#### Soru 86
```
"Python'da if statement nasıl kullanılır?"
```

#### Soru 87
```
"Python'da elif nasıl kullanılır?"
```

#### Soru 88
```
"Python'da else nasıl kullanılır?"
```

#### Soru 89
```
"Python'da nested if statements nasıl yazılır?"
```

#### Soru 90
```
"Python'da ternary operator (conditional expression) nedir?"
```

### 4.2 Döngüler

#### Soru 91
```
"Döngü nedir? Neden kullanılır?"
```

#### Soru 92
```
"Python'da for loop nasıl kullanılır?"
```

#### Soru 93
```
"Python'da range() fonksiyonu nedir? Nasıl kullanılır?"
```

#### Soru 94
```
"Python'da while loop nasıl kullanılır?"
```

#### Soru 95
```
"Python'da break ve continue anahtar kelimeleri ne işe yarar?"
```

#### Soru 96
```
"Python'da for-else ve while-else nasıl çalışır?"
```

#### Soru 97
```
"Python'da nested loops nasıl yazılır?"
```

#### Soru 98
```
"Python'da infinite loop nedir? Nasıl önlenir?"
```

## Seviye 5: Veri Yapıları (Collections)

### 5.1 Lists (Listeler)

#### Soru 99
```
"Python'da list nedir? Nasıl oluşturulur?"
```

#### Soru 100
```
"Python'da list indexing nasıl çalışır? Negative indexing nedir?"
```

#### Soru 101
```
"Python'da list slicing nasıl yapılır?"
```

#### Soru 102
```
"Python'da list'e eleman nasıl eklenir? (append, insert, extend)"
```

#### Soru 103
```
"Python'da list'ten eleman nasıl çıkarılır? (remove, pop, del)"
```

#### Soru 104
```
"Python'da list comprehension nedir? Nasıl kullanılır?"
```

#### Soru 105
```
"Python'da list'te arama nasıl yapılır? (in, index, count)"
```

#### Soru 106
```
"Python'da list sorting nasıl yapılır? (sort vs sorted)"
```

#### Soru 107
```
"Python'da list copying nasıl yapılır? Shallow vs deep copy"
```

### 5.2 Tuples

#### Soru 108
```
"Python'da tuple nedir? List'ten farkı nedir?"
```

#### Soru 109
```
"Python'da tuple nasıl oluşturulur?"
```

#### Soru 110
```
"Python'da tuple unpacking nedir?"
```

#### Soru 111
```
"Python'da named tuples nedir? collections.namedtuple"
```

### 5.3 Dictionaries

#### Soru 112
```
"Python'da dictionary nedir? Nasıl oluşturulur?"
```

#### Soru 113
```
"Python'da dictionary'e key-value pair nasıl eklenir?"
```

#### Soru 114
```
"Python'da dictionary'den değer nasıl okunur? ([], get())"
```

#### Soru 115
```
"Python'da dictionary'den eleman nasıl silinir? (del, pop, clear)"
```

#### Soru 116
```
"Python'da dictionary methods nelerdir? (keys, values, items)"
```

#### Soru 117
```
"Python'da dictionary comprehension nasıl kullanılır?"
```

#### Soru 118
```
"Python'da dictionary'lerde iteration nasıl yapılır?"
```

### 5.4 Sets

#### Soru 119
```
"Python'da set nedir? Ne zaman kullanılır?"
```

#### Soru 120
```
"Python'da set nasıl oluşturulur?"
```

#### Soru 121
```
"Python'da set operations nelerdir? (union, intersection, difference)"
```

#### Soru 122
```
"Python'da frozenset nedir?"
```

#### Soru 123
```
"Python'da set comprehension nasıl kullanılır?"
```

## Seviye 6: Fonksiyonlar

### 6.1 Fonksiyon Temelleri

#### Soru 124
```
"Fonksiyon nedir? Neden önemlidir?"
```

#### Soru 125
```
"Python'da fonksiyon nasıl tanımlanır? def keyword"
```

#### Soru 126
```
"Python'da fonksiyon parametreleri nasıl tanımlanır?"
```

#### Soru 127
```
"Python'da fonksiyon nasıl çağrılır?"
```

#### Soru 128
```
"Python'da return statement nasıl kullanılır?"
```

#### Soru 129
```
"Python'da fonksiyon birden fazla değer nasıl döndürür?"
```

### 6.2 Parametre Türleri

#### Soru 130
```
"Python'da positional arguments nedir?"
```

#### Soru 131
```
"Python'da keyword arguments nedir?"
```

#### Soru 132
```
"Python'da default parameters nasıl tanımlanır?"
```

#### Soru 133
```
"Python'da *args nedir? Variable-length arguments"
```

#### Soru 134
```
"Python'da **kwargs nedir? Keyword variable-length arguments"
```

#### Soru 135
```
"Python'da argument unpacking nasıl yapılır? (*list, **dict)"
```

### 6.3 İleri Fonksiyon Konuları

#### Soru 136
```
"Python'da local vs global variables nedir?"
```

#### Soru 137
```
"Python'da global keyword ne işe yarar?"
```

#### Soru 138
```
"Python'da nonlocal keyword nedir?"
```

#### Soru 139
```
"Python'da lambda functions nedir? Nasıl kullanılır?"
```

#### Soru 140
```
"Python'da nested functions nedir?"
```

#### Soru 141
```
"Python'da closure nedir?"
```

#### Soru 142
```
"Python'da decorator nedir? Temel decorator kullanımı"
```

### 6.4 Built-in Functions

#### Soru 143
```
"Python'da map() fonksiyonu nedir? Nasıl kullanılır?"
```

#### Soru 144
```
"Python'da filter() fonksiyonu nedir?"
```

#### Soru 145
```
"Python'da reduce() fonksiyonu nedir? functools.reduce"
```

#### Soru 146
```
"Python'da zip() fonksiyonu ne işe yarar?"
```

#### Soru 147
```
"Python'da enumerate() fonksiyonu nasıl kullanılır?"
```

#### Soru 148
```
"Python'da sorted() vs list.sort() arasındaki fark nedir?"
```

## Seviye 7: Dosya İşlemleri ve I/O

### 7.1 Dosya Okuma/Yazma

#### Soru 149
```
"Python'da dosya nasıl açılır? open() fonksiyonu"
```

#### Soru 150
```
"Python'da dosya okuma modları nelerdir? (r, w, a, x)"
```

#### Soru 151
```
"Python'da dosyadan nasıl okuma yapılır? (read, readline, readlines)"
```

#### Soru 152
```
"Python'da dosyaya nasıl yazılır? (write, writelines)"
```

#### Soru 153
```
"Python'da with statement nedir? Context manager olarak dosya işlemleri"
```

#### Soru 154
```
"Python'da binary dosyalar nasıl işlenir?"
```

### 7.2 Dosya Sistemi İşlemleri

#### Soru 155
```
"Python'da os modülü nedir? Temel dosya sistemi işlemleri"
```

#### Soru 156
```
"Python'da pathlib modülü nedir? Modern path operations"
```

#### Soru 157
```
"Python'da directory operations nasıl yapılır? (mkdir, rmdir, listdir)"
```

#### Soru 158
```
"Python'da file path operations nasıl yapılır?"
```

### 7.3 JSON ve CSV İşlemleri

#### Soru 159
```
"Python'da JSON nedir? json modülü nasıl kullanılır?"
```

#### Soru 160
```
"Python'da CSV dosyaları nasıl işlenir? csv modülü"
```

## Seviye 8: Hata Yönetimi (Exception Handling)

### 8.1 Exception Temelleri

#### Soru 161
```
"Python'da exception nedir? Hata türleri nelerdir?"
```

#### Soru 162
```
"Python'da try-except nasıl kullanılır?"
```

#### Soru 163
```
"Python'da specific exceptions nasıl yakalanır?"
```

#### Soru 164
```
"Python'da else clause try-except'te nasıl kullanılır?"
```

#### Soru 165
```
"Python'da finally clause ne işe yarar?"
```

### 8.2 Exception Handling Best Practices

#### Soru 166
```
"Python'da custom exceptions nasıl oluşturulur?"
```

#### Soru 167
```
"Python'da raise statement nasıl kullanılır?"
```

#### Soru 168
```
"Python'da exception chaining nedir?"
```

#### Soru 169
```
"Python'da logging vs print ile hata mesajları"
```

## Seviye 9: Modüller ve Paketler

### 9.1 Modül Temelleri

#### Soru 170
```
"Python'da modül nedir? Neden kullanılır?"
```

#### Soru 171
```
"Python'da modül nasıl oluşturulur?"
```

#### Soru 172
```
"Python'da import statement nasıl kullanılır?"
```

#### Soru 173
```
"Python'da from...import nasıl çalışır?"
```

#### Soru 174
```
"Python'da import aliasing nasıl yapılır?"
```

#### Soru 175
```
"Python'da __name__ == '__main__' nedir?"
```

### 9.2 Paketler

#### Soru 176
```
"Python'da package nedir? __init__.py dosyası"
```

#### Soru 177
```
"Python'da relative vs absolute imports"
```

#### Soru 178
```
"Python'da PYTHONPATH nedir?"
```

### 9.3 Standard Library

#### Soru 179
```
"Python standard library'den önemli modüller nelerdir?"
```

#### Soru 180
```
"datetime modülü nasıl kullanılır?"
```

#### Soru 181
```
"random modülü ile rastgele sayı üretimi"
```

#### Soru 182
```
"re modülü ile regular expressions"
```

#### Soru 183
```
"urllib modülü ile HTTP istekleri"
```

## Seviye 10: Nesne Yönelimli Programlama (OOP)

### 10.1 OOP Temelleri

#### Soru 184
```
"Nesne yönelimli programlama nedir? Neden kullanılır?"
```

#### Soru 185
```
"Python'da class nedir? Nasıl tanımlanır?"
```

#### Soru 186
```
"Python'da object nedir? Instance nasıl oluşturulur?"
```

#### Soru 187
```
"Python'da __init__ method nedir? Constructor"
```

#### Soru 188
```
"Python'da self parameter nedir?"
```

#### Soru 189
```
"Python'da instance variables vs class variables"
```

### 10.2 Methods ve Properties

#### Soru 190
```
"Python'da instance methods nasıl tanımlanır?"
```

#### Soru 191
```
"Python'da class methods nedir? @classmethod"
```

#### Soru 192
```
"Python'da static methods nedir? @staticmethod"
```

#### Soru 193
```
"Python'da property decorator nedir? Getter/setter"
```

### 10.3 Inheritance (Kalıtım)

#### Soru 194
```
"Python'da inheritance nedir? Nasıl kullanılır?"
```

#### Soru 195
```
"Python'da super() fonksiyonu ne işe yarar?"
```

#### Soru 196
```
"Python'da method overriding nedir?"
```

#### Soru 197
```
"Python'da multiple inheritance nasıl çalışır?"
```

#### Soru 198
```
"Python'da MRO (Method Resolution Order) nedir?"
```

### 10.4 Special Methods (Dunder Methods)

#### Soru 199
```
"Python'da special methods (__str__, __repr__) nelerdir?"
```

#### Soru 200
```
"Python'da operator overloading nasıl yapılır?"
```

#### Soru 201
```
"Python'da __len__, __getitem__ gibi container methods"
```

#### Soru 202
```
"Python'da context managers (__enter__, __exit__)"
```

### 10.5 Encapsulation ve Access Control

#### Soru 203
```
"Python'da encapsulation nedir? Private ve public members"
```

#### Soru 204
```
"Python'da naming conventions nelerdir? (_var, __var, __var__)"
```

#### Soru 205
```
"Python'da name mangling nedir? Double underscore ile başlayan attributeler"
```

#### Soru 206
```
"Python'da @property ile getter/setter nasıl oluşturulur?"
```

### 10.6 Polymorphism

#### Soru 207
```
"Polymorphism nedir? Python'da nasıl uygulanır?"
```

#### Soru 208
```
"Python'da duck typing nedir?"
```

#### Soru 209
```
"Python'da abstract base classes (ABC) nedir?"
```

#### Soru 210
```
"Python'da interfaces nasıl simüle edilir?"
```

---

## Seviye 11: İleri Python Konuları

### 11.1 Iterators ve Generators

#### Soru 211
```
"Python'da iterator nedir? Iterator protocol"
```

#### Soru 212
```
"Python'da __iter__ ve __next__ methods nasıl çalışır?"
```

#### Soru 213
```
"Python'da generator nedir? yield keyword"
```

#### Soru 214
```
"Python'da generator expressions nasıl kullanılır?"
```

#### Soru 215
```
"Python'da generator vs list comprehension performans farkı"
```

#### Soru 216
```
"Python'da itertools modülü nedir? Önemli fonksiyonları"
```

### 11.2 Decorators (İleri Seviye)

#### Soru 217
```
"Python'da decorator pattern nasıl çalışır? Mantığını açıkla"
```

#### Soru 218
```
"Python'da parametreli decorators nasıl yazılır?"
```

#### Soru 219
```
"Python'da class decorators nedir?"
```

#### Soru 220
```
"Python'da functools.wraps nedir? Neden kullanılır?"
```

#### Soru 221
```
"Python'da built-in decorators nelerdir? (@staticmethod, @classmethod, @property)"
```

### 11.3 Context Managers

#### Soru 222
```
"Python'da context manager nedir? with statement detayları"
```

#### Soru 223
```
"Python'da custom context manager nasıl yazılır?"
```

#### Soru 224
```
"Python'da contextlib modülü nedir? @contextmanager decorator"
```

#### Soru 225
```
"Python'da context manager ile resource management"
```

### 11.4 Metaclasses

#### Soru 226
```
"Python'da metaclass nedir? 'Classes are objects too' konsepti"
```

#### Soru 227
```
"Python'da type() fonksiyonunun iki kullanımı"
```

#### Soru 228
```
"Python'da custom metaclass nasıl oluşturulur?"
```

#### Soru 229
```
"Python'da __new__ vs __init__ arasındaki fark"
```

---

## Seviye 12: Fonksiyonel Programlama

### 12.1 Functional Programming Concepts

#### Soru 230
```
"Fonksiyonel programlama nedir? Python'da nasıl uygulanır?"
```

#### Soru 231
```
"Python'da first-class functions nedir?"
```

#### Soru 232
```
"Python'da higher-order functions nelerdir?"
```

#### Soru 233
```
"Python'da pure functions nedir? Side effects"
```

### 12.2 Advanced Functional Tools

#### Soru 234
```
"Python'da partial functions nedir? functools.partial"
```

#### Soru 235
```
"Python'da currying nedir? Nasıl implement edilir?"
```

#### Soru 236
```
"Python'da function composition nasıl yapılır?"
```

#### Soru 237
```
"Python'da operator modülü nedir? operator.add, operator.mul"
```

---

## Seviye 13: Concurrency ve Parallelism

### 13.1 Threading

#### Soru 238
```
"Python'da threading nedir? GIL (Global Interpreter Lock) problemi"
```

#### Soru 239
```
"Python'da threading modülü nasıl kullanılır?"
```

#### Soru 240
```
"Python'da thread synchronization nedir? Lock, RLock"
```

#### Soru 241
```
"Python'da thread communication nasıl yapılır? Queue"
```

#### Soru 242
```
"Python'da ThreadPoolExecutor nedir?"
```

### 13.2 Multiprocessing

#### Soru 243
```
"Python'da multiprocessing nedir? Threading'den farkı"
```

#### Soru 244
```
"Python'da Process class nasıl kullanılır?"
```

#### Soru 245
```
"Python'da inter-process communication nasıl yapılır?"
```

#### Soru 246
```
"Python'da ProcessPoolExecutor nedir?"
```

### 13.3 Asyncio

#### Soru 247
```
"Python'da asyncio nedir? Asynchronous programming"
```

#### Soru 248
```
"Python'da async/await keywords nasıl kullanılır?"
```

#### Soru 249
```
"Python'da coroutines nedir?"
```

#### Soru 250
```
"Python'da event loop nedir? asyncio.run()"
```

#### Soru 251
```
"Python'da asyncio.gather() vs asyncio.wait() farkı"
```

---

## Seviye 14: Testing

### 14.1 Unit Testing

#### Soru 252
```
"Unit testing nedir? Neden önemlidir?"
```

#### Soru 253
```
"Python'da unittest modülü nasıl kullanılır?"
```

#### Soru 254
```
"Python'da test case nasıl yazılır? TestCase class"
```

#### Soru 255
```
"Python'da assertion methods nelerdir? assertEqual, assertTrue"
```

#### Soru 256
```
"Python'da setUp ve tearDown methods ne işe yarar?"
```

### 14.2 PyTest

#### Soru 257
```
"pytest nedir? unittest'ten farkları nelerdir?"
```

#### Soru 258
```
"pytest ile test nasıl yazılır?"
```

#### Soru 259
```
"pytest fixtures nedir? @pytest.fixture"
```

#### Soru 260
```
"pytest parametrize nedir? @pytest.mark.parametrize"
```

### 14.3 Mocking

#### Soru 261
```
"Python'da mocking nedir? unittest.mock modülü"
```

#### Soru 262
```
"Python'da Mock objects nasıl kullanılır?"
```

#### Soru 263
```
"Python'da patch decorator nedir?"
```

### 14.4 Test Coverage

#### Soru 264
```
"Code coverage nedir? Python'da nasıl ölçülür?"
```

#### Soru 265
```
"coverage.py tool'u nasıl kullanılır?"
```

---

## Seviye 15: Performans ve Optimizasyon

### 15.1 Profiling

#### Soru 266
```
"Python'da code profiling nedir? cProfile modülü"
```

#### Soru 267
```
"Python'da timeit modülü nasıl kullanılır?"
```

#### Soru 268
```
"Python'da memory profiling nasıl yapılır?"
```

### 15.2 Optimization Techniques

#### Soru 269
```
"Python'da performans optimizasyonu için genel prensipler"
```

#### Soru 270
```
"Python'da list comprehension vs loops performans karşılaştırması"
```

#### Soru 271
```
"Python'da __slots__ nedir? Memory optimization"
```

#### Soru 272
```
"Python'da caching techniques nelerdir? functools.lru_cache"
```

### 15.3 Alternative Implementations

#### Soru 273
```
"PyPy nedir? CPython'dan farkı"
```

#### Soru 274
```
"Cython nedir? C extensions yazma"
```

#### Soru 275
```
"Numba nedir? JIT compilation"
```

---

## Seviye 16: Paket Geliştirme ve Dağıtım

### 16.1 Package Structure

#### Soru 276
```
"Python package structure nasıl organize edilir?"
```

#### Soru 277
```
"setup.py ve setup.cfg dosyaları nedir?"
```

#### Soru 278
```
"pyproject.toml nedir? Modern Python packaging"
```

#### Soru 279
```
"Python'da MANIFEST.in dosyası ne işe yarar?"
```

### 16.2 Virtual Environments (İleri)

#### Soru 280
```
"virtualenv vs venv vs conda farkları"
```

#### Soru 281
```
"pipenv nedir? Pipfile ve Pipfile.lock"
```

#### Soru 282
```
"poetry nedir? Modern dependency management"
```

### 16.3 Publishing Packages

#### Soru 283
```
"PyPI nedir? Package nasıl yayınlanır?"
```

#### Soru 284
```
"wheel format nedir? Source distribution vs wheel"
```

#### Soru 285
```
"semantic versioning nedir? Python'da version management"
```

---

## Seviye 17: Debugging ve Logging

### 17.1 Debugging Techniques

#### Soru 286
```
"Python'da debugging yaklaşımları nelerdir?"
```

#### Soru 287
```
"pdb debugger nasıl kullanılır?"
```

#### Soru 288
```
"IDE debugging tools nasıl kullanılır?"
```

#### Soru 289
```
"Python'da breakpoint() fonksiyonu nedir? (Python 3.7+)"
```

### 17.2 Logging

#### Soru 290
```
"Python'da logging nedir? print() vs logging"
```

#### Soru 291
```
"Python'da logging levels nelerdir?"
```

#### Soru 292
```
"Python'da logging configuration nasıl yapılır?"
```

#### Soru 293
```
"Python'da custom logger nasıl oluşturulur?"
```

#### Soru 294
```
"Python'da log formatting ve handlers"
```

---

## Seviye 18: Data Science ve Analysis Temelleri

### 18.1 NumPy Basics

#### Soru 295
```
"NumPy nedir? Python'da neden kullanılır?"
```

#### Soru 296
```
"NumPy array vs Python list performans farkı"
```

#### Soru 297
```
"NumPy array operations nasıl çalışır?"
```

#### Soru 298
```
"NumPy broadcasting nedir?"
```

### 18.2 Pandas Introduction

#### Soru 299
```
"Pandas nedir? Data analysis için neden önemli?"
```

#### Soru 300
```
"Pandas DataFrame ve Series nedir?"
```

#### Soru 301
```
"Pandas ile CSV dosyası nasıl okunur?"
```

#### Soru 302
```
"Pandas ile temel data manipulation işlemleri"
```

### 18.3 Matplotlib Basics

#### Soru 303
```
"Matplotlib nedir? Data visualization"
```

#### Soru 304
```
"Matplotlib ile temel plot nasıl oluşturulur?"
```

#### Soru 305
```
"Matplotlib ile different plot types (bar, scatter, histogram)"
```

---

## Seviye 19: Web Development Temelleri

### 19.1 HTTP ve Web Concepts

#### Soru 306
```
"HTTP protocol nedir? Request/Response cycle"
```

#### Soru 307
```
"Python'da HTTP requests nasıl yapılır? requests library"
```

#### Soru 308
```
"REST API nedir? Python ile API consumption"
```

### 19.2 Flask Introduction

#### Soru 309
```
"Flask nedir? Micro web framework"
```

#### Soru 310
```
"Flask ile basit web application nasıl oluşturulur?"
```

#### Soru 311
```
"Flask routing nasıl çalışır?"
```

#### Soru 312
```
"Flask templates (Jinja2) nasıl kullanılır?"
```

### 19.3 Django Basics

#### Soru 313
```
"Django nedir? Full-stack web framework"
```

#### Soru 314
```
"Django project structure nasıldır?"
```

#### Soru 315
```
"Django models, views, templates (MVT pattern)"
```

---

## Seviye 20: Database İşlemleri

### 20.1 SQL Basics with Python

#### Soru 316
```
"SQL nedir? Python'da database connectivity"
```

#### Soru 317
```
"sqlite3 modülü nasıl kullanılır?"
```

#### Soru 318
```
"Python'da SQL injection nasıl önlenir?"
```

### 20.2 ORM (Object-Relational Mapping)

#### Soru 319
```
"ORM nedir? SQLAlchemy introduction"
```

#### Soru 320
```
"Python'da database models nasıl tanımlanır?"
```

---

## Proje Önerileri ve Pratik Uygulamalar

### Başlangıç Projeleri (Seviye 1-5)
- **Hesap Makinesi**: Temel operatörler ve fonksiyonlar
- **Kelime Sayacı**: String işlemleri ve dosya okuma
- **Sayı Tahmin Oyunu**: Döngüler ve koşullu ifadeler
- **Todo List**: Lists ve basic CRUD operations
- **Basit Quiz Uygulaması**: Dictionaries ve control flow

### Orta Seviye Projeler (Seviye 6-10)
- **Dosya Organizatörü**: File operations ve os modülü
- **Web Scraper**: requests ve BeautifulSoup
- **Password Generator**: random modülü ve string operations
- **Expense Tracker**: OOP principles ve file handling
- **Simple Calculator GUI**: tkinter ile GUI

### İleri Seviye Projeler (Seviye 11-15)
- **Chat Application**: asyncio ve networking
- **API Server**: Flask/FastAPI ile RESTful API
- **Data Analysis Tool**: pandas ve matplotlib
- **Testing Framework**: unittest ve pytest
- **Package Development**: Kendi Python package'ınızı oluşturun

### Uzman Seviye Projeler (Seviye 16-20)
- **Microservice Architecture**: Multiple services with communication
- **Machine Learning Pipeline**: Data processing ve model training
- **Web Application**: Full-stack Django/Flask application
- **Performance Monitoring Tool**: Profiling ve optimization
- **Open Source Contribution**: GitHub'da mevcut projelere katkı

---

## Öğrenme Kaynakları ve Araçlar

### Online Platformlar
- **Interactive Learning**: Codecademy, DataCamp, Coursera
- **Practice Platforms**: HackerRank, LeetCode, Codewars
- **Documentation**: Python.org official docs
- **Community**: Stack Overflow, Reddit r/Python, Python Discord

### Kitap Önerileri
- **Başlangıç**: "Python Crash Course" - Eric Matthes
- **Orta Seviye**: "Effective Python" - Brett Slatkin
- **İleri Seviye**: "Fluent Python" - Luciano Ramalho
- **Data Science**: "Python for Data Analysis" - Wes McKinney

### Tools ve IDE Setup
- **IDE Configuration**: VS Code, PyCharm setup guides
- **Version Control**: Git ve GitHub kullanımı
- **Environment Management**: conda, pipenv, poetry
- **Code Quality**: Black, flake8, mypy integration

---

## Kariyer Yolları ve Specialization Alanları

### Backend Development
- Web frameworks (Django, Flask, FastAPI)
- Database design ve optimization
- API development ve microservices
- Cloud deployment (AWS, Azure, GCP)

### Data Science/Analytics
- NumPy, Pandas, Matplotlib mastery
- Machine Learning (scikit-learn, TensorFlow, PyTorch)
- Statistical analysis ve data visualization
- Big Data tools (Spark, Hadoop ecosystem)

### DevOps/Automation
- Infrastructure as Code (Terraform, Ansible)
- CI/CD pipelines
- Monitoring ve logging systems
- Container technologies (Docker, Kubernetes)

### AI/Machine Learning
- Deep Learning frameworks
- Computer Vision (OpenCV, PIL)
- Natural Language Processing (NLTK, spaCy)
- MLOps ve model deployment

---

## Son Tavsiyeler

### Sürekli Öğrenme
- **Daily Coding**: Her gün en az 30 dakika kod yazın
- **Code Review**: Başkalarının kodlarını inceleyin
- **Open Source**: GitHub'da active olun
- **Community Engagement**: Python meetup'larına katılın

### Best Practices
- **PEP 8 Compliance**: Kod stiline dikkat edin
- **Documentation**: Kodunuzu dokümante edin
- **Testing**: Test yazmayı alışkanlık haline getirin
- **Version Control**: Git kullanımını öğrenin

### Profesyonel Gelişim
- **Portfolio**: GitHub'da projelerinizi sergileyin
- **Blog Writing**: Öğrendiklerinizi paylaşın
- **Networking**: Python community'sine katılın
- **Continuous Learning**: Teknoloji trendlerini takip edin

Bu müfredat, Python programlama dilinde başlangıçtan uzman seviyeye kadar kapsamlı bir öğrenme yolu sunmaktadır. Her seviyede pratik projeler yaparak ve toplulukla etkileşimde bulunarak öğrenme sürecinizi hızlandırabilirsiniz.