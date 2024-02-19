# Plaenterwaldlauf

I took part in the 91st Plänterwaldlauf on 18.02.2024. A few hours later, the organizer published the results in the form of several PDFs, depending on the distance run (5, 10, 15 or 20km). I would now like to analyze this data a bit and see if I can find anything interesting in it.


The first challenge for me was/is that the data is only available as tables in PDFs. So I first had to find a way to get it into a format that I could work with. After failed attempts with Tabula, I now use Camelot. The installation, especially the dependencies, gave me a few gray hairs, but it works now.


However, the tables recognized by Camelot still have their pitfalls. A nice exercise in data cleaning, which I'm currently working on before I can finally analyze the data...

**SETUP OF VIRTUAL ENVIRONMENT**

```
pyenv local 3.9.8
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```