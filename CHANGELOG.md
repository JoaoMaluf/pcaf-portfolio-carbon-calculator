# Changelog

## v3.3.1 — 16/10/2026

### Added
- Guias completo e rápido, ajuda contextual, dicionário de campos, documentação por método e matrizes de preenchimento/cobertura.
- Workbook Integrity e estrutura documental pública.
- FACTOR_INPUTS com 122 slots externos, unidade/ano/fronteira e exigência de fonte/evidência.

### Fixed
- Correções de propagação de fórmulas/linhas vazias, inserção, exclusão, ordenação e atualização de resultados verificadas na regressão homologada.
- Validação de rotas CRE e Vehicles e configuração de proteção das cinco tabelas operacionais, conforme trilha homologada.
- Quatro exemplos internos que multiplicavam fator indisponível agora retornam n.a., correção anterior ao freeze.

### Changed
- Carteira restaurada para 54 operações / US$ 200 milhões, com retirada histórica dos exemplos adicionais de teste.
- Conteúdo numérico externo sem permissão estabelecida foi externalizado; mantidas referências e entradas do usuário.
- Cinco abas operacionais sem proteção, estrutura e motores protegidos/VeryHidden. Classes sem cobertura mostram n.a. e gráficos indicam cobertura parcial.
- Documentos finais organizados para distribuição; nenhuma mudança na calculadora durante o freeze.

### Validation
- 381 verificações aprovadas, zero falhas conhecidas; 15 UI-MANUAL NOT TESTED por limitação/timeout, formalmente dispensados pelo titular para freeze.
- Cópia final binariamente idêntica ao arquivo aprovado. Qualquer mudança futura do workbook exige nova versão, preferencialmente v3.4.0.
