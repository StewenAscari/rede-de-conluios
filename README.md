# Rede de conluios

Análise da coparticipação de empresas em licitações na Paraíba.

A aplicação pode ser acessada em: http://licitantes.info 

## Dependências

- [*R*](https://cran.r-project.org/) >= 3.3
- *libv8* 
  - `apt-get install libv8-dev`

### Pacotes R

Depois de ter o [*R*](https://cran.r-project.org/) instalado, você deve
instalar os pacotes do R. Vá até o diretório raiz do projeto e rode:

```
Rscript instala_pacotes.R
```

### Dados do TCE

Para atualizar os dados das licitações e gerar novamente as estatísticas
de coparticipações, você deve baixar os dados no site do TCE-PB.
Vá até o diretório raiz do projeto e rode:

```
scripts/download_and_uncompress_tce_data.sh
```

## Executar aplicação

Para executar a aplicação e acessar de um browser localmente, rode:

```
Rscript run_app.R
```
