# Machine Learning Classification
## Prediksi Penyakit Stroke menggunakan Machine Learning Classifier

## Latar Belakang

Menurut WHO, stroke adalah penyebab ke dua yang menyebabkan kematian global, yang bertanggung jawab terhadap sekitar 11% total kematian di dunia. Dampak negatif dari stroke tersebut meningkatkan kebutuhan untuk inovasi dasi sisi diagnosis dan managemen terhadap penyakit stroke. Peluang untuk meningkatkan ketepatan hasil diagnosis terhadap potensi seseorang akan menderita penyakit stroke terbuka dengan menggunakan analisis terhadap data medis pasien terdahulu. 
Report ini berisi analisis terhadap hubungan antara faktor faktor yang dapat mempengaruhi kemungkinan seseorang menderita penyakit stroke. Input permasalahan ini adalah beberapa fitur seperti gender, umur, Riwayat hipertensi dan serangan jantung, status pernikahan, tipe pekerja, tipe residental, rata-rata tingkat kadar glukosa darah, bmi, dan status perokok. Kemudian kita gunakan beberapa model prediksi Classification yaitu KNN, Logistic Regression, Decision Tree, dan Random Forest. Output akhir dari penelitian ini adalah analisis terhadap fitur apa saja yang berkolerasi terhadap meningkatkan penyakit stroke dan model prediktif yang dapat memprediksi potensi seseorang menderita penyakit stroke sehingga diharapkan dengan adanya penelitian ini dapat membantu tenaga medis untuk menentukan langkah lanjutan dalam treatment terhadap pasien.

## Objective
* Tujuan utama dari task ini adalah untuk memprediksi seseorang terkena stroke berdasarkan variable yang ada
* Metode yang berguna untuk task ini adalah model klasifikasi yaitu Logistic Regression, K-Nearest Neighbor, Decision Tree, Random Forest dan Support Vector Machine.

## Dataset & Features

a.	id: unique identifier
b.	gender: "Male", "Female" atau "Other"
c.	age: Umur dari pasien
d.	hypertension: 
“No” jika pasien tidak menderita hipertensi 
Normal dengan tekanan darah sistolik < 120 mmHg dan diastolic < 80 mmHg
Pre-hipertensi dengan tekanan darah sistolik 120-139 dan diastolic 80-89)
“Yes” jika pasien menderita hipertensi
Hipertensi derajat 1 dengan tekanan darah sistolik 140-159 mmHg dan diastolic 90-99 mmHg
Hipertensi derajat 2 dengan tekanan darah sistolik >160 mmHg dan diastolic >100 mmHg
e.	heart_disease: “No” jika pasien tidak pernah menderita penyakit jantung, “Yes” jika pasien pernah menderita penyakit jantung
f.	ever_married: "No" atau "Yes"
g.	work_type: "children", "Govt_jov", "Never_worked", "Private" atau "Self-employed"
h.	Residence_type: "Rural" atau "Urban"
i.	avg_glucose_level: rata-rata glukosa dalam darah (mg/dL)
j.	bmi: body mass index
Underweight
Batas Normal
Overweight
Pre-obese
Obese I
Obese II
k.	smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
l.	stroke: 1 if the patient had a stroke or 0 if not
*Note: "Unknown" in smoking_status means that the information is unavailable for this patient
