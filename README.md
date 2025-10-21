# 🎨 Coloring White PNG Images
## English version
### Overview

This script recolors white PNG images with transparent backgrounds into multiple predefined colors.
Each recolored image keeps its transparency and is saved under a new name with the color code added.
All colored images are then packed into a ZIP archive, and a CSV file with filenames is generated automatically.

### How to Use

1. Place your white PNG images inside the input_pngs folder (created automatically).
2. Run the script (coloring_png_images.py) in Python or Jupyter Notebook.
3. The recolored images will appear in colored_output, and a ZIP archive will be created in the same directory.
4. A CSV file listing all generated images will also be saved.

### Output Example

* icon__232642.png
* icon__3E1E1F.png
* ZIP file: colored_pngs_20251021_230000.zip
* CSV file: colored_file_list_20251021_230000.csv

### Requirements

* Python 3.8+
* Pillow (pip install pillow)

### Notes

The script works best with white shapes on a transparent background.

You can edit the color palette in the variable TARGET_COLORS inside the script.

## Русская версия
### Описание

Этот скрипт перекрашивает белые PNG-изображения с прозрачным фоном в несколько заданных цветов.
Прозрачность сохраняется, а имя каждого файла дополняется шестнадцатеричным кодом цвета.
Все перекрашенные изображения сохраняются в ZIP-архив, а список файлов записывается в CSV.

### Как использовать

1. Поместите белые PNG-файлы в папку input_pngs (создаётся автоматически).
2. Запустите файл coloring_png_images.py (в Python или Jupyter Notebook).
3. Готовые изображения появятся в colored_output, рядом создастся ZIP-архив.
4. CSV-файл со списком имён изображений сохранится автоматически.

### Пример вывода

* icon__232642.png
* icon__3E1E1F.png
* ZIP-файл: colored_pngs_20251021_230000.zip
* CSV-файл: colored_file_list_20251021_230000.csv

### Требования

* Python 3.8+
* Библиотека Pillow (pip install pillow)
