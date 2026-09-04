# EZabnt

Automação bibliográfica e modelos pré-formatados segundo a **ABNT NBR 6022** (artigos científicos) e **ABNT NBR 6023** (referências) para o LibreOffice Writer.

O projeto disponibiliza duas abordagens diferentes:
1. **Extensão (`.oxt`):** Adiciona ao LibreOffice Writer a busca automática de referências por DOI/ISBN e a ordenação alfabética automática para as referências em segundo plano.
2. **Modelos (`.ott`):** Para quem **não deseja instalar extensões**, bastando abrir o modelo autossuficiente com macro embutida ou o modelo limpo.

---

## 🚀 Guia de Uso

### Opção A: Utilizando a Extensão (`EZabnt-v1.1.0.oxt`)

Recomendada para integrar os recursos permanentemente ao LibreOffice.

1. **Instalação:**
   * Baixe o arquivo `EZabnt-v1.1.0.oxt` na aba [Releases](../../releases).
   * No Writer, acesse: `Ferramentas` > `Gerenciador de Extensões...` (ou `Ctrl + Alt + E`).
   * Clique em `Adicionar`, escolha o arquivo baixado e reinicie o LibreOffice.
   * Alternativamente, baixe o arquivo `EZabnt-v1.1.0.oxt` e clique duas vezes no arquivo. Siga o processo de instalação na janela de instalação do LibreOffice Writer.
2. **Abra o modelo com facilidade**
   *Abra o LibreOffice Writer e navegue até Arquivo>Novo>Modelos. O modelo fornecido com a extensão irá aparecer com o título "EZabnt - Artigo Científico ABNT"
   *Alternativamente, abra o LibreOffice Writer e pressione Ctrl+Shift+N para abrir o menu de modelos.
4. **Gerar referências via DOI ou ISBN:**
   * Digite ou cole o identificador em qualquer parte do texto (ex.: `10.1016/j.compositesb.2022.109988` ou `978-85-359-0277-8`)[cite: 3].
   * Selecione o texto do identificador com o cursor[cite: 7].
   * Acesse o menu de topo: `EZabnt` > `Gerar Referência (DOI / ISBN)`[cite: 1].
   * A citação completa será formatada e inserida diretamente na seção de referências[cite: 7].
5. **Ordenação alfabética automática:**
   * Basta salvar o documento (`Ctrl + S` ou `Arquivo` > `Salvar`)[cite: 4].
   * Todas as referências da seção serão reordenadas de A a Z de forma silenciosa, preservando negritos, itálicos e links sem alterar o cabeçalho.

---

### Opção B: Utilizando apenas os Modelos (`.ott` — Sem Instalar Extensão)

Ideal para quem não quer ou não pode instalar extensões de terceiros no LibreOffice:

* **`Artigo_Cientifico_COM_MACRO.ott`:** Modelo pré-configurado contendo o macro de inserção de referências com DOI/ISBN (não requer a extensão `.oxt` instalada).
* **`Artigo_Cientifico_SEM_MACRO.ott`:** Modelo estritamente tipográfico, sem scripts ou macros.

#### Formas de uso:
* **Uso direto:** Dê um duplo clique no arquivo `.ott`. O LibreOffice abrirá um novo arquivo de texto editável (`.odt`) mantendo o modelo original preservado.
* **Adicionar ao gerenciador do LibreOffice:**
  * Acesse `Arquivo` > `Modelos` > `Gerenciar Modelos` (`Ctrl + Shift + N`).
  * Clique em `Importar`, selecione o modelo `.ott` e confirme a categoria.

---

## 📌 Recursos e Estrutura Técnica

* **Conformidade Normativa:** Estruturação de artigos conforme a **ABNT NBR 6022** e elaboração de referências conforme a **ABNT NBR 6023**.
* **Busca e Formatação Automatizada:** Integração com as APIs Crossref (periódicos/artigos) e Open Library (livros) para montagem estruturada das entradas bibliográficas[cite: 3]. (Somente com a extensão)
* **Ordenação Estrita ABNT (PT-BR):** Algoritmo imune a problemas com acentuação e pontuações iniciais (trata caracteres acentuados de forma canônica: "Á" é ordenado junto a "A", e não após o "Z"). (Somente com a extensão)
* **Preservação de Formatação Interna (`TextPortions`):** A reordenação atua sobre a árvore de objetos do Writer, conservando destaques em negrito (títulos de obras), itálicos e links ativos.
* **Tipografia e Parágrafo:** O modelo contempla estilos pré-formatados para seções primárias, secundárias e terciárias (títulos numerados progressivamente), corpo de texto, citações diretas longas, resumo, indicação de autoria, palavras-chave, cabeçalho de seção, título e subtítulo do trabalho e itens individuais de referências bibliográficas. Fontes, espaçamento e recuo de primeira linha padronizados de acordo com as normas da ABNT. 
* **Margens:** 3 cm superior e esquerda; 2 cm inferior e direita.
*  **Paginação:** Paginação que obedece as normas da ABNT e é inserida de forma automática.
* **Estilos Hierárquicos e de Fluxo:** Seções com numeração progressiva e alternância automática de estilos ao teclar `Enter`.

---

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
