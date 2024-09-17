# Домашнє завдання: Створення криптогаманця на основі Chrome Extension

## Опис

Це домашнє завдання спрямоване на вивчення основ роботи з криптогаманцями та розширеннями для браузера Chrome. Завдання включає:

1. Огляд криптогаманців і принципів їхньої роботи.
2. Огляд роботи Chrome extensions та створення власного розширення.
3. Додавання публічного ключа для криптогаманця у вигляді інпуту в створеному розширенні.

## Покрокові інструкції

### 1. Прочитайте статті для розуміння теми

- **Про криптогаманці:** Ознайомтеся з основними концепціями роботи криптогаманців за допомогою [цієї статті](https://solana.com/developers/guides/intro/wallets-explained).
- **Про Chrome Extensions:** Прочитайте [цю статтю](https://dev.to/sayan11/how-chrome-extensions-work-54bo) для розуміння, як працюють Chrome extensions.

> Якщо ви хочете практично зрозуміти, як працюють Chrome extensions, рекомендується пройти цей [гайд](https://hackernoon.com/how-to-create-a-chrome-extension-with-react) і створити власне розширення.

### 2. Збір репозиторію та запуск

1. Завантажте або склонуйте репозиторій з темплейтом під це завдання.
2. Встановіть залежності командою:

   ```
   npm install
   ```

3. Для розробки використовуйте команду:

   ```
   npm start
   ```

   Ця команда дозволить вам запустити проект у режимі hot-reload для зручної розробки.

4. Для створення білда використовуйте команду:

   ```
   npm run build
   ```

### 3. Додавання функціоналу гаманця

На сторінці гаманця додайте інпут, який прийматиме публічний ключ користувача. Використовуйте цей ключ для генерації криптографічної адреси.

1. Додайте HTML-елемент `<input>` для введення публічного ключа.
2. Використовуйте бібліотеки Solana для роботи з публічними ключами та генерації адреси.
3. Перевірте, чи коректно працює функція обробки ключів.

### 4. Рекомендації

- Якщо зіткнетеся з проблемами, пов'язаними з поліфілами або несумісностями, звертайтеся до чату для допомоги.
- Для роботи з Solana використовуйте бібліотеки, які ви вже опанували під час попередніх лабораторних робіт.

## Додаткова інформація

- Для кращого розуміння роботи гаманців і безпеки рекомендується ознайомитися з криптографічними концепціями.
- Будьте готові до тестування вашого розширення в браузері Chrome після білду.
