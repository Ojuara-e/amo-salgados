# Amo Salgados – Documentação do Projeto

Bem-vindo ao repositório do site **Amo Salgados**.  
Este projeto apresenta uma **landing page institucional** voltada para o público **B2B** (revendedores, mercados, buffets etc.), destacando os produtos e a história da empresa.

---

## 📑 Sumário
- [Visão geral](#-visão-geral)
- [Estrutura de pastas](#-estrutura-de-pastas)
- [Tecnologias e boas práticas](#-tecnologias-e-boas-práticas)
- [Como executar localmente](#-como-executar-localmente)
- [Contribuição](#-contribuição)
- [Licença](#-licença)

---

## 📖 Visão geral

O objetivo do site é apresentar, de forma clara e responsiva, os serviços e produtos da **Amo Salgados**.  
O conteúdo principal está dividido em quatro páginas:

- **index.html** – Página inicial com chamada para produtos e informações gerais.  
- **produtos.html** – Descrição detalhada das linhas de produtos.  
- **sobre.html** – História, valores e diferenciais da empresa.  
- **contato.html** – Formulário para orçamento e canais de contato.  

---

## 📂 Estrutura de pastas

```bash
amo-salgados/
├── assets/
│   └── images/        # Imagens otimizadas para o site
├── index.html         # Página inicial
├── produtos.html      # Página de produtos
├── sobre.html         # Página "Quem Somos"
├── contato.html       # Página de contato
├── styles.css         # Estilos globais
└── script.js          # Função para abrir/fechar menu móvel
```

---

## 🛠 Tecnologias e boas práticas

- **HTML semântico**: uso de tags `header`, `section`, `nav`, `footer` etc., favorecendo acessibilidade e SEO.  
- **CSS modular e reutilizável**:  
  - Variáveis (`:root`) para cores, espaçamentos e largura máxima.  
  - Responsividade com `max-width` e `media queries`.  
  - Classes utilitárias para grid e espaçamentos.  
- **JavaScript minimalista**: `script.js` apenas para alternar o menu em telas pequenas.  
- **Acessibilidade**:  
  - Textos alternativos (`alt`) em todas as imagens.  
  - Formulários com `label` associados aos campos.  
  - Uso de `aria-label` nos botões de menu.  
- **Separação de responsabilidades**: HTML para conteúdo, CSS para estilo e JS para comportamento.  
- **Design responsivo**: Layout adaptável a diferentes tamanhos de tela sem depender de frameworks externos.  

---

## 🚀 Como executar localmente

Clone o repositório:

```bash
git clone https://github.com/<usuario>/amo-salgados.git
```

Acesse o diretório do projeto:

```bash
cd amo-salgados
```

Inicie um servidor estático ou abra `index.html` no navegador.  

Com Python instalado, execute:

```bash
python -m http.server 8000
```

Depois, acesse no navegador:  
```
http://localhost:8000
```

Ou simplesmente arraste o arquivo `index.html` para a janela do navegador.  

---

## 🤝 Contribuição

1. Faça um **fork** do projeto e crie um branch para suas alterações.  
2. Siga as boas práticas adotadas:  
   - Preservar a semântica e acessibilidade.  
   - Reutilizar variáveis do CSS e respeitar padrões de nomenclatura.  
   - Garantir que todas as páginas continuem responsivas.  
3. Submeta um **pull request** descrevendo claramente as mudanças.  

---

## 📜 Licença

Este projeto está licenciado sob a **MIT License**.  
Você é livre para usar, modificar e distribuir, desde que mantenha os créditos aos autores originais.  

---

📌 Documentação criada para facilitar a manutenção e evolução do site, reforçando as boas práticas de desenvolvimento front-end adotadas no projeto.
