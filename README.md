# PythonProjects

Bem-vindo ao meu primeiro repositorio em pyhton, aqui colocarei projetos simples e de aprendizado conjunto.
Mostrarei todo o meu processo de aprendizado dentro dessa plataforma com esses mini-projetos.

## 📁 Estrutura do Repositório

O repositório está organizado em subdiretórios, onde cada diretório representa um projeto individual. 
Isso torna fácil navegar e encontrar projetos específicos de interesse. A estrutura básica do repositório é a seguinte:

PythonProjects/
│
├── DailyEmailReport/
│ ├── README.md
│ ├── send_daily_report.py
│ └── requirements.txt


## 📝 Projetos Incluídos

### [DailyEmailReport: Envio Diário de Relatório por E-mail](./DailyEmailReport)

Um script Python para automatizar o envio de relatórios diários por e-mail. 
Ele utiliza `smtplib` para enviar e-mails e `schedule` para agendar o envio diário. 
O relatório é anexado como um arquivo PDF ao e-mail.

#### 📋 Descrição

Este projeto permite o envio automatizado de relatórios diários via e-mail. 
Ele é útil para automatizar a rotina de envio de relatórios, economizando tempo 
e garantindo que as informações sejam enviadas de maneira consistente.

#### 📂 Estrutura do Projeto

DailyEmailReport/
├── README.md
├── send_daily_report.py
└── requirements.txt


#### 🚀 Como Usar

## Clone este repositorio
git clone https://github.com/WillianEdsonVieira/PythonProjects.git
cd PythonProjects/DailyEmailReport

## Instale as dependências:
pip install -r requirements.txt

## Configure as informações de e-mail:
Edite o arquivo config/config.py com suas configurações de e-mail.

## Execute o script:
python send_daily_report.py

## Configuração de E-mail:
Você precisará configurar as seguintes informações no arquivo config/config.py:

SMTP_SERVER = 'smtp.seu_servidor.com'
SMTP_PORT = 587
SMTP_USER = 'seu_email@exemplo.com'
SMTP_PASSWORD = 'sua_senha'
FROM_EMAIL = 'seu_email@exemplo.com'
TO_EMAIL = 'destinatario@exemplo.com'

🤝 Contribuições
Contribuições são bem-vindas! Se você tiver um projeto interessante em Python que gostaria de adicionar a este repositório, 
sinta-se à vontade para fazer um fork, adicionar seu projeto e enviar um pull request.

📜 Licença
Este repositório está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

📧 Contato
Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato:

GitHub: WillEdsonVieira

