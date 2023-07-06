**********
*  PYSTACK WEEK 7.0
*  https://pythonando.com.br/
*  
*  Aula 01 (Sistema Windows11/VSCode/Configurações Iniciais)
**********
Criar Ambiente Virtual.
Instalar Django & Pacotes adicionais.

*  Aula 02a (App Extrato)
**********
Adicionar o app Extrato 

*  Aula 02b
**********
EXportar Extrato

pip install weasyprint

quem usa windows, instalar o arq: 
'https://github.com/tschoonj/gtk-for-windows-runtime-environment-installer/releases'

*  Aula 02c
**********

Definir planejamento

python manage.py startapp planejamento

settings.py / INSTALLED_APPS = 'planejamento',
urls.py / path('planejamento/', include('planejamento.urls')),