# Guia de Instalação do Microsoft Office Grátis Oficial Completo 2024

Este guia fornece instruções sobre como baixar e instalar o Microsoft Office 2024 gratuitamente e oficialmente. Siga as etapas abaixo para concluir a instalação.

## Passos para Instalação

1. **Criar uma Pasta para o Setup**
   - Crie uma pasta chamada `MS Office Setup` na raiz do disco `C:\`.

2. **Baixar o Office Customization Tool**
   - Acesse o [Office Customization Tool](https://config.office.com/deploymentsettings) para personalizar sua instalação.

3. **Baixar o Office LTSC Professional Plus 2021**
   - Selecione a versão `64-bit` do `Office LTSC Professional Plus 2021` com licença por volume. Você pode encontrar o link para download [aqui](https://www.microsoft.com/en-us/download/details.aspx?id=49117).

4. **Selecionar o Idioma**
   - Escolha o idioma desejado para o Office.

5. **Formatos do Office Open XML**
   - Garanta que a opção `Office Open XML Formats` esteja selecionada.

6. **Baixar o Office Deployment Tool**
   - Baixe e extraia o `Office Deployment Tool`.

7. **Executar a Instalação**
   - Mova o arquivo `Office Deployment Tool` e os arquivos baixados para a pasta `MS Office Setup` que você criou no passo 1.
   - Abra um terminal ou prompt de comando e navegue até o diretório `C:\MS Office Setup`.

8. **Configuração**
   - Execute o comando abaixo para iniciar a configuração:
     ```sh
     Setup.exe /configure Configuração.xml
     ```

   **Nota:** Certifique-se de que o arquivo `Configuração.xml` está corretamente configurado para atender às suas necessidades.

## Links Úteis

- [Office Customization Tool](https://config.office.com/deploymentsettings)
- [Download do Office LTSC Professional Plus 2021](https://www.microsoft.com/en-us/download/details.aspx?id=49117)

## Observações

- Este guia é destinado a usuários que possuem uma licença por volume para o Office LTSC Professional Plus 2021.
- Certifique-se de seguir cada etapa com atenção para garantir uma instalação bem-sucedida.

Se você encontrar problemas durante a instalação, consulte a documentação oficial da Microsoft ou entre em contato com o suporte técnico.
