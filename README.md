# WordPress-ускорения и оптимизации вашего сайта 
Этот список охватывает все ключевые аспекты производительности WordPress: кэширование, оптимизацию изображений, уменьшение HTTP-запросов, работу с CDN, настройку серверов (NGINX, Apache, Varnish), нагрузочное тестирование, анализ производительности и многое другое.

# ⚡ Awesome WordPress Speed Up (RU)

Коллекция лучших плагинов и ресурсов для ускорения и оптимизации вашего сайта на WordPress.

---

## 📂 Содержание
* [🚀 Плагины кэширования страниц](#-плагины-кэширования-страниц)
* [📦 Плагины объектного кэширования](#-плагины-объектного-кэширования)
* [🧩 Плагины кэширования фрагментов](#-плагины-кэширования-фрагментов)
* [🌐 Кэширование на стороне браузера](#-кэширование-на-стороне-браузера)
* [🧹 Минификация и оптимизация кода](#-минификация-и-оптимизация-кода)
* [🌍 Интеграция с CDN](#-интеграция-с-cdn)
* [🖼 Оптимизация изображений](#-оптимизация-изображений)
* [⏳ Lazy Loading (Ленивая загрузка)](#-lazy-loading-ленивая-загрузка)
* [📉 Сокращение HTTP-запросов](#-сокращение-http-запросов)
* [🗄 Оптимизация базы данных](#-оптимизация-базы-данных)
* [🔍 Отладка и анализ медленных запросов](#-отладка-и-анализ-медленных-запросов)
* [🖥 Управление NGINX и Varnish](#-управление-nginx-и-varnish)
* [🛠 Вспомогательные плагины для кэширования](#-вспомогательные-плагины-для-кэширования)
* [⌨️ Команды и пакеты WP-CLI](#-команды-и-пакеты-wp-cli)
* [📊 Сервисы для проверки производительности](#-сервисы-для-проверки-производительности)
* [🧪 Инструменты нагрузочного тестирования](#-инструменты-нагрузочного-тестирования)
* [📈 Плагины New Relic](#-плагины-new-relic)
* [⚙️ Конфигурации NGINX](#-конфигурации-nginx)
* [📜 Конфигурации Apache](#-конфигурации-apache)
* [🧊 Конфигурации Varnish](#-конфигурации-varnish)
* [📚 Дополнительное чтение](#-дополнительное-чтение)

---

## 🚀 Плагины кэширования страниц
* [WP Fastest Cache](https://wordpress.org/plugins/wp-fastest-cache/) — Создает статические HTML-файлы из вашего динамического блога WordPress.
* [WP Super Cache](https://wordpress.org/plugins/wp-super-cache/) — Генерирует статические HTML-файлы. Веб-сервер отдает эти файлы вместо выполнения тяжелых PHP-скриптов WordPress.
* [Comet Cache](https://wordpress.org/plugins/comet-cache/) — Делает снимки страниц, записей, категорий и ссылок в реальном времени для мгновенной загрузки.
* [Cache Enabler](https://wordpress.org/plugins/cache-enabler/) — Создает статические HTML-файлы и сохраняет их на диске сервера.
* [SG Optimizer](https://wordpress.org/plugins/sg-cachepress/) — Связывает WordPress с сервисами производительности хостинга SiteGround.
* [WP Rocket](https://wp-rocket.me/) — Ваш сайт на скорости света (премиум-решение).
* [W3 Total Cache](https://wordpress.org/plugins/w3-total-cache/) — Самый комплексный плагин: кэширование страниц, объектов, базы данных, минификация и поддержка CDN.
* [Cachify](https://wordpress.org/plugins/cachify/) — Оптимизирует загрузку, кэшируя записи и страницы как статический контент.
* [Hyper Cache](https://wordpress.org/plugins/hyper-cache/) — Плагин кэширования, написанный специально для достижения максимальной скорости.
* [Powered Cache](https://wordpress.org/plugins/powered-cache/) — Всесторонний плагин для кэширования и производительности.
* [Redis Page Cache for WordPress](https://github.com/pressjitsu/pj-page-cache-red) — Гибкое и быстрое кэширование страниц на базе Redis.
* [Varnish Caching](https://github.com/razvanstanga/varnish-caching-wordpress-plugin) — Полная интеграция с Varnish Cache 3.x/4.x.
* [Breeze](https://wordpress.org/plugins/breeze/) — Плагин от Cloudways с поддержкой Varnish и множеством опций оптимизации.
* [Pantheon Advanced Page Cache](https://wordpress.org/plugins/pantheon-advanced-page-cache/) — Автоматическая очистка кэша на стороне Pantheon Edge при обновлении контента.
* [LiteSpeed Cache](https://wordpress.org/plugins/litespeed-cache/) — Плагин для интеграции с LSCache на веб-сервере LiteSpeed.
* [Pegasaas Accelerator WP](https://wordpress.org/plugins/pegasaas-accelerator-wp/) — Оптимизация через Pegasaas API для Google PageSpeed.
* [NitroPack](https://wordpress.org/plugins/nitropack/) — Облачный сервис для автоматической оптимизации производительности.
* [ezCache](https://wordpress.org/plugins/ezcache/) — Инновационный и простой плагин для значительного ускорения сайта.
* [Surge](https://wordpress.org/plugins/surge/) — Максимально простой и быстрый плагин кэширования страниц.
* [SpeedyCache](https://wordpress.org/plugins/speedycache/) — Помогает сократить время загрузки через кэширование, минификацию и сжатие.

## 📦 Плагины объектного кэширования
* [Object Cache Pro](https://objectcache.pro/?ref=luke) — Redis-кэш бизнес-класса для высоконагруженных проектов.
* [Redis Object Cache](https://wordpress.org/plugins/redis-cache/) — Постоянное объектное кэширование на базе Redis. Поддерживает кластеризацию и WP-CLI.
* [Tiny Cache](https://github.com/szepeviktor/tiny-cache) — Кэширует контент записей, переводы и меню в объектном кэше.
* [Docket Cache](https://wordpress.org/plugins/docket-cache/) — Файловый объектный кэш, хранящийся в виде чистого PHP-кода.
* [Memcached Redux](https://wordpress.org/plugins/memcached-redux/) — Современная реализация Memcached для объектного кэширования.
* [WP Redis](https://wordpress.org/plugins/wp-redis/) — Необходим для сайтов с высоким трафиком и динамическими страницами.

## 🧩 Плагины кэширования фрагментов
* [Fragment Cache](https://github.com/Rarst/fragment-cache) — Частичное и асинхронное кэширование тяжелых элементов фронтенда (меню, виджеты, галереи).
* [PJ Fragment Cache](https://github.com/pressjitsu/fragment-cache) — Кэширование фрагментов с поддержкой транзиентов и метаданных.

## 🌐 Кэширование на стороне браузера
* [Speed Up – Browser Caching](https://wordpress.org/plugins/speed-up-browser-caching/) — Легкий плагин (10 Кб) для настройки кэширования статики в Apache.
* [WP Performance Score Booster](https://wordpress.org/plugins/wp-performance-score-booster/) — Улучшает показатели в PageSpeed, YSlow, Pingdom и GTmetrix.

## 🧹 Минификация и оптимизация кода
* [Autoptimize](https://wordpress.org/plugins/autoptimize/) — Объединяет, сжимает и минифицирует скрипты и стили, настраивает заголовки Expires.
* [Autoptimize criticalcss.com power-up](https://wordpress.org/plugins/autoptimize-criticalcss/) — Интеграция с CriticalCSS для мгновенной отрисовки верхней части страницы.
* [WP Roids](https://wordpress.org/plugins/wp-roids/) — Экстремально быстрое кэширование и минификация HTML, CSS и JS.
* [Merge + Minify + Refresh](https://wordpress.org/plugins/merge-minify-refresh/) — Слияние и минификация CSS и JS.
* [Minify HTML](https://www.littlebizzy.com/plugins/) — Деликатная очистка HTML от лишних пробелов, комментариев и переносов.
* [RapidLoad Power-Up for Autoptimize](https://wordpress.org/plugins/unusedcss/) — Автоматическое удаление неиспользуемого CSS кода.
* [Torque](https://wordpress.org/plugins/torque/) — Комплексная оптимизация доставки контента с лучшим уровнем сжатия.
* [SCSS WP Editor](https://wordpress.org/plugins/scss-wp-editor/) — Позволяет добавлять и компилировать SCSS прямо из админки.
* [ShortPixel Critical CSS](https://wordpress.org/plugins/shortpixel-critical-css/) — Автоматическое создание критического CSS через веб-сервис ShortPixel.

## 🌍 Интеграция с CDN
* [CDN Enabler](https://wordpress.org/plugins/cdn-enabler/) — Ускоряет доставку контента через сеть распределенных серверов.
* [Cloudflare](https://wordpress.org/plugins/cloudflare/) — Официальный плагин для простой настройки Cloudflare.
* [Cloudflare Page Cache](https://wordpress.org/plugins/cloudflare-page-cache/) — Кэширование HTML-страниц на стороне Cloudflare через Workers.
* [Fastly](https://wordpress.org/plugins/fastly/) — Автоматическая очистка кэша в сети Fastly при обновлении контента.
* [Cloudinary](https://wordpress.org/plugins/cloudinary-image-management-and-manipulation-in-the-cloud-cdn/) — Облачное управление, оптимизация и доставка изображений.
* [Photon](https://jetpack.com/support/photon/) — Сервис ускорения изображений через инфраструктуру WordPress.com (в составе Jetpack).
* [ILAB Media Tools](https://en-ca.wordpress.org/plugins/ilab-media-tools/) — Набор инструментов для расширенной работы с медиафайлами.
* [WP Offload S3](https://deliciousbrains.com/wp-offload-s3/) — Перенос медиабиблиотеки в Amazon S3 или DigitalOcean Spaces.
* [DADI CDN](https://github.com/dadi/cdn) — Self-hosted решение для манипуляции и доставки ассетов "на лету".
* [Tachyon](https://github.com/humanmade/tachyon-plugin) — Процессор изменения размеров изображений для работы с Amazon S3 и CDN.
* [CDN Linker](https://github.com/wmark/CDN-Linker) — Заменяет внутренние ссылки на ссылки с вашего CDN.
* [C3 Cloudfront Cache Controller](https://wordpress.org/plugins/c3-cloudfront-clear-cache/) — Очистка кэша CloudFront при публикации записей.
* [WP-Stateless](https://wordpress.org/plugins/wp-stateless/) — Хранение и отдача медиафайлов напрямую из Google Cloud Storage.
* [WP Azure offload](https://wordpress.org/plugins/wp-azure-offload/) — Автоматическое копирование медиа в облако Azure.

## 🖼 Оптимизация изображений
* [ShortPixel](https://wordpress.org/plugins/shortpixel-image-optimiser/) — Мощное сжатие изображений и поддержка WebP/AVIF.
* [Imagify](https://wordpress.org/plugins/imagify/) — Оптимизация изображений в один клик без потери качества.
* [EWWW Image Optimizer](https://wordpress.org/plugins/ewww-image-optimizer/) — Оптимизация на вашем сервере или через облако.
* [Smush](https://wordpress.org/plugins/wp-smushit/) — Популярный инструмент для сжатия и ленивой загрузки.

## 🗄 Оптимизация базы данных
* [WP-Optimize](https://wordpress.org/plugins/wp-optimize/) — Очистка базы данных, сжатие изображений и кэширование.
* [Advanced Database Cleaner](https://wordpress.org/plugins/advanced-database-cleaner/) — Глубокая очистка от ревизий, черновиков и осиротевших метаданных.

## 🔍 Отладка и анализ медленных запросов
* [Query Monitor](https://wordpress.org/plugins/query-monitor/) — Лучший инструмент для анализа запросов к БД, ошибок PHP и производительности хуков.
* [Debug Bar](https://wordpress.org/plugins/debug-bar/) — Панель отладки для анализа работы ядра WordPress.

## 📊 Сервисы для проверки производительности
* [Google PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) — Анализ скорости и рекомендации от Google.
* [GTmetrix](https://gtmetrix.com/) — Подробные отчеты о загрузке страниц.
* [WebPageTest](https://www.webpagetest.org/) — Профессиональное тестирование из разных локаций и браузеров.

---
*Для полного списка ресурсов посетите оригинальный репозиторий.*


