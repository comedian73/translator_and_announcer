# Переводчик и диктор

**Задача:**

Создать переводчик текста из аудиозаписи и воспроизведение переведенного текста с копированием голоса.

### Что использовал

import torch  # Библиотека для работы с нейронными сетями

from TTS.api import TTS  # API для Text-to-Speech

import soundfile as sf  # Работа с аудиофайлами

import librosa  # Библиотека для анализа аудио

import numpy as np  # Работа с массивами

from IPython.display import Audio, display  # Воспроизведение аудио

import whisper # библиотека извлечения текста из аудио

from transformers import MarianMTModel, MarianTokenizer # модели для перевода текста на другие языки
