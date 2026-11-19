# Backlog после R0 ревью

## P1 для R0 завершения / R1 блокеры
- [ ] Выделить создание иверификацию certificate для всех направлений, подтвердить QR маршрут (R0 замечание было исправлено).
- [ ] PostgreSQL migration, production session storage, secure cookie/TLS, CSRF/origin защита, brute-force защита и журнал безопасности.
- [ ] Закрыть ISS-01/02/03/04/05 до реального коммерческого запуска.
- [ ] Полный набор course/version/question schema и API OpenAPI.
- [ ] Серверный RBAC: ученик, представитель организации, редактор, reviewer, admin; изоляция организации.
- [ ] Checkout, payment provider, signature verification, idempotency и refund flow после утверждения поставщиков/договоров.
- [ ] Полноценные уроки/тесты по 29 темам; источники и даты проверки для каждого операционного правила.
- [ ] PDF production design, revocation/reissue workflow и аудит.

## Backlog (не блокирует демонстрацию R0)
- [ ] Уведомления email и сброс пароля.
- [ ] Улучшить UX ошибок: inline-валидация, loading states, focus management для dialog.
- [ ] Макеты закрытых страниц LMS и администратора.
- [ ] B2B-заявка с серверным сохранением и антиспамом; сейчас демонстрационная mailto-ссылка.
- [ ] Дизайн-система и кроссбраузерная визуальная регрессия.
- [ ] Удалить Google Fonts remote dependency и локализовать шрифты.
- [ ] Добавить rate limits и автоматическую очистку просроченных сессий.
