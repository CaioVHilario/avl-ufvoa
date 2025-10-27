# VSCode AVL Syntax Highlighter (AVL UFVoa)

Uma extensão do Visual Studio Code que adiciona **syntax highlighting (coloração de sintaxe)** e **comentários inteligentes** para arquivos `.avl`.

O `.avl` é um formato de arquivo usado pelo software Athena Vortex Lattice (AVL) para análise aerodinâmica. Por padrão, esses arquivos são de texto simples, tornando-os difíceis de ler e depurar.

Como **ex-capitão da equipe de AeroDesign Skywards UFVoa**, eu desenvolvi esta extensão para resolver um problema real do nosso time: melhorar drasticamente a legibilidade, a produtividade e a velocidade de depuração ao escrever arquivos de geometria de aeronaves.

---

### ✨ Funcionalidades Principais

* **Coloração de Sintaxe:** Altera as cores de números, palavras-chave e funções (ex: `SECTION`, `ANGLE`) para facilitar a visualização da geometria.
* **Comentários Inteligentes:** Permite usar o atalho padrão do VSCode (`Ctrl+/` ou `Cmd+/`) para **comentar múltiplas linhas** de uma vez. Os comentários são estilizados com uma cor suave (apagada) para não distrair do código ativo.

---

### 🚀 O Problema Resolvido

A extensão transforma um arquivo `.avl` de texto simples...

**Antes (Sem a extensão):**
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c921d27c-32b0-4252-8cb2-3155cd0ba38e" />


**Depois (Com a extensão):**
*...em um arquivo de código legível, organizado e fácil de depurar:*
![Screenshot da extensão AVL UFVoa em ação](image/screen.png)

---

### 🛠️ Tecnologias Utilizadas

* **VSCode Extension API**
* **JSON (TextMate Grammar):** Para definir as regras de coloração de sintaxe.

---

### 🏃 Como Instalar

**Opção 1: Pela VSCode Marketplace**
1.  Abra o VSCode
2.  Vá para a aba de Extensões (Ctrl+Shift+X)
3.  Procure por "**AVL UFVoa**"
4.  Clique em "Instalar"

### 👨‍💻 Autor

**Caio Vieira Hilário**
