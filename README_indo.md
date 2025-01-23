# analisa_sent_3label
Analisa sentimen 3 label dengan dataset IndoNLU + Pretrained indoBERT dan dijalankan dalam google Colab runtime tipe GPU 

Hasil training dan testing:
eval_loss': 0.464749276638031
'eval_accuracy': 0.9412698412698413
'eval_f1': 0.9409519203714527
'eval_runtime': 2.3799
'eval_samples_per_second': 529.441
'eval_steps_per_second': 33.195
'epoch': 10.0
Accuracy on test data: 92.20% 

# Persiapan code
1. Run di google colab dan tidak lupa menyiapkan datasetnya di lokal/drive (incase tidak memenuhi)
2. Persiapkan Versi python 3.2 dan runtime tipe GPU
3. Buat akun wandb.ai jika belum, siapkan API pribadi dari sana. Wandb.ai berguna untuk memantau proses training dan hasil
4. Silahkan ubah parameternya sendiri sesuai kebutuhan masing-masing
5. Jika ada kata lain yang ingin disingkirkan dari wordcloud, tambahkan di stopword

# Status Pengembangan
1. Masih dalam pengembangan karena baru selesai tahap mengenali 3 label saja, negatif, netral dan positif
2. Rencana selanjutnya adalah pengembangan multi-label emosi terhadap model dan mengenali sentimen melalui emotikon
3. Implementasi model yang tersimpan ke dalam LLM based Multi-Agent sebagai salah satu Agent yang mengendalikan respon LLM dan mengenali respon emosional user.
