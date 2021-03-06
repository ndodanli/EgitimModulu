# Eğitim Modülü
Eğitim Modülü, eğitim kurumlarının öğretmenleri ve öğrencileri yöneterek kendi eğitim sistemini online olarak uygulayabilecekleri bir uygulamadır.

  - Kurumlar
  - Öğretmenler
  - Öğrenciler

# Ne yapılabilir?

  - Öğretmenler, kurumdaki öğrenciler için online sınavlar düzenleyebilir
  - Öğretmenler, kurumdaki öğrenciler için döküman paylaşımında bulunabilir
  - Öğretmenler, kurumdaki öğrencileri istatistiksel analizler ile takip edebilir
  - Öğretmenler, kurumdaki öğrenciler ile iletişime geçebilir(düşünülüyor)
  - Kurumlar, öğretmenlerini ve öğrencilerini takip edip istatistiksel analizler ile çıkarımlar yapabilir


Ayrıca:
  - Kurumlar, kendi oluşumlarına uygun planlara göre hizmet alabilir
  >Planları tamamen dinamik olarak belirleme düşünülüyor.
  

## Projenin Tasarlanması

**Wiki**

* [Proje planı] - Projenin içeriklerinin belirlenmesi
* [Gereksinim analizi] - Projede bulunması gereken fonksiyonel gereksinimlerin gösterilmesi

### Projede kullanılması planlanan teknolojiler
**Backend için [NodeJs]**

**Temelde kullanılabilecek bazı paketler(Backend)**
| Npm Paket| Nedir? |
| ------ | ------ |
| express | Web sunucu çatısı |
| express-session | User işlemleri için session|
| passport | Authentication işlemleri |
| sequelize | Database bağlantısı ve işlemleri için ORM |
| pg | PostgreSql işlemleri |

> Not: Authentication işlemleri için **JWT** bazlı doğrulama düşünülebilir**

**Frontend için [ReactJs]**
### Kullanılabilecek kurulum paketleri
- create-react-app(Client Side Rendering, klasik ReactJs)
- NextJs(Server Side Rendering)

**Temelde kullanılabilecek bazı paketler(Frontend)**
| Npm Paket| Nedir? |
| ------ | ------ |
| axios | HTTP Requests |
| redux | Yönetim kütüphanesi(Veri yönetimi)|
| connected-react-router | Routing işlemleri(redux ile uyumlu) |

**Düşünülen CSS Frameworkleri**
- Semantic UI
- Bootstrap
- Material UI
- Tailwind

**Database için [PostgreSQL], [MySQL] ya da [MSSQL] düşünülüyor**

**Projenin ürün aşamasında [DOCKER] desteği düşünülüyor**


### Geliştirme süreci için araştırmalar devam ediyor...


   [Proje planı]: <https://github.com/ndodanli/SinavModulu/wiki/AnaSayfa>
   [Gereksinim analizi]: <https://github.com/ndodanli/SinavModulu/wiki/Gereksinim-Analizi>
   [NodeJs]: <https://nodejs.org/en/>
   [ReactJs]: <https://reactjs.org//>
   [PostgreSQL]: <https://www.postgresql.org/>
   [MySQL]: <https://www.mysql.com/>
   [MSSQL]: <https://www.microsoft.com/tr-tr/sql-server/sql-server-2019>
   [DOCKER]: <https://www.docker.com/>
