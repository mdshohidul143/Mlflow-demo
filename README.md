# Mlflow-demo


'''python 
conda create -n mlflow-demo-env python=3.10 -y
conda activate mlflow-demo-env
pip install -r requirements.txt
'''

'''mlflow run https://github.com/mdshohidul143/Mlflow-demo'''
'''mlflow ui'''

'''
mlflow models serve -m /E:/MLOPs%20on%20AWS/Mlflow-demo/mlruns/0/64a1c988da9c44bb9bd3e8d76db1fea9/artifacts/model --port 9000
'''

'''json
curl -X POST -H "Content-Type:application/json; format=dataframe_split" --data '{"columns":["alcohol", "chlorides", "citric acid", "density", "fixed acidity", "free sulfur dioxide", "pH", "residual sugar", "sulphates", "total sulfur dioxide", "volatile acidity"],"data":[[12.8, 0.029, 0.48, 0.98, 6.2, 29, 3.33, 1.2, 0.39, 75, 0.66]]}' http://127.0.0.1:9000/invocations
''' 