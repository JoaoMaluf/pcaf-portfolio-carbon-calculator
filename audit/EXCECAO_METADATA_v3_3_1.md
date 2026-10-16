# Exceção de metadado — v3.3.1

Em 16/10/2026, durante o fechamento, foi identificado um caminho técnico local de origem em xl/workbook.xml, no metadado x15ac:absPath. Não é link externo de dados e não altera fórmulas, fatores, inputs ou resultados. O caminho foi preservado para manter identidade binária com o workbook homologado.

Após ser informado de que remover esse metadado mudaria o binário e exigiria outra candidata, o titular escolheu expressamente: “Preservar os bytes aprovados e aceitar expressamente a exceção desse caminho no metadado”.

Portanto a regra de ausência de caminhos locais tem uma exceção deliberada e limitada a esse metadado do XLSX. Não se declara ausência absoluta de caminhos no binário. Os demais documentos e matrizes não contêm caminhos locais ou senha administrativa. O caminho completo não é reproduzido nesta documentação.

Essa aceitação não permite alteração silenciosa da calculadora nem amplia direitos sobre terceiros. PUBLIC_FINAL mantém o SHA-256 homologado; a cópia é exata. Qualquer alteração futura exige nova versão, preferencialmente v3.4.0.
