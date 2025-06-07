# Repositório: "simple-package-template"

Nesse repositório trazemos apenas um template de uma estrutura simples para criação de pacotes e publicação no Test Pypi e Pypi.
O template busca estruturar uma organização básica de arquivos necessários à publicação de módulos e pacotes para a comunidade Python:

project_name/
    README.md          # Descrição do pacote, comando para instalação, forma de importação, autor e licença de uso. 
    setup.py           # Parâmetros básicos de construção do pacote (nome do pacote, versão, author, contatos, descrição, requisitos...
    requirements.txt   # Informa as dependências do pacote com as suas versões, se necessário.
    package_name/
        __init__.py    # Arquivo de inicialização do módulo
        file1_name.py  # Módulo 1
        file2_name.py  # Módulo 2
