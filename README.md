# MATLAB İLE CNN AĞLARI İLE ALZHEIMER HASTALIĞININ TEŞHİSİ [TR]
## PROJENİN AMACI

Bu proje, derin öğrenme yöntemlerinden biri olan Convolutional Neural Networks (CNN) kullanarak Alzheimer hastalığının erken teşhisini hedeflemektedir.
MATLAB platformu üzerinde geliştirilen bu projede, beyin MRI görüntülerinden elde edilen veriler kullanılarak Alzheimer hastalığının çeşitli evreleri sınıflandırılmıştır.
Amacımız, sağlık profesyonellerine ve araştırmacılara, Alzheimer hastalığının daha hızlı ve doğru bir şekilde teşhis edilmesine yardımcı olabilecek bir model sunmaktır.
Bu sayede, hastalığın ilerlemesi yavaşlatılabilir ve hastaların yaşam kalitesi artırılabilir.

# VERİ SETİ VE CNN AĞ ÇEŞİTLERİ

Veri seti Kaggle platformu üzerinden https://www.kaggle.com/datasets/uraninjo/augmented-alzheimer-mri-dataset 'i kullanılmıştır. Dataset içeriği 4 sınıfa ayrılmıştır.
 * Mild Demented (8960)
 * Moderate Demented (6464)
 * Non Demented (9600)
 * Very Mild Demented (8960)

Proje 2 adet CNN ağı ile Adam,RMSprop ve SGDM fonksiyonları ile ayrı ayrı eğitimleri yapılmıştır.
Kullanılan CNN ağları
MobileNetV2 ve kendi tasarladığım 'MyCNN' ağlarıdır.

# DIAGNOSIS OF ALZHEIMER'S DISEASE WITH CNN NETWORKS WITH MATLAB [ENG]
## PROJECT PURPOSE

This project aims to diagnose Alzheimer's disease early using Convolutional Neural Networks (CNN), one of the deep learning methods.
In this project developed on the MATLAB platform, various stages of Alzheimer's disease were classified using data obtained from brain MRI images.
Our aim is to provide a model that can help healthcare professionals and researchers diagnose Alzheimer's disease faster and more accurately.
In this way, the progression of the disease can be slowed down and the quality of life of patients can be improved.

# DATASET AND CNN NETWORK TYPES

The dataset was used on the Kaggle platform https://www.kaggle.com/datasets/uraninjo/augmented-alzheimer-mri-dataset . The dataset content is divided into 4 classes.
* Mild Demented (8960)
* Moderate Demented (6464)
* Non Demented (9600)
* Very Mild Demented (8960)

The project was trained separately with 2 CNN networks and Adam, RMSprop and SGDM functions.
The CNN networks used are MobileNetV2 and my own designed 'MyCNN' networks.
