# cookin-up

# Requisitos

Antes de iniciar, você precisa ter o [Node.js](https://nodejs.org/en) instalado em sua máquina. O Node.js é necessário para executar os scripts de desenvolvimento e build do projeto.

## Configuração de IDE Recomendada

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (e desativar o Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Suporte de Tipos para Importações `.vue` no TS

O TypeScript não pode lidar com informações de tipo para importações `.vue` por padrão, então substituímos o CLI `tsc` pelo `vue-tsc` para verificação de tipos. Nos editores, precisamos do [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin) para tornar o serviço de linguagem TypeScript ciente dos tipos `.vue`.

Se o plugin TypeScript standalone não parecer rápido o suficiente para você, o Volar também implementou um [Modo de Tomada de Controle](https://github.com/johnsoncodehk/volar/discussions/471#discussioncomment-1361669) que é mais performático. Você pode ativá-lo seguindo os seguintes passos:

1. Desative a Extensão TypeScript integrada
    1) Execute `Extensions: Show Built-in Extensions` no palete de comandos do VSCode
    2) Encontre `TypeScript and JavaScript Language Features`, clique com o botão direito e selecione `Disable (Workspace)`
2. Recarregue a janela do VSCode executando `Developer: Reload Window` no palete de comandos.

## Personalizar configuração

Veja [Referência de Configuração do Vite](https://vitejs.dev/config/).

## Configuração do Projeto

```sh
npm install
```

### Compilar e Recarga Rápida para Desenvolvimento

```sh
npm run dev
```

### Verificação de Tipos, Compilação e Minificação para Produção

```sh
npm run build
```

---

## 📁 Acesse o projeto
[Clique aqui para ver o projeto em funcionamento.](https://cookin-up-mocha.vercel.app/)
