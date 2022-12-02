### Mục lục

- [Music genre classifier](#music-genre-classifier)
- [Dataset](#dataset) 
- [Colab](#colab)
- [Requirements](#requirements)
- [Flow Chart](#flow-chart)

# Music genre classifier
Với sự phát triển của internet và các ứng dụng hệ thống đa phương tiện xử lý cơ sở dữ liệu, âm nhạc ngày càng trở nên quan trọng và nhu cầu về các ứng dụng truy xuất thông tin âm nhạc cũng tăng lên. Các thể loại âm nhạc không có định nghĩa và ranh giới nghiêm ngặt khi chúng phát sinh thông qua sự tương tác phức tạp giữa các yếu tố công chúng, tiếp thị, lịch sử và văn hóa. Đây là Ứng dụng web phân loại nhạc theo thể loại.
![Output](https://user-images.githubusercontent.com/85569646/205334507-49611ac7-ee01-4b7f-9c3a-3ee16d7355ff.png)

## Dataset
Sử dụng data từ [GTZAN Dataset](https://www.kaggle.com/andradaolteanu/gtzan-dataset-music-genre-classification).

**Gồm 10 thể loại:**
- Blues
- Classical
- Country
- Disco
- Hiphop
- Jazz
- Metal
- Pop
- Reggae
- Rock

## Colab 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1rx35N2HNWm3XklaOPIZr5k7oTkvqBD7C)

**Xây dựng trên các Model:**
- Logistic Regression
- Random Forest
- Decision Tree
- AdaBoost
- Gradient Boosting Classifiers
- XGBoost
- CatBoost
- K-Nearest Neighbors
- Support Vector Machine

## Requirements
- Flask==1.1.2
- Jinja2==2.11.3
- joblib==1.0.1
- matplotlib==3.3.4
- numpy==1.19.2
- pandas==1.2.3
- Werkzeug==1.0.1
- librosa==0.8.0
- catboost==0.25.1

## Flow Chart
![Chart](https://user-images.githubusercontent.com/85569646/205336327-200b662a-7126-43ed-8224-1fd3e84fee7d.png)
