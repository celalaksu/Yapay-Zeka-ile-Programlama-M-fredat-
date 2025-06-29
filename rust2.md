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

**Soru 1:**
Programlama nedir? Hiç programlama bilmeyen birinin anlayacağı şekilde açıkla

**Soru 2:**
Rust programlama dili nedir ve neden önemlidir?

**Soru 3:**
Rust'ın diğer programlama dillerinden farkları nelerdir?

**Soru 4:**
Rust hangi alanlarda kullanılır? Örneklerle açıkla

**Soru 5:**
Rust'ı bilgisayarıma nasıl kurarım? Adım adım anlat

**Soru 6:**
Cargo nedir ve ne işe yarar?

### 1.2 Geliştirme Ortamı Kurulumu (IDE ve Araçlar)

#### 1.2.1 Windows İçin Geliştirme Ortamı

**Soru 7:**
Windows'ta Visual Studio Code nasıl kurulur? Adım adım kurulum rehberi

**Soru 8:**
Windows'ta VS Code için gerekli Rust eklentileri nelerdir ve nasıl kurulur? (rust-analyzer, CodeLLDB, Better TOML, Error Lens)

**Soru 9:**
Windows'ta VS Code ile Rust projesi nasıl oluşturulur?

**Soru 10:**
Windows'ta VS Code'da ilk Rust programı nasıl yazılır ve çalıştırılır?

**Soru 11:**
Windows'ta VS Code debugging özellikleri nasıl kullanılır?

**Soru 12:**
Windows'ta terminal entegrasyonu nasıl yapılır?

#### 1.2.2 Linux İçin Geliştirme Ortamı

**Soru 13:**
Linux'ta Visual Studio Code nasıl kurulur? (Ubuntu, Debian, Fedora, Arch için ayrı talimatlar)

**Soru 14:**
Linux'ta VS Code için gerekli Rust eklentileri nelerdir ve nasıl kurulur? (rust-analyzer, CodeLLDB, Better TOML, Error Lens)

**Soru 15:**
Linux'ta VS Code ile Rust projesi nasıl oluşturulur?

**Soru 16:**
Linux'ta VS Code'da ilk Rust programı nasıl yazılır ve çalıştırılır?

**Soru 17:**
Linux'ta VS Code debugging özellikleri nasıl kullanılır?

**Soru 18:**
Linux'ta terminal entegrasyonu ve zsh/bash konfigürasyonu

#### 1.2.3 macOS İçin Geliştirme Ortamı

**Soru 19:**
macOS'ta Visual Studio Code nasıl kurulur? (Intel ve Apple Silicon Mac'ler için)

**Soru 20:**
macOS'ta VS Code için gerekli Rust eklentileri nelerdir ve nasıl kurulur? (rust-analyzer, CodeLLDB, Better TOML, Error Lens)

**Soru 21:**
macOS'ta VS Code ile Rust projesi nasıl oluşturulur?

**Soru 22:**
macOS'ta VS Code'da ilk Rust programı nasıl yazılır ve çalıştırılır?

**Soru 23:**
macOS'ta VS Code debugging özellikleri nasıl kullanılır?

**Soru 24:**
macOS'ta terminal entegrasyonu ve zsh konfigürasyonu

#### 1.2.4 IDE Kullanım Temelleri ve İpuçları

**Soru 25:**
VS Code'da Rust için yararlı kısayol tuşları nelerdir?

**Soru 26:**
IntelliSense ve kod tamamlama özellikleri nasıl kullanılır?

**Soru 27:**
VS Code'da hata mesajları nasıl okunur ve anlaşılır?

**Soru 28:**
VS Code'da refactoring araçları nasıl kullanılır?

**Soru 29:**
VS Code'da Git entegrasyonu nasıl çalışır?

**Soru 30:**
VS Code workspace ve settings konfigürasyonu nasıl yapılır?

#### 1.2.5 Alternatif IDE'ler

**Soru 31:**
IntelliJ IDEA + Rust Plugin kurulumu nasıl yapılır?

**Soru 32:**
CLion ile Rust geliştirme nasıl yapılır?

**Soru 33:**
Vim/Neovim ile Rust geliştirme ortamı nasıl kurulur?

**Soru 34:**
Emacs ile Rust geliştirme nasıl yapılır?

**Soru 35:**
Hangi IDE hangi durumda tercih edilmelidir?

### 1.3 İlk Rust Programı

**Soru 36:**
İlk Rust programımı nasıl yazarım ve çalıştırırım? (Tüm işletim sistemleri için pratik örnekler)

**Soru 37:**
Hello World programını farklı IDE'lerde nasıl çalıştırırım?

**Soru 38:**
Kod hatalarını IDE'de nasıl tespit ederim ve düzeltirim?

### 1.4 Temel Sözdizimi

**Soru 39:**
Rust'ta kod yazım kuralları nelerdir?

**Soru 40:**
Rust'ta yorum satırları nasıl yazılır?

**Soru 41:**
main fonksiyonu nedir ve neden önemlidir?

**Soru 42:**
println! makrosu nedir ve nasıl kullanılır?

**Soru 43:**
Rust'ta kod blokları nasıl oluşturulur?

## Seviye 2: Değişkenler ve Veri Türleri

### 2.1 Değişkenler

**Soru 44:**
Değişken nedir? Programlama bilgisi olmayan birinin anlayacağı şekilde açıkla

**Soru 45:**
Değişken neden kullanılır? Günlük hayattan örneklerle açıkla

**Soru 46:**
Rust'ta değişken nasıl oluşturulur?

**Soru 47:**
let anahtar kelimesi ne işe yarar?

**Soru 48:**
Değişken isimlendirme kuralları nelerdir?

**Soru 49:**
Rust'ta değişkenler neden varsayılan olarak değiştirilemez?

**Soru 50:**
mut anahtar kelimesi ne işe yarar?

**Soru 51:**
Değişken gölgeleme (shadowing) nedir?

**Soru 52:**
Değişken tanımlarken ownership nasıl çalışır? let x = 5 ile let y = x arasındaki fark nedir?

**Soru 53:**
String değişkeni başka bir değişkene atarken ne olur? Ownership transfer edilir mi?

**Soru 54:**
Copy türleri ile non-Copy türleri değişken atamasında nasıl farklı davranır?

**Soru 55:**
Değişken atamasında move vs copy ne zaman oluşur?

### 2.2 Veri Türleri

**Soru 56:**
Veri türü nedir? Neden önemlidir?

**Soru 57:**
Rust'ta temel veri türleri nelerdir?

**Soru 58:**
Tam sayı türleri nelerdir? (i8, i16, i32, i64, u8, u16, u32, u64)

**Soru 59:**
Ondalıklı sayı türleri nelerdir? (f32, f64)

**Soru 60:**
Boolean türü nedir ve nasıl kullanılır?

**Soru 61:**
Karakter (char) türü nedir?

**Soru 62:**
String ve &str arasındaki fark nedir?

**Soru 63:**
Tür çıkarımı (type inference) nedir?

**Soru 64:**
Tür dönüşümü nasıl yapılır?

**Soru 65:**
Hangi veri türleri Copy trait'ini implement eder? Bu ownership açısından ne anlama gelir?

**Soru 66:**
String gibi heap-allocated türlerin ownership'i nasıl çalışır?

**Soru 67:**
Primitive türlerin stack'te saklanması ownership'i nasıl etkiler?

## Seviye 3: Kontrol Yapıları

### 3.1 Koşullu İfadeler

**Soru 68:**
Koşullu ifade nedir? Günlük hayattan örneklerle açıkla

**Soru 69:**
if ifadesi nasıl kullanılır?

**Soru 70:**
else if nasıl kullanılır?

**Soru 71:**
else nasıl kullanılır?

**Soru 72:**
Rust'ta if ifadesi nasıl değer döndürür?

**Soru 73:**
if koşulunda değişken kullanırken ownership nasıl etkilenir?

**Soru 74:**
if bloğu içinde tanımlanan değişkenlerin ownership'i nasıl çalışır?

**Soru 75:**
Koşullu ifadelerde String gibi owned değerleri nasıl kullanırız?

**Soru 76:**
if ifadesinde reference (&) kullanımı ne zaman gereklidir?

**Soru 77:**
Match guard'larda borrowing nasıl çalışır?

### 3.2 Döngüler

**Soru 78:**
Döngü nedir? Neden kullanılır?

**Soru 79:**
loop döngüsü nasıl kullanılır?

**Soru 80:**
while döngüsü nasıl kullanılır?

**Soru 81:**
for döngüsü nasıl kullanılır?

**Soru 82:**
Range (..) operatörü nedir?

**Soru 83:**
break ve continue anahtar kelimeleri ne işe yarar?

**Soru 84:**
Döngü etiketleri (loop labels) nasıl kullanılır?

**Soru 85:**
for döngüsünde iterator ownership'i nasıl çalışır?

**Soru 86:**
vec.into_iter() vs vec.iter() vs vec.iter_mut() arasındaki ownership farkları nelerdir?

**Soru 87:**
Döngü içinde değişken modify ederken borrowing kuralları nasıl uygulanır?

**Soru 88:**
Döngü değişkeninin scope'u ve ownership'i nasıl çalışır?

**Soru 89:**
Nested loop'larda içteki döngüden dıştaki değişkene erişirken borrowing nasıl olur?

**Soru 90:**
while let döngüsünde pattern matching ile ownership nasıl transfer edilir?

## Seviye 4: Fonksiyonlar

### 4.1 Fonksiyon Temelleri

**Soru 91:**
Fonksiyon nedir? Neden önemlidir?

**Soru 92:**
Rust'ta fonksiyon nasıl tanımlanır?

**Soru 93:**
fn anahtar kelimesi ne işe yarar?

**Soru 94:**
Fonksiyon parametreleri nasıl tanımlanır?

**Soru 95:**
Fonksiyon nasıl çağrılır?

**Soru 96:**
Return anahtar kelimesi nasıl kullanılır?

**Soru 97:**
Rust'ta fonksiyonlar nasıl değer döndürür?

**Soru 98:**
İfade (expression) ve deyim (statement) arasındaki fark nedir?

**Soru 99:**
Fonksiyon parametrelerinde ownership nasıl çalışır?

**Soru 100:**
Fonksiyona değer geçerken move mi copy mi olur?

**Soru 101:**
Fonksiyon parametresi olarak reference (&T) ne zaman kullanılır?

**Soru 102:**
Mutable reference (&mut T) fonksiyon parametresi olarak nasıl kullanılır?

**Soru 103:**
Fonksiyondan ownership döndürmek ne zaman mantıklıdır?

**Soru 104:**
Fonksiyondan reference döndürmenin kuralları nelerdir?

**Soru 105:**
Dangling reference hatası fonksiyonlarda nasıl oluşur?

### 4.2 İleri Fonksiyon Konuları

**Soru 106:**
Fonksiyon overloading Rust'ta mümkün mü?

**Soru 107:**
Closures (anonim fonksiyonlar) nedir?

**Soru 108:**
Higher-order functions nedir?

**Soru 109:**
Closure'larda capture semantiği nasıl çalışır? (move, borrow)

**Soru 110:**
Fn, FnMut, FnOnce trait'lerinin ownership açısından farkları nelerdir?

**Soru 111:**
Closure environment'ı nasıl capture edilir?

## Seviye 5: Ownership Sistemi (Rust'ın Kalbi)

### 5.1 Ownership Temelleri

**Soru 112:**
Ownership nedir? Rust'ı diğer dillerden ayıran bu özellik neden önemlidir?

**Soru 113:**
Memory management nedir? Stack ve heap arasındaki fark nedir?

**Soru 114:**
Ownership kuralları nelerdir?

**Soru 115:**
Bir değişkenin ownership'i nasıl transfer edilir?

**Soru 116:**
Move semantiği nedir?

**Soru 117:**
Copy trait'i nedir? Hangi türler copy edilebilir?

### 5.2 References ve Borrowing

**Soru 118:**
Reference (&) nedir? Nasıl kullanılır?

**Soru 119:**
Borrowing nedir? Ownership'ten farkı nedir?

**Soru 120:**
Mutable reference (&mut) nedir?

**Soru 121:**
Borrowing kuralları nelerdir?

**Soru 122:**
Dangling reference nedir? Rust nasıl engeller?

**Soru 123:**
Reference'ların yaşam süresi (lifetime) nedir?

### 5.3 Slices

**Soru 124:**
Slice nedir? Ne işe yarar?

**Soru 125:**
String slice (&str) nasıl kullanılır?

**Soru 126:**
Array slice nasıl oluşturulur?

## Seviye 6: Compound Data Types

### 6.1 Tuples

**Soru 127:**
Tuple nedir? Nasıl kullanılır?

**Soru 128:**
Tuple elemanlarına nasıl erişilir?

**Soru 129:**
Tuple destructuring nedir?

### 6.2 Arrays

**Soru 130:**
Array nedir? Ne zaman kullanılır?

**Soru 131:**
Array nasıl tanımlanır ve başlatılır?

**Soru 132:**
Array elemanlarına nasıl erişilir?

**Soru 133:**
Array ve Vector arasındaki fark nedir?

### 6.3 Structs

**Soru 134:**
Struct nedir? Neden kullanılır?

**Soru 135:**
Struct nasıl tanımlanır?

**Soru 136:**
Struct instance'ı nasıl oluşturulur?

**Soru 137:**
Struct field'larına nasıl erişilir?

**Soru 138:**
Struct update syntax nedir?

**Soru 139:**
Tuple struct nedir?

**Soru 140:**
Unit struct nedir?

**Soru 141:**
Struct'lara method nasıl eklenir?

**Soru 142:**
impl bloğu nedir?

**Soru 143:**
Associated functions nedir?

## Seviye 7: Enums ve Pattern Matching

### 7.1 Enums

**Soru 144:**
Enum nedir? Ne işe yarar?

**Soru 145:**
Enum nasıl tanımlanır?

**Soru 146:**
Enum variants nasıl kullanılır?

**Soru 147:**
Enum'lara veri nasıl eklenir?

**Soru 148:**
Option enum'u nedir? Null safety nasıl sağlar?

**Soru 149:**
Result enum'u nedir? Error handling'de nasıl kullanılır?

### 7.2 Pattern Matching

**Soru 150:**
Pattern matching nedir? Neden güçlü bir özellik?

**Soru 151:**
match ifadesi nasıl kullanılır?

**Soru 152:**
match arms nasıl yazılır?

**Soru 153:**
Wildcard pattern (_) ne işe yarar?

**Soru 154:**
if let syntax'ı nedir?

**Soru 155:**
while let nasıl kullanılır?

## Seviye 8: Collections

### 8.1 Vectors

**Soru 156:**
Vector nedir? Array'den farkı nedir?

**Soru 157:**
Vector nasıl oluşturulur?

**Soru 158:**
Vector'e eleman nasıl eklenir?

**Soru 159:**
Vector elemanlarına nasıl erişilir?

**Soru 160:**
Vector üzerinde nasıl iterasyon yapılır?

### 8.2 Strings

**Soru 161:**
String ve &str arasındaki detaylı fark nedir?

**Soru 162:**
String nasıl oluşturulur ve manipüle edilir?

**Soru 163:**
String concatenation nasıl yapılır?

**Soru 164:**
String slicing nasıl çalışır?

### 8.3 Hash Maps

**Soru 165:**
HashMap nedir? Ne zaman kullanılır?

**Soru 166:**
HashMap nasıl oluşturulur?

**Soru 167:**
HashMap'e key-value pair nasıl eklenir?

**Soru 168:**
HashMap'ten değer nasıl okunur?

## Seviye 9: Error Handling

### 9.1 Panic

**Soru 169:**
Panic nedir? Ne zaman oluşur?

**Soru 170:**
panic! makrosu nasıl kullanılır?

**Soru 171:**
Recoverable ve unrecoverable error'lar nedir?

### 9.2 Result Type

**Soru 172:**
Result<T, E> nasıl kullanılır?

**Soru 173:**
Error propagation nasıl yapılır?

**Soru 174:**
? operatörü ne işe yarar?

**Soru 175:**
unwrap() ve expect() metotları nedir?

**Soru 176:**
Custom error types nasıl oluşturulur?

## Seviye 10: Generic Types ve Traits

### 10.1 Generics

**Soru 177:**
Generic type nedir? Neden kullanılır?

**Soru 178:**
Generic function nasıl yazılır?

**Soru 179:**
Generic struct nasıl tanımlanır?

**Soru 180:**
Generic enum nasıl oluşturulur?

**Soru 181:**
Type constraints nedir?

### 10.2 Traits

**Soru 182:**
Trait nedir? Interface'lerden farkı nedir?

**Soru 183:**
Trait nasıl tanımlanır?

**Soru 184:**
Trait nasıl implement edilir?

**Soru 185:**
Default implementations nedir?

**Soru 186:**
Trait bounds nedir?

**Soru 187:**
Trait objects nedir?

**Soru 188:**
Common traits nelerdir? (Debug, Clone, Copy, etc.)

## Seviye 11: Lifetimes (Detaylı)

### 11.1 Lifetime Basics

**Soru 189:**
Lifetime nedir? Reference'ların yaşam süresi neden önemlidir?

**Soru 190:**
Lifetime annotation syntax'ı nasıldır? 'a nedir?

**Soru 191:**
Lifetime parameter nedir? Generic type parameter'dan farkı nedir?

**Soru 192:**
Lifetime elision rules nelerdir? Compiler ne zaman lifetime'ları otomatik çıkarır?

**Soru 193:**
Function signature'larda lifetime nasıl specify edilir?

### 11.2 Lifetime Annotations

**Soru 194:**
Lifetime annotation ne zaman gereklidir?

**Soru 195:**
Multiple lifetime parameters (&'a str, &'b str) nasıl kullanılır?

**Soru 196:**
Lifetime subtyping nedir? 'a: 'b ne demektir?

**Soru 197:**
Input lifetimes ve output lifetimes arasındaki ilişki nedir?

### 11.3 Struct ve Lifetime

**Soru 198:**
Struct field'larında lifetime nasıl kullanılır?

**Soru 199:**
Struct definition'da lifetime parameter nasıl tanımlanır?

**Soru 200:**
Self-referential struct'lar neden problemlidir?

### 11.4 Advanced Lifetimes

**Soru 201:**
Static lifetime ('static) nedir? Ne zaman kullanılır?

**Soru 202:**
Lifetime bounds nedir? T: 'a ne demektir?

**Soru 203:**
Higher-ranked trait bounds (HRTB) nedir?

**Soru 204:**
Lifetime'lar ile generic types nasıl kombine edilir?

## Seviye 12: Testing

### 12.1 Unit Testing

**Soru 205:**
Rust'ta test nasıl yazılır?

**Soru 206:**
#[test] attribute'u nedir?

**Soru 207:**
assert! makroları nasıl kullanılır?

**Soru 208:**
cargo test komutu nasıl çalışır?

**Soru 209:**
Test organization nasıl yapılır?

### 12.2 Integration Testing

**Soru 210:**
Integration test nedir?

**Soru 211:**
tests/ directory nasıl kullanılır?

**Soru 212:**
Benchmark testing nasıl yapılır?

## Seviye 13: I/O Operations

###