👤 Identificação
Nome: Ana 

Instituição: UNA

Curso: Análise e Desenvolvimento de Sistemas (ADS)

🧠 Relatório Técnico
• Implementação Blazor (Hierarquia Visual)
A transposição do protótipo do Miro para o Blazor foi feita priorizando a Visibilidade do Status do Sistema.

O Saldo Geral recebeu destaque principal com a cor azul (bg-primary), sendo o elemento de maior peso visual.

Valores de crédito e débito utilizam cores semânticas (verde e vermelho) para que a interpretação seja imediata, sem necessidade de leitura textual aprofundada, respeitando a hierarquia de importância definida no rascunho.

• Dificuldade Técnica (Componentização)
O maior desafio ao componentizar o GrupoCard foi gerenciar a estilização dinâmica. Foi necessário criar uma lógica que interpretasse os dados do objeto Grupo para aplicar classes CSS condicionais. Garantir que o componente alterasse bordas, textos e rótulos ("Você deve" vs "Você recebe") automaticamente, mantendo a responsividade do layout, foi a parte mais complexa da implementação.
