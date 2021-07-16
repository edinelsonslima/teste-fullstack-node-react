# Teste fullstack

Leia primeiro todo o projeto, faça sua estimativa de horas para o desenvolvimento e envie um email com o título `[Teste Fullstack] Estimativa` para rh@4.events

Forke este projeto, faça o desenvolvimento e quando finalizar faça um PR aqui. Envie um email com o título `[Teste Fullstack] Finalizado` para rh@4.events com o link do seu PR.

Se você não sabe o que é fazer um "Forke" ou um "PR", pesquise. Valorizamos muito a proatividade.

**Lembre-se: atualize este README informando como instalar e executar seu projeto.**

## Missão backend

Desenvolver uma **API JSON RESTful** em **Node**, que utilize os métodos `GET` e `POST`.

Faça o teste unitário da **API** (Bônus :star:)
### Especificação

Monte uma base de veículo com a seguinte estrutura:

```
veiculo:   string
ano:       integer
descricao: text
vendido:   bool
created:   datetime
```

Utilize **MongoDB** ou **MySQL** para armazenar os dados que a **API** irá consumir.

### API endpoints

`GET /veiculos`

Retorna todos os veículos

---

`GET /veiculos/find`

Retorna os veículos de acordo com o termo passado parâmetro `q`

---

`POST /veiculos`

Adiciona um novo veículo


## Missão frontend

Desenvolver uma **UI (User Interface)** de acordo com o desenho que está na pasta [layout]

### Especificação

- Cross browser support (IE11+)
- Consumir **API** criada acima
- Criar uma tela que tenha...
    - Listagem de veículos
    - Busca
    - Formulário de novo veículo

### Dica

Utilize algum framework para auxiliar no desenvolvimento da interface, por exemplo:

- https://getmdl.io/
- http://getbootstrap.com/css/
- http://foundation.zurb.com/

## Dúvida

Se tiver qualquer dúvida sobre esse teste, envie um email com o título `[Teste Fullstack] O assunto que vc deseja` para rh@4.events
