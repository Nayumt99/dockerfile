# Configuração do Servidor Apache e Aplicação Hello World

Este repositório contém uma configuração YAML para um servidor Apache e uma estrutura básica de diretórios para uma aplicação Hello World.

## Arquivo YAML

O arquivo `config.yml` contém as seguintes configurações:

### Configurações do Servidor Apache

- **Nome do Servidor**: Apache HTTP Server
- **Versão**: 2.4.41
- **Porta**: 80
- **Diretório Raiz do Documento**: /var/www/html
- **Arquivo de Log de Erros**: /var/log/httpd/error.log
- **Arquivo de Log de Acesso**: /var/log/httpd/access.log
- **Admin do Servidor**: webmaster@example.com
- **Nome do Servidor**: example.com
- **Alias do Servidor**: www.example.com

### Configurações da Aplicação

- **Nome da Aplicação**: Hello World Application
- **Descrição**: Uma simples aplicação Hello World
- **Localização dos Arquivos**: /var/www/html/hello_world
- **Arquivo Index**: index.html

## Estrutura da Aplicação Hello World

A estrutura de diretórios para a aplicação Hello World é a seguinte:

```
/var/www/html/hello_world
│   index.html
│   style.css
│   script.js
```

### Conteúdo dos Arquivos

- **`index.html`**: O arquivo HTML principal da aplicação Hello World.
- **`style.css`**: O arquivo CSS para estilizar a aplicação.
- **`script.js`**: O arquivo JavaScript para interatividade.

## Instruções de Uso

Para configurar um servidor Apache com esta configuração e hospedar a aplicação Hello World, siga estas etapas:

1. Instale o Apache HTTP Server em seu sistema.
2. Clone este repositório ou copie o conteúdo do arquivo `config.yml`.
3. Configure o Apache de acordo com as configurações especificadas no arquivo YAML.
4. Crie os diretórios e arquivos da aplicação Hello World conforme descrito na seção "Estrutura da Aplicação Hello World".
5. Reinicie o servidor Apache.
6. Acesse a aplicação Hello World pelo navegador utilizando o endereço do servidor.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas (issues) e enviar pull requests para melhorias.

## Licença

Este projeto está licenciado sob a Nayum Teixeira
