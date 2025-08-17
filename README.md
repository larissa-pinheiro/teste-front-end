# 🛒 Teste Front-End Jr  
<div align="center">

  <!-- React -->
  <img src="https://img.shields.io/badge/React-Componentes_Intuitivos-61DAFB?style=for-the-badge&logo=react&logoColor=white" alt="React Badge" />

  <!-- TypeScript -->
  <img src="https://img.shields.io/badge/TypeScript-Tipos_Fortes-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript Badge" />

  <!-- Vite -->
  <img src="https://img.shields.io/badge/Vite-Dev_Rápido-646CFF?style=for-the-badge&logo=vite&logoColor=FFD62E" alt="Vite Badge" />

  <!-- Sass -->
  <img src="https://img.shields.io/badge/Sass-Estilo_Escalável-CC6699?style=for-the-badge&logo=sass&logoColor=white" alt="Sass Badge" />

  <!-- Axios -->
  <img src="https://img.shields.io/badge/Axios-Requisições_Fáceis-5A29E4?style=for-the-badge&logo=axios&logoColor=white" alt="Axios Badge" />

  <!-- ESLint + Prettier -->
  <img src="https://img.shields.io/badge/Código-Limpo-4B32C3?style=for-the-badge&logo=eslint&logoColor=white" alt="ESLint Badge" />

</div>


Este projeto foi desenvolvido como parte do processo seletivo para a vaga de **Desenvolvedor Front-End Jr**.  
O objetivo foi criar uma página em **React + TypeScript**, consumindo dados de uma API em JSON e exibindo uma vitrine de produtos conforme layout fornecido no Figma.  

## 📌 Especificações Atendidas

- [x] Desenvolvimento em **React** com **TypeScript**  
- [x] Consumo de informações dos produtos via JSON  
- [x] Vitrine de produtos responsiva  
- [x] Modal de detalhes ao clicar em um produto  
- [x] Estilização com **Sass**  
- [x] Respeito ao layout pixel-perfect (cores, fontes, botões, espaçamentos)  
- [x] Uso de **HTML semântico** e boas práticas de **SEO**  
- [x] Projeto organizado e componentizado  

## 🛠️ Tecnologias Utilizadas

- **React** + **TypeScript**
- **Vite** (para build rápido e dev server)  
- **Sass** (pré-processador CSS)  
- **Axios** (requisições HTTP ao JSON de produtos)  
- **ESLint + Prettier** (padronização de código)  

## 📂 Estrutura do Projeto

```bash
├── public/               # Arquivos estáticos
├── src/
│   ├── assets/           # Imagens, ícones, fontes
│   ├── components/       # Componentes reutilizáveis
│   │   ├── ProductCard/  # Card de produto
│   │   ├── Modal/        # Modal de detalhes do produto
│   ├── pages/            # Páginas principais
│   ├── services/         # Consumo da API (JSON)
│   ├── styles/           # Estilos globais (Sass)
│   ├── types/            # Tipagens TypeScript
│   ├── App.tsx           # Componente raiz
│   └── main.tsx          # Entrada da aplicação
├── package.json
├── tsconfig.json
├── vite.config.ts
└── README.md
```  

## ▶️ Como rodar o projeto

### 1. Clonar repositório
```bash
git clone https://github.com/larissa-pinheiro/teste-front-end.git
cd teste-front-end
```

### 2. Instalar dependências
```bash
yarn
```

### 3. Rodar em desenvolvimento
```bash
yarn dev
```

Aplicação disponível em:  
👉 `http://localhost:5173`

### 4. Gerar build de produção
```bash
yarn build
```

### 5. Visualizar build local
```bash
yarn preview
```

## 🚀 Melhorias Futuras

- Paginação ou lazy loading dos produtos  
- Testes unitários 
- Integração com API real  
- Melhorias de acessibilidade (ARIA roles, navegação via teclado)  

## 📧 Contato

Desenvolvido por Larissa Pinheiro  
🔗 LinkedIn: [Larissa Pinheiro](https://www.linkedin.com/in/larissa-mpinheiro/)  
