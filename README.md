# Install-SAP-GUI-800
Instalação do SAP GUI v8.00 x86 via Intune

##Passo 01
Fazer o download do SAP GUI na versão 8.00 direto do o portal da SAP.
Caso seja um teste em laboratório pode utilizar o link para download https://mega.nz/file/W55XgYQD#PT3JWohCG_3W_hbHGtKj4Pq1rK8ehcatdiRGMQUasf4

##Passo 02
Extraia o arquivo e navegue até a pasta abaixo e abra o arquivo NwSapSetupAdmin.exe:
![image](https://github.com/user-attachments/assets/f5c3ad03-592f-4583-b44a-537866945b46)


##Passo 03
Crie um Novo Pacote para instalação
![image](https://github.com/user-attachments/assets/9c22c4f2-c3f1-4925-a7a5-6ce70d9dddd5)

Selecione o SAP GUI
![image](https://github.com/user-attachments/assets/6c70d75c-636f-49eb-9668-92573ab374ba)

Dê um nome ao Pacote de instalação, por exemplo "SAP_GUI_8_x86" clique Next, Next ... e finalize a criação. Pronto, um novo pacote foi criado com o nome que você deu:
![image](https://github.com/user-attachments/assets/80cfa5ba-96c7-4b22-af1c-4747687d3a1c)

Selecione o pacote criado e exporte ele como um instalar único:
![image](https://github.com/user-attachments/assets/a5ec753f-919d-4c68-9294-f8cde075815c)

Escolha uma pasta para onde o arquivo será criado e deixe o processo encerrar
![image](https://github.com/user-attachments/assets/9e162e51-04c5-434c-8cf7-1237e47a11de)

##Passo04
Pegue o arquivo que foi criado na pasta de destino, copie ele e inclua em uma outra pasta qualquer e crie um arquivo de instalação para o Intune.
Há muitos artigos que tratam esse assunto, por exemplo, esse https://www.systemcenterdudes.com/deploy-microsoft-intune-win32-apps/.
Esse artigo não está focado nisso.




