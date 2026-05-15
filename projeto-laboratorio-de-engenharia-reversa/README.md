🧪 Laboratório de Engenharia Reversa: Markdown Live

Projeto de Reconstrução Full-Stack assistida por IA Generativa.
Este projeto faz parte do portfólio de Gustavo Matsuo para a disciplina de Inteligência Artificial.

🛠️ Tecnologias & Ferramentas

🎯 Objetivo do Projeto

O desafio consistiu em reconstruir o aplicativo StackEdit atuando como um Desenvolvedor Full-Stack. O objetivo central foi replicar a interface e as regras de lógica de negócio utilizando exclusivamente a observação externa e a Engenharia de Prompts via Google AI Studio, sem acesso ao código-fonte original.

Análise: Mapeamento visual e funcional da referência.

Configuração: Definição de System Instructions para o Gemini 3.

Validação: Testes iterativos para garantir paridade estética e funcional.

✨ Funcionalidades Implementadas

⚙️ Motor de Renderização

Real-time Preview: Conversão instantânea de Markdown para HTML conforme a digitação.

GitHub Flavored Markdown: Suporte completo para tabelas, listas de tarefas, blocos de código e links.

🛠️ Barra de Ferramentas

Formatação Contextual: Botões para Negrito, Itálico, Títulos (H1, H2).

Inserção Inteligente: Adiciona tags de formatação ao redor da seleção do cursor.

💾 Persistência e Exportação

Auto-save: Armazenamento automático no localStorage do navegador.

Download .md: Geração de arquivo Blob para salvamento local do documento.

Copy HTML: Conversão e cópia do código renderizado para o clipboard.

🚀 Como Executar

Clone o repositório:

git clone [https://github.com/Gustavo-Matsuo/portfolio-gustavo-da-costa-matsuo.git](https://github.com/Gustavo-Matsuo/portfolio-gustavo-da-costa-matsuo.git)


Acesse a pasta:
Navegue até projeto-laboratorio-de-engenharia-reversa.

Abra o arquivo:
Execute o index.html em qualquer navegador moderno.

🧠 Metodologia (Prompt Engineering)

A estrutura foi gerada através de uma abordagem de IA-Assisted Development:

Persona: Configuração do modelo para atuar como desenvolvedor sênior.

Modularização: Solicitação de código limpo integrando React e Tailwind via CDN para portabilidade.

Refinamento: Ajustes finos para garantir que a interface fosse responsiva e seguisse o padrão Dark Mode Slate.

📂 Estrutura de Arquivos

index.html: Arquivo único contendo a estrutura, estilização e lógica do aplicativo.

README.md: Documentação técnica do processo de engenharia reversa.

Este repositório é um exemplo prático de como ferramentas de IA podem acelerar o ciclo de vida de desenvolvimento de software.
