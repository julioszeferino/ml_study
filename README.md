# Estrutura

- data: contem os dados, cru e pre processado (usar o dvc)
- config: var ambiente, parametros, hiperparametros etc
- models: vamos armazenar todos os modelos treinados (usar o dvc)
- notebooks: notebooks de experimentacao
- src: (scripts python)
    - plots (scripts que plotam graficos)
    - training (scripts de treino)
    - validating
    - evaluating
    ...
- tests (adicionar testes automatizados)


ipykernel==6.15.1
pytorch-lightning==1.6.5
jupyter==1.0.0
torchvision==0.13.0
matplotlib==3.5.2
pandas==1.4.3
seaborn==0.11.2
yellowbrick==1.4
black
mkdocs-material==8.3.9

mkdocs new .\

https://squidfunk.github.io/mkdocs-material/

git commit -am ":sparkles: Initial config"
