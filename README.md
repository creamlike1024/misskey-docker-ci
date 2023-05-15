# misskey-docker-ci

Build linux/amd64, linux/arm64 image

## How to

1. Registry a DockerHub account, generate an access token with write permission and create a new repository
2. Fork this Github repo
3. Go to `Settings -> Secrtes and variables -> Action` Click `New repository secret`
4. Add these secrets:
    |Name|Secret|
    |:----|:----|
    |`DOCKERHUB_USERNAME`| Your DockerHub username|
    |`DOCKERHUB_TOKEN`| Your DockerHub token|
    |`DOCKERHUB_REPO`| Your DockerHub repo name|
    |`DOCKERHUB_TAG`| Image Tag you want to use|
5. Now you can manually run this workflow, it will auto build and upload newest misskey master branch image to your DockerHub repository
6. If you are looking for some automatic tool to update misskey, try use this repo with [misskey-ci-bot](https://github.com/creamlike1024/misskey-ci-bot)

## 使用方法

1. 注册一个 DockerHub 帐号，生成一个带有 write 权限的 access token 并新建一个 repository
2. Fork 这个 Github 仓库
3. 转到 `Settings -> Secrtes and variables -> Action` 点击 `New repository secret`
4. 添加以下 secrets：
    |Name|Secret|
    |:----|:----|
    |`DOCKERHUB_USERNAME`| 你的 DockerHub 用户名|
    |`DOCKERHUB_TOKEN`| 你的 DockerHub access token|
    |`DOCKERHUB_REPO`| 你的 DockerHub 仓库名|
    |`DOCKERHUB_TAG`| 想使用的镜像 tag|
5. 现在你可以手动运行这个 workflow 了，它会自动构建并上传 misskey master 分支的最新镜像
6. 如果你想自动化 misskey 的更新，可以试试 [misskey-ci-bot](https://github.com/creamlike1024/misskey-ci-bot)

1. 注册一个 DockerHub 帐号，生成一个带有 write 权限的 access token 并新建一个 repository
2. Fork 这个 Github 仓库
3. 转到 `Settings -> Secrtes and variables -> Action` 点击 `New repository secret`
4. 添加以下 secrets：
    |Name|Secret|
    |:----|:----|
    |`DOCKERHUB_USERNAME`| 你的 DockerHub 用户名|
    |`DOCKERHUB_TOKEN`| 你的 DockerHub access token|
    |`DOCKERHUB_REPO`| 你的 DockerHub 仓库名|
    |`DOCKERHUB_TAG`| 想使用的镜像 tag|
5. 现在你可以手动运行这个 workflow 了，它会自动构建并上传 misskey master 分支的最新镜像
6. 如果你想自动化 misskey 的更新，可以试试 [misskey-ci-bot](https://github.com/creamlike1024/misskey-ci-bot)