<div align="center">
  <img src="media/logo.png" alt="Logo" width="100%"/>
  <br>
  <a href="https://huggingface.co/collections/vladlinv/ru-ocr"><img src="https://img.shields.io/badge/🤗_Hugging_Face-RU_OCR-FFD21E" alt="Hugging Face"></a>
  <a href="https://github.com/vladlinv/PP-OCRv6_rec_ru"><img src="https://img.shields.io/badge/GitHub-PP--OCRv6__rec__ru-181717?logo=github" alt="GitHub"></a>
</div>

## PP-OCRv6, дообученная для русского языка на 2 млн примеров из реальных и синтетических документов, включая рукописный текст.

<table>
  <thead>
    <tr>
      <th colspan="7" align="left">
        Сравнение на сложном
        <a href="https://huggingface.co/datasets/vladlinv/ru-ocr-benchmark-hard">бенчмарке</a>
        (2 196 примеров)
      </th>
    </tr>
    <tr>
      <th align="left">Model</th>
      <th align="center">1-NED</th>
      <th align="center">Accuracy</th>
      <th align="center">CER</th>
      <th align="center">WER</th>
      <th align="center">CPU</th>
      <th align="center">GPU</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left">
        <a href="https://huggingface.co/vladlinv/PP-OCRv6_medium_rec_ru_onnx">
          <b>RapidOCR (PP-OCRv6 Medium RU)</b>
        </a>
      </td>
      <td align="center"><b>0.9397</b></td>
      <td align="center"><b>52.50%</b></td>
      <td align="center"><b>7.03%</b></td>
      <td align="center"><b>23.98%</b></td>
      <td align="center">⚡</td>
      <td></td>
    </tr>
    <tr>
      <td align="left">
        <a href="https://huggingface.co/vladlinv/PP-OCRv6_medium_rec_ru">
          <b>PP-OCRv6 Medium RU</b>
        </a>
      </td>
      <td align="center"><b>0.9301</b></td>
      <td align="center"><b>51.46%</b></td>
      <td align="center"><b>9.25%</b></td>
      <td align="center"><b>28.49%</b></td>
      <td></td>
      <td align="center">⚡</td>
    </tr>
    <tr>
      <td align="left">
        <a href="https://huggingface.co/vladlinv/PP-OCRv6_tiny_rec_ru_onnx">
          <b>RapidOCR (PP-OCRv6 Tiny RU)</b>
        </a>
      </td>
      <td align="center"><b>0.9144</b></td>
      <td align="center"><b>42.03%</b></td>
      <td align="center"><b>7.87%</b></td>
      <td align="center"><b>28.04%</b></td>
      <td align="center">⚡</td>
      <td></td>
    </tr>
    <tr>
      <td align="left">
        <a href="https://huggingface.co/vladlinv/PP-OCRv6_tiny_rec_ru">
          <b>PP-OCRv6 Tiny RU</b>
        </a>
      </td>
      <td align="center"><b>0.9120</b></td>
      <td align="center"><b>41.30%</b></td>
      <td align="center"><b>8.44%</b></td>
      <td align="center"><b>29.73%</b></td>
      <td></td>
      <td align="center">⚡</td>
    </tr>
    <tr>
      <td align="left">Chandra OCR 2</td>
      <td align="center">0.8349</td>
      <td align="center">41.44%</td>
      <td align="center">21.75%</td>
      <td align="center">34.15%</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td align="left">RapidOCR (PP-OCRv5 Cyrillic)</td>
      <td align="center">0.8322</td>
      <td align="center">28.87%</td>
      <td align="center">14.86%</td>
      <td align="center">42.17%</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td align="left">RapidOCR (PP-OCRv5 Slavic)</td>
      <td align="center">0.8224</td>
      <td align="center">26.68%</td>
      <td align="center">15.49%</td>
      <td align="center">44.17%</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td align="left">Surya OCR v2</td>
      <td align="center">0.8119</td>
      <td align="center">30.19%</td>
      <td align="center">18.80%</td>
      <td align="center">41.29%</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td align="left">dots.mocr</td>
      <td align="center">0.8028</td>
      <td align="center">33.65%</td>
      <td align="center">24.50%</td>
      <td align="center">40.58%</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td align="left">PaddleOCR-VL 1.5</td>
      <td align="center">0.7770</td>
      <td align="center">29.28%</td>
      <td align="center">32.97%</td>
      <td align="center">42.09%</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td align="left">PaddleOCR-VL 1.6</td>
      <td align="center">0.7394</td>
      <td align="center">25.27%</td>
      <td align="center">27.82%</td>
      <td align="center">42.55%</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td align="left">Tesseract 5 Standard</td>
      <td align="center">0.6538</td>
      <td align="center">12.57%</td>
      <td align="center">29.58%</td>
      <td align="center">63.16%</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td align="left">Tesseract 5 Best</td>
      <td align="center">0.6399</td>
      <td align="center">13.34%</td>
      <td align="center">30.83%</td>
      <td align="center">61.78%</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

## Использование

### 🚀 Рекомендуемые для CPU (RapidOCR / ONNX)
* [**RapidOCR (PP-OCRv6 Medium RU)**](https://huggingface.co/vladlinv/PP-OCRv6_medium_rec_ru_onnx)
* [**RapidOCR (PP-OCRv6 Tiny RU)**](https://huggingface.co/vladlinv/PP-OCRv6_tiny_rec_ru_onnx)

### 🚀 Рекомендуемые для GPU (PaddlePaddle)
* [**PP-OCRv6 Medium RU**](https://huggingface.co/vladlinv/PP-OCRv6_medium_rec_ru)
* [**PP-OCRv6 Tiny RU**](https://huggingface.co/vladlinv/PP-OCRv6_tiny_rec_ru)

## Детали
PP-OCRv6  — линейка легковесных моделей распознавания текста от PaddlePaddle. Оптимизированы для быстрого инференса на CPU и GPU без высоких требований к железу и памяти. Дообучены для русского языка на 2 млн строк: реальные сканы документов, рукописный текст и синтетика. Полностью совместимы со стандартным пайплайном PaddleOCR.

Текущая версия уверенно распознаёт разборчивый рукописный текст, однако при работе со скорописью и менее чётким почерком возможны неточности. Следующий релиз будет сфокусирован на углубленном распознавании рукописного текста.


<img src="https://raw.githubusercontent.com/vladlinv/PP-OCRv6_rec_ru/master/media/sample1.png" alt="Пример 1" width="50%"/><br>
PP-OCRv6 Medium: Мир меняется быстро (score: 0.9952)<br>
PP-OCRv6 Tiny: Мир меняется быстро (score: 0.8645)<br>

<img src="https://raw.githubusercontent.com/vladlinv/PP-OCRv6_rec_ru/master/media/sample2.png" alt="Пример 2" width="50%"/><br>
PP-OCRv6 Medium: Технологии меняют привычки незаметно (score: 0.9512)<br>
PP-OCRv6 Tiny: Тетолоти меннт приви нозалто (score: 0.6429)<br>

## Ссылки

Стандартные аугментации при обучении модели дополнялись собственным пайплайном.<br>
Часть пайплайна: [vladlinv/OCR-Recognition-Augmentations](https://github.com/vladlinv/OCR-Recognition-Augmentations)

Бенчмарк для проверки качества моделей: [vladlinv/ru-ocr-benchmark-hard](https://huggingface.co/datasets/vladlinv/ru-ocr-benchmark-hard)

Часть примеров рукописи из [AntiplagiatCompany/HWR200](https://huggingface.co/datasets/AntiplagiatCompany/HWR200)

Оригинальный репозиторий PaddleOCR: [PaddlePaddle/PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR)<br>
Фреймворк RapidOCR: [RapidAI/RapidOCR](https://github.com/RapidAI/RapidOCR)
