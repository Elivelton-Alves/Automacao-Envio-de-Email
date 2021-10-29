# Automacao-Envio-de-Email
O projeto automatiza um processo de cálculo de indicadores e envio de e-mail e arquivos em anexo.
Utiliza-se arquivos em excel para simular uma base de dados, nas quais diariamente seriam consultadas para gerar os indicadores. 

DESCRIÇÃO DOS PROCESSOS:
Para cada loja foi criada uma pasta de backup, onde é salvo as planilhas com as informações geradas.
Cada gerente receberá somente o arquivo com os indicadores referente a loja a qual é responsável.
Para a diretoria é enviado um email com informações das lojas no corpo do e-mail e arquivos com ranking diário e anual das lojas.

TECNOLOGIAS UTILIZADAS:
No projeto foram utilizadas as bibliotecas PANDAS, win32com.client e pathlib.
A biblioteca PANDAS foi necessária para ler os arquivos excel que estavam em uma pasta do computador no código Python.
A biblioteca win32com.client foi utilizada para o envio de e-mails.
E a biblioteca pathlib foi utilizada para localizar os arquivos de excel no computador.

FINALIDADE DO PROJETO:
O projeto foi realizado durante o Curso Python Impressionador ministrado pela Hashtag Treinamentos, com a finalidade de treinamento e aplicação
de automação num cenário real para o mercado de trabalho.
