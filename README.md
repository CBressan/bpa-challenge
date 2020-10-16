<div align="center">
<a href="https://bpatechnologies.com" target="_blank">
    <img src="https://bpatechnologies.com/images/logo_header.png" height="100px" alt="PlanD"/>
</a>

<h3>Backend Developer Challenge</h3>

<a href="https://www.python.org" target="_blank">
  <img src="https://img.shields.io/badge/devel-Python-brightgreen" alt="Python"/>
</a>

<a href="https://pypi.org/project/XlsxWriter" target="_blank">
  <img src="https://img.shields.io/badge/lib-xlsxWriter-brightgreen" alt="XlsxWriter"/>
</a>

<a href="https://pandas.pydata.org" target="_blank">
  <img src="https://img.shields.io/badge/lib-Pandas-brightgreen" alt="Pandas"/>
</a>

<a href="https://www.selenium.dev" target="_blank">
  <img src="https://img.shields.io/badge/main--lib-Selenium-brightgreen" alt="Selenium"/>
</a>

<a href="https://docs.conda.io/en/latest/miniconda.html" target="_blank">
  <img src="https://img.shields.io/badge/venv-Conda-brightgreen" alt="Conda"/>
</a>

<a href="https://opensource.org/licenses/MIT" target="_blank">
  <img src="https://img.shields.io/badge/license-MIT-brightgreen" alt="MIT"/>
</a>

</div>

## Execução do projeto
#### Download 

```
$ git clone https://github.com/CBressan/bpa-challenge.git
```
#### Configuração do ambiente:

- Crie um ambiente virtual com seu sistema de gerenciamento favorito (conda, pyenv, virtualenv, etc);

- Ative o ambiente criado

#### Instalar dependências
<pre><code> $ pip install -r requirements.txt </code></pre>

Executar projeto:

<pre><code> $ python main.py </code></pre>

### Descrição do desáfio
O desáfio consiste em fazer em Python um programa que navega no site da Amazon, pesquisa o termo IPHONE, pegue todos os resultados da primeira página e para cada um, grava uma linha em um arquivo excel, com o nome do produto e o preço.


### Solução
A solução utilizada para este teste foi utilizando as bibliotecas as seguintes bibliotecas: selenium(para navegação nas páginas e coleta dos dados), pandas(para manipulação dos dados obtidos) e xlrwiter(gravação dos dados em xlsx).
