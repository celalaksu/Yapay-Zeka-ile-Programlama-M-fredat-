# Rust Programlama Dili Müfredatı - Yapay Zeka Destekli Öğrenme

## Genel Öğrenme Yaklaşımı ve Öneriler

### Öğrenme Metodolojisi
Her seviyede aşağıdaki yaklaşımı benimseyin:
- **Teoriyi önce anlayın**: Kavramları tam olarak kavramadan kod yazmaya geçmeyin
- **Pratik örnekler yazın**: Her yeni kavram için mutlaka el ile kod yazın
- **Cargo ile yeni projeler oluşturun**: Her konuyu ayrı bir projede deneyimleyin
- **IDE'nizin özelliklerini aktif kullanın**: Tooling'i sadece text editor olarak değil, tam potansiyeliyle kullanın
- **Rust documentation'ını okuyun**: Official docs'lar en güvenilir kaynak
- **Community resources'larını takip edin**: Rust Book, Rust by Example gibi kaynakları kullanın
- **Stack Overflow ve Rust forums'larında aktif olun**: Soru sorun, başkalarının sorularını okuyun
- **Kod yazarken IDE'nin IntelliSense özelliklerinden faydalanın**: Auto-completion ve inline docs'ları kullanın
- **Debugging araçlarını öğrenin ve kullanın**: Print debugging'den ziyade proper debugger kullanın

### IDE Kullanım İpuçları
- **Kısayol tuşlarını öğrenin**: Her IDE için temel kısayolları ezberleyin (Ctrl+Shift+P, F12, Ctrl+., vs.)
- **Eklentileri aktif kullanın**: rust-analyzer gibi eklentiler Rust geliştirmeyi dramatik şekilde kolaylaştırır
- **Debugging araçlarını kullanın**: Breakpoint, step-through, variable inspection gibi özellikleri öğrenin
- **Git entegrasyonunu kullanın**: IDE içinden commit, push, merge işlemlerini yapın
- **Workspace ayarlarını optimize edin**: Her proje için uygun ayarları yapılandırın
- **Code formatting**: rustfmt'i otomatik çalışacak şekilde ayarlayın
- **Linting**: Clippy'yi IDE'ye entegre edin, uyarıları ciddiye alın

### Değerlendirme Soruları
Her seviye sonunda kendinizi test etmek için şu soruları sorun:
- "Bu konuyu hiç programlama bilmeyen birine nasıl açıklardım?"
- "Bu kavramı kullanarak küçük ama anlamlı bir program yazabilir miyim?"
- "Bu konunun daha önce öğrendiğim kavramlarla bağlantısı nedir?"
- "Gerçek dünya projelerinde bu nasıl ve ne zaman kullanılır?"
- "IDE'mde bu konuyla ilgili hangi özellikleri kullanabilirim?"
- "Bu konsepti ownership sistemi açısından nasıl değerlendiririm?"

### Proje Bazlı Öğrenme
Her seviyede şunları yapın:
- Küçük demo projeler oluşturun
- Önceki seviyelerden kavramları kombine edin
- GitHub'da kod paylaşın ve review isteyin
- Başkalarının kodlarını okuyun ve anlamaya çalışın

---

## Seviye 1: Temel Kavramlar ve Başlangıç

### 1.1 Programlama ve Rust'a Giriş

#### Soru 1
```
"Programlama nedir? Hiç programlama bilmeyen birinin anlayacağı şekilde açıkla"
```

#### Soru 2
```
"Rust programlama dili nedir ve neden önemlidir?"
```

#### Soru 3
```
"Rust programlama dilinin diğer programlama dillerinden farkları nelerdir?"
```

#### Soru 4
```
"Rust programlama dili hangi alanlarda kullanılır? Örneklerle açıkla"
```

#### Soru 5
```
"Rust programlama dilini bilgisayarıma nasıl kurarım? Adım adım anlat"
```

#### Soru 6
```
"Rust programlama dilinde, Cargo nedir ve ne işe yarar?"
```

### 1.2 Geliştirme Ortamı Kurulumu (IDE ve Araçlar)

#### 1.2.1 Windows İçin Geliştirme Ortamı

#### Soru 7
```
"Windows'ta Visual Studio Code nasıl kurulur? Adım adım kurulum rehberi"
```

#### Soru 8
```
"Windows'ta VS Code için gerekli Rust eklentileri nelerdir ve nasıl kurulur?"
- rust-analyzer eklentisi kurulumu
- CodeLLDB (debugging için) kurulumu
- Better TOML eklentisi kurulumu
- Error Lens eklentisi kurulumu
```

#### Soru 9
```
"Windows'ta VS Code ile Rust projesi nasıl oluşturulur?"
```

#### Soru 10
```
"Windows'ta VS Code'da ilk Rust programı nasıl yazılır ve çalıştırılır?"
```

#### Soru 11
```
"Windows'ta VS Code debugging özellikleri nasıl kullanılır?"
```

#### Soru 12
```
"Windows'ta terminal entegrasyonu nasıl yapılır?"
```

#### 1.2.2 Linux İçin Geliştirme Ortamı

#### Soru 13
```
"Linux'ta Visual Studio Code nasıl kurulur? (Ubuntu, Debian, Fedora, Arch için ayrı talimatlar)"
```

#### Soru 14
```
"Linux'ta VS Code için gerekli Rust eklentileri nelerdir ve nasıl kurulur?"
- rust-analyzer eklentisi kurulumu
- CodeLLDB (debugging için) kurulumu  
- Better TOML eklentisi kurulumu
- Error Lens eklentisi kurulumu
```

#### Soru 15
```
"Linux'ta VS Code ile Rust projesi nasıl oluşturulur?"
```

#### Soru 16
```
"Linux'ta VS Code'da ilk Rust programı nasıl yazılır ve çalıştırılır?"
```

#### Soru 17
```
"Linux'ta VS Code debugging özellikleri nasıl kullanılır?"
```

#### Soru 18
```
"Linux'ta terminal entegrasyonu ve zsh/bash konfigürasyonu"
```

#### 1.2.3 macOS İçin Geliştirme Ortamı

#### Soru 19
```
"macOS'ta Visual Studio Code nasıl kurulur? (Intel ve Apple Silicon Mac'ler için)"
```

#### Soru 20
```
"macOS'ta VS Code için gerekli Rust eklentileri nelerdir ve nasıl kurulur?"
- rust-analyzer eklentisi kurulumu
- CodeLLDB (debugging için) kurulumu
- Better TOML eklentisi kurulumu  
- Error Lens eklentisi kurulumu
```

#### Soru 21
```
"macOS'ta VS Code ile Rust projesi nasıl oluşturulur?"
```

#### Soru 22
```
"macOS'ta VS Code'da ilk Rust programı nasıl yazılır ve çalıştırılır?"
```

#### Soru 23
```
"macOS'ta VS Code debugging özellikleri nasıl kullanılır?"
```

#### Soru 24
```
"macOS'ta terminal entegrasyonu ve zsh konfigürasyonu"
```

#### 1.2.4 IDE Kullanım Temelleri ve İpuçları

#### Soru 25
```
"VS Code'da Rust için yararlı kısayol tuşları nelerdir?"
```

#### Soru 26
```
"IntelliSense ve kod tamamlama özellikleri nasıl kullanılır?"
```

#### Soru 27
```
"VS Code'da hata mesajları nasıl okunur ve anlaşılır?"
```

#### Soru 28
```
"VS Code'da refactoring araçları nasıl kullanılır?"
```

#### Soru 29
```
"VS Code'da Git entegrasyonu nasıl çalışır?"
```

#### Soru 30
```
"VS Code workspace ve settings konfigürasyonu nasıl yapılır?"
```

#### 1.2.5 Alternatif IDE'ler

#### Soru 31
```
"IntelliJ IDEA + Rust Plugin kurulumu nasıl yapılır?"
```

#### Soru 32
```
"CLion ile Rust geliştirme nasıl yapılır?"
```

#### Soru 33
```
"Vim/Neovim ile Rust geliştirme ortamı nasıl kurulur?"
```

#### Soru 34
```
"Emacs ile Rust geliştirme nasıl yapılır?"
```

#### Soru 35
```
"Hangi IDE hangi durumda tercih edilmelidir?"
```

### 1.3 İlk Rust Programı

#### Soru 36
```
"İlk Rust programımı nasıl yazarım ve çalıştırırım? (Tüm işletim sistemleri için pratik örnekler)"
```

#### Soru 37
```
"Hello World programını farklı IDE'lerde nasıl çalıştırırım?"
```

#### Soru 38
```
"Kod hatalarını IDE'de nasıl tespit ederim ve düzeltirim?"
```

### 1.4 Temel Sözdizimi

#### Soru 39
```
"Rust programlama dilinde, kod yazım kuralları nelerdir?"
```

#### Soru 40
```
"Rust programlama dilinde, yorum satırları nasıl yazılır?"
```

#### Soru 41
```
"Rust programlama dilinde, main fonksiyonu nedir ve neden önemlidir?"
```

#### Soru 42
```
"Rust programlama dilinde, println! makrosu nedir ve nasıl kullanılır?"
```

#### Soru 43
```
"Rust programlama dilinde, kod blokları nasıl oluşturulur?"
```

## Seviye 2: Değişkenler ve Veri Türleri

### 2.1 Değişkenler

#### Soru 44
```
"Değişken nedir? Programlama bilgisi olmayan birinin anlayacağı şekilde açıkla"
```

#### Soru 45
```
"Değişken neden kullanılır? Günlük hayattan örneklerle açıkla"
```

#### Soru 46
```
"Rust programlama dilinde, değişken nasıl oluşturulur?"
```

#### Soru 47
```
"Rust programlama dilinde, let anahtar kelimesi ne işe yarar?"
```

#### Soru 48
```
"Rust programlama dilinde, değişken isimlendirme kuralları nelerdir?"
```

#### Soru 49
```
"Rust programlama dilinde, değişkenler neden varsayılan olarak değiştirilemez?"
```

#### Soru 50
```
"Rust programlama dilinde, mut anahtar kelimesi ne işe yarar?"
```

#### Soru 51
```
"Rust programlama dilinde, değişken gölgeleme (shadowing) nedir?"
```

#### Soru 52
```
"Rust programlama dilinde, değişken tanımlarken ownership nasıl çalışır? let x = 5 ile let y = x arasındaki fark nedir?"
```

#### Soru 53
```
"Rust programlama dilinde, String değişkeni başka bir değişkene atarken ne olur? Ownership transfer edilir mi?"
```

#### Soru 54
```
"Rust programlama dilinde, Copy türleri ile non-Copy türleri değişken atamasında nasıl farklı davranır?"
```

#### Soru 55
```
"Rust programlama dilinde, değişken atamasında move vs copy ne zaman oluşur?"
```

### 2.2 Veri Türleri

#### Soru 56
```
"Veri türü nedir? Neden önemlidir?"
```

#### Soru 57
```
"Rust programlama dilinde, temel veri türleri nelerdir?"
```

#### Soru 58
```
"Rust programlama dilinde, tam sayı türleri nelerdir? (i8, i16, i32, i64, u8, u16, u32, u64)"
```

#### Soru 59
```
"Rust programlama dilinde, ondalıklı sayı türleri nelerdir? (f32, f64)"
```

#### Soru 60
```
"Rust programlama dilinde, Boolean türü nedir ve nasıl kullanılır?"
```

#### Soru 61
```
"Rust programlama dilinde, karakter (char) türü nedir?"
```

#### Soru 62
```
"Rust programlama dilinde, String ve &str arasındaki fark nedir?"
```

#### Soru 63
```
"Rust programlama dilinde, tür çıkarımı (type inference) nedir?"
```

#### Soru 64
```
"Rust programlama dilinde, tür dönüşümü nasıl yapılır?"
```

#### Soru 65
```
"Rust programlama dilinde, hangi veri türleri Copy trait'ini implement eder? Bu ownership açısından ne anlama gelir?"
```

#### Soru 66
```
"Rust programlama dilinde, String gibi heap-allocated türlerin ownership'i nasıl çalışır?"
```

#### Soru 67
```
"Rust programlama dilinde, primitive türlerin stack'te saklanması ownership'i nasıl etkiler?"
```

## Seviye 3: Kontrol Yapıları

### 3.1 Koşullu İfadeler

#### Soru 68
```
"Koşullu ifade nedir? Günlük hayattan örneklerle açıkla"
```

#### Soru 69
```
"Rust programlama dilinde, if ifadesi nasıl kullanılır?"
```

#### Soru 70
```
"Rust programlama dilinde, else if nasıl kullanılır?"
```

#### Soru 71
```
"Rust programlama dilinde, else nasıl kullanılır?"
```

#### Soru 72
```
"Rust programlama dilinde, if ifadesi nasıl değer döndürür?"
```

#### Soru 73
```
"Rust programlama dilinde, if koşulunda değişken kullanırken ownership nasıl etkilenir?"
```

#### Soru 74
```
"Rust programlama dilinde, if bloğu içinde tanımlanan değişkenlerin ownership'i nasıl çalışır?"
```

#### Soru 75
```
"Rust programlama dilinde, koşullu ifadelerde String gibi owned değerleri nasıl kullanırız?"
```

#### Soru 76
```
"Rust programlama dilinde, if ifadesinde reference (&) kullanımı ne zaman gereklidir?"
```

#### Soru 77
```
"Rust programlama dilinde, match guard'larda borrowing nasıl çalışır?"
```

### 3.2 Döngüler

#### Soru 78
```
"Döngü nedir? Neden kullanılır?"
```

#### Soru 79
```
"Rust programlama dilinde, loop döngüsü nasıl kullanılır?"
```

#### Soru 80
```
"Rust programlama dilinde, while döngüsü nasıl kullanılır?"
```

#### Soru 81
```
"Rust programlama dilinde, for döngüsü nasıl kullanılır?"
```

#### Soru 82
```
"Rust programlama dilinde, Range (..) operatörü nedir?"
```

#### Soru 83
```
"Rust programlama dilinde, break ve continue anahtar kelimeleri ne işe yarar?"
```

#### Soru 84
```
"Rust programlama dilinde, döngü etiketleri (loop labels) nasıl kullanılır?"
```

#### Soru 85
```
"Rust programlama dilinde, for döngüsünde iterator ownership'i nasıl çalışır?"
```

#### Soru 86
```
"Rust programlama dilinde, vec.into_iter() vs vec.iter() vs vec.iter_mut() arasındaki ownership farkları nelerdir?"
```

#### Soru 87
```
"Rust programlama dilinde, döngü içinde değişken modify ederken borrowing kuralları nasıl uygulanır?"
```

#### Soru 88
```
"Rust programlama dilinde, döngü değişkeninin scope'u ve ownership'i nasıl çalışır?"
```

#### Soru 89
```
"Rust programlama dilinde, nested loop'larda içteki döngüden dıştaki değişkene erişirken borrowing nasıl olur?"
```

#### Soru 90
```
"Rust programlama dilinde, while let döngüsünde pattern matching ile ownership nasıl transfer edilir?"
```

## Seviye 4: Fonksiyonlar

### 4.1 Fonksiyon Temelleri

#### Soru 91
```
"Fonksiyon nedir? Neden önemlidir?"
```

#### Soru 92
```
"Rust programlama dilinde, fonksiyon nasıl tanımlanır?"
```

#### Soru 93
```
"Rust programlama dilinde, fn anahtar kelimesi ne işe yarar?"
```

#### Soru 94
```
"Rust programlama dilinde, fonksiyon parametreleri nasıl tanımlanır?"
```

#### Soru 95
```
"Rust programlama dilinde, fonksiyon nasıl çağrılır?"
```

#### Soru 96
```
"Rust programlama dilinde, return anahtar kelimesi nasıl kullanılır?"
```

#### Soru 97
```
"Rust programlama dilinde, fonksiyonlar nasıl değer döndürür?"
```

#### Soru 98
```
"Rust programlama dilinde, ifade (expression) ve deyim (statement) arasındaki fark nedir?"
```

#### Soru 99
```
"Rust programlama dilinde, fonksiyon parametrelerinde ownership nasıl çalışır?"
```

#### Soru 100
```
"Rust programlama dilinde, fonksiyona değer geçerken move mi copy mi olur?"
```

#### Soru 101
```
"Rust programlama dilinde, fonksiyon parametresi olarak reference (&T) ne zaman kullanılır?"
```

#### Soru 102
```
"Rust programlama dilinde, mutable reference (&mut T) fonksiyon parametresi olarak nasıl kullanılır?"
```

#### Soru 103
```
"Rust programlama dilinde, fonksiyondan ownership döndürmek ne zaman mantıklıdır?"
```

#### Soru 104
```
"Rust programlama dilinde, fonksiyondan reference döndürmenin kuralları nelerdir?"
```

#### Soru 105
```
"Rust programlama dilinde, dangling reference hatası fonksiyonlarda nasıl oluşur?"
```

### 4.2 İleri Fonksiyon Konuları

#### Soru 106
```
"Rust programlama dilinde, fonksiyon overloading mümkün mü?"
```

#### Soru 107
```
"Rust programlama dilinde, closures (anonim fonksiyonlar) nedir?"
```

#### Soru 108
```
"Rust programlama dilinde, higher-order functions nedir?"
```

#### Soru 109
```
"Rust programlama dilinde, closure'larda capture semantiği nasıl çalışır? (move, borrow)"
```

#### Soru 110
```
"Rust programlama dilinde, Fn, FnMut, FnOnce trait'lerinin ownership açısından farkları nelerdir?"
```

#### Soru 111
```
"Rust programlama dilinde, closure environment'ı nasıl capture edilir?"
```

## Seviye 5: Ownership Sistemi (Rust'ın Kalbi)

### 5.1 Ownership Temelleri

#### Soru 112
```
"Rust programlama dilinde, ownership nedir? Rust'ı diğer dillerden ayıran bu özellik neden önemlidir?"
```

#### Soru 113
```
"Memory management nedir? Stack ve heap arasındaki fark nedir?"
```

#### Soru 114
```
"Rust programlama dilinde, ownership kuralları nelerdir?"
```

#### Soru 115
```
"Rust programlama dilinde, bir değişkenin ownership'i nasıl transfer edilir?"
```

#### Soru 116
```
"Rust programlama dilinde, move semantiği nedir?"
```

#### Soru 117
```
"Rust programlama dilinde, Copy trait'i nedir? Hangi türler copy edilebilir?"
```

### 5.2 References ve Borrowing

#### Soru 118
```
"Rust programlama dilinde, reference (&) nedir? Nasıl kullanılır?"
```

#### Soru 119
```
"Rust programlama dilinde, borrowing nedir? Ownership'ten farkı nedir?"
```

#### Soru 120
```
"Rust programlama dilinde, mutable reference (&mut) nedir?"
```

#### Soru 121
```
"Rust programlama dilinde, borrowing kuralları nelerdir?"
```

#### Soru 122
```
"Rust programlama dilinde, dangling reference nedir? Rust nasıl engeller?"
```

#### Soru 123
```
"Rust programlama dilinde, reference'ların yaşam süresi (lifetime) nedir?"
```

### 5.3 Slices

#### Soru 124
```
"Rust programlama dilinde, slice nedir? Ne işe yarar?"
```

#### Soru 125
```
"Rust programlama dilinde, string slice (&str) nasıl kullanılır?"
```

#### Soru 126
```
"Rust programlama dilinde, array slice nasıl oluşturulur?"
```

## Seviye 6: Compound Data Types

### 6.1 Tuples

#### Soru 127
```
"Rust programlama dilinde, tuple nedir? Nasıl kullanılır?"
```

#### Soru 128
```
"Rust programlama dilinde, tuple elemanlarına nasıl erişilir?"
```

#### Soru 129
```
"Rust programlama dilinde, tuple destructuring nedir?"
```

### 6.2 Arrays

#### Soru 130
```
"Rust programlama dilinde, array nedir? Ne zaman kullanılır?"
```

#### Soru 131
```
"Rust programlama dilinde, array nasıl tanımlanır ve başlatılır?"
```

#### Soru 132
```
"Rust programlama dilinde, array elemanlarına nasıl erişilir?"
```

#### Soru 133
```
"Rust programlama dilinde, array ve Vector arasındaki fark nedir?"
```

### 6.3 Structs

#### Soru 134
```
"Rust programlama dilinde, struct nedir? Neden kullanılır?"
```

#### Soru 135
```
"Rust programlama dilinde, struct nasıl tanımlanır?"
```

#### Soru 136
```
"Rust programlama dilinde, struct instance'ı nasıl oluşturulur?"
```

#### Soru 137
```
"Rust programlama dilinde, struct field'larına nasıl erişilir?"
```

#### Soru 138
```
"Rust programlama dilinde, struct update syntax nedir?"
```

#### Soru 139
```
"Rust programlama dilinde, tuple struct nedir?"
```

#### Soru 140
```
"Rust programlama dilinde, unit struct nedir?"
```

#### Soru 141
```
"Rust programlama dilinde, struct'lara method nasıl eklenir?"
```

#### Soru 142
```
"Rust programlama dilinde, impl bloğu nedir?"
```

#### Soru 143
```
"Rust programlama dilinde, associated functions nedir?"
```

## Seviye 7: Enums ve Pattern Matching

### 7.1 Enums

#### Soru 144
```
"Rust programlama dilinde, enum nedir? Ne işe yarar?"
```

#### Soru 145
```
"Rust programlama dilinde, enum nasıl tanımlanır?"
```

#### Soru 146
```
"Rust programlama dilinde, enum variants nasıl kullanılır?"
```

#### Soru 147
```
"Rust programlama dilinde, enum'lara veri nasıl eklenir?"
```

#### Soru 148
```
"Rust programlama dilinde, Option enum'u nedir? Null safety nasıl sağlar?"
```

#### Soru 149
```
"Rust programlama dilinde, Result enum'u nedir? Error handling'de nasıl kullanılır?"
```

### 7.2 Pattern Matching

#### Soru 150
```
"Rust programlama dilinde, pattern matching nedir? Neden güçlü bir özellik?"
```

#### Soru 151
```
"Rust programlama dilinde, match ifadesi nasıl kullanılır?"
```

#### Soru 152
```
"Rust programlama dilinde, match arms nasıl yazılır?"
```

#### Soru 153
```
"Rust programlama dilinde, wildcard pattern (_) ne işe yarar?"
```

#### Soru 154
```
"Rust programlama dilinde, if let syntax'ı nedir?"
```

#### Soru 155
```
"Rust programlama dilinde, while let nasıl kullanılır?"
```

## Seviye 8: Collections

### 8.1 Vectors

#### Soru 156
```
"Rust programlama dilinde, Vector nedir? Array'den farkı nedir?"
```

#### Soru 157
```
"Rust programlama dilinde, Vector nasıl oluşturulur?"
```

#### Soru 158
```
"Rust programlama dilinde, Vector'e eleman nasıl eklenir?"
```

#### Soru 159
```
"Rust programlama dilinde, Vector elemanlarına nasıl erişilir?"
```

#### Soru 160
```
"Rust programlama dilinde, Vector üzerinde nasıl iterasyon yapılır?"
```

### 8.2 Strings

#### Soru 161
```
"Rust programlama dilinde, String ve &str arasındaki detaylı fark nedir?"
```

#### Soru 162
```
"Rust programlama dilinde, String nasıl oluşturulur ve manipüle edilir?"
```

#### Soru 163
```
"Rust programlama dilinde, String concatenation nasıl yapılır?"
```

#### Soru 164
```
"Rust programlama dilinde, String slicing nasıl çalışır?"
```

### 8.3 Hash Maps

#### Soru 165
```
"Rust programlama dilinde, HashMap nedir? Ne zaman kullanılır?"
```

#### Soru 166
```
"Rust programlama dilinde, HashMap nasıl oluşturulur?"
```

#### Soru 167
```
"Rust programlama dilinde, HashMap'e key-value pair nasıl eklenir?"
```

#### Soru 168
```
"Rust programlama dilinde, HashMap'ten değer nasıl okunur?"
```

## Seviye 9: Error Handling

### 9.1 Panic

#### Soru 169
```
"Rust programlama dilinde, panic nedir? Ne zaman oluşur?"
```

#### Soru 170
```
"Rust programlama dilinde, panic! makrosu nasıl kullanılır?"
```

#### Soru 171
```
"Rust programlama dilinde, recoverable ve unrecoverable error'lar nedir?"
```

### 9.2 Result Type

#### Soru 172
```
"Rust programlama dilinde, Result<T, E> nasıl kullanılır?"
```

#### Soru 173
```
"Rust programlama dilinde, error propagation nasıl yapılır?"
```

#### Soru 174
```
"Rust programlama dilinde, ? operatörü ne işe yarar?"
```

#### Soru 175
```
"Rust programlama dilinde, unwrap() ve expect() metotları nedir?"
```

#### Soru 176
```
"Rust programlama dilinde, custom error types nasıl oluşturulur?"
```

## Seviye 10: Generic Types ve Traits

### 10.1 Generics

#### Soru 177
```
"Rust programlama dilinde, generic type nedir? Neden kullanılır?"
```

#### Soru 178
```
"Rust programlama dilinde, generic function nasıl yazılır?"
```

#### Soru 179
```
"Rust programlama dilinde, generic struct nasıl tanımlanır?"
```

#### Soru 180
```
"Rust programlama dilinde, generic enum nasıl oluşturulur?"
```

#### Soru 181
```
"Rust programlama dilinde, type constraints nedir?"
```

### 10.2 Traits

#### Soru 182
```
"Rust programlama dilinde, trait nedir? Interface'lerden farkı nedir?"
```

#### Soru 183
```
"Rust programlama dilinde, trait nasıl tanımlanır?"
```

#### Soru 184
```
"Rust programlama dilinde, trait nasıl implement edilir?"
```

#### Soru 185
```
"Rust programlama dilinde, default implementations nedir?"
```

#### Soru 186
```
"Rust programlama dilinde, trait bounds nedir?"
```

#### Soru 187
```
"Rust programlama dilinde, trait objects nedir?"
```

#### Soru 188
```
"Rust programlama dilinde, common traits nelerdir? (Debug, Clone, Copy, etc.)"
```

## Seviye 11: Lifetimes (Detaylı)

### 11.1 Lifetime Basics

#### Soru 189
```
"Rust programlama dilinde, lifetime nedir? Reference'ların yaşam süresi neden önemlidir?"
```

#### Soru 190
```
"Rust programlama dilinde, lifetime annotation syntax'ı nasıldır? 'a nedir?"
```

#### Soru 191
```
"Rust programlama dilinde, lifetime parameter nedir? Generic type parameter'dan farkı nedir?"
```

#### Soru 192
```
"Rust programlama dilinde, lifetime elision rules nelerdir? Compiler ne zaman lifetime'ları otomatik çıkarır?"
```

#### Soru 193
```
"Rust programlama dilinde, function signature'larda lifetime nasıl specify edilir?"
```

### 11.2 Lifetime Annotations

#### Soru 194
```
"Rust programlama dilinde, lifetime annotation ne zaman gereklidir?"
```

#### Soru 195
```
"Rust programlama dilinde, multiple lifetime parameters (&'a str, &'b str) nasıl kullanılır?"
```

#### Soru 196
```
"Rust programlama dilinde, lifetime subtyping nedir? 'a: 'b ne demektir?"
```

#### Soru 197
```
"Rust programlama dilinde, input lifetimes ve output lifetimes arasındaki ilişki nedir?"
```

### 11.3 Struct ve Lifetime

#### Soru 198
```
"Rust programlama dilinde, struct field'larında lifetime nasıl kullanılır?"
```

#### Soru 199
```
"Rust programlama dilinde, struct definition'da lifetime parameter nasıl tanımlanır?"
```

#### Soru 200
```
"Rust programlama dilinde, self-referential struct'lar neden problemlidir?"
```

### 11.4 Advanced Lifetimes

#### Soru 201
```
"Rust programlama dilinde, static lifetime ('static) nedir? Ne zaman kullanılır?"
```

#### Soru 202
```
"Rust programlama dilinde, lifetime bounds nedir? T: 'a ne demektir?"
```

#### Soru 203
```
"Rust programlama dilinde, higher-ranked trait bounds (HRTB) nedir?"
```

#### Soru 204
```
"Rust programlama dilinde, lifetime'lar ile generic types nasıl kombine edilir?"
```

## Seviye 12: Testing

### 12.1 Unit Testing

#### Soru 205
```
"Rust programlama dilinde, test nasıl yazılır?"
```

#### Soru 206
```
"Rust programlama dilinde, #[test] attribute'u nedir?"
```

#### Soru 207
```
"Rust programlama dilinde, assert! makroları nasıl kullanılır?"
```

#### Soru 208
```
"Rust programlama dilinde, cargo test komutu nasıl çalışır?"
```

#### Soru 209
```
"Rust programlama dilinde, test organization nasıl yapılır?"
```

### 12.2 Integration Testing

#### Soru 210
```
"Rust programlama dilinde, integration test nedir?"
```

#### Soru 211
```
"Rust programlama dilinde, tests/ directory nasıl kullanılır?"
```

#### Soru 212
```
"Rust programlama dilinde, benchmark testing nasıl yapılır?"
```

## Seviye 13: I/O Operations

### 13.1 File Operations

#### Soru 213
```
"Rust programlama dilinde, file okuma/yazma nasıl yapılır?"
```