# For docker user

## Clone this repo.

```bash
git clone git@github.com:ikuzo198/labelImg.git
cd labelImg
git checkout ycb
```

## Build the container

```bash
sudo sh docker/build-docker.sh
sudo sh docker/run-docker.sh 
```

## In container

```bash
make qt5py3
python3 labelImg.py
```

## Local

- labelImg/datasets 内にアノテーションしたいデータセットを持ってくる
