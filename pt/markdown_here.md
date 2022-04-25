---
Text: texto
Hello: Oi
---

<a href="https://gitlocalize.com/repo/4578/ru?utm_source=badge"> <img src="https://gitlocalize.com/repo/4578/ru/badge.svg"> </a>

# ![Logo Markdown Aqui](https://raw.github.com/adam-p/markdown-here/master/src/common/images/icon48.png) Remarcação aqui

[**Visite o site.**](http://markdown-here.com)<br>[**Obtenha-o para o Chrome.**](https://chrome.google.com/webstore/detail/elifhakcjgalahccnjkneoccemfahfoa)<br>[**Obtenha-o para o Firefox.**](https://addons.mozilla.org/en-US/firefox/addon/markdown-here/)<br>[**Obtenha-o para o Safari.**](https://s3.amazonaws.com/markdown-here/markdown-here.safariextz)<br>[**Obtenha para Thunderbird e Postbox.**](https://addons.mozilla.org/en-US/thunderbird/addon/markdown-here/)<br>[**Obtê-lo para o Opera.**](https://addons.opera.com/en/extensions/details/markdown-here/)<br>[**Discuta e faça perguntas no Grupo do Google.**](https://groups.google.com/forum/?fromgroups#!forum/markdown-here/)<br>

*Markdown Aqui* está uma extensão do Google Chrome, Firefox, Safari, Opera e Thunderbird que permite escrever e-mails <sup>†</sup> no Markdown <sup>‡</sup> e renderizá-los antes de enviar. Ele também suporta realce de sintaxe (apenas especifique o idioma em um bloco de código protegido).

Escrever e-mail com código é bastante tedioso. Escrever Markdown com código é fácil. Eu me peguei escrevendo e-mail no Markdown no editor no navegador do Github e copiando a visualização no e-mail. Este é um workflow bem absurdo, então decidi criar uma ferramenta para escrever e renderizar Markdown direto no email.

Para descobrir o que pode ser feito com o Markdown no *Markdown Here* , confira o[Markdown Here Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet) e as outras [páginas do wiki](https://github.com/adam-p/markdown-here/wiki) .

<sup>†: E postagens do Grupos do Google, postagens do Blogger, notas do Evernote e postagens do Wordpress! <a href="#compatibility">Veja mais</a> .</sup><br><sup>‡: E as fórmulas matemáticas do TeX!</sup>

![captura de tela da conversão](https://raw.github.com/adam-p/markdown-here/master/store-assets/markdown-here-image1.gimp.png)

### Índice

**[instruções de instalação](#installation-instructions)**<br>**[Instruções de uso](#usage-instructions)**<br>**[Solução de problemas](#troubleshooting)**<br>**[Compatibilidade](#compatibility)**<br>**[Notas e Diversos](#notes-and-miscellaneous)**<br>**[Construindo os pacotes de extensão](#building-the-extension-bundles)**<br>**[Próximas etapas, créditos, feedback, licença](#next-steps)**<br>

## instruções de instalação

### cromada

#### Loja online do Chrome

Vá para a [página da Chrome Web Store para *Markdown Here*](https://chrome.google.com/webstore/detail/elifhakcjgalahccnjkneoccemfahfoa) e instale normalmente.

Após a instalação, certifique-se de recarregar seu webmail ou reiniciar o Chrome!

#### Manual/Desenvolvimento

1. Clone este repositório.
2. No Chrome, abra as configurações de extensões. (Botão de chave, Ferramentas, Extensões.)
3. Na página de configurações de extensões, clique na caixa de seleção "Modo de desenvolvedor".
4. Clique no botão "Carregar extensão descompactada..." agora visível. Navegue até o diretório em que você clonou o repositório e, em seguida, o diretório `src` sob ele.
5. A extensão *Markdown Here* agora deve estar visível na sua lista de extensões.
6. Recarregue sua página de webmail (e talvez aplicativo) antes de tentar converter um e-mail.

### Firefox e Thunderbird

#### Site de complementos da Mozilla

Vá para a [página de complementos do Firefox para *Markdown Here*](https://addons.mozilla.org/en-US/firefox/addon/markdown-here/) e instale normalmente.

Ou vá para o menu "Ferramentas &gt; Complementos" e procure por "Markdown aqui".

Após a instalação, certifique-se de reiniciar o Firefox/Thunderbird!

**Observação:** leva até um mês para a Mozilla aprovar as alterações na extensão Firefox/Thunderbird, portanto, as atualizações (recursos, correções) ficarão para trás do que é mostrado aqui. Você pode optar manualmente por instalar a versão mais recente antes de ser revisada na lista de versões: [https://addons.mozilla.org/en-US/firefox/addon/markdown-here/versions/](https://addons.mozilla.org/en-US/firefox/addon/markdown-here/versions/)

#### Manual/Desenvolvimento

1. Clone este repositório.
2. Siga as instruções no artigo MDN ["Configurando um ambiente de desenvolvimento de extensão"](https://developer.mozilla.org/en/Setting_up_extension_development_environment) .

### Safári

[Baixe a extensão diretamente.](https://s3.amazonaws.com/markdown-here/markdown-here.safariextz) Quando terminar de baixar, clique duas vezes nele para instalar.

#### Preferências

Para acessar as preferências do Markdown Here, abra as preferências do Safari e vá para a guia "Extensões". Em seguida, clique na caixa "Clique em mim para mostrar as opções do Markdown aqui".

### Ópera

Observe que o *Markdown Here* funciona apenas com as versões 16 e superiores do Opera (ou seja, aquelas baseadas no Chromium).

Vá para a [página da loja de complementos do Opera para *Markdown Here*](https://addons.opera.com/en/extensions/details/markdown-here/) e instale normalmente.

Após a instalação, certifique-se de recarregar seu webmail ou reiniciar o Chrome!

## Instruções de uso

Instale-o e depois…

1. No Chrome/Safari/Opera, *certifique-se* de recarregar sua página de webmail antes de tentar usar o Markdown Here.

2. No Chrome/Firefox/Safari/Opera, faça login na sua conta Gmail, Hotmail ou Yahoo e inicie um novo e-mail. No Thunderbird, inicie uma nova mensagem.

3. Certifique-se de estar usando o editor avançado.

    - No Gmail, clique no link "Formatação avançada", se estiver visível.
    - No Thunderbird, certifique-se de que "Escrever mensagens em formato HTML" esteja ativado no painel "Configurações da conta", "Composição e endereçamento".

4. Componha um e-mail no Markdown. Por exemplo:

    <pre>   **Hello** `world`.

       ```javascript
       alert('Hello syntax highlighting.');
       ```
       </pre>

5. Clique com o botão direito do mouse na caixa de composição e escolha o item "Markdown Toggle" no menu de contexto. Ou clique no botão que aparece na barra de endereços. Ou use a tecla de atalho ( <kbd>CTRL</kbd> + <kbd>ALT</kbd> + <kbd>M</kbd> por padrão).

6. Você deve ver seu e-mail renderizado corretamente do Markdown em HTML avançado.

7. Envie seu e-mail incrível para todos que você conhece. Ele aparecerá para eles da mesma forma que parece para você.

### Reverter para Markdown

Depois de renderizar seu Markdown para HTML bonito, você ainda pode voltar ao seu Markdown original. Basta clicar com o botão direito do mouse em qualquer lugar no Markdown recém-renderizado e clicar em "Markdown Toggle" - o corpo da composição do seu e-mail mudará de volta para o Markdown que você escreveu.

Observe que todas as alterações feitas no HTML bonito serão perdidas quando você reverter para o Markdown.

No Gmail, você também pode usar o comando Desfazer do navegador ( <kbd>CTRL</kbd> + <kbd>Z</kbd> / <kbd>CMD</kbd> + <kbd>Z</kbd> ou no menu Editar). Esteja avisado de que você também pode perder os últimos caracteres inseridos.

### Respostas

No Gmail, Thunderbird e Google Groups, você pode usar "Markdown Toggle" normalmente: basta escrever sua resposta (topo, fundo, inline, onde quer que seja) e depois converter. O e-mail original ao qual você está respondendo será deixado em paz. (Tecnicamente: os blocos de `blockquote` existentes serão deixados intactos.)

No Hotmail e Yahoo (que não colocam o original em `blockquote` ), e opcionalmente no Gmail, Thunderbird e Google Groups, você pode garantir que apenas a parte da resposta que você escreveu seja convertida selecionando o que você deseja converter e depois clicando em "Markdown Toggle" -- veja a próxima seção.

### Seleção/conversão de peça

Às vezes você não quer converter o e-mail inteiro; às vezes seu e-mail não é totalmente Markdown. Para converter apenas parte do e-mail, selecione o texto (com o mouse ou teclado), clique com o botão direito nele e clique no item de menu "Markdown Toggle". Sua seleção é magicamente renderizada em um belo HTML.

Para reverter para Markdown, basta colocar o cursor em qualquer lugar no bloco de texto convertido, clicar com o botão direito e clicar no item de menu "Markdown Toggle" novamente. Agora está magicamente de volta ao Markdown original.

![captura de tela da conversão de seleção](https://raw.github.com/adam-p/markdown-here/master/store-assets/markdown-here-image2.gimp.png)

#### O que você deve saber sobre como converter/reverter uma seleção

- Se você selecionar apenas parte de um bloco de texto, somente esse texto será convertido. O bloco convertido será envolvido em um elemento de parágrafo, de modo que a linha original será dividida. Você provavelmente não quer fazer isso nunca.

- Você pode selecionar e reverter vários blocos convertidos ao mesmo tempo. Um resultado disso é que você pode selecionar todo o seu e-mail, clicar em "Markdown Toggle" e todas as partes que você converteu serão revertidas.

- Se você não tiver nada selecionado quando clicar em "Markdown Toggle", o *Markdown Here* verificará se há blocos convertidos em qualquer lugar da mensagem e os reverterá. Se nenhum bloco convertido for encontrado, ele converterá todo o e-mail.

### Opções

A página *Markdown Here* Options pode ser acessada através da lista de extensões do Chrome, Firefox, Safari ou Thunderbird. As opções disponíveis incluem:

- Modificações de estilo para o Markdown renderizado.
- Sintaxe destacando a seleção e modificação do tema.
- Habilitação e personalização do processamento de fórmulas matemáticas do TeX.
- Qual deve ser a tecla de atalho.

Para Chrome e Firefox, quaisquer alterações feitas nas opções *Markdown Here* são sincronizadas automaticamente entre suas outras instalações desse navegador (se você tiver o recurso de sincronização ativado no navegador).

![captura de tela de opções](https://raw.githubusercontent.com/adam-p/markdown-here/master/store-assets/markdown-here-chrome-options-1.gimp.png)

## Solução de problemas

Consulte a [página wiki de solução de problemas](https://github.com/adam-p/markdown-here/wiki/Troubleshooting) .

## Compatibilidade

Consulte a [página wiki de compatibilidade](https://github.com/adam-p/markdown-here/wiki/Compatibility) .

## Notas e Diversos

- *Markdown Aqui* usa o [Github Flavored Markdown](http://github.github.com/github-flavored-markdown/) , com a limitação de que links especiais GFM não são suportados ( [problema nº 11](https://github.com/adam-p/markdown-here/issues/11) ); nem serão, pois o MDH não é específico do Github.

- Os idiomas disponíveis para realce de sintaxe (e a maneira como eles devem ser escritos no bloco de código protegido) podem ser vistos na [página de demonstração highlight.js](http://softwaremaniacs.org/media/soft/highlight/test.html) .

- As imagens incorporadas em seu Markdown serão mantidas quando você "Alternar Markdown". O Gmail permite que você coloque imagens embutidas em seu e-mail. Isso pode ser muito mais fácil do que fazer referência a uma imagem externa.

- As assinaturas de e-mail são automaticamente excluídas da conversão. Especificamente, qualquer coisa após o semi-padrão `'-- '` (observe o espaço à direita) é deixado sozinho.

    - Observe que o Hotmail e o Yahoo *não* adicionam automaticamente o `'-- '` às assinaturas, portanto, você mesmo deve adicioná-lo.

- O item de menu "Markdown Toggle" aparece para mais tipos de elementos do que pode renderizar corretamente. Isso tem como objetivo ajudar as pessoas a perceberem que não estão usando um editor avançado. Caso contrário, eles simplesmente não veem o item de menu e não sabem por quê.

- Estilo:

    - O uso de estilos específicos do navegador (-moz-, -webkit-) deve ser evitado. Se usados, eles podem não ser renderizados corretamente para pessoas que estão lendo o email em um navegador diferente daquele para o qual o email foi enviado.
    - O uso de estilos dependentes de estado (como `a:hover` ) não funciona porque eles não correspondem no momento em que os estilos são tornados explícitos. (No e-mail, os estilos devem ser aplicados explicitamente a todos os elementos - as folhas de estilo são removidas.)

- Para recursos mais aprimorados, visite a seção [Dicas e truques](https://github.com/adam-p/markdown-here/wiki/Tips-and-Tricks) .

## Construindo os pacotes de extensão

```
cd utils
node build.js
```

### Extensão do Chrome e Opera

Crie um arquivo com extensão `.zip` contendo estes arquivos e diretórios:

```
manifest.json
common/
chrome/
```

### Extensão Firefox/Thunderbird

Crie um arquivo com extensão `.xpi` contendo estes arquivos e diretórios:

```
chrome.manifest
install.rdf
common/
firefox/
```

### Extensão do Safari

O código específico do navegador está localizado no projeto [`markdown-here-safari`](https://github.com/adam-p/markdown-here-safari) .

Use o Construtor de Extensões do Safari.

## Próximos passos

Veja a [lista de problemas](https://github.com/adam-p/markdown-here/issues) e o [Wiki de Notas](https://github.com/adam-p/markdown-here/wiki/Development-Notes) . Todas as ideias, bugs, planos, reclamações e sonhos vão acabar em um desses dois lugares.

Sinta-se à vontade para criar um problema de solicitação de recurso se o que você deseja ainda não estiver lá. Se preferir uma abordagem menos formal para divulgar uma ideia, poste no [Grupo do Google "markdown-here"](https://groups.google.com/forum/?fromgroups=#!forum/markdown-here) .

Também é preciso um pouco de trabalho para se manter atualizado com as alterações mais recentes em todos os aplicativos e sites em que o Markdown Here funciona.

## Créditos

*Markdown Here* foi codificado nos ombros de gigantes.

- Markdown-to-HTML: [chjj / marcado](https://github.com/chjj/marked)
- Realce de sintaxe: [isagalaev / highlight.js](https://github.com/isagalaev/highlight.js)
- HTML para texto: [mtrimpe / jsHtmlToText](https://github.com/mtrimpe/jsHtmlToText)

## Comentários

Todos os bugs, solicitações de recursos, solicitações de pull, feedback, etc., são bem-vindos. [Crie um problema](https://github.com/adam-p/markdown-here/issues) . Ou [poste no Grupo do Google "markdown-here"](https://groups.google.com/forum/?fromgroups=#!forum/markdown-here) .

## Licença

### Código

Licença MIT: http://adampritchard.mit-license.org/ ou veja [o arquivo `LICENSE`](https://github.com/adam-p/markdown-here/blob/master/LICENSE) .

### Logotipo

Direitos autorais 2015, [Austin Anderson](http://protractor.ninja/) . Licenciado para Markdown Here sob o[contrato de licença de contribuidor MDH](https://github.com/adam-p/markdown-here/blob/master/CLA-individual.md) .

### Outras imagens

[Licença Creative Commons Atribuição 3.0 Não Adaptada (CC BY 3.0)](http://creativecommons.org/licenses/by/3.0/)

---

![O homem Dos Equis diz](https://raw.github.com/adam-p/markdown-here/master/store-assets/dos-equis-MDH.jpg)

- pull request
- Também dá um pouco de trabalho
- Licença
- Erro
- Código
