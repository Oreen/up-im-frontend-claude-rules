# Структура frontend
- Корневая директория:
	- [package.json](frontend/package.json), [package-lock.json](frontend/package-lock.json)
	- [tsconfig.json](frontend/tsconfig.json), [next.config.js](frontend/next.config.js)
	- [next-env.d.ts](frontend/next-env.d.ts), [env.d.ts.ts](frontend/env.d.ts.ts)
	- [.eslintrc.json](frontend/.eslintrc.json)
- Папка [src/](frontend/src):
	- [src/app/](frontend/src/app): директория Next.js App Router с маршрутами и
	  серверными/клиентскими компонентами
	- [src/components/](frontend/src/components): переиспользуемые UI-компоненты с
	  модулями SCSS
	- [src/ui/](frontend/src/ui): базовые утилитарные UI-компоненты с
	  модулями SCSS
	- [src/styles/](frontend/src/styles): глобальные SCSS-файлы
	- [src/fonts/](frontend/src/fonts): шрифты проекта
	- [src/interfaces/](frontend/src/interfaces): определения TypeScript интерфейсов
	- [src/utils/](frontend/src/utils): вспомогательные утилиты
- Папка [public/](frontend/public): статические ресурсы (изображения, спрайты,
  favicon)
- Папка [.vscode/](frontend/.vscode): настройки редактора и дебаггера