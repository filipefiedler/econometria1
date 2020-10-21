# econometria1
Exercises from Econometria 1 Epge Master's course

Passo-a-passo inicial:

Crie uma vm na google cloud

Entre na vm através do prompt de comando: gcloud beta compute ssh --zone "us-central1-a" "instance-2" --project "tokyo-hall-292412"

Crie o arquivo de configuração inicial da vm: nano vmcfg.sh

Edite as configurações iniciais da vm: Copie o conteúdo do arquivo vmcfg.sh desse tutorial

Execute o arquivo de configuração inicial: sh vmcfg.sh

Adicione o grupo 'docker' ao seu usuário linux (para facilitar depois): sudo usermod -aG docker <seu-nome-de-usuário> (seu nome aparece no prompt)

Saia e entre na vm (precisa renovar o terminal p/ habilitar o grupo docker): exit gcloud compute ssh

Clone o repositório econometria1: git clone https://github.com/rbrandao22/econometria1.git

Crie a imagem de container 'my-python-app' e rode o primeiro "hello world": cd econometria1 cd ops sh build.sh

Inicie o Python dentro do container: sh run_python3.sh

Dentro do container, execute o arquivo exercicio1.py: python exercicio1.py
