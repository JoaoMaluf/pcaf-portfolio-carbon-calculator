# v3.3.1 — Educational Public Release

## Highlights
Calculadora educacional independente de emissões financiadas com carteira sintética, Dashboard, cenários, integridade e documentação por método. Freeze sem mudança do workbook homologado.

## Supported Asset Classes
Corporate Loans; Project Finance; Commercial Real Estate; Mortgages; Motor Vehicle Loans.

## Methodology
Referência PCAF Part A 2025, com AF e DQ conforme implementação documentada. S1+2 e S3 nas classes/rotas implementadas; fontes externas não incorporadas devem ser fornecidas pelo usuário.

## Validation
381 verificações aprovadas; zero falhas conhecidas. 15 passos UI-MANUAL NOT TESTED por timeout da ferramenta, com dispensa expressa para freeze. A cópia final é binariamente idêntica ao arquivo aprovado; não se declara nova execução dos testes anteriores.

## Documentation
Guias completo e rápido, matrizes de preenchimento e cobertura, registro de métodos/fatores/fontes, homologação e reconciliação acompanham o pacote.

## Known Limitations
54 operações / US$ 200 milhões, com cobertura pública S1+2 de 52,5% até fornecer fatores externos; resultados são parciais. 26 rotas calculam com inputs próprios completos, 16 adicionais dependem de fatores externos; duas S3/2a não se aplicam e duas S3/2b não têm fator compatível. Excel 2013+ para ISFORMULA. Evidências sintéticas não são asseguração. O motor de veículos mantém validação global do kit anual. Indicador de integridade não valida todo o conteúdo de fórmulas ou fontes.

## License
Educational and Evaluation License v1.0, com atribuição e restrições de autoria/redistribuição. Não é apresentada como Open Source. Não concede direitos sobre fontes externas.

## Disclaimer
Implementação independente, sem produto oficial, endosso, certificação, auditoria ou asseguração das instituições citadas. Não constitui parecer jurídico, financeiro ou contábil. Usuário revisa inputs, métodos e fatores antes de uso profissional.

## Download
URL remota ainda não disponível. Após upload real, adicionar o endereço verificado. Assets preparados: calculadora PUBLIC_FINAL e pacote PUBLIC_RELEASE.zip. Conferir SHA-256 antes de usar.
