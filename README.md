# Deneme
 `KOD`
[Readme yazım klavuzu](https://help.github.com/en/articles/basic-writing-and-formatting-syntax)

### VsCode ile repo bağlantılarını demek için yapıldı.

- Repo clonlamak: <br/>
 *git clone repo adresi*

- **Staged:** "+" işaretine bastığımızda staged (sahneye alma) durumuna getirmeliyiz.cmd ile yaparsak:(git add README.md)<br/>
VSCode üzerinde yapabilmek için ilgili dosya ismi üzerinde yer alan + işaretine basabilirsiniz veya birden fazla dosyanının durumunu staged’a getirmek için CHANGES yazan satırın yanındaki + işaretine basabilirsiniz.

- **Commit:** İlgili dosyalardaki değişiklikleri kabul ettikten sonra yorum girerek commit etmemiz gerekmektedir.Tik işareti ile yapabilirsin.

- **Push:** Commit sonrası dosyalarımızı karşı tarafa yüklemek için ... işaretine basıp Push seçeneğini seçmeliyiz.
- **Pull:** en son değişiklikleri (commit) yerel deponuza almak için(git pull) otomatik merge yapar.
- **Pull rebase:** Seçersek ,pull +fetch yapar. (git fetch bu komutla), GitHub’daki değişiklikler farklı bir dala alınır.Kendin merge yapman gerekir.Önce bi kodları kontrol etmemizi sağlar.

- Sol alt köşede mevcut dalın üzerine tıklayarak **dallar arası geçiş** yapılabilir.
- Yanında **Senkronizasyon** sekmesi var .Ek olarak ... işaretinden Snyc ile repo ve bilgisayar arasında bilgi transferi sağlanılabilir.

- **Yeni bir dal** oluşturmak için sol alt köşede mevcut dalın üzerine tıklayıp Komut Paletinden ; Create new branch  sekmesine tıklanılır ardından açık dallar listelenir.From yazısı gelir.Yeni dalın hangi daldan türetileceği seçilir.

- **Git History** Bu eklenti ile yapılan işlemleri ,dalları listeleyebilir üzerinde değişiklik yapabilirsin.
   - Eski dosyaları gözlemleyebilir, yenileriyle karşılaştırabilirsin (dosya ismine tıklayınız.)
   - Eski dosyadan yeni bir dal açabilirsin (Sah hizadaki düğüme tıklayınız.)
   - İşlem zamanlamasını tahlil edebilir,Özel bir dal üzerinde yapılan değişikliklere bakabilirsin.
   - Dosya değişiklerini geri silebilirsiniz.
   
- **Etiket:** git tag -a v1.4 -m 'sürümüm 1.4'
- **Yardım:** git help komut_adi

### Projenin ilk cmd komutları
- İlk komutlar kendimizi sisteme tanıtmak içindir.<br/>

*git config --global user.name "talimgah" <br/>*
*git config --global user.email eposta@adresiniz.com*
  

 

  
  
