# React Form CEP

## Descrição

Este projeto é um formulário React para consulta de CEP (Código de Endereçamento Postal) brasileiro. A aplicação permite ao usuário digitar um CEP e automaticamente preenche os dados de endereço consumindo uma API pública de CEP (como ViaCEP).

Ideal para aplicações que necessitam capturar endereços de forma ágil, simples e segura, melhorando a experiência do usuário ao evitar preenchimento manual dos campos.

## Tecnologias Utilizadas

- **React** (Create React App)
- **TypeScript** (caso aplicável)
- **Styled Components** ou CSS Modules (caso aplicável)
- **API ViaCEP** para busca dos dados de endereço
- **React Hook Form** ou Formik para gerenciamento de formulários (caso aplicável)

## Funcionalidades

- Campo para digitação do CEP
- Busca automática de endereço ao digitar um CEP válido
- Preenchimento automático de rua, bairro, cidade e estado
- Validação de CEP e dos campos obrigatórios do formulário
- Exibição de mensagens de erro para CEP inválido ou não encontrado

## Como usar

1. **Clone o repositório:**
    ```bash
    git clone https://github.com/fabiocberg/react-form-cep.git
    cd react-form-cep
    ```

2. **Instale as dependências:**
    ```bash
    npm install
    # ou
    yarn install
    ```

3. **Rode o app:**
    ```bash
    npm start
    # ou
    yarn start
    ```
    O app estará disponível em `http://localhost:3000`.

## Exemplo de uso

Ao digitar um CEP válido, os campos de endereço são preenchidos automaticamente:

```plaintext
CEP: 01001-000
Rua: Praça da Sé
Bairro: Sé
Cidade: São Paulo
Estado: SP
```

## Estrutura de Pastas

```
src/
├── components/        # Componentes reutilizáveis de formulário
├── services/          # Serviços de integração com a API ViaCEP
├── App.js             # Componente principal
└── index.js           # Bootstrap da aplicação
```

## Personalização

- Substitua a API de consulta de CEP conforme necessidade.
- Integre o formulário com seu back-end ou sistema desejado.
- Adicione máscaras, validações ou campos extras conforme o contexto da sua aplicação.

## Licença

MIT

---

> Este projeto é um exemplo educacional e pode ser extendido para uso em aplicações reais.