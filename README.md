# Integração Python com E-mail
2 formas de integrar:
- Gmail
- Outlook

## Requisitos 
- Jupyter Notebook (Anaconda 3)
- Python
- Importar as bibliotecas 

## Licença
Distribuido sob a licença MIT License. Veja `LICENSE` para mais informações.

## Método Gmail
Você precisa liberar o seu e-mail para esse tipo de atividade. (ou criar um e-mail novo). <br>
https://myaccount.google.com/lesssecureapps -> Vá em 'Gerenciar sua Conta do Google' -> Segurança -> Acesso app menos seguro (ative essa opção). <br>
Como tudo no Python, existem várias bibliotecas que podem ajudar nisso, usaremos a yagmail porque ela simplifica muito a nossa vida. <br>
Precisamos instalar o Yagmail, no terminal do anaconda digite: `pip intall yagmail`. <br>

## Integração Python com Outlook
Funciona para qualquer e-mail: corporativo, gmail, hotmail, etc.
1) Importar win32 e inicializar o outlook.
2) Escrever o e-mail e disparar.
3) Enviar mais de um arquivo.
