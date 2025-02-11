# 📊 Relationship Matrix 

Bu proje, ders ve program çıktıları arasındaki ilişkileri analiz etmek ve öğrenci başarı oranlarını hesaplamak için geliştirilmiştir. SQL Server ile veri tabanı yönetimi sağlanırken, Python ile veri işleme ve OpenPyXL ile Excel entegrasyonu gerçekleştirilmiştir.
- **Yapılış Tarihi:** 30 Aralık 2024  
- **Son Güncelleme:** 7 Şubat 2024

## 🎯 Projenin Amacı
- Ders ve program çıktıları arasındaki ilişkileri analiz etmek.
- Öğrenci notlarını işleyerek başarı oranlarını hesaplamak.
- Ağırlıklı değerlendirme tabloları oluşturarak analizleri görselleştirmek.
- Verileri Excel tablolarına aktararak raporlamak.

## 🚀 Özellikler
- **Ders Çıktıları ve Değerlendirme Kriterleri İlişki Matrisi** oluşturma.
- **Program Çıktıları ve Ders Çıktıları İlişki Matrisi** hesaplama.
- **Öğrenci Notları Tablosu** ile öğrenci başarılarını analiz etme.
- **Ağırlıklı Değerlendirme Tablosu** ile ders çıktılarının etkisini ölçme.
- **Başarı Oranı Hesaplama** ile öğrencilerin program hedeflerine katkısını değerlendirme.
- **Excel Entegrasyonu** ile tüm verilerin kullanıcı dostu raporlanması.

## 🖥️ Kullanılan Teknolojiler
- **Python** 🐍 (Veri İşleme)
- **SQL Server** (Veri Tabanı Yönetimi)
- **PyODBC** (Veri tabanı bağlantısı)
- **OpenPyXL** (Excel entegrasyonu)

## 📌 Kurulum
Projeyi klonlayın:
```bash
git clone https://github.com/senemadalan/Iliski_Matrisi.git
cd Iliski_Matrisi
```
Gerekli bağımlılıkları yükleyin:
```bash
pip install pyodbc openpyxl
```
Veri tabanı bağlantısını yapılandırın:
```python
connection = pyodbc.connect('DRIVER={SQL Server};SERVER=SunucuAdı;DATABASE=RelationMatrix;Trusted_Connection=yes;')
```
Uygulamayı başlatın:
```bash
python main.py
```

## 🛠️ Kullanım
1. **Ders ve program çıktıları arasındaki ilişkileri ekleyin.**
2. **Öğrenci notlarını girin ve başarı oranlarını hesaplayın.**
3. **Ağırlıklı değerlendirme tablolarını oluşturun.**
4. **Excel dosyalarına veri aktararak analizlerinizi raporlayın.**

## Menü Ekranı
![Image](https://github.com/user-attachments/assets/58ea0309-e3fd-457f-8dac-bc8d9192490c)
