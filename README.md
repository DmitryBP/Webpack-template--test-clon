# Клонирование репозитория

### 1. Берем шаблон WebPack с репозитория:

[Скачать шаблон](https://github.com/DmitryBP/WebPack-Template)

### 2. Клонируем шаблон в корень нового проекта:

    git clone https://github.com/DmitryBP/WebPack-Template

### 3. Посмотрим имя удаленного репозитория:

    git remote show 

### 4. Отключим удаленный репозиторий с именем origin 
    
    git remote remove origin 

### 5. Устанавливаем зависимости 
    
    npm i

### 5. Привязка к новому удаленному репозиторию 

 Идем на GitHub создаем репозиторий для нового проекта

 Копируем ссылку на новый репо добавляем к команде добавления удаленного репо: 

    git remote add origin https://github.com/DmitryBP/Webpack-template--test-clon.git

Пушим проект в новый репозиторий 

    git push -u origin main

### 6. Добавляем новый проект в appveyor

[AppVeyor](https://ci.appveyor.com/projects)

Добавляем бейдж в readme

[![Build status](https://ci.appveyor.com/api/projects/status/u36hwut3jr2skqlv?svg=true)](https://ci.appveyor.com/project/DmitryBP/webpack-template-test-clon)