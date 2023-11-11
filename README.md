# techbookfest15-mlflow-sample

技術書典15 「Azureで始めるMLflow」のサンプルノートブックです。

書籍内のコードと1対1に対応していません。書籍内で扱った各種コードが実際にはどのように使われるか例示し使用時の参考にするためのサンプルノートブックです。

# 環境構築

condaによる仮想環境管理とipynbを取り扱える環境を前提とします。

```bash
conda env create -f environment.yaml
conda install ipykernel
ipython kernel install --user --name=azureml-mlflow-env
```
