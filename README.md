# Rekrutacja BioMedical AI w semestrze zimowym 2023/2024.

W ramach zadania rekruacyjnego wybierz i spróbuj rozwiązać **jeden** z poniższych problemów. 
**UWAGA!!! Zadanie 1 jest przeznaczone tylko dla studentów pierwszego roku!!! Studenci wyższych lat mogą wybierać jedynie spośród zadań2-3!!!**

## Zadania

### Zadanie 1 [DO WYBORU TYLKO DLA PIERWSZOROCZNYCH] - Klasyfikacja Obrazów FashionMNIST
Link do zbioru: https://www.kaggle.com/datasets/zalando-research/fashionmnist

W tym zadaniu musisz stworzyć model klasyfikujący ubrania ze zbioru FashionMNIST. Należy dokonać odpowiedniego proprocessingu danych, zaimplementować wybrane modele, przeprowadzić eksperymenty oraz przeanalizować otrzymane wyniki.

#### Uwagi i porady
* Dane można załadować również z biblioteki `torchvision`.
* Pamiętaj o odpowiednim podziale zbioru na train, val oraz test.
* Zastanów się, jakie metryki do oceny rozwiązania wybrać.
* Sugerowane modele: Convolutional Neural Networks.


### Zadanie 2 - Segmentacja Obrazów Retinograficznych z Wykorzystaniem Grupowo-Ekwiwariantnych Sieci Neuronowych
Link do zbioru: https://www.kaggle.com/datasets/abdallahwagih/retina-blood-vessel

W tym zadaniu musisz stworzyć modele **segmentacji** obrazów z wykorzystaniem **grupowo ekwiwariantnych sieci neuronowych**. Należy dokonać odpowiedniego proprocessingu danych, zaimplementować wybrane modele, przeprowadzić eksperymenty oraz przeanalizować otrzymane wyniki.

#### Uwagi i porady
* Tutaj znajduje się dobry tutorial dotyczący grupowo-ekwiwariantnych sieci neuronowych: https://www.youtube.com/watch?v=z2OEyUgSH2c
* Sugerowana biblioteka: https://github.com/QUVA-Lab/e2cnn
* Pamiętaj o odpowiednim podziale zbioru na train, val oraz test.
* Zastanów się, jakie metryki do oceny rozwiązania wybrać.
* Sugerowane modele: E(3)-UNet, GCNN


### Zadanie 3 - Generowanie Danych 
Link do zbioru: https://www.kaggle.com/datasets/jessicali9530/stanford-dogs-dataset

W tym zadaniu musisz stworzyć model generatywny, będący w stanie generować nowe obrazy piesków. Model może generować obrazy bezwarunkowo lub warunkowo. Należy dokonać odpowiedniego proprocessingu danych, zaimplementować wybrane modele, przeprowadzić eksperymenty oraz przeanalizować otrzymane wyniki.  

#### Uwagi i porady
* Należy być gotowym na dokładne wyjaśnienie również **teoretycznych** aspektów modelu, takich jak funkcja kosztu czy uzasadnienie generatywności.
* Zastanów się, w jaki sposób możesz ocenić jakość zaproponowanych rozwiązań.
* Sugerowane modele: Generative Adversarial Networks, Denoising Diffusion Probabilistic Models, Normalizing Flows, Variational Autoencoders
* W celu szybszego wykonywania eksperymentów warto zresizować obrazy do rozmiaru np. 64x64 lub 32x32.

## Oddawanie zadań
W celu oddawania zadań należy:
1. Sforkować te repozytorium
2. Zamieścić swoje rozwiązanie, opakowane w folder "Zadanie\_{NUMER\_ZADANIA}".
3. Wykonać pull-request z tytułem "IMIE\_NAZWISKO\_NUMER\_ZADANIA".

**Zadania należy oddać do godziny 22:00 21 listopada 2023r.**

## Uwagi i wskazówki
* Każde z powyższych zadań powinno być wykonane przy pomocy języka Python oraz frameworka [PyTorch](https://pytorch.org/).
* Zalecanym sposobem prezentacji kodu i wyników jest notatnik [Jupyter](https://jupyter.org/).
* Dodatkowe biblioteki, które mogą okazać się pomocne przy wykonaniu zadania: NumPy, Pandas, Matplotlib, Scikit-learn.
* Do trenowania modelu zaleca się użycia platformy Google Collab lub Kaggle. Po wykonaniu zadania, notatnik można pobrać i wrzucić na repo.  
* Nawet jeśli nie uda Ci się wykonać zadania w pełni, **warto je wysłać**. Dla nas liczy się przede wszystkim pokazanie znajomości tematu oraz tok rozumowania.
* Należy być przygotowanym na dokładne wyjaśnienie swojego rozwiązania.
* **W razie problemów proszę kontaktować się na maila biomedical.ai@pwr.edu.pl**.
