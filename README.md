## Vamos fazer um virtualenv chamado meuenv. O formato geral desse comando é:

command-line
>python3 -m venv myvenv

## Instalando o Django
Agora que você tem seu virtualenv ativo, pode instalar o Django.

Antes de fazer isto, devemos garantir que temos instalada a última versão do pip, que é o software que usamos para instalar o Django:

command-line
>python3 -m pip install --upgrade pip

E adicione o seguinte texto ao arquivo requirements.txt:

requirements.txt
>Django~=2.0.6

Agora, execute para instalar o Django.
>pip install -r requirements.txt 

No MacOS ou no console do Linux, rode o comando abaixo (não esqueça de adicionar o ponto . no final):
>django-admin startproject mysite .

No Windows, rode o seguinte comando (não esqueça de adicionar o ponto . no final!)
>django-admin.exe startproject mysite .

Para criar um banco de dados, vamos executar o seguinte comando no console. (precisamos estar no diretório que contém o arquivo manage.py). Se isso der certo, você deve ver algo assim:
Digite: 
>python manage.py migrate 


## Iniciando o servidor web
Você precisa estar no diretório que contém o arquivo manage.py . No console, nós podemos iniciar o servidor web executando o python manage.py runserver:

command-line
>python manage.py runserver
