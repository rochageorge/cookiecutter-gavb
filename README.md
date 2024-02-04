
Este projeto tem como objetivo, servir como estrutura base para a criação de novos projetos de ciências de dados na GAVB, para que possam estar melhor preparados para deploy em produção e menutenabilidade.


# cookiecutter

pip install --user cookiecutter

pip install --upgrade cookiecutter




# miniconda3 - https://docs.conda.io/projects/miniconda/en/latest/

### Linux 

    mkdir -p ~/miniconda3
    wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -O ~/miniconda3/miniconda.sh
    bash ~/miniconda3/miniconda.sh -b -u -p ~/miniconda3
    rm -rf ~/miniconda3/miniconda.sh

    ~/miniconda3/bin/conda init bash
    ~/miniconda3/bin/conda init zsh


### Windows

    acesse: https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe
    
    clique em Miniconda3-latest-Windows-x86_64.exe
    


Problema ao buscar o conda env no Windows

    conda env list
    copia o path do env desejado
    ctrl + shift + p
    cola e aperta em enter




#### Faça uma cópia da estrutura de pastas do repositório

cookiecutter https://github.com/rochageorge/cookiecutter-gavb.git
