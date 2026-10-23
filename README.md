# Gerador de Códigos - Plataforma Adaptativa SESC

Uma ferramenta de busca rápida e gerador de links dinâmicos desenvolvida para otimizar o fluxo de trabalho da equipe na plataforma adaptativa Educat/SESC.

## O Problema e a Solução
No nosso ambiente de trabalho, momentos de alta demanda exigem respostas rápidas. A navegação tradicional na plataforma nativa requer a seleção manual de diversos filtros consecutivos, o que frequentemente resulta em lentidão e gargalos no processo. 

Este aplicativo foi desenvolvido para **contornar essa lentidão**. Ele permite que a equipe encontre o código exato (ID) da prova de forma instantânea e pule as etapas de filtragem nativa, acessando diretamente a página do estudante/prova com apenas um clique.

##  Funcionalidades
* **Filtro Inteligente e Dinâmico:** Seleção rápida por Ano/Série, Área de Conhecimento e Especificação da prova (Normal, Simplificada ou Reduzida).
* **Validação de Existência:** O sistema cruza os dados em tempo real e exibe apenas as especificações que realmente existem para aquela série/área, evitando erros de busca.
* **Copy & Paste Ágil:** Botão dedicado para copiar o ID numérico da prova diretamente para a área de transferência.
* **Acesso Direto (Bypass de Filtros):** O botão "Abrir na Educat" gera a URL final (`https://adaptativo-sesc.educat.net.br/estudantes/lista_estudantes/[CÓDIGO]`) e redireciona o usuário imediatamente para a página alvo.

##  Como Utilizar
A ferramenta não requer instalação e roda diretamente no navegador.

1. Acesse o link da aplicação: **[Pendente]**
2. Selecione o **Ano/Série** desejado.
3. Escolha a **Área de Conhecimento** correspondente.
4. Defina a **Especificação** (se houver variação disponível).
5. Clique em **Buscar Código**.
6. Escolha entre **Copiar Código** (para uso em planilhas ou relatórios) ou **Abrir na Educat** (para ir direto à plataforma já com a página correta carregada).

##  Tecnologias Utilizadas
* **HTML5:** Estruturação semântica.
* **CSS3:** Design responsivo, interface corporativa alinhada à identidade visual do SESC e efeitos modernos (*Glassmorphism*).
* **JavaScript (Vanilla):** Lógica de filtragem do banco de dados interno e manipulação dinâmica de URLs.
