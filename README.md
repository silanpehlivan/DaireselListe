<div align="center">

# Dairesel Bağlı Liste

**Veri yapıları ve döngüsel bağlantılar**

![C#](https://img.shields.io/badge/C%23-2563eb?style=flat-square)
![.NET](https://img.shields.io/badge/.NET-0891b2?style=flat-square)
[![MIT License](https://img.shields.io/badge/License-MIT-16a34a?style=flat-square)](LICENSE)

Dairesel bağlı listenin düğüm yapısını ve temel işlemlerini C# ile uygulayan konsol projesi.

</div>

---

## Öne Çıkanlar

- Başa, sona ve araya eleman ekleme
- Düğüm silme ve listeyi görüntüleme
- Son düğümden ilk düğüme döngüsel bağlantı

## Teknolojiler

C# · .NET

<details>
<summary><strong>Kurulum, kullanım ve teknik ayrıntılar</strong></summary>

Bu proje, veri yapılarının temel konularından biri olan **dairesel bağlı liste (Circular Linked List)** yapısının C# dilinde nasıl oluşturulduğunu ve temel işlemlerinin nasıl gerçekleştirildiğini göstermektedir.

---

## Özellikler

- **Dairesel Bağlı Liste:** Son düğümün `next` işaretçisinin ilk düğümü gösterdiği yapı
- **Düğüm Yapısı:** Her düğüm `Data` (int) ve `Next` (Node) içerir
- **Ekleme İşlemleri:**
  - Başa ekleme
  - Sona ekleme
  - Belirli bir sıraya ekleme
- **Silme İşlemleri:**
  - Baştan silme
  - Sondan silme
  - Belirli düğümü silme
- **Görüntüleme:** Listenin tüm elemanlarını dolaşarak ekrana yazdırma

---

## Teknik Detaylar

- **Dil:** C#
- **Veri Yapısı:** Dairesel Bağlı Liste (Circular Linked List)
- **Mantık:** Son düğümün ilk düğüme bağlanmasıyla oluşan döngüsel yapı

---

## Kazanımlar

- Dinamik veri yapılarıyla çalışma becerisi
- Dairesel yapı mantığını öğrenme
- Ekleme ve silme algoritmalarının uygulanması
- Traversal (döngüsel gezinme) mantığını kavrama
- Round Robin gibi gerçek sistem mantıklarına giriş

---

## Kurulum

1.  Projeyi klonlayın veya ZIP olarak indirin  
2.  `DaireselListe-master` klasörüne gidin  
3.  Visual Studio ile `.sln` dosyasını açın  
4.  Projeyi derleyip çalıştırın  

---

## Kullanım

Program çalıştırıldığında `Program.cs` dosyası üzerinden:

- Listeye eleman ekleme işlemleri  
- Silme işlemleri  
- Listeyi görüntüleme işlemleri  

adım adım konsol ekranında gösterilir.

---

## Node Sınıfı

Her düğüm:
- `Data` (veri)
- `Next` (sonraki düğüm bağlantısı)

---

## DaireselBağlantılıListe Sınıfı (Örnek İşlemler)

- SonaEkle()
- BaşaEkle()
- ArayaEkle()
- BaştanSil()
- SondanSil()
- BelirliDüğümSil()
- Goruntule()

---

## Proje Yapısı

- App.config  
- LICENSE  
- Node.cs  
- Program.cs  
- Ödev3.csproj  
- Ödev3.sln  
- README.md  

---

## Katkıda Bulunma

Katkılarınız memnuniyetle karşılanır. Hata bildirimi veya yeni özellik önerileri için issue açabilir veya pull request gönderebilirsiniz.

---


</details>

---

<div align="center">

**© 2025 Şilan PEHLİVAN**

Bu proje MIT lisansı kapsamında sunulmaktadır. Kullanım ve dağıtım koşulları: [LICENSE](LICENSE).

</div>
