# Avtomobil Elanlarının Statistik Analizi

Bu layihədə Azərbaycan avtomobil bazarına aid elan məlumatları üzərində statistik analiz və Exploratory Data Analysis (EDA) aparılmışdır. Layihənin əsas məqsədi avtomobil qiymətlərinə təsir edən faktorları araşdırmaq, qruplar arasında qiymət fərqlərini statistik testlərlə yoxlamaq və nəticələri biznes baxımından interpretasiya etməkdir.

## Layihənin məqsədi

Layihə çərçivəsində aşağıdakı əsas analizlər həyata keçirilmişdir:

- Avtomobil qiymətlərinin əsas statistik göstəricilərinin analizi
- Marka, ötürücü növü və satıcı tipinə görə qiymət fərqlərinin araşdırılması
- Mühərrik həcmi və yürüş göstəricilərinin statistik təhlili
- Statistik hipotezlərin qurulması və yoxlanılması
- Nəticələrin biznes qərarları ilə əlaqələndirilməsi

## Hipotez testləri

Parametrik testlərdən əvvəl əsas fərziyyələr yoxlanılmışdır:

- **Shapiro–Wilk testi** ilə normallıq fərziyyəsi yoxlanılmışdır.
- **Levene testi** ilə dispersiyaların bərabərliyi qiymətləndirilmişdir.

Fərziyyələrin ödənilmədiyi hallarda qeyri-parametrik testlər tətbiq edilmişdir.

## Əsas biznes sualları və hipotezlər

### 1. Ötürücü növü avtomobil qiymətinə təsir edirmi?

**H₀:** Müxtəlif ötürücü qruplarının median qiymətləri arasında fərq yoxdur.  
**H₁:** Ən azı bir ötürücü qrupunun median qiyməti digərlərindən fərqlənir.

İstifadə olunan testlər:

- Kruskal–Wallis testi
- Dunn post-hoc testi (Bonferroni korreksiyası ilə)
- Bootstrap 95% etibar intervalı

Nəticə:
Tam ötürücülü avtomobillərin qiymətləri digər ötürücü növləri ilə müqayisədə statistik olaraq daha yüksək olmuşdur. Bu fərq real bazar fərqini göstərsə də, nəticə digər faktorlarla (buraxılış ili, mühərrik gücü, SUV kateqoriyası və s.) birlikdə qiymətləndirilməlidir.

---

### 2. Satıcı tipi avtomobil qiymətinə təsir edirmi?

**H₀:** Salon və fərdi satıcıların avtomobil qiymətləri arasında fərq yoxdur.  
**H₁:** İki satıcı qrupu arasında qiymət fərqi mövcuddur.

İstifadə olunan test:

- Mann–Whitney U testi
- Bootstrap 95% etibar intervalı

Nəticə:
Salon və fərdi satıcılar tərəfindən təklif olunan avtomobillərin qiymətləri arasında statistik olaraq əhəmiyyətli fərq müəyyən edilmişdir. Salon avtomobillərinin qiymətlərinin daha yüksək olması onların daha yeni və yüksək seqment modellərlə əlaqəli olması ilə izah edilə bilər.

---

## Deskriptiv analiz nəticələri

Aparılan analizlər göstərmişdir ki:

- Avtomobil qiymətləri və yürüş göstəriciləri əsasən sağa meyilli paylanmaya malikdir.
- Bəzi markalarda qiymət və mühərrik həcmi üzrə dəyişkənlik yüksəkdir.
- Marka, ötürücü növü, yürüş məsafəsi və satıcı tipi avtomobil qiymətlərində fərqlərin yaranmasında mühüm rol oynayır.

## Biznes nəticəsi

Analiz nəticələri göstərir ki, avtomobil qiymətlərinin qiymətləndirilməsi zamanı yalnız marka deyil, həmçinin texniki xüsusiyyətlər və bazar faktorları birlikdə nəzərə alınmalıdır. Statistik nəticələr qiymət strategiyasının qurulması, bazar seqmentlərinin müəyyənləşdirilməsi və daha düzgün qiymət analizlərinin aparılması üçün istifadə edilə bilər.
