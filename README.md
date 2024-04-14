# Среда запуска
1. Развертывание производится в любом интерпретаторе поддерживающий Python 3
2. Требуется установленный Python 
3. Требуются все установленные библиотеки во вкладке bib
4. Установить все папки AI, real, test где, папка AI содержит только сгенерированную речь, папка real содержит только человеческую речь, папка test содержит и сгенерированную и человеческую речи
# Подставить в # Пути к папкам с аудиофайлами баз данных
1. database1ai_path = 'путь_к_файлу\\ai';  database2real_path = 'путь_к_файлу\\real'; и # Пути к папке с аудиофайлами для проверки test_database_path = 'путь_к_файлу\\test'
# Установка
Установка bib
1. pip install os
2. pip install librosa
3. pip install numpy
4. pip install tensorlow
5. pip install sklearn.metrics
6. pip install tensorflow.keras
# Реализованная функциональность
1. Классификация синтезированной речи 50% (из-за недостатка времени обучения)
2. Документация для развертывания и использования системы
3. Добавление больших условий для выявления синтезированной речи
4. Обработка болших объемов данных
5. Обработка аудио при постороннием шуме, наложении голоса и других помех
# Киллер-фича
1. Определение синтезированной речи по Мел-частотным кепстральным коэффициентам (MFCC)
2. дальнейшее развитие проекта позволит определять синтезированную речь >90%
3. Простота пользования
# Разработчики:
1. Белозерцев Кирилл - fullstack https://t.me/harrow4ik
2. Бондарь Николай - fullstack https://t.me/nickridtz
