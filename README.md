![GitHub repo size](https://img.shields.io/github/repo-size/DanielMelloo/dmtoolbox?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/DanielMelloo/dmtoolbox?style=for-the-badge)
![Bitbucket open issues ](https://img.shields.io/bitbucket/issues/DanielMelloo/dmtoolbox?style=for-the-badge)
![Bitbucket open pull requests ](https://img.shields.io/bitbucket/pr/DanielMelloo/dmtoolbox?style=for-the-badge)  


# dmtoolbox


- [dmtoolbox](#dmtoolbox)
  - [Descrição](#descrição)
  - [Funcionalidades](#funcionalidades)
  - [Funcionalidades dos Módulos](#funcionalidades-dos-módulos)
    - [fmfunc.py](#fmfuncpy)
    - [genJsons.py](#genjsonspy)
    - [nginxDefaults.py  e nginxUtils.py](#nginxdefaultspy--e-nginxutilspy)
    - [numericFuncs.py](#numericfuncspy)
    - [osFuncs.py](#osfuncspy)
    - [portTools.py](#porttoolspy)
  - [Instalação do Pacote dmtoolbox](#instalação-do-pacote-dmtoolbox)
    - [Pré-Requisitos](#pré-requisitos)
    - [Passo 1: Criação de um Ambiente Virtual (Opcional, mas Recomendado)](#passo-1-criação-de-um-ambiente-virtual-opcional-mas-recomendado)
    - [Passo 2: Instalação do Pacote dmtoolbox](#passo-2-instalação-do-pacote-dmtoolbox)
    - [Solução Alternativa: Instalação Manual das Dependências e Clonagem do Repositório](#solução-alternativa-instalação-manual-das-dependências-e-clonagem-do-repositório)
  - [Exemplos de Uso](#exemplos-de-uso)
  - [Contribuições](#contribuições)
  - [Autor](#autor)
  - [Licença](#licença)



## Descrição
Este pacote Python é uma coleção abrangente de ferramentas projetadas para facilitar a automação de tarefas e operações no ambiente Windows, manipulação avançada de arquivos e diretórios, criação e gestão de executáveis, manipulação de dados JSON, gerenciamento de configurações NGINX, análise numérica, e muito mais.


## Funcionalidades
- **Gerenciamento de Arquivos e Diretórios**: Criação e manipulação de estruturas de arquivos no AppData e outras localizações, com suporte para operações que requerem privilégios elevados.

- **Manipulação de JSON**: Ferramentas para converter dados para e de JSON, e atualizar scripts com novas declarações de variáveis baseadas em conteúdo JSON.
- **Gerenciamento do NGINX**: Funcionalidades para configurar, iniciar, parar e reiniciar o servidor NGINX, além de verificar e ajustar configurações de acordo com as necessidades do usuário.
- **Análise Numérica e Visualização**: Funções para manipulação matemática avançada, incluindo operações com matrizes, geração de tabelas formatadas, e plotagem de gráficos 2D e 3D.
- **Interação com o Sistema Operacional**: Utilitários para verificar privilégios de administrador, manipular registros do Windows, e mais.
- **Gerenciamento de Portas**: Ferramentas para verificar a disponibilidade de portas e configurar portas para aplicações.



## Funcionalidades dos Módulos
Cada módulo traz um conjunto de funcionalidades específicas, detalhadas a seguir:


### [fmfunc.py](https://github.com/DanielMelloo/dmtoolbox/blob/main/dmtoolbox/fmfunc.py)
- Oferece um conjunto diversificado de funções utilitárias para operações comuns, como manipulação de datas, tamanhos de arquivos, e caminhos de diretórios.

### [genJsons.py](https://github.com/DanielMelloo/dmtoolbox/blob/main/dmtoolbox/genJsons.py)
- Permite a conversão eficiente de dados para o formato JSON e vice-versa, além da atualização dinâmica de scripts com novos dados JSON.

### [nginxDefaults.py](https://github.com/DanielMelloo/dmtoolbox/blob/main/dmtoolbox/nginxDefaults.py)  e [nginxUtils.py](https://github.com/DanielMelloo/dmtoolbox/blob/main/dmtoolbox/nnginxUtils.py) 
- Proporcionam ferramentas para o gerenciamento detalhado de configurações do servidor NGINX, incluindo inicialização, parada, e verificação de status.

### [numericFuncs.py](https://github.com/DanielMelloo/dmtoolbox/blob/main/dmtoolbox/numericFuncs.py)
- Inclui funções para análises numéricas avançadas, manipulação de matrizes, e visualização de dados em 2D e 3D.

### [osFuncs.py](https://github.com/DanielMelloo/dmtoolbox/blob/main/dmtoolbox/osFuncs.py)
- Contém utilitários para interações avançadas com o sistema operacional, como verificação de privilégios de administrador e manipulação de arquivos e diretórios.

### [portTools.py](https://github.com/DanielMelloo/dmtoolbox/blob/main/dmtoolbox/portTools.py)
- Fornece métodos para verificar a disponibilidade de portas TCP/IP e selecionar portas disponíveis para aplicações.



## Instalação do Pacote dmtoolbox

Para instalar o pacote dmtoolbox de maneira eficiente e segura, siga os passos abaixo. Recomendamos a utilização de um ambiente virtual Python para evitar conflitos de dependências com outros pacotes instalados no sistema.

### Pré-Requisitos

- Certifique-se de que o Python está instalado em seu sistema. O dmtoolbox é compatível com Python 3.6 ou superior.
- É recomendável ter o pip, o gerenciador de pacotes do Python, atualizado. Para atualizar o pip, execute o seguinte comando no terminal:
```bash
python -m pip install --upgrade pip
```

### Passo 1: Criação de um Ambiente Virtual (Opcional, mas Recomendado)

1. Abra um terminal.
2. Navegue até o diretório onde deseja armazenar o ambiente virtual e seu projeto.
3. Execute o comando para criar um ambiente virtual. Substitua `meuenv` pelo nome que deseja dar ao seu ambiente virtual:

python -m venv meuenv

4. Ative o ambiente virtual:

   - No Windows:
    ```powershell
    .\meuenv\Scripts\activate
    ```

    - No Unix ou MacOS:
    ```bash
    source meuenv/bin/activate
    ```

### Passo 2: Instalação do Pacote dmtoolbox

Com o ambiente virtual ativado, instale o pacote dmtoolbox utilizando o pip:
```bash
pip install dmtoolbox
```

### Solução Alternativa: Instalação Manual das Dependências e Clonagem do Repositório

Caso encontre problemas ao instalar o pacote via pip, você pode optar por instalar manualmente as dependências e clonar o repositório do projeto. Primeiro, instale as dependências listadas no arquivo `requirements.txt`:
```bash
pip install -r requirements.txt
```

Em seguida, clone o repositório do GitHub ou baixe os arquivos do projeto diretamente para o seu ambiente de trabalho.


## Exemplos de Uso

Para ajudá-lo a começar, fornecemos uma série de exemplos práticos no diretório [`Exemplos de Código`](https://github.com/DanielMelloo/dmtoolbox/tree/main/Exemplos%20de%20Código). Aqui você encontrará amostras de código demonstrando como utilizar as funcionalidades disponíveis no dmtoolbox.

Para acessar os exemplos, navegue até a pasta [`Exemplos de Código`](https://github.com/DanielMelloo/dmtoolbox/tree/main/Exemplos%20de%20Código) no repositório do projeto ou clique no link.


## Contribuições
Encorajamos contribuições! Se deseja sugerir melhorias, corrigir bugs ou adicionar novas funcionalidades, por favor, abra uma issue ou submeta um pull request.


## Autor

- Nome: Daniel Mello
- Website: [Portfólio](https://www.danielmello.tech)
- GitHub: [github.com/DanielMelloo](https://github.com/DanielMelloo)


## Licença
Este projeto é licenciado sob a GNU General Public License v3.0 - veja o arquivo [LICENSE](LICENSE) para mais detalhes.


[⬆ Voltar ao topo](#dmtoolbox)