mkdir -p app data/raw docs models src/iris_mlops tests
cd src/iris_mlops && touch api.py config.py data.py predict.py train.py
cd ../../app && touch gradio_app.py
