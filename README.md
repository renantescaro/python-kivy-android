#### Pequeno teste para gerar app de Android utilizando Python 🐍

## Geração de APK funciona APENAS em LINUX 🐧

<img src='doc/print.jpeg' style="width: 200px">

### Instalar todas as dependências
* > wget https://github.com/HeaTTheatR/KivyMD-data/raw/master/install-kivy-buildozer-dependencies.sh
chmod +x install-kivy-buildozer-dependencies.sh
* > ./install-kivy-buildozer-dependencies.sh

### Gerar APK 🤖
* > buildozer init
* > buildozer android debug

### VENV apenas para desenvolvimento
```bash
python -m venv venv
venv\Scripts\activate.bat
pip install -r requirements.txt
```

### Executar aplicação
* > python main.py
