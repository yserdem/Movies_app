# HTTP / AJAX II React Modül Projesi: CRUD Film

Bugün CRUD operasyonlarını put, delete, edit requestleri ile yapmayı öğrendiniz. Ayrıca, Route bağlantılı bileşenlere propların nasıl iletileceğini ve bir API'den değer almak için URL parametrelerinin nasıl kullanılacağını araştırdınız. Bu projede, geçen hafta üzerinde çalıştığımız film veritabanı uygulamasına CRUD işlevleri ekleyeceksiniz.

## Giriş

CRUD uygulamaları çoğu web uygulamasının temelidir. Harici bir kaynaktan veri oluşturmayı, düzenlemeyi ve silmeyi yönetebilmek, olabildiğince önemli bir beceridir. Bu projede, tüm bu temel eylemlere izin vermek için gerekli kodu tamamlayacaksınız.

### Kaynak: API dökümanı

#### GET `http://localhost:9000/api/movies`

- Aşağıdaki formatta sunucudaki tüm filmleri getirir.

```
[{
  id: 5,
  title: 'Tombstone',
  director: 'George P. Cosmatos',
  metascore: 89,
  genre: "Drama",
  description: : "A successful lawman's plans to retire anonymously in Tombstone, Arizona are disrupted by the kind of outlaws he was famous for eliminating."
}]
```

#### GET `http://localhost:9000/api/movies/:id`

- Girilen id'ye sahip filmi getirir.

#### POST `http://localhost:9000/api/movies`

- Body de aktarılan bilgilerle yeni bir film ekler. **Güncellenmiş movie listesini döndürür.**

#### PUT `http://localhost:9000/api/movies/:id`

- Girilen id li filmin body deki bilgilerini günceller. **Güncellenmiş film listesini döndürür.**

#### DELETE `http://localhost:9000/api/movies/:id`

- Girilen id deki filmi listeden siler. **Silinen filmin id sini döndürür.**

