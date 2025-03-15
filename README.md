# God Hand EST Swap Tool

O **God Hand EST Swap Tool** é uma aplicação Windows Forms projetada para facilitar a edição e manipulação de arquivos `.EST`, permitindo ao usuário copiar ou trocar rapidamente efeitos (filhos ou chunks) entre dois arquivos diferentes. Esta ferramenta é especialmente útil para modding ou ajustes rápidos de arquivos em jogos ou aplicações que utilizam o formato EST.

## Funcionalidades

- **Visualização clara dos arquivos:**
  - Exibe dois arquivos `.EST` lado a lado, com seus respectivos filhos organizados claramente.
  - Cada arquivo `.EST` tem seus filhos listados de forma organizada com o respectivo tamanho.

- **Troca rápida de efeitos:**
  - Mover efeitos do arquivo esquerdo para o arquivo direito (e vice-versa).
  - Trocar diretamente dois efeitos selecionados entre os arquivos.

- **Desfazer/Refazer**
  - Suporte completo para desfazer (`Undo`) e refazer (`Redo`) ações realizadas.

- **Interface Amigável**
  - Interface intuitiva usando Windows Forms.
  - Controles fáceis para facilitar a manipulação e visualização dos arquivos e suas camadas internas usando componentes visuais como `TreeView` e `ListBox`.

## Como usar

1. **Abrindo arquivos EST:**
   - Clique em abrir arquivos e selecione dois arquivos `.EST` para manipular.

2. **Manipulando os Efeitos:**
   - Após carregar, os arquivos serão exibidos em duas listas ou estruturas `TreeView`, permitindo fácil visualização e seleção dos efeitos (filhos).
   - Selecione um efeito em cada arquivo para copiar ou trocar.

3. **Copiar/Trocar:**
   - Utilize os botões dedicados:
     - `>` para copiar o efeito do arquivo esquerdo para substituir o item selecionado do arquivo direito.
     - `<` para o contrário.
     - `<>` para trocar simultaneamente efeitos selecionados entre os dois arquivos.

4. **Desfazendo ou Refazendo ações:**
   - Utilize os botões `Desfazer` ou `Refazer` para corrigir erros ou restaurar alterações anteriores.

5. **Salvando as alterações:**
   - A cada alteração, os arquivos são automaticamente atualizados, permitindo que sejam salvos imediatamente.

## Interface

- Interface intuitiva com destaque dos arquivos selecionados e seus tamanhos em KB.
- Informações detalhadas e feedback visual após cada ação.

## Exemplo visual

![image](https://github.com/user-attachments/assets/98355fc5-c1a3-44f5-a2d3-4f260106ad64)

## Pré-requisitos

- Windows
- .NET Framework

## Instalação

1. Faça o download do arquivo .zip na seção de Releases.
2. Extraia e execute o arquivo `.exe`.

---

Para qualquer dúvida, reporte um issue ou entre em contato através do GitHub.

