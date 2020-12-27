## MISSP 2020/21

Pliki od "zajecia_1" do "zajecia_6" działają na Google Colab.

Pliki z folderów "Zajęcia 7" i "Zajęcia 9" działają tylko i wyłącznie na Kaggle - najlepiej odpalić dany kurs i przekleić cały kod.

<br/>

**Zajęcia 1** - podstawy, sortowanie, szukanie

**Zajęcia 2** - podstawy cd., sprawdzanie numeru telefonu

**Zajęcia 3** - blending problem (whiskas), sardynki

**Zajęcia 4** - fabryka okien

**Zajęcia 5** - rezystory

**Zajęcia 6** - pracownicy w sklepie

**Zajęcia 7** - https://www.kaggle.com/learn/intro-to-machine-learning 

**Zajęcia 8** - https://www.kaggle.com/learn/pandas (części 1, 2, 3)

**Titanic** -  https://www.kaggle.com/c/titanic, pliki do Titanica znajdują się w folderze **misc**

Titanica można odpalić na Kaggle (zostawiając jak jest) - należy jednak pamiętać o wrzuceniu (lub zimportowaniu) plików.<br>
Można też odpalić na Google Colab, wtedy należy (najszybciej) zamienić na początku linijki z wczytywania plików na następujące:<br>
```
train = pd.read_csv('https://raw.githubusercontent.com/ptrxpl/missp-final/main/misc/train.csv', header = 0, dtype={'Age': np.float64})
test  = pd.read_csv('https://raw.githubusercontent.com/ptrxpl/missp-final/main/misc/test.csv' , header = 0, dtype={'Age': np.float64})
```
