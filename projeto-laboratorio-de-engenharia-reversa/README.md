Markdown Live Clone - Reconstrução Assistida por IA

Este projeto é uma aplicação web funcional que permite a edição e visualização de Markdown em tempo real. Foi desenvolvido como parte de uma atividade de engenharia reversa de software, utilizando o Google AI Studio e o modelo Gemini.

🎯 Objetivo

Reconstruir a interface e a lógica de negócio do StackEdit através da observação externa e engenharia de prompts, sem acesso ao código original.

✨ Principais Funcionalidades Implementadas

⚙️ Motor de Renderização

Marked.js: Implementação de suporte a GitHub Flavored Markdown, incluindo tabelas, listas de tarefas e quebras de linha automáticas.

🛠️ Barra de Ferramentas

Formatação: Negrito e Itálico com manipulação de seleção de texto.

Cabeçalhos: Inserção rápida de H1 e H2.

Links: Template inteligente de link que posiciona o cursor para edição imediata.

📤 Exportação e Utilitários

Download .md: Geração de arquivo Blob em tempo real para salvamento local.

Copy HTML: Conversor de Markdown para HTML puro com cópia direta para a área de transferência.

Auto-save: Persistência de dados via localStorage para evitar perda de progresso.

🎨 UI/UX Sênior

Design: Dark Mode moderno baseado na paleta Slate do Tailwind CSS.

Interface: Layout Split Screen com rolagem independente e tipografia otimizada (Fira Code para o editor e Inter para a UI).

Analytics: Contadores de palavras e caracteres no rodapé para controle de texto.

🛠️ Tecnologias Utilizadas

React.js: Biblioteca principal para a interface e gestão de estado.

Tailwind CSS: Estilização responsiva e moderna.

Marked.js: Parser para processamento de Markdown.

Google AI Studio (Gemini): Motor de IA para geração de código e arquitetura.

🚀 Como Executar

Clone este repositório.

Abra o ficheiro index.html em qualquer navegador moderno.
