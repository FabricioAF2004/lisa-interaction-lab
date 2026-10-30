# Lisa Interaction Lab — Teste B

Página estática para testar se uma ferramenta de navegação consegue:
1. ler a página;
2. acionar um botão e observar `CLICK-731`;
3. preencher e enviar um campo de texto;
4. acionar outro botão e descobrir `LISA-274`.

**Importante:** o formulário só mostra a mensagem no próprio navegador. Não há backend, não há envio para a Lisa e não há armazenamento externo.

## Publicar gratuitamente com GitHub Pages
1. Entre em https://github.com e crie um repositório público, por exemplo `lisa-interaction-lab`.
2. Envie o arquivo `index.html` para a raiz do repositório.
3. No repositório, abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha a branch `main` e a pasta `/(root)`, depois salve.
6. Aguarde a publicação. O GitHub mostrará o endereço público do site na mesma página de Pages.
7. Abra esse endereço no navegador comum primeiro para conferir se funciona; então envie o link à Lisa.

O endereço final depende do nome da conta e do repositório, então não deve ser adivinhado antecipadamente.

## Próxima etapa
Se o teste de clique funcionar, isso só comprova a interação com elementos da página. Para mensagens reais de ida e volta entre a Lisa e você, será necessário um backend com armazenamento e a ferramenta de navegação precisa conseguir enviar dados e consultar respostas.
