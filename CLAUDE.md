# divbyone-main

## CI и расходы GitHub (Alex, 2026-11-12)

Никаких платных трат на GitHub. Actions не запускаются автоматически на push и PR. Если появится CI, проверка идёт один раз, при ручном деплое (`workflow_dispatch`, только после «деплой» от Alex). Перед push всё проверяется локально. Новые workflow с триггерами push, pull_request, schedule не добавлять.
