# Como Editar o Link do Botão no Convite Digital

Parabéns! A página web do convite digital do Gabriel com o botão "Confirmar Presença Aqui" está pronta.

Como você ainda não tem o link definitivo do seu formulário do Google, o botão na página está com um link provisório. Siga os passos abaixo para substituí-lo pelo seu link real quando ele estiver pronto:

1.  **Baixe o arquivo `index.html`**: Este arquivo foi enviado junto com estas instruções.

2.  **Abra o arquivo `index.html` em um editor de texto simples**:
    *   **No Windows:** Você pode usar o Bloco de Notas (Notepad). Clique com o botão direito no arquivo `index.html`, vá em "Abrir com" e escolha "Bloco de Notas". Se não aparecer, clique em "Escolher outro aplicativo" e procure por ele.
    *   **No macOS:** Você pode usar o TextEdit. Clique com o botão direito no arquivo `index.html`, vá em "Abrir Com" e escolha "TextEdit". Por padrão, o TextEdit pode abrir em modo de texto formatado. Se isso acontecer, vá no menu "Formato" e selecione "Converter para texto normal" (Make Plain Text).
    *   **Outros editores:** Qualquer editor de código simples como VS Code, Sublime Text, Notepad++ também funcionará perfeitamente.

3.  **Localize a linha do link do botão**:
    *   Com o arquivo aberto, procure (geralmente usando a função "Localizar" ou "Find", Ctrl+F no Windows ou Cmd+F no Mac) pelo seguinte trecho de código:

        ```html
        <a href="#LINK_DO_FORMULARIO_AQUI" class="botao-confirmar" id="botaoConfirmarPresenca">
        ```

4.  **Substitua o link provisório**:
    *   Você verá `href="#LINK_DO_FORMULARIO_AQUI"`. Apague apenas o texto `#LINK_DO_FORMULARIO_AQUI` (mantenha as aspas `""`).
    *   No lugar, cole o link completo do seu formulário do Google. A linha deverá ficar parecida com isto (exemplo):

        ```html
        <a href="https://docs.google.com/forms/d/e/SEU_CODIGO_LONGO_DO_FORMULARIO/viewform?usp=sf_link" class="botao-confirmar" id="botaoConfirmarPresenca">
        ```
        (Obviamente, use o seu link real no lugar do exemplo acima).

5.  **Salve o arquivo**:
    *   Após fazer a substituição, salve o arquivo `index.html`. No Bloco de Notas ou TextEdit, geralmente é em "Arquivo" > "Salvar".

6.  **Teste a página**:
    *   Abra o arquivo `index.html` salvo em um navegador de internet (Google Chrome, Firefox, Edge, Safari, etc.) clicando duas vezes sobre ele. O convite deve aparecer, e ao clicar no botão "Confirmar Presença Aqui", você deverá ser direcionado para o seu formulário do Google.

7.  **Como compartilhar**:
    *   Para compartilhar o convite via WhatsApp, você precisará hospedar esta pasta (`convite_digital_gabriel`, que contém o `index.html` e a pasta `img` com a imagem) em algum serviço de hospedagem de sites estáticos (existem opções gratuitas como GitHub Pages, Netlify, Vercel, etc.). Após hospedar, você terá um link público para a página `index.html`, e é este link que você compartilhará no WhatsApp.
    *   Se precisar de ajuda para hospedar, me diga!

Pronto! Seus convidados poderão acessar o convite e confirmar a presença facilmente.

