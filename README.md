
# Search Products

## Como Executar

### Clonar o Repositório

```bash
git clone https://github.com/Luis020-hub/Lambda-Search
```

### Configurando o Ambiente

1. Renomeie o arquivo `.env.sample` para `.env`.
2. Renomeie o arquivo `template.sample.yml` para `template.yaml`.

Depois de renomeados, preencha com suas informações.

### Instalar as Dependências

```bash
cd ./search
npm install
```

### Executar os Testes

```bash
npm run test
```

### Build e Deploy

```bash
sam build
sam deploy --guided
```

### Remover a Função

```bash
sam delete
```
