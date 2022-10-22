1. Detección

	* Silbidos
	* Clicks
	* Armónicos
	* + extra volcán

2. Eliminar el ruido de la señal

Version mini del dataset: https://colab.research.google.com/drive/1-fJKPZTd4kSQNOPOvjccfB9aUeAA7IhB?usp=sharing

CSV 71000 registros: dataset1 = pd.read_csv("https://bit.ly/dataset1marine")

Dataset mini: https://bit.ly/marinedataset1_mini_ogg

Dataset 1 completo en OGG (menor tamaño): https://storage.googleapis.com/datathon2022/dataset1_all_ogg.zip
Dataset 1 completo en WAV (mayor tamaño pero sin pérdida de calidad). https://storage.googleapis.com/datathon2022/dataset1_all_wav.zip


conda install -c conda-forge pydub
https://visualstudio.microsoft.com/es/visual-cpp-build-tools/
pip install audiosegment
conda install -c conda-forge librosa

Amplify 43 dB
Filtro Butterworth pasabajas orden 10 menor a 1.5KHz
Filtro Butterworth pasaaltas orden 10 mayor a 1.25KHz
Amplify 20 dB
Noise reduction < 6dB
