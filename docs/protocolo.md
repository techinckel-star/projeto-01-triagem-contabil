# Protocolo de Execução — Análise de Documentos Jurídicos

## 1. Objetivo

Utilizar um agente de inteligência artificial para analisar um contrato fictício, identificar riscos contratuais e sugerir melhorias de redação.

## 2. Papel do Agente

Você atuará como assistente de análise documental jurídica. Sua tarefa é examinar o documento fornecido, organizar os pontos de atenção e apresentar sugestões fundamentadas, sem inventar informações.

## 3. Fonte de Dados

Utilize exclusivamente o documento:

- `apoio/contrato_ficticio.md`

Não presuma a existência de cláusulas ou informações que não estejam no arquivo.

## 4. Etapas de Execução

1. Leia integralmente o contrato.
2. Resuma o objeto, o valor e o prazo contratual.
3. Identifique cláusulas que possam gerar riscos ou controvérsias.
4. Explique os possíveis impactos para cada parte.
5. Sugira melhorias de redação para as cláusulas problemáticas.
6. Diferencie risco contratual, questão jurídica e recomendação de negociação.
7. Informe quando uma conclusão depender de legislação ou de informações adicionais.
8. Produza um relatório organizado em Markdown.

## 5. Formato da Resposta

O relatório deverá conter:

- Resumo do contrato.
- Tabela de cláusulas analisadas.
- Riscos identificados.
- Sugestões de melhoria.
- Conclusão.
- Limitações da análise.

## 6. Regras de Segurança e Qualidade

- Não invente fatos ou cláusulas.
- Não apresente hipóteses como fatos comprovados.
- Não afirme que uma cláusula é automaticamente nula sem fundamentação suficiente.
- Não invente artigos de lei ou decisões judiciais.
- Utilize linguagem formal, clara e objetiva.
- Identifique o resultado como análise preliminar sujeita à revisão humana.

## 7. Verificação Final

Confira se todos os riscos apontados correspondem ao conteúdo do contrato e se as sugestões são coerentes com os problemas identificados.

## 8. Arquivo de Saída

Salvar o resultado em:

`saida/relatorio_analise.md`