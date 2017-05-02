# Önlab vázlat:

##  Bevezetés / célkitűzés
 - pitvarfibrilláció társadalmi helyzete
 - pitvarfibrilláció mechanizmusa (segéd videó [Atrial Fibrillation Animation](https://www.youtube.com/watch?v=tPqs4xKPG3A))
 - korábbi megközelítések
 - verseny kiírás

## Korábbi munkák (related works)
 - Elváltozás jellegzetességek orvosi szemmel
 - Feature extraction (Pan Tompkins)
 - Clusterezés
 - Machine Learning alapú megközelítések
 - Time-series classification általában

## Saját munka
 - Klasszifikáló modellek tesztelése
    - Recurrent -> LSTM/GRU
    - FullyConnected
    - ConvNet
    - ResidualNet
 - Kiértékelés (osztály alulreprezentáltság kezelése)
    - Confusion Matrix
    - Data Augmentation
    - Weighted Loss
 - Eredmények
    - Páronkénti összehasonlítás
    - Test/Validation Set
    - Legjobb eredmény
    - Legjobb modell által kiválogatott feature-ök (esetleg DeConv)

## Mérési eredmények

- összegzés
- kitekintés

# FÖT vázlat:

## Bevezetés / célkitűzés
 - Deep Learning modellek alkalmazása
 - Lehetséges implementációk
 - Leggyakrabban előforduló mintázatok

## Olvasmányok
 - Források, ahol a hatékonyság növelésére tesznek javaslatokat

## Saját munka
 - Kutatócsoport kísérleteihez a keretrendszer kiépítése
 - Adatok formalizálása a párhuzamos betöltés érdekében
 - TensorFlow-ban moduláris modell kialakítása
 - Entry point-ok különböző handcrafted-feature-ök számára
 - TensorBoardban magas szintű részletes logging automatizálása
 - Egy GPU maximális kihasználtságára tett törekvések
     - TensorFlow lfilter és filtfilt operáció implementálása
 - Egyszerre több GPU igénybevétele párhuzamos kísérletekkel
 - Real-Time Inference rendszer kiépítése

## Mérési eredmények

- összegzés
- kitekintés
