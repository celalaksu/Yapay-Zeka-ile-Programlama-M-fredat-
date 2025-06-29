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

```
Programlama nedir? Hiç programlama bilmeyen birinin anlayacağı şekilde açıkla
```

```
Rust programlama dili nedir ve neden önemlidir?
```

```
Rust'ın diğer programlama dillerinden farkları nelerdir?
```

```
Rust hangi alanlarda kullanılır? Örneklerle açıkla
```

```
Rust'ı bilgisayarıma nasıl kurarım? Adım adım anlat
```

```
Cargo nedir ve ne işe yarar?
```

### 1.2 Geliştirme Ortamı Kurulumu (IDE ve Araçlar)

#### 1.2.1 Windows İçin Geliştirme Ortamı

```
Windows'ta Visual Studio Code nasıl kurulur? Adım adım kurulum rehberi
```

```
Windows'ta VS Code için gerekli Rust eklentileri nelerdir ve nasıl kurulur?
- rust-analyzer eklentisi kurulumu
- CodeLLDB (debugging için) kurulumu
- Better TOML eklentisi kurulumu
- Error Lens eklentisi kurulumu
```

```
Windows'ta VS Code ile Rust projesi nasıl oluşturulur?
```

```
Windows'ta VS Code'da ilk Rust programı nasıl yazılır ve çalıştırılır?
```

```
Windows'ta VS Code debugging özellikleri nasıl kullanılır?
```

```
Windows'ta terminal entegrasyonu nasıl yapılır?
```

#### 1.2.2 Linux İçin Geliştirme Ortamı

```
Linux'ta Visual Studio Code nasıl kurulur? (Ubuntu, Debian, Fedora, Arch için ayrı talimatlar)
```

```
Linux'ta VS Code için gerekli Rust eklentileri nelerdir ve nasıl kurulur?
- rust-analyzer eklentisi kurulumu
- CodeLLDB (debugging için) kurulumu  
- Better TOML eklentisi kurulumu
- Error Lens eklentisi kurulumu
```

```
Linux'ta VS Code ile Rust projesi nasıl oluşturulur?
```

```
Linux'ta VS Code'da ilk Rust programı nasıl yazılır ve çalıştırılır?
```

```
Linux'ta VS Code debugging özellikleri nasıl kullanılır?
```

```
Linux'ta terminal entegrasyonu ve zsh/bash konfigürasyonu
```

#### 1.2.3 macOS İçin Geliştirme Ortamı

```
macOS'ta Visual Studio Code nasıl kurulur? (Intel ve Apple Silicon Mac'ler için)
```

```
macOS'ta VS Code için gerekli Rust eklentileri nelerdir ve nasıl kurulur?
- rust-analyzer eklentisi kurulumu
- CodeLLDB (debugging için) kurulumu
- Better TOML eklentisi kurulumu  
- Error Lens eklentisi kurulumu
```

```
macOS'ta VS Code ile Rust projesi nasıl oluşturulur?
```

```
macOS'ta VS Code'da ilk Rust programı nasıl yazılır ve çalıştırılır?
```

```
macOS'ta VS Code debugging özellikleri nasıl kullanılır?
```

```
macOS'ta terminal entegrasyonu ve zsh konfigürasyonu
```

#### 1.2.4 IDE Kullanım Temelleri ve İpuçları

```
VS Code'da Rust için yararlı kısayol tuşları nelerdir?
```

```
IntelliSense ve kod tamamlama özellikleri nasıl kullanılır?
```

```
VS Code'da hata mesajları nasıl okunur ve anlaşılır?
```

```
VS Code'da refactoring araçları nasıl kullanılır?
```

```
VS Code'da Git entegrasyonu nasıl çalışır?
```

```
VS Code workspace ve settings konfigürasyonu nasıl yapılır?
```

#### 1.2.5 Alternatif IDE'ler

```
IntelliJ IDEA + Rust Plugin kurulumu nasıl yapılır?
```

```
CLion ile Rust geliştirme nasıl yapılır?
```

```
Vim/Neovim ile Rust geliştirme ortamı nasıl kurulur?
```

```
Emacs ile Rust geliştirme nasıl yapılır?
```

```
Hangi IDE hangi durumda tercih edilmelidir?
```

### 1.3 İlk Rust Programı

```
İlk Rust programımı nasıl yazarım ve çalıştırırım? (Tüm işletim sistemleri için pratik örnekler)
```

```
Hello World programını farklı IDE'lerde nasıl çalıştırırım?
```

```
Kod hatalarını IDE'de nasıl tespit ederim ve düzeltirim?
```

### 1.4 Temel Sözdizimi

```
Rust'ta kod yazım kuralları nelerdir?
```

```
Rust'ta yorum satırları nasıl yazılır?
```

```
main fonksiyonu nedir ve neden önemlidir?
```

```
println! makrosu nedir ve nasıl kullanılır?
```

```
Rust'ta kod blokları nasıl oluşturulur?
```

## Seviye 2: Değişkenler ve Veri Türleri

### 2.1 Değişkenler

```
Değişken nedir? Programlama bilgisi olmayan birinin anlayacağı şekilde açıkla
```

```
Değişken neden kullanılır? Günlük hayattan örneklerle açıkla
```

```
Rust'ta değişken nasıl oluşturulur?
```

```
let anahtar kelimesi ne işe yarar?
```

```
Değişken isimlendirme kuralları nelerdir?
```

```
Rust'ta değişkenler neden varsayılan olarak değiştirilemez?
```

```
mut anahtar kelimesi ne işe yarar?
```

```
Değişken gölgeleme (shadowing) nedir?
```

```
Değişken tanımlarken ownership nasıl çalışır? let x = 5 ile let y = x arasındaki fark nedir?
```

```
String değişkeni başka bir değişkene atarken ne olur? Ownership transfer edilir mi?
```

```
Copy türleri ile non-Copy türleri değişken atamasında nasıl farklı davranır?
```

```
Değişken atamasında move vs copy ne zaman oluşur?
```

### 2.2 Veri Türleri

```
Veri türü nedir? Neden önemlidir?
```

```
Rust'ta temel veri türleri nelerdir?
```

```
Tam sayı türleri nelerdir? (i8, i16, i32, i64, u8, u16, u32, u64)
```

```
Ondalıklı sayı türleri nelerdir? (f32, f64)
```

```
Boolean türü nedir ve nasıl kullanılır?
```

```
Karakter (char) türü nedir?
```

```
String ve &str arasındaki fark nedir?
```

```
Tür çıkarımı (type inference) nedir?
```

```
Tür dönüşümü nasıl yapılır?
```

```
Hangi veri türleri Copy trait'ini implement eder? Bu ownership açısından ne anlama gelir?
```

```
String gibi heap-allocated türlerin ownership'i nasıl çalışır?
```

```
Primitive türlerin stack'te saklanması ownership'i nasıl etkiler?
```

## Seviye 3: Kontrol Yapıları

### 3.1 Koşullu İfadeler

```
Koşullu ifade nedir? Günlük hayattan örneklerle açıkla
```

```
if ifadesi nasıl kullanılır?
```

```
else if nasıl kullanılır?
```

```
else nasıl kullanılır?
```

```
Rust'ta if ifadesi nasıl değer döndürür?
```

```
if koşulunda değişken kullanırken ownership nasıl etkilenir?
```

```
if bloğu içinde tanımlanan değişkenlerin ownership'i nasıl çalışır?
```

```
Koşullu ifadelerde String gibi owned değerleri nasıl kullanırız?
```

```
if ifadesinde reference (&) kullanımı ne zaman gereklidir?
```

```
Match guard'larda borrowing nasıl çalışır?
```

### 3.2 Döngüler

```
Döngü nedir? Neden kullanılır?
```

```
loop döngüsü nasıl kullanılır?
```

```
while döngüsü nasıl kullanılır?
```

```
for döngüsü nasıl kullanılır?
```

```
Range (..) operatörü nedir?
```

```
break ve continue anahtar kelimeleri ne işe yarar?
```

```
Döngü etiketleri (loop labels) nasıl kullanılır?
```

```
for döngüsünde iterator ownership'i nasıl çalışır?
```

```
vec.into_iter() vs vec.iter() vs vec.iter_mut() arasındaki ownership farkları nelerdir?
```

```
Döngü içinde değişken modify ederken borrowing kuralları nasıl uygulanır?
```

```
Döngü değişkeninin scope'u ve ownership'i nasıl çalışır?
```

```
Nested loop'larda içteki döngüden dıştaki değişkene erişirken borrowing nasıl olur?
```

```
while let döngüsünde pattern matching ile ownership nasıl transfer edilir?
```

## Seviye 4: Fonksiyonlar

### 4.1 Fonksiyon Temelleri

```
Fonksiyon nedir? Neden önemlidir?
```

```
Rust'ta fonksiyon nasıl tanımlanır?
```

```
fn anahtar kelimesi ne işe yarar?
```

```
Fonksiyon parametreleri nasıl tanımlanır?
```

```
Fonksiyon nasıl çağrılır?
```

```
Return anahtar kelimesi nasıl kullanılır?
```

```
Rust'ta fonksiyonlar nasıl değer döndürür?
```

```
İfade (expression) ve deyim (statement) arasındaki fark nedir?
```

```
Fonksiyon parametrelerinde ownership nasıl çalışır?
```

```
Fonksiyona değer geçerken move mi copy mi olur?
```

```
Fonksiyon parametresi olarak reference (&T) ne zaman kullanılır?
```

```
Mutable reference (&mut T) fonksiyon parametresi olarak nasıl kullanılır?
```

```
Fonksiyondan ownership döndürmek ne zaman mantıklıdır?
```

```
Fonksiyondan reference döndürmenin kuralları nelerdir?
```

```
Dangling reference hatası fonksiyonlarda nasıl oluşur?
```

### 4.2 İleri Fonksiyon Konuları

```
Fonksiyon overloading Rust'ta mümkün mü?
```

```
Closures (anonim fonksiyonlar) nedir?
```

```
Higher-order functions nedir?
```

```
Closure'larda capture semantiği nasıl çalışır? (move, borrow)
```

```
Fn, FnMut, FnOnce trait'lerinin ownership açısından farkları nelerdir?
```

```
Closure environment'ı nasıl capture edilir?
```

## Seviye 5: Ownership Sistemi (Rust'ın Kalbi)

### 5.1 Ownership Temelleri

```
Ownership nedir? Rust'ı diğer dillerden ayıran bu özellik neden önemlidir?
```

```
Memory management nedir? Stack ve heap arasındaki fark nedir?
```

```
Ownership kuralları nelerdir?
```

```
Bir değişkenin ownership'i nasıl transfer edilir?
```

```
Move semantiği nedir?
```

```
Copy trait'i nedir? Hangi türler copy edilebilir?
```

### 5.2 References ve Borrowing

```
Reference (&) nedir? Nasıl kullanılır?
```

```
Borrowing nedir? Ownership'ten farkı nedir?
```

```
Mutable reference (&mut) nedir?
```

```
Borrowing kuralları nelerdir?
```

```
Dangling reference nedir? Rust nasıl engeller?
```

```
Reference'ların yaşam süresi (lifetime) nedir?
```

### 5.3 Slices

```
Slice nedir? Ne işe yarar?
```

```
String slice (&str) nasıl kullanılır?
```

```
Array slice nasıl oluşturulur?
```

## Seviye 6: Compound Data Types

### 6.1 Tuples

```
Tuple nedir? Nasıl kullanılır?
```

```
Tuple elemanlarına nasıl erişilir?
```

```
Tuple destructuring nedir?
```

### 6.2 Arrays

```
Array nedir? Ne zaman kullanılır?
```

```
Array nasıl tanımlanır ve başlatılır?
```

```
Array elemanlarına nasıl erişilir?
```

```
Array ve Vector arasındaki fark nedir?
```

### 6.3 Structs

```
Struct nedir? Neden kullanılır?
```

```
Struct nasıl tanımlanır?
```

```
Struct instance'ı nasıl oluşturulur?
```

```
Struct field'larına nasıl erişilir?
```

```
Struct update syntax nedir?
```

```
Tuple struct nedir?
```

```
Unit struct nedir?
```

```
Struct'lara method nasıl eklenir?
```

```
impl bloğu nedir?
```

```
Associated functions nedir?
```

## Seviye 7: Enums ve Pattern Matching

### 7.1 Enums

```
Enum nedir? Ne işe yarar?
```

```
Enum nasıl tanımlanır?
```

```
Enum variants nasıl kullanılır?
```

```
Enum'lara veri nasıl eklenir?
```

```
Option enum'u nedir? Null safety nasıl sağlar?
```

```
Result enum'u nedir? Error handling'de nasıl kullanılır?
```

### 7.2 Pattern Matching

```
Pattern matching nedir? Neden güçlü bir özellik?
```

```
match ifadesi nasıl kullanılır?
```

```
match arms nasıl yazılır?
```

```
Wildcard pattern (_) ne işe yarar?
```

```
if let syntax'ı nedir?
```

```
while let nasıl kullanılır?
```

## Seviye 8: Collections

### 8.1 Vectors

```
Vector nedir? Array'den farkı nedir?
```

```
Vector nasıl oluşturulur?
```

```
Vector'e eleman nasıl eklenir?
```

```
Vector elemanlarına nasıl erişilir?
```

```
Vector üzerinde nasıl iterasyon yapılır?
```

### 8.2 Strings

```
String ve &str arasındaki detaylı fark nedir?
```

```
String nasıl oluşturulur ve manipüle edilir?
```

```
String concatenation nasıl yapılır?
```

```
String slicing nasıl çalışır?
```

### 8.3 Hash Maps

```
HashMap nedir? Ne zaman kullanılır?
```

```
HashMap nasıl oluşturulur?
```

```
HashMap'e key-value pair nasıl eklenir?
```

```
HashMap'ten değer nasıl okunur?
```

## Seviye 9: Error Handling

### 9.1 Panic

```
Panic nedir? Ne zaman oluşur?
```

```
panic! makrosu nasıl kullanılır?
```

```
Recoverable ve unrecoverable error'lar nedir?
```

### 9.2 Result Type

```
Result<T, E> nasıl kullanılır?
```

```
Error propagation nasıl yapılır?
```

```
? operatörü ne işe yarar?
```

```
unwrap() ve expect() metotları nedir?
```

```
Custom error types nasıl oluşturulur?
```

## Seviye 10: Generic Types ve Traits

### 10.1 Generics

```
Generic type nedir? Neden kullanılır?
```

```
Generic function nasıl yazılır?
```

```
Generic struct nasıl tanımlanır?
```

```
Generic enum nasıl oluşturulur?
```

```
Type constraints nedir?
```

### 10.2 Traits

```
Trait nedir? Interface'lerden farkı nedir?
```

```
Trait nasıl tanımlanır?
```

```
Trait nasıl implement edilir?
```

```
Default implementations nedir?
```

```
Trait bounds nedir?
```

```
Trait objects nedir?
```

```
Common traits nelerdir? (Debug, Clone, Copy, etc.)
```

## Seviye 11: Lifetimes (Detaylı)

### 11.1 Lifetime Basics

```
Lifetime nedir? Reference'ların yaşam süresi neden önemlidir?
```

```
Lifetime annotation syntax'ı nasıldır? 'a nedir?
```

```
Lifetime parameter nedir? Generic type parameter'dan farkı nedir?
```

```
Lifetime elision rules nelerdir? Compiler ne zaman lifetime'ları otomatik çıkarır?
```

```
Function signature'larda lifetime nasıl specify edilir?
```

### 11.2 Lifetime Annotations

```
Lifetime annotation ne zaman gereklidir?
```

```
Multiple lifetime parameters (&'a str, &'b str) nasıl kullanılır?
```

```
Lifetime subtyping nedir? 'a: 'b ne demektir?
```

```
Input lifetimes ve output lifetimes arasındaki ilişki nedir?
```

### 11.3 Struct ve Lifetime

```
Struct field'larında lifetime nasıl kullanılır?
```

```
Struct definition'da lifetime parameter nasıl tanımlanır?
```

```
Self-referential struct'lar neden problemlidir?
```

### 11.4 Advanced Lifetimes

```
Static lifetime ('static) nedir? Ne zaman kullanılır?
```

```
Lifetime bounds nedir? T: 'a ne demektir?
```

```
Higher-ranked trait bounds (HRTB) nedir?
```

```
Lifetime'lar ile generic types nasıl kombine edilir?
```

## Seviye 12: Testing

### 12.1 Unit Testing

```
Rust'ta test nasıl yazılır?
```

```
#[test] attribute'u nedir?
```

```
assert! makroları nasıl kullanılır?
```

```
cargo test komutu nasıl çalışır?
```

```
Test organization nasıl yapılır?
```

### 12.2 Integration Testing

```
Integration test nedir?
```

```
tests/ directory nasıl kullanılır?
```

```
Benchmark testing nasıl yapılır?
```

## Seviye 13: I/O Operations

### 13.1 File Operations

```
File okuma/yazma nasıl yapılır?
```

```
std::fs modülü nasıl kullanılır?
```

```
Path ve PathBuf nedir?
```

```
File permissions nasıl kontrol edilir?
```

### 13.2 Console I/O

```
Kullanıcıdan input nasıl alınır?
```

```
stdin, stdout, stderr nedir?
```

```
Command line arguments nasıl işlenir?
```

## Seviye 14: Concurrency

### 14.1 Threads

```
Thread nedir? Rust'ta nasıl kullanılır?
```

```
std::thread modülü nasıl kullanılır?
```

```
Thread safety nasıl sağlanır?
```

```
Move closure'lar thread'lerde nasıl kullanılır?
```

### 14.2 Message Passing

```
Channel nedir? Nasıl kullanılır?
```

```
mpsc (multiple producer, single consumer) nedir?
```

```
Sender ve Receiver nasıl çalışır?
```

### 14.3 Shared State

```
Mutex nedir? Nasıl kullanılır?
```

```
Arc (Atomically Reference Counted) nedir?
```

```
Deadlock nedir? Nasıl önlenir?
```

## Seviye 15: Advanced Topics

### 15.1 Smart Pointers

```
Smart pointer nedir?
```

```
Box<T> nedir? Ne zaman kullanılır?
```

```
Rc<T> nedir? Reference counting nasıl çalışır?
```

```
RefCell<T> nedir? Interior mutability nedir?
```

### 15.2 Advanced Functions

```
Function pointers nedir?
```

```
Closure traits nelerdir? (Fn, FnMut, FnOnce)
```

```
Iterator trait nasıl implement edilir?
```

### 15.3 Macros

```
Macro nedir? Function'dan farkı nedir?
```

```
Declarative macro nasıl yazılır?
```

```
Procedural macro nedir?
```

```
Custom derive macro nasıl oluşturulur?
```

## Seviye 16: Unsafe Rust

### 16.1 Unsafe Operations

```
Unsafe Rust nedir? Ne zaman kullanılır?
```

```
Raw pointers nedir?
```

```
Unsafe functions nasıl tanımlanır?
```

```
External functions (FFI) nasıl kullanılır?
```

## Seviye 17: Project Management ve Ecosystem

### 17.1 Cargo Advanced

```
Cargo.toml dosyası detaylı olarak nasıl yapılandırılır?
```

```
Dependencies nasıl yönetilir?
```

```
Workspace nedir? Nasıl kullanılır?
```

```
Feature flags nedir?
```

```
Build scripts nasıl yazılır?
```

### 17.2 Popular Crates

```
Serde nedir? JSON serialization nasıl yapılır?
```

```
Tokio nedir? Async programming nasıl yapılır?
```

```
Clap nedir? CLI applications nasıl oluşturulur?
```

```
Reqwest ile HTTP requests nasıl yapılır?
```

## Seviye 18: Performance ve Optimization

### 18.1 Performance

```
Rust kodunu nasıl optimize ederim?
```

```
Profiling nasıl yapılır?
```

```
Memory usage nasıl optimize edilir?
```

```
Zero-cost abstractions nedir?
```

### 18.2 Debugging

```
Rust kodunu nasıl debug ederim?
```

```
GDB/LLDB ile Rust debugging nasıl yapılır?
```

```
Print debugging best practices nelerdir?
```

## Seviye 19: Real-World Projects

### 19.1 Web Development

```
Rust ile web backend nasıl geliştirilir?
```

```
Warp/Axum framework'leri nasıl kullanılır?
```

```
Database integration nasıl yapılır?
```

### 19.2 System Programming

```
Rust ile system programming nasıl yapılır?
```

```
OS bindings nasıl kullanılır?
```

```
Performance critical applications nasıl yazılır?
```

### 19.3 WebAssembly

```
Rust kod WASM'a nasıl compile edilir?
```

```
wasm-pack nasıl kullanılır?
```

```
Rust + JavaScript integration nasıl yapılır?
```

---

## Kullanım Talimatları

Bu müfredat 269 adet yapay zekaya sorulabilecek soru içermektedir. Her soru kopyalanabilir formatta kod blokları içinde sunulmuştur. 

### Önerilen Kullanım:
1. Her seviyeyi sırayla takip edin
2. Bir sonraki seviyeye geçmeden önce mevcut seviyedeki tüm soruları tamamlayın
3. Her soruyu yapay zekaya sorun ve aldığınız cevapları pratik yaparak pekiştirin
4. IDE kurulumu ve kullanımı konularına özel önem verin
5. Ownership sistemi konularını derinlemesine çalışın

### İpuçları:
- Soruları olduğu gibi kopyalayıp yapay zekaya sorun
- Örnekler istemeyi unutmayın
- Anlamadığınız kısımlar için follow-up sorular sorun
- Her konuyu mutlaka pratik kodlarla test edin