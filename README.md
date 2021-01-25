<h1 align="center">
  Conceitos Mobx
  <div>
    <img src="https://img.shields.io/badge/-ReactJS-blue" />
    <img src="https://img.shields.io/badge/-Mobx-blueviolet" />
  </div>
</h1>

> Aplicação contendo um contador utilizando o Mobx.

## Conceitos

O Mobx é uma ferramenta para gerenciar estado de forma global. Alguns dos conceitos estudados:

- Observable: são propriedades observáveis por outros componentes da aplicação, mais precisamente são os estados globais que são gerenciados pela store.
- Action: uma action permite alterar o valor de determinada propriedade já definida como observável, ou seja, os dados da store são manipulados através de actions.
- Computed: são propriedades derivadas das mudanças de estado de outra propriedade.
- Observer: é responsável por observar, acompanhar as mudanças nas propriedades observáveis. Quando é percebida uma mudança no estado, o React é notificado e os componentes são renderizados com base nas novas informações.
- Store: a store é um container de informações, é a fonte de dados globais da aplicação. Diferentemente do funcionamento no Redux, a store do Mobx além de conter os dados, também contém as actions que permitem as alterações desses dados.


## Instalação

1. Abra seu terminal em uma pasta qualquer e clone este repositório
`git clone https://github.com/gustavo2892/conceitos-mobx.git`.
2. Navegue até o diretório da aplicação `cd conceitos-mobx`.
3. Rode `yarn` ou `npm i` para instalar todas as dependências.<br />
4. Rode `yarn start` ou `npm run start` e aguarde o sistema ser aberto em `http://localhost:3000`.