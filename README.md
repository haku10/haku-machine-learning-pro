# haku_machine_learning_pro
Machine Learning implementation

# Dockerイメージの作成
`docker build . -t haku_machine_learning_pro`

# Docker起動時のコマンド
```
docker run  \
-v ${PWD}/contents/:/tf/contents \
-p 9901:8888 -p 9902:6006 haku_machine_learning_pro
```
→
`docker-compose build`
`docker-compose up`
で起動できるように変更(2021/01/31)
# Jupyter Notebookの起動
