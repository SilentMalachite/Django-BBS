# Python製WebフレームワークDjangoによる掲示板システム（認証付き）
練習と自分のチュートリアル用です

## 環境
* Python3.8以上
* Django3.2.12

## 開発環境

python3 -m venv django-env

cd django-env

source bin/activate

pip install --upgrade pip

pip install django==3.2.12

mkdir Django-BBS && cd Django-BBS

django-admin startproject config .

python manage.py startapp snsapp

## 進捗状況

約１ヶ月ぶりに更新。テンプレートの細部を調整する