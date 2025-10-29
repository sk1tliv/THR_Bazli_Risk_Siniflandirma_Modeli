# ========================================
# Spor Salonu Üyeleri Risk Analizi Proje Özeti
# ========================================
Bu projenin temel amacı, spor salonu üyelerinin egzersiz verilerini kullanarak, potansiyel aşırı antrenman ve kardiyak zorlanma risklerini tespit etmek ve bu risklerin demografik ve antrenman alışkanlıklarıyla nasıl ilişkili olduğunu görselleştirmektir. Analiz, üyelerin antrenmanlarının güvenliğini ve sürdürülebilirliğini artırmayı hedeflemektedir.

## Temel Metrikler
Bu projenin temelini oluşturan iki risk metriği, üyelerin antrenmanlarının verimliliğini ve güvenliğini bilimsel formüllere dayanarak ölçer.

1. THR Üstü Riski (High_Intensity_Risk)

Bu metrik, bir üyenin antrenman sırasında sürekli olarak ne kadar zorladığını gösterir ve aşırı yoğunluğu tespit etmeye yarar.

- Karvonen Formülü

Karvonen metodu, sadece yaşa bağlı maksimum kalp atış hızını değil, kişinin Dinlenme Kalp Atış Hızını (Resting_BPM) da hesaba katar. Bu sayede, kişinin gerçek seviyesine göre kişiselleştirilmiş bir hedef bölge (THR) belirlenir.

2. Teorik Maksimum Üstü Riski

Bu metrik, bir üyenin tek bir anda ulaştığı en yüksek kalp atış hızının, bilimsel olarak belirlenen üst güvenlik sınırını aşıp aşmadığını kontrol eder. Bu, direkt olarak kalbin zorlanma riskini ölçer.

# Somut Bulgular ve Analizler

1. Demografik Bulgular (Yaş ve Kilo) : Yüksek yoğunluk riskini gösteren kırmızı noktalar, Yaş ve Kilo düzlemine göreceli olarak homojen dağılmıştır. Bu durum, aşırı yoğunluk riskinin spesifik bir demografik profile değil, daha çok bireyin antrenman kararlarına ve fizyolojik durumuna bağlı olduğunu göstermektedir. Ancak, genç yaş gruplarında veya ekstrem kilo gruplarında kalbi zorlama (Teorik Maksimum Üstü) riskinde hafif kümelenmeler gözlemlenmiştir.

![Yaş ve Kilo Saçılım Grafiği](Unknown-1.png)

3. Antrenman Alışkanlıkları Bulguları :

- Yüksek Yoğunluk Riski: HIIT ve Cardio antrenman tiplerinde, özellikle haftada 3 ve 4 gün sıklıkta, risk oranı belirgin şekilde yükselmiştir. Bu, bu aktivitelerin doğası gereği yüksek stres seviyesi yarattığını doğrulamaktadır.
- Düşük Riskli Alanlar: Yoga antrenmanları ve haftada 2 gün gibi seyrek sıklıklar, her iki risk metriğinde de en düşük oranlara sahiptir.

![Antrenman Isı Haritası](Unknown.png)
