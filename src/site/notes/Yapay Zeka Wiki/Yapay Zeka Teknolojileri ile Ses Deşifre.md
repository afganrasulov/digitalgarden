---
{"dg-publish":true,"permalink":"/yapay-zeka-wiki/yapay-zeka-teknolojileri-ile-ses-desifre/"}
---

Yapay zeka teknolojisi sayesinde sesi metne dönüştürüyor, deşifre ediyor ve istenilen dile tercüme ediyoruz. Ayrıca, istenilen uzunluktaki ses veya videoyu metne dönüştürüp istenilen dile tercüme etmek için yapay zeka teknolojilerini uygulamalı olarak kullanacağız.
# **Whisper by Open AI**

OpenAI Platform  
Explore developer resources, tutorials, API docs, and dynamic examples to get the most out of OpenAI's platform.  
[https://platform.openai.com/playground](https://platform.openai.com/playground)  
Whisper, OpenAI tarafından geliştirilen bir otomatik konuşma tanıma (ASR) sistemi. Bu model, 680,000 saat çok dilli ve çoklu görevli denetimli veri toplandıktan sonra eğitilmiştir. Bu veri kümesinin genişliği ve çeşitliliği, aksanlara, arka plan gürültüsüne ve teknik dile karşı sağlamlığı artırmaktadır. Whisper, çeşitli formatlarda ses dosyalarını metne dönüştürebilir, ayrıca çoklu dil tanıma, dil çevirisi ve dil tanıma gibi çoklu görevleri yerine getirebilir. Whisper, daha yüksek doğruluk oranlarına sahip olmak için GPU'lar üzerinde çalıştırıldığında daha yüksek performans gösterir. Whisper, araştırmacılar, geliştiriciler ve gazeteciler gibi birçok kişi için kullanışlı bir araçtır. Whisper API, m4a, mp3, mp4, mpeg, mpga, wav ve webm gibi çeşitli formatlardaki ses dosyalarını yazıya dönüştürebilir ve kullanım bedeli dakika başına 10 kuruş ($0.006) 'dir. Whisper, açık kaynak kodlu bir yazılımdır ve geliştiriciler ve kullanıcılar tercih ettikleri hesaplama platformunda çalıştırabilirler, örneğin dizüstü bilgisayarda, masaüstü iş istasyonunda, mobil cihazda veya bulut sunucusunda.
# **Whisper JAX**

Whisper JAX - a Hugging Face Space by sanchit-gandhi  
Discover amazing ML apps made by the community  
[https://huggingface.co/spaces/sanchit-gandhi/whisper-jax](https://huggingface.co/spaces/sanchit-gandhi/whisper-jax)  
Whisper JAX, OpenAI tarafından geliştirilen Whisper modelinin optimize edilmiş bir uygulamasıdır. Arka planda JAX ve TPU v4-8 kullanır. A100 GPU'da PyTorch'a kıyasla [**70 kat daha hızlı**](https://github.com/sanchit-gandhi/whisper-jax#benchmarks) olduğundan, bu, mevcut en hızlı Whisper API'dir.
Dikkat: Zirve saatlerinde bu demo için sıra bekleyebilirsiniz. Bir istek gönderdiğinizde, sıra pozisyonunuz demo penceresinin sağ üst köşesinde gösterilir. Sıranın önüne geçtiğinizde, ses dosyanız transkribe edilir ve ilerleme bir ilerleme çubuğuyla gösterilir.