# Д.О.Х.Е.Р.А.
## Директива Объединений: Хороших, Естественных, Релевантных, Актуальных
  
### Что это?
В последнее время появилось очень много сообществ, ресурсов, материалов и везде есть что - то полезное.

В этой директиве в удобном формате хранятся:
- Полезные Youtube-каналы и блогеры
- Ценные документы и гайды
- Важные ресурсы и сайты
- Годные сообщества и паблики
  
### Как этим пользоваться?
В каждой папке есть набор текстовых файлов с кратким описанием чего-либо.
Каждому файлу соответствует один источник. Это нужно для простоты поиска.

### Как добавить своё?
> Прежде, чем читать инструкции ниже, прочтите [правила оформления материалов](#правила-оформления-материалов)

<details>
  <summary>Я разработчик и/или понимаю, как пользоваться GitHub</summary>

  - Создать форк репозитория

  - Сделать ветку с названием статьи транслитом

  - Закинуть в нее папку с постом. Важно, чтобы название папки было уникальным, иначе произойдет обновление существующего поста (за раз можно добавить не более 10 файлов)

  - Создать PR

</details>

<details>
  <summary>Мне нужна подробная инструкция</summary>
  
  - Создать отдельную ветку от main, в текстовом поле ввести название новой ветки, нажать на **Create branch**
  
    ![pr_creating](https://user-images.githubusercontent.com/48432436/165773036-c069375a-be64-4acc-9588-f7feff17f86d.png)

  - Перейти в новую ветку и кликнуть **Add file**' => **Upload files**

    ![file_upload](https://user-images.githubusercontent.com/48432436/165773878-ec09aa84-1e31-4bd3-9f5d-75bfa10ed0b5.png)

  - Перетащить файл поста или папку с файлом в поле на новой странице. После успешной загрузки нажать зеленую кнопку **Commit changes**
    - При создании нового поста важно, чтобы название папки было уникальным, иначе произойдет обновление существующего поста (за раз можно добавить не более 10 файлов)

    ![drag_n_drop](https://user-images.githubusercontent.com/48432436/165774478-9143844f-141a-4fda-8602-2b4c183768dc.png)

  - Если все прошло успешно, то на экране появится соответствующее сообщение, в котором предлагается создать Pull Request. Кликаем зеленую кнопку **Compare & pull request**

    ![create_pr](https://user-images.githubusercontent.com/48432436/165775602-7d316595-dc96-455a-8b18-aa0ca94afc08.PNG)

  - В новом окне надо задать информацию о Pull Request. На данном этапе необязательно заполнять все как в последний раз, у вас еще будет возможно все отредактировать. После всех приготовлений кликаем зеленую кнопку **Create pull request**

    ![Pr_desc](https://user-images.githubusercontent.com/48432436/165777031-a5195bf2-cd7a-465d-a010-487b23bc444d.PNG)

  - В следующем окне отображается вся информация о вашем Pull Request, вы в любой момент можете его закрыть и вернуться позднее, прогресс не пропадет. Создание поста происходит после клика на кнопку **Merge pull request**

</details>

### Правила оформления материалов
Для максимального удобства и качественной навигации следует придерживаться единого формата публикаций.

<details>
  <summary>Шаблон оформления</summary>

  При добавлении материал должен иметь следующую структуру:

  ```markdown
  # Заголовок
  ## Описание
  ![img](превью.png)
  
  ### Что это?
  Абзац о чём материал
  
  ### Что ценного?
  Абзац о том, чем материал является/может являться особенным
  
  ### Кому подойдет?
  1-2 предложения описывающих потенциальную аудиторию
  
  ### Ссылки
  [ссылка 1](https://ссылка-1)
  [ссылка 1](https://ссылка-2)
  ```

  ### Важные моменты

  - Материал должен быть в отдельной папке. Каждая папка - в одном из ключевых разделов.
  - Описание в одну строку. Меньше лишних слов - лучше.
  - По изображениям желателен любой горизонтальный формат (`.jpg`, `.png`, `.jpeg`). Соотношение сторон между 4:3 и 16:9 либо приближенное
  - При необходимости добавить более одного изображения - помещать их после ссылок внизу отдельным разделом

</details>

### Я знаю как лучше. Куда нести фидбек?
В разделе issues можете заводить любые предложения по улучшению работы, структурированию данных, или стилизации.