# Homologação final — v3.3.1

**READY — EDUCATIONAL PUBLIC RELEASE**. Freeze: 16/10/2026. Arquivo: PCAF_Portfolio_Carbon_Calculator_v3_3_1_PUBLIC_FINAL.xlsx.

381 verificações aprovadas; zero falhas conhecidas na homologação: 103 NATIVE-EXCEL, 20 suplementares, 92 execuções por rota e 166 estáticas. São evidências herdadas da versão aprovada, não testes reexecutados ou contagens infladas pelo fechamento. A cadeia de desenvolvimento não foi repetida porque o workbook permaneceu binariamente idêntico.

## UI-MANUAL waiver

Os 15 passos de interface permanecem **NOT TESTED — waived** por limitação/timeout da ferramenta. O titular relatou testes sem problemas e dispensou expressamente a repetição indisponível para READY em 16/10/2026; o prompt de fechamento confirmou a dispensa para freeze. Nenhum PASS foi atribuído a esses itens. O relato do titular, as tentativas de automação e as evidências manuais anteriores foram mantidos separadamente no arquivo privado. Não se declara execução manual independente pelo agente.

## Escopo e disponibilidade

Cinco classes: Corporate Loans, Project Finance, Commercial Real Estate, Mortgages e Motor Vehicle Loans. Há 46 definições de classe/rota/escopo: 26 calculam com fixtures próprias completas; 16 adicionais requerem fatores externos; duas 2a/S3 não se aplicam e duas 2b/S3 ainda não têm fator produtivo de fronteira S3 compatível. As matrizes descrevem as condições. Não se homologa cálculo para as quatro definições indisponíveis.

54 operações / US$ 200 milhões preservados. Cobertura pública S1+2 de 52,5%; resultados parciais descritos na reconciliação. Dashboard, Scenarios e oito gráficos presentes. Estrutura protegida, cinco abas operacionais sem proteção e seis motores VeryHidden, conforme aprovado. Workbook Integrity armazenado = OK; zero células de erro nos caches. Não houve recálculo no freeze.

## Conteúdo de terceiros

A auditoria de 90 itens, mais três parâmetros GWP individualizados, resultou em 33 itens próprios, 57 itens numéricos externalizados e três referências institucionais. Não foi identificada pendência documental ou de redistribuição no conteúdo público conhecido. Valores sem permissão estabelecida não acompanham o pacote; fonte, URL, unidade e fronteira são orientações para fornecimento pelo usuário. Não é parecer jurídico nem autorização sobre dados futuros.

## Compatibilidade e integridade

Excel 2013 ou posterior é necessário para ISFORMULA, preservada no indicador de integridade. Não foram introduzidas funções de matriz dinâmica. A homologação usou o Excel instalado; versões anteriores não foram testadas. O indicador verifica presença de fórmulas, não toda sua correção ou a autenticidade de evidências. Não há restauração automática de fórmulas.

SHA-256 oficial: `d4fe35fbe8cf0e5fcc5c18c3a8f7f6703947166a8deda1420e7f5fe5f79d2a7a`. Comparação binária e de partes XML: MATCH, zero diferenças. Nenhuma fórmula, fator, tabela, entrada, proteção, cenário ou texto interno foi alterado. Referências internas à etapa de preparação permaneceram porque modificar texto no Excel quebraria o freeze; os documentos externos identificam a release final. Qualquer alteração futura da calculadora pertence a v3.4.0 ou posterior.

## Exceção de metadado no freeze
A varredura ampliada detectou um caminho técnico de origem em x15ac:absPath do XLSX. O titular aceitou expressamente preservá-lo para manter os bytes homologados. A exceção não afeta cálculos e não representa ausência absoluta de caminhos no arquivo. Consulte o registro de exceção que acompanha a release. Nenhuma modificação ou reexecução da regressão foi necessária.
