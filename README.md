# 🌟 Estrelas do Amanhã - Formulário de Matrícula

Este projeto é um formulário web moderno e responsivo para matrícula de crianças na escola de educação infantil "Estrelas do Amanhã". O formulário foi desenvolvido com foco na experiência do usuário, acessibilidade e design intuitivo.

## 📋 Índice

- [Visão Geral](#-visão-geral)
- [Funcionalidades](#-funcionalidades)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Como Usar](#-como-usar)
- [Design e Interface](#-design-e-interface)
- [Formulário Detalhado](#-formulário-detalhado)
- [Responsividade](#-responsividade)
- [Contribuição](#-contribuição)
- [Licença](#-licença)

## 🎯 Visão Geral

O **Estrelas do Amanhã** é um formulário de matrícula escolar que permite aos pais e responsáveis inscreverem seus filhos de forma prática e intuitiva. O projeto destaca-se por sua interface limpa, moderna e pela atenção aos detalhes na experiência do usuário.

### Características Principais

- **Interface Moderna**: Design clean e profissional
- **Experiência Intuitiva**: Fluxo de preenchimento lógico e organizado
- **Validação de Dados**: Validação de campos obrigatórios e formatação
- **Upload de Arquivos**: Sistema de drag-and-drop para documentos
- **Responsivo**: Adaptável a diferentes tamanhos de tela

## ✨ Funcionalidades

### 📝 Coleta de Informações Completa
- **Dados da Criança**: Nome, data de nascimento, sexo e informações médicas
- **Endereço Residencial**: CEP, rua, número, cidade e estado
- **Responsável**: Nome, telefone e email de contato
- **Opções de Matrícula**: Turno de estudo e modalidade esportiva

### 🎨 Interface Rica
- **Ícones Personalizados**: Conjunto completo de ícones SVG
- **Elementos Interativos**: Radio buttons, checkboxes e select customizados
- **Feedback Visual**: Estados de hover, foco e erro
- **Design Responsivo**: Layout adaptável para mobile e desktop

### 📁 Upload de Documentos
- **Drag and Drop**: Interface intuitiva para upload de arquivos
- **Validação de Arquivos**: Suporte para documentos necessários
- **Feedback Visual**: Indicadores claros do status do upload

## 🛠 Tecnologias Utilizadas

- **HTML5**: Estrutura semântica e acessível
- **CSS3**: Estilização moderna com variáveis CSS e flexbox
- **JavaScript**: (implícito para funcionalidades interativas)
- **Google Fonts**: Tipografia Poppins e Archivo
- **SVG Icons**: Ícones escaláveis personalizados

## 📁 Estrutura do Projeto

```
projeto-formulario/
├── index.html              # Página principal
├── README.md               # Documentação do projeto
├── assets/                 # Recursos visuais
│   ├── Illustration.svg    # Ilustração principal
│   ├── logo.svg           # Logo da escola
│   └── icons/             # Conjunto de ícones SVG
│       ├── alert-circle.svg
│       ├── arrow-*.svg
│       ├── sports/*.svg
│       └── ...
└── styles/                # Arquivos de estilo
    ├── index.css          # Importações principais
    ├── global.css         # Estilos globais e variáveis
    ├── layout.css         # Layout e estrutura
    ├── forms.css          # Estilos dos formulários
    └── fields/            # Componentes específicos
        ├── buttons.css
        ├── checkbox.css
        ├── droparea.css
        ├── input.css
        └── radio.css
```

## 🚀 Como Usar

1. **Clone ou baixe o projeto**
   ```bash
   git clone https://github.com/Lstark10/projeto-formulario.git
   ```

2. **Abra o projeto**
   - Navegue até a pasta do projeto
   - Abra o arquivo `index.html` em seu navegador

3. **Preencha o formulário**
   - Complete todos os campos obrigatórios
   - Faça upload da certidão de nascimento
   - Selecione as opções desejadas
   - Aceite os termos e condições

4. **Envie a matrícula**
   - Clique em "Fazer matrícula" para submeter o formulário

## 🎨 Design e Interface

### Paleta de Cores
```css
--text-primary: #292524     /* Texto principal */
--text-secondary: #57534E   /* Texto secundário */
--text-tertiary: #8F8881    /* Texto terciário */
--text-highlight: #E43A12   /* Destaque */
--surface-primary: #FFFFFF  /* Fundo principal */
--surface-secondary: #FEE7D6 /* Fundo secundário */
--stroke-highlight: #F3541C /* Bordas em destaque */
```

### Tipografia
- **Fonte Principal**: Poppins (Google Fonts)
- **Fonte Secundária**: Archivo (Google Fonts)
- **Hierarquia**: Sistema consistente de tamanhos e pesos

### Componentes Visuais
- **Botões**: Dois estilos (primário e secundário)
- **Campos de Input**: Design consistente com estados visuais
- **Radio Buttons**: Customizados com ícones temáticos
- **Checkboxes**: Estados visuais claros
- **Dropzone**: Interface drag-and-drop intuitiva

## 📋 Formulário Detalhado

### Seção 1: Informações da Criança
- Nome completo (obrigatório)
- Data de nascimento
- Sexo (select)
- Informações médicas (textarea)
- Upload da certidão de nascimento

### Seção 2: Endereço Residencial
- CEP
- Rua (preenchimento automático)
- Número da residência
- Cidade (preenchimento automático)
- Estado (preenchimento automático)

### Seção 3: Responsável
- Nome do responsável
- Telefone de contato
- Email (com validação)

### Seção 4: Opções de Matrícula
- **Turno de Estudo**:
  - Manhã (ícone sol com nuvem)
  - Tarde (ícone sol)

- **Modalidades Esportivas**:
  - Futebol ⚽
  - Basquete 🏀
  - Natação 🏊
  - Yoga 🧘
  - Vôlei 🏐
  - Box 🥊

### Seção 5: Termos e Condições
- Checkbox obrigatório para aceitar termos
- Links para políticas da escola

## 📱 Responsividade

O projeto foi desenvolvido com design responsivo em mente:

- **Layout Flexível**: Uso de flexbox para adaptação
- **Breakpoints**: Pontos de quebra para diferentes dispositivos
- **Mobile First**: Abordagem mobile-first no desenvolvimento
- **Imagens Adaptáveis**: SVGs que se ajustam a qualquer resolução

## 🎯 Acessibilidade

- **HTML Semântico**: Uso correto de tags e estrutura
- **Labels Associados**: Todos os campos possuem labels apropriados
- **Estados de Foco**: Navegação por teclado funcional
- **Contraste**: Cores que atendem critérios de acessibilidade
- **Textos Alternativos**: Imagens com atributos alt descritivos


## 📄 Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.


