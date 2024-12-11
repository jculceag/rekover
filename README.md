# rekover 

Projeto de estudo em Next com Vercel, usando a Rekover como referencia! 

=====================================

Criação inicial do projeto next com node e suas dependencias:
1. `` npm init -y
2. `` npm install next
3. `` npm install react 
4. `` npm install next react react-dom

=====================================
você nao precisa configurar rotas no seu projeto, pq para cada arquivo dentro da pasta pages
vira automaticamente uma rota e uma página, assim como no PHP.

Então só criar a pasta na raiz com nome pages e dentro dela um arquivo index.js ou ts
se quiser trabalhar com typeScript

function Home() {
    return <div><h2>Página em construção!</h2></div>
}

export default Home

=====================================

depois de add o ambiente no arquivo package.json 

  "scripts": {
    "dev": "next dev"
  },

bora executar o ambiente
`` npm run dev

=====================================