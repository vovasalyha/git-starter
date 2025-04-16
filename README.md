# Git
- [Що таке система контролю версій та чому це важливо?](https://git-scm.com/book/uk/v2/%d0%92%d1%81%d1%82%d1%83%d0%bf-%d0%9f%d1%80%d0%be-%d1%81%d0%b8%d1%81%d1%82%d0%b5%d0%bc%d1%83-%d0%ba%d0%be%d0%bd%d1%82%d1%80%d0%be%d0%bb%d1%8e-%d0%b2%d0%b5%d1%80%d1%81%d1%96%d0%b9)
- [Коротка історія створення Git](https://git-scm.com/book/uk/v2/%D0%92%D1%81%D1%82%D1%83%D0%BF-%D0%9A%D0%BE%D1%80%D0%BE%D1%82%D0%BA%D0%B0-%D1%96%D1%81%D1%82%D0%BE%D1%80%D1%96%D1%8F-Git)
- [Історія створення Git (довгочит, але дуже цікавий, рекомендую)](https://www.linuxjournal.com/content/git-origin-story)
- [Основи Git](https://git-scm.com/book/uk/v2/%D0%92%D1%81%D1%82%D1%83%D0%BF-%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D0%B8-Git)
- [Інсталяція Git](https://git-scm.com/book/uk/v2/%D0%92%D1%81%D1%82%D1%83%D0%BF-%D0%86%D0%BD%D1%81%D1%82%D0%B0%D0%BB%D1%8F%D1%86%D1%96%D1%8F-Git)
- [Початкове налаштування Git](https://git-scm.com/book/uk/v2/%D0%92%D1%81%D1%82%D1%83%D0%BF-%D0%9F%D0%BE%D1%87%D0%B0%D1%82%D0%BA%D0%BE%D0%B2%D0%B5-%D0%BD%D0%B0%D0%BB%D0%B0%D1%88%D1%82%D1%83%D0%B2%D0%B0%D0%BD%D0%BD%D1%8F-Git)
- [Три стани файлів в Git](https://git-scm.com/book/uk/v2/%D0%92%D1%81%D1%82%D1%83%D0%BF-%D0%A2%D1%80%D0%B8-%D1%81%D1%82%D0%B0%D0%BD%D0%B8)

## Основні команди Git
- [`git help`](https://git-scm.com/book/uk/v2/%D0%92%D1%81%D1%82%D1%83%D0%BF-%D0%9E%D1%82%D1%80%D0%B8%D0%BC%D0%B0%D0%BD%D0%BD%D1%8F-%D0%B4%D0%BE%D0%BF%D0%BE%D0%BC%D0%BE%D0%B3%D0%B8) - отримання довідки щодо команд Git
- [`git init`](https://git-scm.com/book/uk/v2/%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D0%B8-Git-%D0%A1%D1%82%D0%B2%D0%BE%D1%80%D0%B5%D0%BD%D0%BD%D1%8F-Git-%D1%81%D1%85%D0%BE%D0%B2%D0%B8%D1%89%D0%B0) - створення Git-сховища (репозиторія)
- [Запис змін до репозиторія](https://git-scm.com/book/uk/v2/%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D0%B8-Git-%D0%97%D0%B0%D0%BF%D0%B8%D1%81-%D0%B7%D0%BC%D1%96%D0%BD-%D0%B4%D0%BE-%D1%80%D0%B5%D0%BF%D0%BE%D0%B7%D0%B8%D1%82%D0%BE%D1%80%D1%96%D1%8F) - `git status`, `git add`, `git commit` - команди які використовуються найчастіше для перевірки та запису змін до репозиторія
- [`git log`](https://git-scm.com/book/uk/v2/%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D0%B8-Git-%D0%9F%D0%B5%D1%80%D0%B5%D0%B3%D0%BB%D1%8F%D0%B4-%D1%96%D1%81%D1%82%D0%BE%D1%80%D1%96%D1%97-%D0%BA%D0%BE%D0%BC%D1%96%D1%82%D1%96%D0%B2) - перегляд історії комітів
- [`git commit --amend`](https://git-scm.com/book/uk/v2/%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D0%B8-Git-%D0%A1%D0%BA%D0%B0%D1%81%D1%83%D0%B2%D0%B0%D0%BD%D0%BD%D1%8F-%D1%80%D0%B5%D1%87%D0%B5%D0%B9) - внесення змін до останнього коміту
- [`git checkout — <file>…​`](https://git-scm.com/book/uk/v2/%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D0%B8-Git-%D0%A1%D0%BA%D0%B0%D1%81%D1%83%D0%B2%D0%B0%D0%BD%D0%BD%D1%8F-%D1%80%D0%B5%D1%87%D0%B5%D0%B9) - скасування змін у зміненому файлі

## Синхронізація локального репозиторія з GitHub
- [`git remote`](https://git-scm.com/book/uk/v2/%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D0%B8-Git-%D0%92%D0%B7%D0%B0%D1%94%D0%BC%D0%BE%D0%B4%D1%96%D1%8F-%D0%B7-%D0%B2%D1%96%D0%B4%D0%B4%D0%B0%D0%BB%D0%B5%D0%BD%D0%B8%D0%BC%D0%B8-%D1%81%D1%85%D0%BE%D0%B2%D0%B8%D1%89%D0%B0%D0%BC%D0%B8) - налаштування комунікації з репозиторієм на віддаленому сервері (GitHub, GitLab etc.)
- [`git push`](https://git-scm.com/book/uk/v2/%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D0%B8-Git-%D0%92%D0%B7%D0%B0%D1%94%D0%BC%D0%BE%D0%B4%D1%96%D1%8F-%D0%B7-%D0%B2%D1%96%D0%B4%D0%B4%D0%B0%D0%BB%D0%B5%D0%BD%D0%B8%D0%BC%D0%B8-%D1%81%D1%85%D0%BE%D0%B2%D0%B8%D1%89%D0%B0%D0%BC%D0%B8) - відправка локальних змін на сервер
- [`git pull`](https://git-scm.com/book/uk/v2/%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D0%B8-Git-%D0%92%D0%B7%D0%B0%D1%94%D0%BC%D0%BE%D0%B4%D1%96%D1%8F-%D0%B7-%D0%B2%D1%96%D0%B4%D0%B4%D0%B0%D0%BB%D0%B5%D0%BD%D0%B8%D0%BC%D0%B8-%D1%81%D1%85%D0%BE%D0%B2%D0%B8%D1%89%D0%B0%D0%BC%D0%B8) - завантаження актуальних змін з серверу в локальний репозиторій
