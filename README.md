**HuggingFaceHub** 🤗</br>

Hugging Face tarafından sağlanan bir platformdur ve önceden eğitilmiş modeller (machine learning models) ve veri setleri ile ilgili hizmetler sunar. </br>
Hugging Face Hub, özellikle transformer tabanlı modeller için popüler bir platformdur (örn. BERT, GPT, T5, BART, vb.)</br>

Bu kod, google/flan-t5-large modelini Hugging Face Hub'dan yükler. </br>
</br>
**Model Yükleme:** google/flan-t5-large modelini Hugging Face Hub'dan yükler.</br>
**Model Parametrelerini Ayarlama:** model_kwargs parametresi, modelin nasıl çalışacağını etkiler. Burada, modelin sıcaklık ve maksimum token uzunluğu gibi özellikleri ayarlanır.</br>
**API ile Etkileşim:** huggingfacehub_api_token, Hugging Face API'sine erişim için gerekli olan token'dır. Bu, modelin kullanılabilirliği ve API üzerinden doğru şekilde erişebilmesi için gereklidir.</br>
**Dil Modeli ile Çalışma:** Bu modelin sağladığı API üzerinden, verilen girişlere göre yanıtlar almayı sağlar. Örneğin, metin üretimi, özetleme, çeviri gibi işlemleri gerçekleştirmeyi sağlar.</br>

**HuggingFaceHub'tan Token Alma:** </br> 
HuggingFaceHub sayfasından bir hesap oluşturularak profil ayarları kısmından Access Tokens sekmesinde Create New Token butonuna tıklayarak yeni bir API token oluşturulabilir. Token bir kez gösterildikten sonra bir daha gösterilmeyecektir, bu yüzden doğru şekilde saklamak önemlidir. Hugging Face API'lerine erişim sağlamak için bu token kullanılabilir. Token, HUGGINGFACEHUB_API_TOKEN environment variable ile projelerde kullanılabilir.
![image](https://github.com/user-attachments/assets/2096830d-613b-467a-bb38-e495ae86fd12)


Bu örnek, "What is the capital of UK" gibi bir giriş cümlesi verildiğinde modelin cevabını döndürmektedir.</br>

