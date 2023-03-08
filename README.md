Verilen dizi: [22, 27, 16, 2, 18, 6]

1.Adım: İlk eleman olan 22'yi pivot olarak seçtik. Dizide pivot elemandan küçük olanlar sol tarafa, büyük olanlar sağ tarafa ayrıldı. Son durum: [2, 18, 16, 6, 22, 27]


2.Adım: Sol taraftaki alt diziyi aynı şekilde sıraladık. Pivot olarak 2'yi seçtik. Dizide pivot elemandan küçük olanlar sol tarafa, büyük olanlar sağ tarafa ayrıldı. Son durum: [2, 6, 16, 18, 22, 27]


3.Adım: Sağ taraftaki alt diziyi aynı şekilde sıraladık. Pivot olarak 22'yi seçtik. Dizide pivot elemandan küçük olanlar sol tarafa, büyük olanlar sağ tarafa ayrıldı. Son durum: [2, 6, 16, 18, 22, 27]
Büyük O gösterimi: O(n log n)


18 sayısı için ortalama durumda O(log n) zaman karmaşıklığı beklenir. Bu nedenle, 18 sayısının sıralanması için ortalama durumda O(log n) zaman karmaşıklığı beklenir.
