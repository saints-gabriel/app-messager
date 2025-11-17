# Website de mensagens (Chat geral e PV)



Como rodar a aplicação (Host)



* Tenha Python e Ngrok instalados na máquina que vai rodar
* Checando versão e se está instalado

```

python --version

```
* Instalando dependências
```

pip install flask, flask_socketio

```
* Configurando o Ngrok (Conecte sua conta Github no website deles)
```

ngrok config add-authtoken SEUCÓDIGODEAUTORIZACAONGROK

```
* Abra 2 terminais (1 para cada serviço)
* Terminal 1 (Aberto dentro da pasta do projeto): 

```

python app.py

```

* Terminal 2 (Serviço para rodar sem deploy, conecte sua conta GitHub com Ngrok)

```

ngrok http 5000

```

* Após isso é só enviar o link criado pelo Ngrok no terminal
