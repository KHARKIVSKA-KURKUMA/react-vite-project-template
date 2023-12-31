# React Project Template Single Page

Цей проєкт був зібраний за допомогою
[Vite](https://vitejs.dev/). Щоб ознайомитись та налаштувати додатковий функціонал
[перейдіть до документації](https://vitejs.dev/guide/).

## Початок

Для запуску цього React Project Template на вашому локальному комп'ютері, виконайте ці дії:

### Склонуйте цей репозиторій

```bash

git clone https://github.com/KHARKIVSKA-KURKUMA/react-vite-project-template.git

```

Або натисніть `«Use this template»` і виберіть
`«Create a new repository»`

### Встановіть залежності

```bash

npm install

```

### Запустіть додаток

```bash
npm start

```

<a id="deployment-section"></a>

## Розгортання (Deploy)

Замініть `<YOUR_REPO_NAME>` на назву вашого репозиторія в файлі `vite.config.js`

```jsx
if (command !== "serve") {
  config.base = "/<YOUR_REPO_NAME>/";
}
```

Продакшн-версія проєкту буде автоматично створена та розгортатиметься на GitHub page кожного разу, коли гілка `main`
оновлюється.

Далі потрібно зайти в налаштування репозиторію GitHub (`Settings` >
`Pages`) і встановити розповсюдження робочої версії файлів за допомогою GitHub Action, якщо це не було зроблено автоматично. Ви можете побачити це на зображенні нижче.

![GitHub Pages settings](./public/assets/repo-settings.png)

### Статус Розгортання

Статус розгортання останнього коміту відображається разом з іконкою

- ![Yellow](https://via.placeholder.com/15/9e6a03/000000?text=+) - проєкт в процесі розгортання.
- ![Green](https://via.placeholder.com/15/3fb950/000000?text=+) - розгортання завершено успішно.
- ![Red](https://via.placeholder.com/15/f85149/000000?text=+) - сталася помилка під час розгортання.

Більш детальну інформацію про статус можна переглянути, натиснувши на іконку
і у випадному вікні перейти за посиланням `Details`.

### Жива сторінка

Через деякий час, як правило, пару хвилин, сторінку можна буде переглянути за
адресою, `https://<YOUR_GITHUB_USERNAME>.github.io/<REPO_NAME>/`. Наприклад, ось посилання
до живої версії для цього репозиторію

[https://kharkivska-kurkuma.github.io/react-vite-project-template-js/](https://kharkivska-kurkuma.github.io/react-vite-project-template-js/).

Якщо відкривається порожня сторінка, переконайтеся, що на вкладці `Console` немає помилок
пов'язаних з неправильними шляхами до файлів проєкту (**404**). Якщо помилки існують перевірте шляхи описані в секції [Deploy](#deployment-section)
