# 🍿 Popcorn
## Canlı versiyon : <a href="https://popcorn-movie-review.netlify.app/">Popcorn</a>
- Create react app ile oluşturduğum, kullanıcıların izledikleri film veya dizileri puanlayıp kaydedebildiği basit bir react web uygulamasıdır.

## 📝Proje Özellikleri:

- Kullanıcı puanlamak istediği film veya diziye arama motorundan kolaylıkla ulaşabilir.
- Seçilen film veya dizi kullanıcılar tarafından 1-10 arası puanlanabilir ve izlenenler listesine eklenebilir.
- Puanlanan dizi veya film aynı kullanıcı tarafından tekrardan puanlanamaz.
- Oylanan dizi veya filmler kolaylıkla izlenenler listesinden çıkarılabilir.
- Kullanıcı, enter tuşu ile arama kutucuğuna focuslanabilir.

# 🛠 Kullanılan React Özellikleri:

- Arama girdisini kontrol altına almak için react controlled elements kullandım (value -  onChange).
- Arama durumuna bağlı olarak conditional rendering kullandım (Start searching-Loading-Not found).
- Arama keyine göre api işlemlerimi yönetmek için (veri getirmek) fecth api kullandım.
- Veri almak, local storage ve keyPress durumları için custom hooks kullandım.
- Arayüzü verilerle senkronize tutmak için useState ve useEffect kullandım.
- Yeniden kullanılabilir StarRating componenti kullandım.
- Performansı artırmak için giriş alanına girilen her veriden sonra önceki API çağrılarının temizlenmesi(Signal abort).
- API işlemlerini yönetirken fetch kullanmanın yanı sıra, gereksiz ağ isteklerinden kaçınmak ve kaynak tüketimini optimize etmek için AbortController özelliğini de kullandım. Özellikle kullanıcı etkileşimleri sırasında iptal edilmesi gereken isteklerde signal ile fetch isteklerini kontrol edip AbortController ile dinamik olarak isteği iptal ettim. Bu yöntem sayesinde giriş alanına girilen her veriden sonra önceki API çağrılarının temizlemiş, projemde hızlı ve verimli veri işleme sağlarken kullanıcı deneyimini de iyileştimiş oldum.
- React'in bildirimsel yapısını bozmamak için component içinde bir html elementi seçmek için UseRef kullandım.

![React-use-Pop-Corn](public/usePopCorn.gif)
