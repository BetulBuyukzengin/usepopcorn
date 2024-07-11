# 🍿 Popcorn
## Canlı versiyon : <a href="https://popcorn-movie-review.netlify.app/">Popcorn</a>
- Kullanıcıların izledikleri film veya dizileri puanlayıp kaydedebildiği basit bir web uygulamasıdır.

## 📝Proje Özellikleri:

- Kullanıcı puanlamak istediği film veya diziye arama motorundan kolaylıkla ulaşabilir.
- Seçilen film veya dizi kullanıcılar tarafından 1-10 arası puanlanabilir ve izlenenler listesine eklenebilir.
- Puanlanan dizi veya film aynı kullanıcı tarafından tekrardan puanlanamaz.
- Oylanan dizi veya filmler kolaylıkla izlenenler listesinden çıkarılabilir.
- Kullanıcı, enter tuşu ile arama kutucuğuna focuslanabilir.

# 🛠 Kullanılan React Özellikleri:

- Arama girdisini kontrol altına almak için react controlled elements kullandım (value -  onChange).
- Arama durumuna bağlı olarak conditional rendering kullandım (Start searching-Loading-Not found).
- Arama keyine göre apiden veri getirme (fecth).
- Veri almak, local storage ve keyPress durumları için custom hooks kullandım.
- Arayüzü verilerle senkronize tutmak için useState ve useEffect.
- Yeniden kullanılabilir StarRating componenti.
- Performansı artırmak için giriş alanına girilen her veriden sonra önceki API çağrılarının temizlenmesi(Signal abort).
- React'in bildirimsel yapısını bozmamak için component içinde bir html elementi seçmek için UseRef.

![React-use-Pop-Corn](public/usePopCorn.gif)
