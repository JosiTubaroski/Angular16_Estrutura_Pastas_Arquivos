<div> 
<p><a href="https://github.com/JosiTubaroski/-FullStackAngular_16_-_.NET/blob/main/README.md">Home</a></p>
</div> 

# Angular16 estrutura de Pastas e Arquivos

Quando você cria um projeto em <b>Angular 16</b> usando o Angular CLI (com o comando ng new nome-do-projeto), ele já gera uma <b>estrutura completa</b> de arquivos e pastas, pensada para escalabilidade e boas práticas.

Aqui vai um resumo da <b>estrutura inicial</b> e <b>para que serve cada parte:</b>

## 🗂️ Estrutura de pastas geradas pelo Angular 16

       meu-projeto/
       ├── node_modules/
       ├── src/
       │   ├── app/
       │   │   ├── app.component.ts
       │   │   ├── app.component.html
       │   │   ├── app.component.css
       │   │   └── app.module.ts
       │   ├── assets/
       │   ├── environments/
       │   ├── index.html
       │   ├── main.ts
       │   ├── styles.css

       ├── angular.json
       ├── package.json
       ├── tsconfig.json
       └── README.md

### 🧠 Entendendo cada parte:

📁 node_modules/

- Pasta onde ficam <b>todas as dependências</b> do projeto (bibliotecas do Angular, etc).
- Criada automaticamente com npm install.

📁 src/

<b>Onde vive o código-fonte da sua aplicação.</b>

- Aqui ficam os <b>componentes, módulos, serviços e rotas</b> da sua aplicação.
- Exemplo:
  - app.component.ts: lógica do componente principal (AppComponent).
  - app.component.html: HTML do AppComponent.
  - app.component.css: estilo do AppComponent.
  - app.module.ts: <b>módulo raiz</b>, onde se declara os componentes e importa outros módulos.

 📁 assets/

 - Onde ficam <b>imagens, fontes, arquivos estáticos</b> que você vai usar no front.


