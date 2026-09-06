# EZabnt — Referências ABNT no LibreOffice Writer

O **EZabnt** automatiza a formatação e a organização de referências bibliográficas segundo as normas da ABNT diretamente no LibreOffice Writer. Você seleciona o texto, clica no botão e a referência formatada entra na seção correta em ordem alfabética.

---

## O que você pode referenciar

Basta colar ou digitar o identificador no texto, selecioná-lo e acionar o EZabnt:

* **Legislação e Normas:** Leis Ordinárias, Leis Complementares, Decretos, Medidas Provisórias e Emendas Constitucionais (somente a nível federal).
* **Constituição Federal:** menções a `CF/88` ou `Constituição de 1988`.
* **Decisões e Processos Judiciais:** numerações de processos do padrão CNJ e ações diretas do STF (ADI, ADC, ADPF, ADO).
* **Livros:** códigos ISBN (de 10 ou 13 dígitos, nacionais ou estrangeiros).
* **Artigos e Periódicos:** links ou códigos DOI, artigos do SciELO, arXiv e PubMed (PMID).

---

## Principais Recursos da Extensão

* **Formatação Automática:** aplica negrito, pontuação e data de acesso conforme as normas da ABNT.
* **Proteção contra Duplicatas:** identifica se uma referência já está na sua lista e bloqueia inserções repetidas.
* **Ordenação Alfabética em Tempo Real:** a lista de referências é reorganizada automaticamente a cada nova inserção.
* **Campos Faltantes Sinalizados:** caso uma base pública não informe algum dado (como cidade ou editora), o programa insere marcadores visíveis como `[Local]` para você localizar facilmente.

---

## Como Usar

1. Use o modelo pré-configurado(ou garanta que seu documento possua uma seção chamada `SecaoReferencias`).
2. Digite ou cole o identificador em qualquer parte do texto (ex.: `Lei 14.133/2021`, um ISBN ou DOI).
3. Selecione o identificador com o mouse.
4. Clique no botão do **EZabnt** na barra de ferramentas:
   * O identificador é removido do texto corrente.
   * A referência pronta é inserida na seção de referências.
   * A lista completa é reordenada alfabeticamente.

---
## Modelo de Artigo Científico (`.ott`)

Template em formato **OpenDocument Text Template (`.ott`)**, desenvolvido para o LibreOffice Writer e compatíveis, projetado para eliminar o atrito de formatação e estruturação durante a escrita acadêmica. **(modelo já vem instalado junto com a extensão .oxt)**

### O que o modelo entrega:

* **Estrutura pré-definida:** Seções canônicas de um artigo científico já organizadas (Título, Autoria, Resumo/Abstract, Palavras-chave, Introdução, Desenvolvimento, Conclusão e Referências).
* **Hierarquia e estilos de parágrafo:** Configuração pronta para títulos numerados (H1, H2, H3), corpo de texto com recuo padrão, citações diretas longas (recuo de 4 cm e fonte reduzida), paginação adequada (pula a primeira página e se situa no local correto) e notas de rodapé.
* **Padronização dimensional:** Margens, entrelinhamento (1,5) e tipografia já configurados conforme os padrões acadêmicos.
* **Segurança na edição:** Por ser um arquivo `.ott`, ao abri-lo o editor cria automaticamente um novo documento `.odt` sem risco de sobrescrever o template original.

### Como usar:
1. Baixe o arquivo `modelo.ott`.
2. Dê um duplo clique para abrir diretamente no LibreOffice Writer (ou acesse via `Arquivo` > `Modelos` > `Gerenciar modelos` para instalá-lo permanentemente).
3. Substitua o texto de exemplo pelo conteúdo da sua pesquisa.

## Instalação (extensão .oxt)

1. Baixe o arquivo **`EZabnt-v1.1.1.oxt`** na aba de **Releases**.
2. Abra o LibreOffice e acesse **Ferramentas** > **Gerenciador de Extensões...** (`Ctrl + Alt + E`).
3. Clique em **Adicionar**, selecione o arquivo baixado e confirme.
4. Reinicie o LibreOffice.

## ☕ Apoie o Projeto

Se o **EZabnt** facilitou a redação do seu trabalho e você deseja incentivar a manutenção e atualizações:

<div align="center">
  <img src="pix_qrcode.jpeg" alt="QR Code Pix - Doação EZabnt" width="220" />
</div>

#### Pix Copia e Cola
```text
78ed33e5-d307-4044-b8e3-3dc0e6c9660d
```
## 📄 Licença

Distribuído sob a licença MIT.
