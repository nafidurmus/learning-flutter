Flutter nedir ? neden kullanılır ? nasıl kurulum yapılır ? \* { font-family: Georgia, Cambria, "Times New Roman", Times, serif; } html, body { margin: 0; padding: 0; } h1 { font-size: 50px; margin-bottom: 17px; color: #333; } h2 { font-size: 24px; line-height: 1.6; margin: 30px 0 0 0; margin-bottom: 18px; margin-top: 33px; color: #333; } h3 { font-size: 30px; margin: 10px 0 20px 0; color: #333; } header { width: 640px; margin: auto; } section { width: 640px; margin: auto; } section p { margin-bottom: 27px; font-size: 20px; line-height: 1.6; color: #333; } section img { max-width: 640px; } footer { padding: 0 20px; margin: 50px 0; text-align: center; font-size: 12px; } .aspectRatioPlaceholder { max-width: auto !important; max-height: auto !important; } .aspectRatioPlaceholder-fill { padding-bottom: 0 !important; } header, section\[data-field=subtitle\], section\[data-field=description\] { display: none; }

Flutter nedir ? neden kullanılır ? nasıl kurulum yapılır ?
==========================================================

Şimdiye kadar hep web programlamayla uğraştım. Kendimi biraz da mobil programlamada geliştirmek istiyordum. Araştırmaya başladım hangi…

* * *

### Flutter Nedir? Neden Kullanılır? Nasıl Kurulum Yapılır?

Şimdiye kadar hep **web programlama**yla uğraştım. Kendimi biraz da mobil programlamada geliştirmek istiyordum. Araştırmaya başladım hangi dillerde kendimi geliştirebilirim.

![](https://cdn-images-1.medium.com/max/800/1*-3MC_-uS_jmSI2Y5Sxk9HA.png)

Bu programlama dilleri arasından **Flutter** öğrenmeye karar verdim.

**Flutter nedir ?**

![](https://cdn-images-1.medium.com/max/800/1*bYuD5OBj28zyea3-K2bdHQ.gif)

İlk olarak **Google’ın 2017 I/O developer** konferansında duyurulan Flutter, 1.0 sürümünün duyurmasının üstünden çok geçmemesine rağmen **Groupon, Philips Hue, Tencent, Alibaba** gibi birçok şirket tarafından beta sürecinde uygulamalar geliştirilmiş ve kullanıma sunulmuştur.

**Flutter**, içinde framework, widget ve diğer araçları barındıran, geliştiricilere **_Android_** ve **_iOS_** platformu için uygulama geliştirmeler imkanı sunan bir mobil uygulama SDK’sıdır. Google tarafından geliştirilen Flutter, açık kaynak kodlu olup, tüm geliştirici ve tasarımcılar tarafından ücretsiz olarak kullanılabilirdir.

**Flutter’ın avantajları nelerdir ?**

Cross platform desteği. Cross platform, **ios** ve **android** platformları uygulama çıkarmaktır. **Cordova, Xamarin, React Native** gibi araçlar da bu işi görüyordu fakat bu araçları kullanırken araya hep araç ya da köprü giriyordu. Flutter da ise direk olarak native çıktısını alabiliyoruz.

![](https://cdn-images-1.medium.com/max/800/1*VKUiM2RoFX4DZAeVTxS1Tg.png)

Flutter mimarisi

Daha derin **Flutter incelemesi** için aşağıdaki yazıya göz atabilirsiniz.

[**Flutter nedir, nasıl çalışır, ne olacak? (Dikkat React N t ve çıkabilir)**  
_Başlıktaki parantez içi eksik değil. Yukarıda gördüğünüz 6 ay önce yazdığım yazının başlığına küçük bir gönderme :)_medium.com](https://medium.com/kodcular/flutter-nedir-nas%C4%B1l-%C3%A7al%C4%B1%C5%9F%C4%B1r-ne-olacak-dikkat-react-n-t-ve-%C3%A7%C4%B1kabilir-685c41977a88 "https://medium.com/kodcular/flutter-nedir-nas%C4%B1l-%C3%A7al%C4%B1%C5%9F%C4%B1r-ne-olacak-dikkat-react-n-t-ve-%C3%A7%C4%B1kabilir-685c41977a88")[](https://medium.com/kodcular/flutter-nedir-nas%C4%B1l-%C3%A7al%C4%B1%C5%9F%C4%B1r-ne-olacak-dikkat-react-n-t-ve-%C3%A7%C4%B1kabilir-685c41977a88)

**Kurulum nasıl yapılır ?**

Kurulum için aşağıdaki yazıları takip edebilirsiniz. Ben altında Linux için nasıl kurulması gerektiğini anlatacağım.

[**Install**  
_Select the operating system on which you are installing Flutter:{{site.alert.note}} \*\*Are you on Chrome OS?\*\* If so…_flutter.dev](https://flutter.dev/docs/get-started/install "https://flutter.dev/docs/get-started/install")[](https://flutter.dev/docs/get-started/install)

**Flutter Linux kurulumu ?**

1.  Şuradan [**https://flutter.dev/docs/get-started/install/linux**](https://flutter.dev/docs/get-started/install/linux) .tar uzantılı dosyayı indierlim.
2.  İndirdikten sonra aşağıdaki kodları çalıştıralım

    cd ~/development$ tar xf ~/Downloads/flutter_linux_v1.7.8+hotfix.4-stable.tar.xz

3\. Path atalım.

export PATH=”$PATH:\`pwd\`/flutter/bin

4\. Aşağıdaki kodları çalıştıralım.

    flutter precacheflutter doctor

![](https://cdn-images-1.medium.com/max/800/1*QdFyMrDLppZIqlGU9SS60g.png)

**flutter doctor** komutunun çıktısıdır. bu çıktı bütün kurulum bittikten sonraki halidir. Sizdekinin hepsini tik olmayabilir.

5\. Şimdi Path’ı güncelleyelim.

nano .bashrc   
export PATH=$PATH:/<home/nafi/Masaüstü/flu>/flutter/bin

Yukarıda <> arasındaki alanı kendi dosya konumunuza göre ayarlayabilirsiniz.

6\. Android studio’yu bilgisayarımıza indirelim.

[**Download Android Studio and SDK tools**  
_Create complex layouts with ConstraintLayout by adding constraints from each view to other views and guidelines. Then…_developer.android.com](https://developer.android.com/studio "https://developer.android.com/studio")[](https://developer.android.com/studio)

7\. Android studio’yu kurduktan sonra emulator oluşturalım.

Sırasıyla

Android Studio > Tools > Android > AVD Manager açın  
Create Virtual Device  
Uygun telefonunu ve sistemi seçerek emulator kurulumunu tamamlayın.

8\. Android Studio’ya Flutter eklentisini indirelim.

1.  Android Studio’yu başlatın
2.  Eklentiler kısmını açınız (**File > Settings > Plugins** ).
3.  **Browse repositories** seçin, Flutter eklentisini bulun ve indirin.
4.  Dart eklentisini de buluo ve indirin.
5.  Android Studio’yu tekrar başlatınız.

9\. Visual Studio Code içinde Flutter ve Dart eklentisini ekleyebilirsiniz. Ben Visual Studio Code’u kullanıyorum kod yazmak için.

![](https://cdn-images-1.medium.com/max/800/1*4YQ70cxnr-a8d-ZQxAkepw.png)

> 1 numara -> debug kısmını tıklayınız

> 2 numara -> tıklayarak flutter’ı seçiniz.

> 3 numara -> play tuşuna tıklayarak emulatoru başlatabilirsiniz.

![](https://cdn-images-1.medium.com/max/800/1*nxIJafam3MJLqWlQRo791A.png)

emulator’u başlattıktan sonra çalışan araç çubuğu

10\. Şimdi tekrar **flutter doctor** komutunu çalıştıralım. Bütün maddelerin doğru çalıştığına emin olunuz.

![](https://cdn-images-1.medium.com/max/800/1*QdFyMrDLppZIqlGU9SS60g.png)

Şimdi istediğiniz mobil uygulamayı yazmaya başlayabilirsiniz.

* * *

Bana ulaşabileceğiniz iletişim adresleri ,

> [**_Twitter_**](http://www.twitter.com/nafidurmus?source=post_page---------------------------)  _,_ [**_Instangram_**](http://www.instagram.com/nafidurmus?source=post_page---------------------------) _,_ [**_Facebook_**](https://www.facebook.com/nafidurmus?source=post_page---------------------------) **_,_** [**_Medium_**](https://medium.com/@nafidurmus?source=post_page---------------------------) **_,_** [**_Github_**](https://github.com/nafidurmus) **_,_**[**_Linkedin_**](https://www.linkedin.com/in/nafidurmus?source=post_page---------------------------)**_,_**[**_Youtube_**](https://www.youtube.com/c/nafidurmus?source=post_page---------------------------)**_,_**[**_Mail_**](http://nafidurmus07@gmail.com/?source=post_page---------------------------)

By [nafi durmuş](https://medium.com/@nafidurmus) on [August 4, 2019](https://medium.com/p/7bc38366e80c).

[Canonical link](https://medium.com/@nafidurmus/flutter-nedir-neden-kullan%C4%B1l%C4%B1r-nas%C4%B1l-kurulum-yap%C4%B1l%C4%B1r-7bc38366e80c)

Exported from [Medium](https://medium.com) on August 10, 2019.
