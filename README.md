# React Film Platformu

Bu, **The Movie Database (TMDb)** API'sini kullanarak film bilgilerini bulmanıza, keşfetmenize ve kendi izleme listenizi oluşturmanıza olanak tanıyan, React tabanlı modern bir web uygulamasıdır. Bu proje, React'in temel ve ileri düzey konseptlerini (Hooks, Context API, Routing) ve harici bir API ile nasıl çalışılacağını anlamak için mükemmel bir örnektir.

## İçindekiler

- [Özellikler](#özellikler)
- [Kullanılan Teknolojiler](#kullanılan-teknolojiler)
- [Başlarken](#başlarken)
  - [Ön Gereksinimler](#ön-gereksinimler)
  - [Kurulum](#kurulum)
- [Kullanım](#kullanım-)
- [Katkıda Bulunma](#katkıda-bulunma-)
- [Lisans](#lisans-)

## Özellikler

- Popüler ve en yüksek puanlı filmleri listeleyin.
- Filmleri başlığa göre anlık olarak arayın.
- Filmlerin detaylı bilgilerini (konu, oyuncular, puan vb.) görüntüleyin.
- Kullanıcıya özel "İzleme Listesi" (Watchlist) oluşturma ve yönetme.
- Farklı sayfalar arasında hızlı geçiş sağlayan modern SPA (Tek Sayfa Uygulaması) mimarisi.
- Mobil ve tablet gibi farklı cihazlarla uyumlu duyarlı tasarım.

## Kullanılan Teknolojiler

- HTML5 & CSS3
- JavaScript (ES6+)
- **React.js** (Context API ve Hooks ile)
- **React Router** (Sayfa yönlendirme için)
- **The Movie Database (TMDb) API**

## Başlarken

### Ön Gereksinimler

Başlamadan önce, sisteminizde aşağıdakilerin kurulu olduğundan emin olun:

- **Node.js** - [nodejs.org](https://nodejs.org/) adresinden indirin ve kurun.
- **TMDb API Anahtarı** - [themoviedb.org](https://www.themoviedb.org/signup) adresinden ücretsiz bir hesap oluşturup API anahtarınızı alın.

### Kurulum

1.  Depoyu (repository) yerel makinenize klonlayın:
    ```bash
    git clone [https://github.com/D-veloper/react-movie-app.git](https://github.com/D-veloper/react-movie-app.git)
    ```

2.  Proje dizinine gidin:
    ```bash
    cd react-movie-app
    ```

3.  Proje bağımlılıklarını kurun:
    ```bash
    npm install
    ```
4.  Projenin ana dizininde `.env` adında bir dosya oluşturun ve içine TMDb API anahtarınızı aşağıdaki gibi ekleyin:
    ```
    REACT_APP_API_KEY=anahtarınızı_buraya_yapıştırın
    ```

5.  Geliştirme sunucusunu başlatın:
    ```bash
    npm start
    ```

6.  Web tarayıcınızı açın ve uygulamayı görüntülemek için `http://localhost:3000` adresine gidin.

## Kullanım 📝

### Filmleri Keşfetme 🍿

- **Ana sayfada** popüler filmlere göz atın.
- **Navigasyon menüsünü** kullanarak "Popüler" veya "En Yüksek Puanlı" filmlerin olduğu sayfalara gidin.

### Film Arama 🎥

1.  Sayfanın üst kısmındaki **arama kutusuna** bulmak istediğiniz filmin adını yazmaya başlayın.
2.  Uygulama, siz yazdıkça arama sonuçlarını **anlık olarak** güncelleyecektir.

### Film Detaylarını Görüntüleme 📽️

- Herhangi bir film afişine tıklayarak o filmin konusunu, türlerini, oyuncu kadrosunu ve puanını içeren **detay sayfasına** gidin.

### İzleme Listesi Oluşturma  watchlist 

- Film kartlarındaki veya detay sayfasındaki **"Listeme Ekle"** ikonuna/butonuna tıklayarak filmi kişisel izleme listenize ekleyin.
- Navigasyon menüsündeki **"İzleme Listem"** linkine tıklayarak listenizi görüntüleyin.

## Katkıda Bulunma 🤝

Katkılarınız projenin gelişimi için çok değerlidir! Eğer katkıda bulunmak isterseniz, lütfen aşağıdaki adımları izleyin:

1.  **Depoyu GitHub'da Fork'layın.**
2.  **Fork'ladığınız Depoyu Yerel Makinenize Klonlayın.**
    ```bash
    git clone [https://github.com/](https://github.com/)<kullanici-adiniz>/react-movie-app.git
    ```
3.  **Yeni Bir Branch Oluşturun.**
    ```bash
    git checkout -b ozellik/harika-yeni-ozellik
    ```
4.  **Değişikliklerinizi Yapın ve Anlamlı Mesajlarla Commit'leyin.**
    ```bash
    git commit -m "Özellik eklendi: Kullanıcıların filmlere puan verebilmesi sağlandı"
    ```
5.  **Değişikliklerinizi GitHub'daki Fork'unuza Push'layın.**
    ```bash
    git push origin ozellik/harika-yeni-ozellik
    ```
6.  **Ana Depoya Bir Pull Request Oluşturun.**
    Değişikliklerinizi net bir şekilde açıklayarak bir pull request gönderin.
