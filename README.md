# MyDictionary

C# dilinde `Dictionary<TKey, TValue>` veri yapısının sıfırdan, yalnızca diziler kullanılarak generic bir implementasyonu.

## Öne Çıkanlar
- .NET'in hazır `Dictionary` sınıfı kullanılmadan, iki paralel dizi (key ve value) ile çalışan generic yapı
- `Add` metodu her ekleme işleminde diziyi yeniden boyutlandırıp verileri kopyalar
- Generic tip parametreleriyle (`TKey`, `TValue`) herhangi iki tip için kullanılabilir

## Tech Stack
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![.NET Framework](https://img.shields.io/badge/.NET_Framework-512BD4?style=flat-square&logo=dotnet&logoColor=white)

## Çalıştırma

Visual Studio'da `MyDictionary.sln` dosyasını aç ve çalıştır.

## Öğrendiklerim
- Generic sınıf yazımı (`class MyDictonary<TKey, TValue>`)
- Veri yapılarının arka planda nasıl çalıştığı (dizi yeniden boyutlandırma)
- `Dictionary` gibi built-in koleksiyonların temel mantığı
