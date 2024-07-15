<p align="center">
<img src="https://cwmkt.com.br/wp-content/uploads/2024/04/logo_github.png" width="240" />
<p align="center">Seja bem-vindo ao Guia de Instalação Chatwoot+Evolution+Typebot 🚀</p>
</p>
  
<p align="center"> 
<a href="https://hubconnect.top" target="_blank">👉 Participe da Comunidade HubConnect 👈</a>
</p>

<hr />
<hr />

## Comando para Instalar EasyPanel

```bash
curl -sSL https://get.easypanel.io | sh
```

Adicione nome de Project

![48098522-0c485df00f5cadb0d329061c35fee46c](https://github.com/cwmkt/easypanelevotypebot/assets/91642837/b72c1359-91ca-4bf6-9fb1-32525ba5747b)

Clique na aba Templates

![48098535-90f9b4f370bb8b06cfd7e4acf0ee0f97](https://github.com/cwmkt/easypanelevotypebot/assets/91642837/03c1830c-621c-40b3-94ee-93eb568c8d2e)

Vamos na aba Templates, localize Typebot clique em cima dele

![48098867-1f193bf0502665271ad9a61741724f5a](https://github.com/cwmkt/easypanelevotypebot/assets/91642837/656d552f-4152-4670-8424-837c3edf0fb0)

![48098877-369c271a9da0a7a8e8a1bc22806dbf2e](https://github.com/cwmkt/easypanelevotypebot/assets/91642837/e0243b00-9bdc-48a3-8ab1-8cea763a89d7)

Dois campos abaixo vai colocar 

```bash
https://builder.dominio.easypanel.host
```

```bash
https://viewer.dominio.easypanel.host
```

![48098918-e15e56041dbfe36ba6c11bf276b5e8f4](https://github.com/cwmkt/easypanelevotypebot/assets/91642837/2d41d589-35d7-4544-aa98-db9790f534cc)

Em Github Client ID* e Github Client ID* coloque qualquer coisa, não vamos usa-lo, lugar usaremos smtp

![48098946-9a7bc558b3fed0bc871f4dee67392da8](https://github.com/cwmkt/easypanelevotypebot/assets/91642837/536468b9-6f19-418d-abac-ab7e482ce9d5)

Em Environment adicione variaveis de SMTP no final de parecer com esse

```bash
DATABASE_URL=postgres://postgres:c298a1247ecaee9df640@$(PROJECT_NAME)_typebot-db:5432/$(PROJECT_NAME)
NEXTAUTH_URL=https://builder.dominio.easypanel.host
NEXT_PUBLIC_VIEWER_URL=https://viewer.dominio.easypanel.host
ENCRYPTION_SECRET=be13eedd3c063fd099175d65ab5f304b
ADMIN_EMAIL=contato@dominio.com.br
DISABLE_SIGNUP=false
ADMIN_EMAIL=contato@dominio.com.br
NEXT_PUBLIC_SMTP_FROM='Suporte' <contato@dominio.com.br>
SMTP_AUTH_DISABLED=false
SMTP_USERNAME=contato@dominio.com.br
SMTP_PASSWORD=SenhadSMTP
SMTP_HOST=smtp.dominio.com.br
SMTP_PORT=465
SMTP_SECURE=true
S3_ACCESS_KEY=minio
S3_SECRET_KEY=1c79420ac1dd742d625d
S3_BUCKET=typebot
S3_ENDPOINT=http://$(PROJECT_NAME)_typebot-minio:9000
```

![48098960-e885495cf9ec690ba46f0b97068008fa](https://github.com/cwmkt/easypanelevotypebot/assets/91642837/8080e201-f15c-40d6-99f4-55886298baf2)

Mande executar DEPLOY

![48098978-79214e0a2541429040e68a101b3f44d9](https://github.com/cwmkt/easypanelevotypebot/assets/91642837/a3ae51ba-894f-4c36-b185-555c284227a7)

Clique no Icone para abrir Typebot, coloque email cadastrado no SMTP, recebera link em seu email, para accessa Typebot

![48099001-7406354be1635d5a0f827411729b083c](https://github.com/cwmkt/easypanelevotypebot/assets/91642837/f11193c7-91f5-4422-8f94-c348c9990fee)


