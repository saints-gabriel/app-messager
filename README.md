# Website de mensagens (Chat geral e PV)



Como rodar a aplicação (Host)



* Tenha Python e Ngrok instalados na máquina que vai rodar
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