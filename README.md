# Phishing para captura de senhas do Facebook

### Ferramentas

- Kali Linux
- setoolkit

### Savando a página de login e alterando o código fonte

- Salve a página de login no Facebook (www.facebook.com) com o nome `index.html`;
- Na mesma página, abra a janela de inspeção e encontre a id do botão de login:

![](https://img001.prntscr.com/file/img001/4zA7h_7zRwue_9k62hm7zg.png)

- Copie o código fonte da página de login do Facebook (www.facebook.com);
- Abra o arquivo `index.html` salvo anteriormente no editor de texto e substitua pelo código copiado no passo anterior;
- No novo código pesquise pelo ID do botão de login (apenas os 6 primeiros caracteres), apague todo o script em que ele se encontra e salve o arquivo.

![](https://img001.prntscr.com/file/img001/S5zAJdaYQhWURUUtpEDL-Q.png)

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ```Custom Import```
- Opção de cópia: ```Copy te entire folder```
- URL do site: http://www.facebook.com

### Resutado

![](https://img001.prntscr.com/file/img001/WNeTC987Q_a9e8thGSkGQQ.png)

