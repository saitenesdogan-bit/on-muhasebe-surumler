# Ön Muhasebe — kurulum ve güncelleme

Bu sayfa programın **kurulum dosyalarını** ve **güncellemelerini** dağıtır. Kayıtlarınız (müşteriler, satışlar, giderler…) buraya hiçbir zaman gelmez; her bilgisayarda yalnız o bilgisayarda saklanır.

## İndir (her zaman en son sürüm)

| Bilgisayar | Dosya |
| --- | --- |
| **Mac** (macOS 13.5 ve üstü) | [On-Muhasebe-Mac.dmg](https://github.com/saitenesdogan-bit/on-muhasebe-surumler/releases/latest/download/On-Muhasebe-Mac.dmg) |
| **Windows** (10 ve 11) | [On-Muhasebe-Windows-Kurulum.exe](https://github.com/saitenesdogan-bit/on-muhasebe-surumler/releases/latest/download/On-Muhasebe-Windows-Kurulum.exe) |

Tüm sürümler ve yenilikler: [Sürümler](https://github.com/saitenesdogan-bit/on-muhasebe-surumler/releases)

## Mac'e kurulum

1. `On-Muhasebe-Mac.dmg` dosyasını açın.
2. **Ön Muhasebe** simgesini yanındaki **Uygulamalar** klasörüne sürükleyin.
3. Uygulamalar klasöründen **Ön Muhasebe**'yi açın.

İlk açılışta macOS *"Apple, Ön Muhasebe'nin kötü amaçlı yazılım içermediğini doğrulayamadı"* diyebilir (program App Store dışından geldiği için). Bu durumda **Bitti** deyin, **Sistem Ayarları › Gizlilik ve Güvenlik** bölümünü açın, aşağıdaki *"Ön Muhasebe engellendi"* yazısının yanındaki **Yine de Aç** düğmesine basın ve parolanızı girin. Bu yalnız bir kez sorulur.

## Windows'a kurulum

1. `On-Muhasebe-Windows-Kurulum.exe` dosyasını çalıştırın.
2. Windows *"Bilgisayarınız korundu"* derse **Ek bilgi › Yine de çalıştır**'a basın.
3. Kurulum yönetici izni istemez; masaüstüne ve Başlat menüsüne **Ön Muhasebe** kısayolu ekler.

## İlk açılış

Kullanıcı adınızı ve şifrenizi (en az 8 karakter) belirleyin. Ardından açılan **kurulum sihirbazı** şirket bilgilerinizi, logonuzu, KDV oranınızı ve müşteri/şirketlerinizin açılış borçlarını adım adım sorar. İstediğiniz adımı atlayıp sonra yapabilirsiniz.

## Güncelleme — kayıtlarınız silinmez

Yeni sürüm çıkınca programın sol menüsünde **"Yeni sürüm hazır"** uyarısı çıkar. Tıklayıp **Güncelle**'ye basın:

- Program önce kayıtlarınızın **yedeğini alır**,
- yeni sürümü indirir ve **dijital imzasıyla** gerçekten yayıncıdan geldiğini doğrular (imzası tutmayan paket kurulmaz),
- kurar ve birkaç saniye içinde yeniden açılır.

Kurulum dosyasını yeniden çalıştırmak (üstüne kurmak) da kayıtlara dokunmaz. Programı kaldırmak bile kayıtları silmez.

**Kayıtların yeri:**

- Mac: *Kullanıcı klasörü › Kitaplık › Application Support › Ön Muhasebe*
- Windows: *%APPDATA%\Ön Muhasebe*

## Bilgisayar değiştirirken

Eski bilgisayarda **Yedekleme › Şimdi yedek al ve indir** ile yedek alın. Yeni bilgisayara programı kurun, aynı sayfadaki **Yedekten geri yükle** ile o dosyayı yükleyin. Mac'te **iCloud'a haftalık şifreli kopya** açıksa iCloud Drive'daki `.omyedek` dosyasını da yedek şifrenizle yükleyebilirsiniz.
