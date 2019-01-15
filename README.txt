--- Progetto finale di Text Mining and Search di Beatrice Fumagalli e Matteo Porcino --- 
--    The 20 Newsgroups dataset     --
-----    Text Classification     -----
  
-- Files --
   All'interno dell'archivio "Text_mining_Fumagalli_Porcino.zip" sono presenti i seguenti file:
	
	- 20_newsgroups: cartella contenente il corpus di documenti utilizzati nel progetto
	- TM_Project: file di Jupyter Notebook contenente il codice del progetto
	- README
	- Report
	- 20_newsgroups_slides

-- Dataset --
   Il dataset utilizzato � "20_newsgroups�, una raccolta di 20.000 documenti, suddivisi in modo uniforme 
   in 20 diversi newsgroups. 

-- Codice e Librerie --
   Il codice del progetto � stato implementato interamente in Python (Anaconda), le librerie utilizzate
   all'interno del codice sono le seguenti:

	- pandas
	- numpy
	- time
	- os
	- string
	- unicodedata
	- contractions
	- inflect
	- re
	- nltk
	- matplotlib.pyplot
	- seaborn
	- sklearn

-- Installazione --

 - Prerequisiti -

   Per eseguire il codice all'interno del file "TM_Project.ipynb" � necessario aver installato:
	
	- Anaconda 5.2 (Python 3.6 version) 

 - Preparazione dell'ambiente - 
   All'interno della working directory di Anaconda creare un cartella ed estrarre al suo interno il contenuto
   dell'archivio "Text_mining_Fumagalli_Porcino".

 - Esecuzione -
   Aprire il file "TM_Project.ipynb" con Jupyter Notebook ed eseguire tutte le celle di codice utilizzando il
   men�: Cell -> Run All.
   Le eventuali librerie non presenti nell'ambiente corrente di Python verranno installate automaticamente.

   - Libreria NLTK -
   Se � la prima volta che si utilizza questa libreria sar� necessario rimuovere il commento nel secondo 
   blocco di codice alla riga n�2 ( nltk.download() ), dopo aver eseguito il comando "Run All" si aprir�
   una finestra in cui verranno mostrate le collections disponibili all'interno della libreria, cliccare 
   su "Download", una volta finito il download si potr� chiudere la finestra ed eseguire i blocchi 
   successivi di codice. 







