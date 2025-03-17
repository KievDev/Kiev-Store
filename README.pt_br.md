<h1 align="center"><a href="https://kiev-store.onrender.com">KIEVSTORE</a></h1>

<br/>

![Demo App](/frontend/public/demo-app.png)
<br/>
<h1>O Projeto</h1>
<p>O principal motivo do projeto foi demonstrar o uso de várias tecnologias modernas em um aplicativo fullstack, com foco na PERN stack.

No total, há 13 temas para o usuário escolher e personalizar sua experiência à vontade.

Podemos adicionar um produto ao banco de dados, juntamente com seu nome, preço e foto, editar cada um desses itens e também excluir os mesmos produtos.

Temos uma função de “atualização”, para que possamos obter os dados mais recentes do banco de dados.

Códigos e pastas estruturados de forma limpa, para facilitar a manutenção e a escalabilidade.</p>
<br/>
![Product Demo](/frontend/public/demo-product.png)
<br/>
<h1>Temas</h1>
<p>Como mencionado acima, há 13 temas diferentes para escolher.

Aqui estão alguns exemplos além do que já foi mostrado.</p>
<div align="center" display="flex" flex-direction="row" justify-content="center">
  
![Theme Demo 1](/frontend/public/theme1.png)![Theme Demo 2](/frontend/public/theme2.png)
</div>
<br/>
<h1>Tech Stack</h1>
<ul>
  <br/>
  <li>Frontend</li>
    <ul>
      <br/>
      <li>React.js – A principal biblioteca de front-end que cria UIs interativas com componentes reutilizáveis. Ela ajuda a gerenciar dados dinâmicos e o estado de forma eficiente.</li>
      <li>Tailwind CSS – Uma estrutura CSS que prioriza a utilidade e acelera a criação de estilos sem a necessidade de escrever CSS personalizado. Excelente para designs responsivos.</li>
      <li>DaisyUI – Uma biblioteca de componentes de interface do usuário baseada no Tailwind que fornece componentes pré-estilizados, reduzindo o tempo de desenvolvimento.</li>
      <li>Lucide Icons – Um conjunto de ícones limpo e personalizável para aprimorar o design da interface do usuário. Útil para botões, navegação e alertas.</li>
      <li>Hot Toast – Uma biblioteca leve de notificação de torradas para exibir alertas, erros e mensagens de sucesso em seu aplicativo.</li>
      <li>Zustand – Uma biblioteca de gerenciamento de estado para o React que é mais simples e mais leve que o Redux. Útil para gerenciamento de estado global.</li>
      <li>Vite – Uma ferramenta rápida de criação de front-end e servidor de desenvolvimento, que substitui o Webpack para melhorar o desempenho e acelerar o Hot Module Reloading (HMR).</li>
      <br/>
    </ul>
  <li>Backend</li>
    <ul>
      <br/>
      <li>Node.js – O tempo de execução que permite que o JavaScript seja executado no lado do servidor, manipulando a lógica de back-end e as solicitações de API.</li>
      <li>Express.js – Uma estrutura leve do Node.js para criar APIs. Ele gerencia rotas, middleware e lógica de servidor de forma limpa.</li>
      <li>PostgreSQL – Um poderoso banco de dados relacional usado para armazenar dados estruturados para o seu aplicativo, acessado por meio de consultas SQL.</li>
      <br/>
    </ul>
  <li>Ferramentas e Nuvem</li>
    <ul>
      <br/>
      <li>Neon Tech – Um serviço PostgreSQL sem servidor nativo da nuvem. Ele fornece uma solução de banco de dados gerenciado com dimensionamento automático, facilitando a implantação.</li>
      <li>Arcjet – Um serviço de implantação e hospedagem, provavelmente usado para implantar seu backend e banco de dados com configuração mínima.</li>
      <li>Postman – Uma ferramenta de teste de API que ajuda você a enviar solicitações para o back-end, depurar APIs e testar endpoints com facilidade.</li>
      <br/>
    </ul>
</ul>

### Configurar o arquivo .env

```js
PORT=3000

PGUSER=...
PGPASSWORD=...
PGHOST=...
PGDATABASE=...

ARCJET_KEY=...
ARCJET_ENV=development
```

### Iniciar API

```shell
npm run dev
```

### Iniciar frontend

```shell
cd frontend
npm run dev
```
