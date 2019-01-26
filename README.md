Проект плеер oni файлов
----------
Python 3.6.5 :: Anaconda, Inc.

Зависимости:
- pip install primesense (https://pypi.org/project/primesense/)
- pip install opencv_python-3.4.5+contrib-cp36-cp36m-win_amd64.whl (https://www.lfd.uci.edu/~gohlke/pythonlibs/#opencv)
- OpenNI-Windows-x64-2.2.0.33.zip (https://structure.io/openni)
----------
pip show primesense

Name: primesense
Version: 2.2.0.30.post5
Summary: OpenNI2 and NiTE2 python bindings

pip show opencv_python

Name: opencv-python
Version: 3.4.5+contrib
Summary: OpenCV (Open Source Computer Vision) is a library of programming functions for real time computer vision.
----------
Скрины:
- screens/start.jpg - запуск приложения
- screens/load_oni_file_frames_splash_screen.jpg - загрузка фреймов oni-файла и показ заставки загрузки
- screens/play_oni_file.jpg - проигрывание фреймов
- screens/depth_gray_window.jpg - окно глубины в gray
- screens/resize_and_exit_dialog.jpg - функционал изменения размера окна и диалог выхода
----------
Тестировалось на Windows7-64 sp1, windows10-64

запуск: python main.py