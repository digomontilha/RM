# Estrutura do Site - Sistema RM (Represa Management)

## Requisitos do Site

### Objetivo Principal
Criar uma plataforma digital simples e eficaz para promover o equilíbrio entre preservação ambiental e desenvolvimento urbano no Parque da Represa em Jundiaí.

### Público-Alvo
- Moradores do Parque da Represa (antigos e novos)
- Comerciantes locais
- Visitantes da região
- Jovens e estudantes
- Representantes de instituições (DAE, Prefeitura)

### Requisitos Funcionais
1. Apresentar informações sobre o Parque da Represa e sua importância ambiental
2. Divulgar políticas de preservação dos recursos hídricos
3. Listar comércios locais sustentáveis
4. Mostrar projetos ambientais em andamento
5. Permitir contato para dúvidas e sugestões
6. Fornecer calendário de eventos/workshops

### Requisitos Técnicos
1. Site estático (HTML, CSS, JavaScript básico)
2. Design responsivo (adaptável a dispositivos móveis)
3. Carregamento rápido
4. Navegação intuitiva
5. Acessibilidade básica

## Estrutura de Páginas

### 1. Página Inicial (index.html)
- Banner principal com imagem do Parque da Represa
- Breve introdução ao Sistema RM
- Destaques (eventos próximos, notícias)
- Menu de navegação
- Chamadas para ação (CTA) para as principais seções

### 2. Sobre o Parque (sobre.html)
- História do Parque da Represa
- Importância ambiental
- Mapa da região
- Galeria de fotos
- Dados e estatísticas relevantes

### 3. Preservação (preservacao.html)
- Políticas de preservação dos recursos hídricos
- Dicas de sustentabilidade
- Projetos ambientais em andamento
- Como participar/contribuir

### 4. Guia Comercial (comercios.html)
- Listagem de comércios locais sustentáveis
- Filtros por categoria
- Informações de contato
- Práticas sustentáveis adotadas

### 5. Eventos (eventos.html)
- Calendário de workshops e eventos
- Formulário para inscrição
- Galeria de eventos passados

### 6. Contato (contato.html)
- Formulário de contato
- Informações para contato direto
- FAQ (Perguntas Frequentes)
- Mapa de localização

## Estrutura de Arquivos

```
sistema_rm_site/
│
├── index.html                  # Página inicial
├── sobre.html                  # Página Sobre o Parque
├── preservacao.html            # Página de Preservação
├── comercios.html              # Página de Guia Comercial
├── eventos.html                # Página de Eventos
├── contato.html                # Página de Contato
│
├── css/
│   ├── style.css               # Estilos principais
│   └── responsive.css          # Estilos responsivos
│
├── js/
│   ├── main.js                 # Funcionalidades gerais
│   └── eventos.js              # Funcionalidades específicas para eventos
│
├── images/
│   ├── logo.png                # Logo do Sistema RM
│   ├── banner.jpg              # Banner principal
│   ├── parque/                 # Fotos do parque
│   ├── comercios/              # Fotos dos comércios
│   └── icons/                  # Ícones utilizados
│
└── docs/
    └── politicas.pdf           # Documentos para download
```

## Paleta de Cores

- **Azul principal** (#1a5276): Representa a água da represa
- **Verde** (#2ecc71): Representa a vegetação e sustentabilidade
- **Marrom claro** (#d4ac0d): Representa a terra/solo
- **Cinza claro** (#ecf0f1): Fundo de seções e textos
- **Branco** (#ffffff): Fundo principal e textos em áreas escuras

## Tipografia

- **Títulos**: Montserrat (sans-serif)
- **Corpo de texto**: Open Sans (sans-serif)
- **Destaques**: Roboto (sans-serif)

## Elementos de Design

- Ícones simples e intuitivos
- Botões com cantos arredondados
- Cards para apresentação de comércios e eventos
- Imagens de alta qualidade do Parque da Represa
- Gráficos simples para dados ambientais
