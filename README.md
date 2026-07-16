## 📊 Key Insights & Business Recommendations

Data analizi (EDA) və maşın öyrənməsi modellərinin nəticələrinə əsasən əldə etdiyimiz əsas biznes tapıntıları və strateji tövsiyələr aşağıdakılardır:

---

### 🔍 Əsas Tapıntılar (Key Insights)

*   **Müqavilə Tipinin Təsiri:** Aylıq müqaviləsi olan müştərilərin (`Month-to-month`) şirkəti tərk etmə ehtimalı, 1 və ya 2 illik müqaviləsi olanlara nisbətən kəskin dərəcədə yüksəkdir. Short-term (qısamüddətli) müqavilələr ən böyük churn riskini yaradır.
*   **İnternet Xidməti Növü:** Optik lifli internet (`Fiber optic`) istifadəçilərinin churn faizi, DSL istifadəçilərinə görə olduqca yüksəkdir. Bu, qiymət narazılığı və ya texniki xidmət keyfiyyətinin aşağı olması ilə bağlı ola bilər.
*   **Müştəri Ömrü (Tenure):** Şirkətdə ilk 6 ayını keçirən yeni müştərilər arasında itki dərəcəsi ən yüksək səviyyədədir. Müştəri şirkətdə qaldığı müddət artdıqca (xüsusilə 24 aydan sonra) loyalılıq hissi güclənir və churn riski azalır.
*   **Ödəniş Metodu:** Elektron qəbzlə (`Electronic check`) ödəniş edən müştərilər, avtomatik ödəniş (Bank transfer/Credit card) edənlərə nisbətən daha tez-tez churn edirlər.

---

### 💡 Biznes üçün Tövsiyələr (Recommendations)

*   **Uzunmüddətli Müqavilələrə Keçid Kampaniyası:** Aylıq müqavilədə olan müştəriləri 1 illik və ya 2 illik müqavilələrə cəlb etmək üçün xüsusi endirimlər və ya bonuslar təklif edilməlidir. Müqavilə müddətinin uzadılması churn-ü birbaşa azaldacaq.
*   **Fiber Optik Xidmətinin Yoxlanılması:** Fiber optik istifadəçilərinin niyə getdiyini anlamaq üçün onlara məmnuniyyət sorğuları göndərilməli, qiymət/performans balansı yenidən nəzərdən keçirilməli və texniki dəstək sürətləndirilməlidir.
*   **Yeni Müştərilər üçün Onboarding Proqramı:** İlk 6 ayda olan yeni müştərilər üçün xüsusi "xoş gəldiniz" kampaniyaları və proaktiv müştəri xidmətləri təşkil edilməlidir. Onların ilkin mərhələdə qarşılaşdığı problemlər dərhal həll olunmalıdır.
*   **Avtomatik Ödənişə Həvəsləndirmə:** Elektron qəbzdən avtomatik bank/kart ödənişinə keçən müştərilərə birdəfəlik kiçik endirimlər və ya keşbeklər təklif edilərək ödəniş prosesi avtomatlaşdırılmalıdır. Bu, müştərinin hər ay ödəniş edərkən şirkətdən ayrılma fikrinə düşməsinin qarşısını alır.

---

### 🤖 Model Performansı və Biznes Dəyəri

Tədqiqat çərçivəsində qurulan **Logistic Regression Pipeline** modeli vasitəsilə potensial gedəcək müştəriləri yüksək həssaslıqla (**Recall: ~78.5%**) əvvəlcədən təxmin edə bilirik. 

*   **Tətbiq Sahəsi:** Model hər ay riskli müştərilərin siyahısını marketinq komandasına ötürür.
*   **Biznes Faydası:** Komanda yalnız bu hədəflənmiş kütləyə yönələrək büdcəni optimal xərcləyir və müştəri itkisinin qarşısını effektiv şəkildə alır.