<div style="float: right;">
  <a href="../de/intro.html" style="margin-left: 10px;">🇩🇪 Deutsch</a>
  <a href="../en/intro.html">🇬🇧 English</a>
</div>

# Free Python environment – Data Literacy at TU Dortmund University

In this environment, you can work freely with Python without having to install 
an IDE locally. All datasets from DaLi Topic 3 are already integrated into the 
course and can simply be read in via
```bash
import pandas as pd
df = pd.read_csv("DOKUMENT_NAME.csv", sep=";", decimal=",")
```
You can read the following files using this method:
- Dataset Eingangsbefragung: "Eingangsbefragung.csv"
- Dataset Data NFL: "DLT3_Daten_NFL.csv"
- Dataset Todesursachen: "DLT3_Daten_Todesursachen.csv"
- Dataset Telefone pro 100 Einwohner: "DLT3_Daten_Telefone_pro_100_Einwohner.csv"
- Dataset TodesfaelleHitzeKaelte: "DL04_Test_DatenTodesfaelleHitzeKaelte.csv"
- Dataset Risiko: "DL04_Test_DatensatzRisiko.csv"

```{attention}
To edit and execute the Python code in this course, you will find this symbol ![live code symbol](code_symbol.PNG) at the top of every page that contains Python code. You can click on it and then select "Live code" to edit and run the code yourself. The first time you do this, it will take several minutes to load the live code environment. This is normal. You will be able to run your code when it says "ready". Feel free to try different things and experiment with the code.
```

To save your results locally, use the download symbol located to the right of the run symbol. Select a download as an ipynb file, which can then later be opened in any IDE.

If you have any questions, please don't hesitate to send us an email:
- Kai-Robin Lange ([kalange@statistik.tu-dortmund.de](mailto:kalange@statistik.tu-dortmund.de))
- Henrike Weinert ([henrike.weinert@tu-dortmund.de](mailto:henrike.weinert@tu-dortmund.de))




```{tableofcontents}
```
