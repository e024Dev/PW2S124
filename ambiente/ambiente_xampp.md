# Resumo de instalação do ambiente de desenvolvimento para a Linguagem PHP

## 1. Baixe o XAMPP

Visite o site oficial do [XAMPP](https://www.apachefriends.org/index.html) e faça o download da versão mais recente do XAMPP para Windows.

## 2. Execute o instalador

Após o download, execute o arquivo de instalação do XAMPP. Você pode ser solicitado a conceder permissões de administrador para instalar o software.

## 3. Selecione os componentes

Durante o processo de instalação, você será solicitado a selecionar os componentes que deseja instalar. Certifique-se de selecionar o PHP juntamente com o Apache e o MySQL, pois são necessários para o ambiente de desenvolvimento PHP.

## 4. Escolha o diretório de instalação

Escolha o diretório onde deseja instalar o XAMPP. O diretório padrão geralmente é C:\xampp.

## 5. Conclua a instalação

Continue com as configurações padrão ou faça ajustes conforme necessário. Depois de configurar todas as opções, clique em "Next" ou "Finish" para concluir a instalação.

## 6. Inicie os serviços

Após a instalação, você pode iniciar o XAMPP Control Panel, que geralmente é encontrado no diretório de instalação do XAMPP. No painel de controle, você verá uma lista de serviços, incluindo Apache e MySQL. Clique nos botões "Start" ao lado de cada serviço para iniciá-los.

## 7. Verifique a instalação

Abra um navegador da web e digite http://localhost na barra de endereços. Se tudo estiver configurado corretamente, você deverá ver a página inicial do XAMPP.

## 8. Configure o PHP

O XAMPP já vem com o PHP instalado e configurado. Você pode criar arquivos PHP e colocá-los no diretório htdocs dentro do diretório de instalação do XAMPP. Esses arquivos serão acessíveis através do navegador usando o endereço http://localhost/nome_do_arquivo.php.

## 9. Teste o PHP

Para testar se o PHP está funcionando corretamente, crie um arquivo PHP simples com o seguinte conteúdo:

```php
<?php
    phpinfo();
?>
```

Salve o arquivo como info.php dentro do diretório htdocs. Em seguida, abra um navegador e digite http://localhost/info.php. Se o PHP estiver funcionando corretamente, você verá uma página com informações detalhadas sobre a configuração do PHP.

Com esses passos, você terá configurado com sucesso um ambiente de desenvolvimento para PHP no Windows usando o XAMPP. Agora você pode começar a desenvolver aplicativos web em PHP localmente.