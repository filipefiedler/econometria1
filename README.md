# econometria1
Exercises from Econometria 1 Epge Master's course

Passo-a-passo inicial

Entrar na VM: gcloud compute ssh instance-2
  
Entrar no container: run_python3.sh

Executar o programa de forma interativa: python -m pdb

Jogar arquivos da cloud para o pc: gcloud compute scp instance-2:econometria1/test temp.png

Jogar arquivos do pc para a cloud: gcloud compute scp temp.csv instance-2:econometria1/test
