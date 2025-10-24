# 🧠 Attention Is All You Need - Azərbaycan dilinə tərcümə

Bu layihə "Attention Is All You Need" məqaləsinin Azərbaycan dilinə tərcüməsidir. Bu tarixi məqalə Transformer arxitekturasını təqdim edib və müasir süni intellekt və dil modellərinin əsasını qoyub.

## 📖 Haqqında

**Orijinal məqalə:** Vaswani et al. (2017) - "Attention Is All You Need"  
**Məqalə linki:** [arXiv:1706.03762](https://arxiv.org/abs/1706.03762)

Bu məqalə:
- Transformer arxitekturasını ilk dəfə təqdim edir
- Rekurrent və konvolyusiya şəbəkələrindən tam imtina edərək yalnız diqqət mexanizminə əsaslanır
- Maşın tərcüməsində yeni standartlar müəyyən edir (WMT 2014: 28.4 BLEU)
- BERT, GPT, T5 və digər müasir modellərin əsasını təşkil edir

## 🎯 Məqsəd

Bu tərcümənin məqsədi Azərbaycan dilində danışan tədqiqatçılar, tələbələr və AI sahəsində maraq göstərən hər kəs üçün bu fundamental məqaləni əlçatan etməkdir.

## 📁 Layihə Strukturu

```
.
├── index.html              # Əsas HTML səhifə (tam tərcümə)
├── 1706.03762v7.pdf       # Orijinal məqalə (PDF formatında)
└── README.md              # Bu fayl
```

## 🚀 İstifadə

### Onlayn Baxış
Sadəcə `index.html` faylını istənilən müasir brauzer (Chrome, Firefox, Safari, Edge) ilə açın.

### Lokal İstifadə
1. Layihəni klonlayın və ya endirin
2. `index.html` faylını brauzerdə açın
3. Heç bir server və ya əlavə konfiqurasiya tələb olunmur

## ✨ Xüsusiyyətlər

- 📱 **Responsive dizayn** - mobil və masaüstü cihazlarda mükəmməl görünür
- 🎨 **Modern UI/UX** - gradient rənglər və vizual cəlbedici dizayn
- 📊 **Formul və cədvəllər** - texniki məzmunun aydın təqdimatı
- 🔗 **Naviqasiya** - bölmələr arasında sürətli keçid
- 📥 **PDF yükləmə** - orijinal məqaləyə birbaşa çıxış
- 🌐 **Tam Azərbaycan dilində** - texniki terminlər və izahlar daxil olmaqla

## 📚 Məzmun

Tərcümə aşağıdakı əsas bölmələri əhatə edir:

1. **Xülasə (Abstract)** - Məqalənin qısa xülasəsi
2. **Giriş (Introduction)** - Transformer-in zərurəti və motivasiyası
3. **Model Arxitekturası** - Kodlayıcı və dekodlaşdırıcı strukturu
4. **Diqqət Mexanizmi** - Scaled Dot-Product və Multi-Head Attention
5. **Təlim (Training)** - Təlim prosesi və parametrlər
6. **Nəticələr (Results)** - Performans göstəriciləri və müqayisələr

## 🎓 Texniki Təfərrüatlar

### Əsas Komponentlər
- **Encoder-Decoder Strukturu**: N=6 qat
- **Multi-Head Attention**: 8 başlıq
- **Model Ölçüsü**: d_model = 512
- **Feed-Forward Şəbəkə**: d_ff = 2048
- **Dropout**: 0.1

### Nəticələr
- **WMT 2014 EN-DE**: 28.4 BLEU
- **WMT 2014 EN-FR**: 41.8 BLEU
- **Təlim vaxtı**: 12 saat (8 P100 GPU)

## 🔧 Texnologiyalar

- **HTML5** - Struktur
- **CSS3** - Stil və dizayn (gradient, flexbox, grid)
- **Vanilla JavaScript** - Minimal interaktivlik (PDF yükləmə)

## 👥 Orijinal Müəlliflər

- Ashish Vaswani (Google Brain)
- Noam Shazeer (Google Brain)
- Niki Parmar (Google Research)
- Jakob Uszkoreit (Google Research)
- Llion Jones (Google Research)
- Aidan N. Gomez (University of Toronto)
- Łukasz Kaiser (Google Brain)
- Illia Polosukhin

## 📝 Tərcümə Haqqında

Bu tərcümə akademik dəqiqlik və oxunabilirlik arasında tarazlığı saxlamağa çalışır. Texniki terminlər mümkün qədər Azərbaycan dilində verilmiş, lakin zəruri hallarda ingilis terminlər də qeyd edilmişdir.

### Terminologiya
- **Attention** → Diqqət
- **Transformer** → Transformer (saxlanılıb)
- **Encoder** → Kodlayıcı
- **Decoder** → Dekodlaşdırıcı
- **Self-Attention** → Özünə-diqqət
- **Multi-Head** → Çox başlıqlı

## 🤝 Töhfə

Bu tərcüməni təkmilləşdirmək üçün töhfələr alqışlanır! Səhv tapdığınız və ya təkmilləşdirmə təklifi etmək istədiyiniz hissələr varsa:

1. Issue açın
2. Pull request göndərin
3. Düzəlişlərinizi təklif edin

## 📄 Lisenziya

Orijinal məqalə: [Apache License 2.0](https://arxiv.org/abs/1706.03762)  
Bu tərcümə: Təhsil məqsədləri üçün pulsuz istifadə edilə bilər

## 🔗 Əlaqəli Mənbələr

- [Orijinal məqalə (arXiv)](https://arxiv.org/abs/1706.03762)
- [TensorFlow tensor2tensor](https://github.com/tensorflow/tensor2tensor)
- [The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/)
- [Attention Is All You Need (Video)](https://www.youtube.com/watch?v=iDulhoQ2pro)

## 📧 Əlaqə

Suallar və ya rəylər üçün issue açın.

---

**Qeyd:** Bu tərcümə təhsil və tədqiqat məqsədləri üçün hazırlanmışdır. Orijinal məqaləyə istinad etməyi unutmayın:

```bibtex
@article{vaswani2017attention,
  title={Attention is all you need},
  author={Vaswani, Ashish and Shazeer, Noam and Parmar, Niki and Uszkoreit, Jakob and Jones, Llion and Gomez, Aidan N and Kaiser, {\L}ukasz and Polosukhin, Illia},
  journal={Advances in neural information processing systems},
  volume={30},
  year={2017}
}
```

⭐ Layihəni bəyəndinizsə, ulduz verməyi unutmayın!
