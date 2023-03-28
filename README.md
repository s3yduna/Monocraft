# Monocraft

[![Github all releases](https://img.shields.io/github/downloads/IdreesInc/Monocraft/total.svg)](https://GitHub.com/IdreesInc/Monocraft/releases/)
![](https://img.shields.io/github/license/IdreesInc/Monocraft)
[![](https://img.shields.io/github/v/release/IdreesInc/Monocraft)](https://GitHub.com/IdreesInc/Monocraft/releases/)

<img width="996" alt="previewTurkish" src="https://user-images.githubusercontent.com/80430560/228266828-aba1f2de-7dc9-4505-8ed5-60bc27796ebb.png">


Minecraft'ı seven yazılımcılar için tek aralıklı yeni bir font tipi.

*Uyarı: Bu projenin Minecraft veya Mojang ile bir bağı yoktur, hayran projesidir. Bu font Minecraft arayüzünde kullanılan yazı tipinden esinlenerek yapılmıştır.
Orjinal oyun dosyalarından birini veya yazı tipi dosyalarını içermez.*

## Özellikler

- Minecraft!
  - Kullanılan karakterler Minecraft arayüzünde bulunan [yazı tipini](https://github.com/IdreesInc/Minecraft-Font) kaynak almıştır, her bir gilf okunabilirliği arttırmak amacıyla güncellenmiştir. 
- Tek Aralıklı!
  - Yazı tipi içerisinde bulunan 500+ glif tek aralıklı yazı tiplerinde çalışacak şekilde dikkatlice yeniden tasarlandı
  - "i" ve "l" gibi ince karakterlere daha iyi görünebilmeleri için kuyruklar eklendi 
- Bitişik Programlama Harfleri !
  - Yeni eklenen birleşik karakterler ile kod satırlarınıza renk katın
  - Oklar artık birer ok gibi görünüyor ve karşılaştırma operatörleri çok daha ön planda

## Glifler

![](images/glyphs.png)

## Kurulum Aşamaları

### Windows

`Monocraft.ttf` dosyasının son sürümünü [Sürümler](https://github.com/IdreesInc/Monocraft/releases) sayfasından indirin. İndirdiğiniz dosyaya sağ tıklayın ve **Install** basın. Kullandığınız cihaza göre değişkenlik göstermekle birlikte yönetici izni isteyebilir.

### Mac

#### Homwbrew Kullananlar İçin

```shell
brew tap homebrew/cask-fonts
brew install --cask font-monocraft
```

#### Manuel Kurulum

`Monocraft.ttf` dosyasının son sürümünü [Sürümler](https://github.com/IdreesInc/Monocraft/releases) sayfasından indirin. İndirdiğiniz dosyaya sağ tıklayın ve **Install** basın. Daha fazla yardıma [buradan](https://support.apple.com/en-us/HT201749) ulaşabilirsiniz.

### Linux

`Monocraft.ttf` dosyasının son sürümünü [Sürümler](https://github.com/IdreesInc/Monocraft/releases) sayfasından indirin. Dosyayı to ~/.local/share/fonts (eğer klasör yok ise kendiniz oluşturun) konumuna taşıyın. Terminal üzerinden, run `fc-cache -fv`. Çıkış yaptıktan sonra tekrar giriş yapın.

## Nasıl Kulanırım

Yukarıda yazan talimatları uyguladıktan sonra "Monocraft" yazı tipini (boşluğa dikkat) özel yazı tiplerini destekleyen bir program içerisinden seçin. Yazı tipinin görünür olabilmesi için programı veya bilgisayarınızı yeniden başlatmanız gerekebilir.

## SSS

### Ne tür bitişik harfler içeriyor?

Şu ana dek aşağıda bulunan bitişik harfler eklendi:

<img src="images/ligatures.png" width="300">

Farklı karakterlerin kombinasyonunu istiyorsanız eğer "Issues" kısmından yazmayı unutmayın.

### Bu karakterler nasıl oluşturuldu?

[FontForge'un](https://fontforge.org/en-US/) harika Python eklentisini kullanarak. Daha fazlası için [src](https://github.com/IdreesInc/Monocraft/tree/main/src) klasörü içinde bulunan kaynak kodlarını inceleyebilirsiniz.

### Orjinal Minecraft tipine sahip bir sürümünüz bulunmakta mı (tek aralıklı olmamak kaydıyla)?

Tabii ki, [buradan](https://github.com/IdreesInc/Minecraft-Font) Minecraft yazı tipi klonumu kontrol edebilirsiniz.

### Harbiden güzel bir font kullanmak istersem?

Anlayabiliyorum, [Fira Code](https://github.com/tonsky/FiraCode) harika detaylı yazı tipleri için ziyaret edebilirsiniz, veya [Scientifica'ya](https://github.com/nerdypepper/scientifica) da bakabilirsiniz. Bitmap'i Monocraft'ı andırıyor.
