# Classes Sociais - LIS (Ensino Médio) 📚

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)

## 📚 Sobre o Projeto

Material didático interativo e completo sobre **Classes Sociais: Teorias, Estratificação e Mobilidade**, desenvolvido para estudantes do 2º ano do Ensino Médio da **Escola Estadual Joaquim Diégues** como parte das atividades do **Laboratório de Iniciativas Sociais (LIS) - 2ª série C**.

Este projeto foi desenvolvido com foco na **acessibilidade**, **responsividade** e **experiência do usuário**, oferecendo uma abordagem moderna e interativa para o aprendizado sobre classes sociais, desigualdade e estratificação.

## ✨ Funcionalidades

### 🎨 Interface e Design

- **Design Responsivo**: Adapta-se perfeitamente a smartphones, tablets e desktops
- **Tema Escuro/Claro**: Toggle between light and dark modes
- **Animações Suaves**: Transições e efeitos visuais aprimorados
- **Tipografia Otimizada**: Fontes legíveis e hierarquia visual clara

### 🔍 Busca e Navegação

- **Busca Interna**: Sistema de busca avançado com destaque de resultados
- **Navegação Rápida**: Menu sticky com links para todas as seções
- **Breadcrumbs**: Navegação contextual para melhor orientação
- **Smooth Scrolling**: Rolagem suave entre seções

### ♿ Acessibilidade

- **WCAG 2.1 AA Compliant**: Segue as melhores práticas de acessibilidade
- **Skip Links**: Links para pular para conteúdo principal
- **ARIA Labels**: Rótulos apropriados para leitores de tela
- **Navegação por Teclado**: Suporte completo para navegação via teclado
- **Alto Contraste**: Suporte para preferências de alto contraste

### 📱 Progressive Web App (PWA)

- **Funciona Offline**: Cache inteligente para acesso sem internet
- **Instalável**: Pode ser instalado como app nativo
- **Rápido**: Carregamento otimizado e cache estratégico
- **Service Worker**: Atualizações em background

### 📊 Analytics e Performance

- **Reading Progress**: Barra de progresso de leitura
- **Engagement Tracking**: Monitoramento de interações
- **Performance Optimized**: Carregamento rápido e eficiente
- **Lazy Loading**: Carregamento sob demanda de conteúdo

## 🗺️ Conteúdo

### Principais Seções

1. **🎯 O que são Classes Sociais?**
   - Definição e importância
   - Fatores determinantes (renda, educação, ocupação, poder)
   - Divisão social do trabalho

2. **📚 Karl Marx e a Perspectiva Econômica**
   - Burguesia e Proletariado
   - Mais-valia
   - Alienação
   - Consciência e luta de classes

3. **🔍 Max Weber e a Análise Multidimensional**
   - Três dimensões (Classe, Status, Poder)
   - Análise comparativa com Marx

4. **📊 Estratificação Social**
   - Tipos: Castas, Estamentos, Classes
   - Visões teóricas (Marx vs Weber)

5. **📈 Mobilidade Social**
   - Tipos de mobilidade (vertical, horizontal)
   - Mobilidade intergeracional e intrageracional
   - Contexto brasileiro

6. **🇧🇷 Estrutura de Classes no Brasil**
   - Desigualdade de renda e oportunidades
   - Políticas públicas
   - Iniciativas sociais

7. **📚 Recursos Complementares**
   - Vídeos educativos
   - Artigos acadêmicos
   - Links para conteúdo adicional

## 🚀 Tecnologias Utilizadas

### Frontend

- **HTML5**: Estrutura semântica e acessível
- **CSS3**: Estilos avançados com variáveis CSS e Grid Layout
- **JavaScript ES6+**: Funcionalidades interativas modernas
- **Font Awesome 6**: Ícones vetoriais

### Performance e PWA

- **Service Worker**: Cache offline e sincronização
- **Web App Manifest**: Metadados para PWA
- **Lazy Loading**: Otimização de carregamento
- **Critical CSS**: CSS crítico inline

### SEO e Acessibilidade

- **Open Graph**: Metadados para redes sociais
- **Schema.org**: Dados estruturados
- **ARIA**: Acessibilidade para leitores de tela
- **Semantic HTML**: Estrutura semântica apropriada

## 💻 Estrutura do Projeto

```
lis-2c-classes-sociais/
│
├── index.html        # Página principal
├── manifest.json     # Manifesto PWA
├── sw.js            # Service Worker
├── README.md        # Documentação
├── robots.txt       # SEO robots
├── sitemap.xml      # Sitemap SEO
│
├── .github/         # GitHub configurations
│
├── css/
│   └── style.css    # Estilos principais
│
├── js/
│   └── script.js    # JavaScript principal
│
└── icons/           # Ícones PWA (planejado)
```

## 🚀 Como Usar

### Acesso Online

O projeto está disponível em: [https://alexandrehenriqueventura.github.io/lis-2c-classes-sociais/](https://alexandrehenriqueventura.github.io/lis-2c-classes-sociais/)

### Instalação Local

1. **Clone o repositório**:

```bash
git clone https://github.com/alexandrehenriqueventura/lis-2c-classes-sociais.git
```

2. **Navegue para o diretório**:

```bash
cd lis-2c-classes-sociais
```

3. **Sirva os arquivos**:

```bash
# Com Python
python -m http.server 8000

# Com Node.js (serve)
npx serve .

# Com PHP
php -S localhost:8000
```

4. **Acesse no navegador**:

```
http://localhost:8000
```

### Instalação como PWA

1. Acesse o site no navegador
2. Procure pelo ícone de "Instalar" na barra de endereço
3. Clique em "Instalar" quando o prompt aparecer
4. O app será instalado e poderá ser usado offline

## 🎨 Personalização

### Temas

O projeto suporta temas claro e escuro automaticamente:

- Detecta preferência do sistema
- Permite toggle manual
- Salva preferência no localStorage

### Cores

As cores podem ser facilmente personalizadas no CSS usando variáveis:

```css
:root {
  --primary: #2d8653;      /* Verde principal */
  --secondary: #236b43;    
  --accent: #1a5232;       
  --light: #f5fef8;        
  --dark: #0f3d22;         
}
```

### Conteúdo

O conteúdo pode ser facilmente atualizado editando o `index.html`. Cada seção é bem estruturada e documentada.

## 🔍 Busca

O sistema de busca inclui:

- Busca em tempo real
- Destaque de termos encontrados
- Navegação por teclado nos resultados
- Snippets contextuais

## 📊 Performance

### Métricas

- **First Contentful Paint**: < 1.5s
- **Largest Contentful Paint**: < 2.5s
- **Cumulative Layout Shift**: < 0.1
- **First Input Delay**: < 100ms

### Otimizações

- CSS e JavaScript minificados
- Lazy loading de conteúdo
- Service Worker para cache
- Prefetch de links importantes

## ♿ Acessibilidade

### Recursos Implementados

- Contraste de cores WCAG AA
- Navegação por teclado completa
- Rótulos ARIA apropriados
- Skip links para conteúdo principal
- Suporte a leitores de tela
- Textos alternativos para ícones

### Testes

O projeto foi testado com:

- NVDA (Windows)
- JAWS (Windows)
- VoiceOver (macOS/iOS)
- TalkBack (Android)
- axe DevTools

## 📱 Responsividade

### Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

### Adaptações

- Menu hamburguer no mobile
- Layout flexível
- Tipografia responsiva
- Touch-friendly em interações móveis

## 🛠️ Desenvolvimento

### Estrutura do Código

- **CSS**: Organizado em seções lógicas com comentários
- **JavaScript**: Classes ES6 com separação de responsabilidades
- **HTML**: Semântico e bem estruturado

### Boas Práticas

- Mobile-first design
- Progressive enhancement
- Graceful degradation
- Performance budget
- Semantic versioning

## 🔄 Atualizações Futuras

### Planejadas

- 🎥 Vídeos educacionais integrados
- 🧩 Quiz interativo sobre classes sociais
- 📊 Gráficos e visualizações de dados
- 🗺️ Mapas interativos sobre desigualdade
- 📧 Export para PDF
- 🔔 Notificações push
- 🌍 Internacionalização (i18n)
- 📝 Glossário de termos sociológicos

## 📄 Licença

Este projeto não possui uma licença específica definida. É um material educacional desenvolvido para fins didáticos.

## 🤝 Contribuições

Contribuições são muito bem-vindas! Para contribuir:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

### Tipos de Contribuição

- 🐛 Correção de bugs
- ✨ Novas funcionalidades
- 📝 Melhoria da documentação
- 🎨 Melhorias de design
- ♿ Melhorias de acessibilidade
- 🔍 Otimizações de performance
- 🌍 Traduções

## 📞 Contato

**Alexandre Henrique Ventura**

- Email: alexandrehenrique.ventura@gmail.com
- GitHub: [@alexandrehenriqueventura](https://github.com/alexandrehenriqueventura)

**Instituição**

- Escola Estadual Joaquim Diégues
- Laboratório de Iniciativas Sociais - 2ª série C
- Viçosa, Alagoas, Brasil

## 🙏 Agradecimentos

- **Escola Estadual Joaquim Diégues**: Pelo apoio institucional
- **Estudantes da 2ª série C**: Pelo feedback e testes
- **Comunidade Open Source**: Pelas ferramentas e inspiração
- **Autores clássicos**: Marx, Weber e demais sociólogos

---

**Desenvolvido com ❤️ para a educação em Ciências Sociais**

[Brasil Escola - Classes Sociais](https://brasilescola.uol.com.br/sociologia/classes-sociais.htm) • [Toda Matéria - Estratificação Social](https://www.todamateria.com.br/estratificacao-social/) • [Mundo Educação - Classe Social](https://mundoeducacao.uol.com.br/sociologia/classe-social.htm)
