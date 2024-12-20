HuggingFaceHub 🤗</br>

Hugging Face tarafından sağlanan bir platformdur ve önceden eğitilmiş modeller (machine learning models) ve veri setleri ile ilgili hizmetler sunar. </br>
Hugging Face Hub, özellikle transformer tabanlı modeller için popüler bir platformdur (örn. BERT, GPT, T5, BART, vb.)</br>

Bu kod, google/flan-t5-large modelini Hugging Face Hub'dan yükler. </br>
</br>
Model Yükleme: google/flan-t5-large modelini Hugging Face Hub'dan yükler.</br>
Model Parametrelerini Ayarlama: model_kwargs parametresi, modelin nasıl çalışacağını etkiler. Burada, modelin sıcaklık ve maksimum token uzunluğu gibi özellikleri ayarlanır.</br>
API ile Etkileşim: huggingfacehub_api_token, Hugging Face API'sine erişim için gerekli olan token'dır. Bu, modelin kullanılabilirliği ve API üzerinden doğru şekilde erişebilmesi için gereklidir.</br>
Dil Modeli ile Çalışma: Bu modelin sağladığı API üzerinden, verilen girişlere göre yanıtlar almayı sağlar. Örneğin, metin üretimi, özetleme, çeviri gibi işlemleri gerçekleştirmeyi sağlar.</br>

Bu örnek, "What is the capital of UK" gibi bir giriş cümlesi verildiğinde modelin cevabını döndürmektedir.</br>
