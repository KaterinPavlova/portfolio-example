---
title: Руководство по началу работы
order: 0.3
---

После этого руководства вы сможете войти в систему, создать первый проект и пригласить коллег.

## Шаг 1. Войдите в систему

1. Откройте [app.taskboard.example.com](https://example.com).

2. Нажмите [cmd:Войти] в правом верхнем углу.

3. Введите email и пароль из письма-приглашения.

:::tip Первый вход

При первом входе система попросит сменить временный пароль. Выберите пароль длиной не менее 8 символов -- с буквами и цифрами.

:::

## Шаг 2. Настройте профиль

После входа вы попадёте в «Настройки профиля». Заполните:

| Поле         | Зачем нужно                                 |
|--------------|---------------------------------------------|
| Имя          | Отображается в комментариях и уведомлениях  |
| Аватар       | Помогает коллегам быстро вас найти          |
| Часовой пояс | Важно для корректного отображения дедлайнов |

Нажмите [cmd:Сохранить].

## Шаг 3. Создайте проект

1. На боковой панели нажмите [cmd:＋ Новый проект»].

2. Введите название -- например, «Запуск сайта».

3. Выберите шаблон:

   1. Канбан. Визуальная доска с колонками: «К выполнению», «В работе», «Готово». Подходит для команд, которые хотят видеть статус каждой задачи с первого взгляда.

   2. Список. Линейный список задач с сортировкой по дедлайну или приоритету. Подходит для личных задач и небольших проектов.

   3. Пустой. Начните с чистого листа и настройте структуру под себя.

4. Нажмите [cmd:Создать].

## Шаг 4. Добавьте задачи

В открывшемся проекте:

1. Нажмите [cmd:+ Добавить задачу] в нужной колонке.

2. Введите название задачи.

3. Нажмите [kbd:Enter].

Чтобы добавить детали -- кликните на задачу:

-  Дедлайн -- выберите дату в календаре.

-  Исполнитель -- назначьте участника проекта.

-  Метки -- категоризируйте задачу по теме.

-  Вложения -- прикрепите файлы до 100 МБ.

## Шаг 5. Пригласите коллег

1. Откройте «Настройки проекта» (значок ⚙️ рядом с названием).

2. Перейдите на вкладку «Участники».

3. Введите email коллеги.

4. Нажмите [cmd:Пригласить].

Коллега получит письмо со ссылкой для входа.

:::lab Роли участников

Выбирайте роль осознанно:

-  Редактор -- создаёт и изменяет задачи.

-  Наблюдатель -- только просмотр.

-  Администратор -- полный доступ, включая удаление проекта.

Роль администратора нельзя назначить внешнему подрядчику.

:::

## Готово! Что дальше?

-  🔔 [Настройте уведомления](#) -- выберите, о чём получать оповещения.

-  🔗 [Подключите Slack](#) -- обновления прямо в вашем канале.

-  ⌨️ [Горячие клавиши](#) -- работайте быстрее без мышки.

---

[html]

<div style="background: #ffffff; border: 1px solid #e8e8e8; border-radius: 12px; padding: 1.25rem 1.5rem; font-family: sans-serif; margin: 0 auto;">

  <div style="display: flex; align-items: center; gap: 10px; margin-bottom: 1rem;">
    <div style="width: 32px; height: 32px; border-radius: 50%; background: #eff6ff; display: flex; align-items: center; justify-content: center; flex-shrink: 0;">
      <svg width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="#3b82f6" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/></svg>
    </div>
    <p style="font-size: 15px; font-weight: 600; margin: 0; color: #111827;">Нужна помощь?</p>
  </div>

  <div style="display: flex; flex-direction: column;">

    <a href="#" style="display: flex; align-items: center; gap: 12px; padding: 10px 0; border-bottom: 1px solid #f3f4f6; text-decoration: none; color: inherit;">
      <div style="width: 32px; height: 32px; border-radius: 8px; background: #f9fafb; display: flex; align-items: center; justify-content: center; flex-shrink: 0;">
        <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="#6b7280" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/></svg>
      </div>
      <div style="flex: 1; min-width: 0;">
        <p style="margin: 0; font-size: 14px; font-weight: 500; color: #111827;">Чат поддержки</p>
        <p style="margin: 0; font-size: 12px; color: #6b7280;">Значок ? в правом нижнем углу</p>
      </div>
      <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="#d1d5db" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="9 18 15 12 9 6"/></svg>
    </a>

    <a href="mailto:support@taskboard.example.com" style="display: flex; align-items: center; gap: 12px; padding: 10px 0; border-bottom: 1px solid #f3f4f6; text-decoration: none; color: inherit;">
      <div style="width: 32px; height: 32px; border-radius: 8px; background: #f9fafb; display: flex; align-items: center; justify-content: center; flex-shrink: 0;">
        <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="#6b7280" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="4" width="20" height="16" rx="2"/><path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7"/></svg>
      </div>
      <div style="flex: 1; min-width: 0;">
        <p style="margin: 0; font-size: 14px; font-weight: 500; color: #111827;">Электронная почта</p>
        <p style="margin: 0; font-size: 12px; color: #6b7280; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;">support@taskboard.example.com</p>
      </div>
      <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="#d1d5db" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="9 18 15 12 9 6"/></svg>
    </a>

    <a href="#" style="display: flex; align-items: center; gap: 12px; padding: 10px 0; text-decoration: none; color: inherit;">
      <div style="width: 32px; height: 32px; border-radius: 8px; background: #f9fafb; display: flex; align-items: center; justify-content: center; flex-shrink: 0;">
        <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="#6b7280" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M4 19.5A2.5 2.5 0 0 1 6.5 17H20"/><path d="M6.5 2H20v20H6.5A2.5 2.5 0 0 1 4 19.5v-15A2.5 2.5 0 0 1 6.5 2z"/></svg>
      </div>
      <div style="flex: 1; min-width: 0;">
        <p style="margin: 0; font-size: 14px; font-weight: 500; color: #111827;">База знаний</p>
        <p style="margin: 0; font-size: 12px; color: #6b7280;">Статьи и инструкции</p>
      </div>
      <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="#d1d5db" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="9 18 15 12 9 6"/></svg>
    </a>

  </div>

  <div style="margin-top: 1rem; padding-top: 1rem; border-top: 1px solid #f3f4f6; display: flex; align-items: center; gap: 8px;">
    <div style="width: 6px; height: 6px; border-radius: 50%; background: #22c55e; flex-shrink: 0;"></div>
    <p style="margin: 0; font-size: 12px; color: #6b7280;">Среднее время ответа — <span style="color: #111827; font-weight: 500;">2 часа</span> в рабочие дни</p>
  </div>

</div>

[/html]