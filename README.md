# CI e pipelines no Github Actions

Neste projeto foram desenvolvidos scripts para automação de ações no github action, para que à cada commit realizado seja:
- Testado um código golang em diferentes versões do Ubuntu e diferentes versões do golang
- Compilado o código golang em um arquivo
- Criada uma imagem do projeto
- Subida a imagem do projeto no dockerhub

Além disso, também foi feita a criação de uma Docker file para criar a imagem e a criação de um script docker-compose para subir o respectivo docker.

| Nome | Descrição |
| -- | --|
| [Script do Github Actions principal](https://github.com/lucasbalponti/CI-e-pipelines-no-Github-Actions/blob/main/.github/workflows/go.yml) | Script onde foram configuradas as ações de testar o projeto, compilar o mesmo e chamar o script do docker. |
| [Script do Github Actions para o Docker](https://github.com/lucasbalponti/CI-e-pipelines-no-Github-Actions/blob/main/.github/workflows/Docker.yml) | Script onde foram configuradas as ações relacionadas à criação da imagem. |
| [Dockerfile](https://github.com/lucasbalponti/CI-e-pipelines-no-Github-Actions/blob/main/src/Dockerfile) | Dockerfile para a criação da imagem |
| [Script docker compose](https://github.com/lucasbalponti/CI-e-pipelines-no-Github-Actions/blob/main/src/docker-compose.yml) | Arquivo onde são feitas as configurações do docker do banco de dados  |
| [Ações no github actions](https://github.com/lucasbalponti/CI-e-pipelines-no-Github-Actions/actions) | Histórico de ações no github actions |
| [Commits](https://github.com/lucasbalponti/CI-e-pipelines-no-Github-Actions/commits/main) | Histórico de commits |