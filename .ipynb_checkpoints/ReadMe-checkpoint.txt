# Verificar e instalar 

# Instalar

apt update
apt install pip

# Instalar pacotes se necessário

pip install ipython
pip install nbformat
pip install pandas
pip install scikit-learn
pip install matplotlib

# Scripts trabalhados

SVM_Exemplo_001.ipynb - SVM sem "balanceamento de classes" e "sem validação cruzada"

SVM_Exemplo_002.ipynb - SVM com "balanceamento de classes Undersampling" e "sem validação cruzada"

SVM_Exemplo_003.ipynb - SVM com "balanceamento de classes Oversampling" e "sem validação cruzada"

SVM_Exemplo_004.ipynb - SVM com "balanceamento de classes Undersampling" e "validação cruzada"

SVM_Exemplo_005.ipynb - SVM com "balanceamento de classes Oversampling" e "validação cruzada"

# Somente rodar 

./run_all_ipynb.sh 

# Resultados serão gravados em resultados.csv