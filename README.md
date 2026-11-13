# my-lovely-car-site

Бывшие страницы приложения My Lovely Car на GitHub Pages:
<https://kaayuone.github.io/my-lovely-car-site/>. Страницы приложения и его политика
конфиденциальности переехали на сайт разработчика <https://darkaayu.com/my-lovely-car/>, здесь
остались только переадресации:

- `privacy-policy.html` → <https://darkaayu.com/my-lovely-car/privacy-policy/>. Этот адрес зашит
  в приложение до версии 1.0.1 включительно, поэтому страницу не удалять. Источник политики —
  `docs/product/privacy-policy.html` в репозитории приложения, сюда новые редакции не копируются.
- `index.html` → <https://darkaayu.com/my-lovely-car/>.
- `.nojekyll` — GitHub Pages отдаёт файлы как есть, без обработки Jekyll.

Переадресация — мгновенный `<meta http-equiv="refresh">` и `<link rel="canonical">` на новый
адрес: серверной 301 на другой домен GitHub Pages не умеет.

В январе 2027 года репозиторий архивируется. Pages при этом не выключать: архивированный
репозиторий продолжает отдавать сайт, и старые версии приложения попадают на новый адрес.
Снять сайт с публикации можно, только когда в статистике Play Console почти не останется версий
до 1.0.2.
