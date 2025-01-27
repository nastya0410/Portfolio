# Portfolio
| Junior QA Tester  

**Навички та інструменти:**
- 🛠️ Інструменти: Postman, DevTools, Jira, TestRail, Git
- 🧪 Тестування: Функціональне, UI/UX, API;
- 📜 Навички: написання тест-кейсів, створення bug-репортів, аналіз вимог

**Контакти:** [LinkedIn](www.linkedin.com/in/anastasii-buzumurga) | [Email](nastiabuzumurga@gmail.com)

## Pet-project

https://docs.google.com/spreadsheets/d/1Fa5UB9SEHSWRn76yFbR97yVJb7TYhqCAaoh2DZL1n3s/edit?usp=sharing

## Приклади


## 🧪 **Test Cases**

### Приклад 1: Тестування форми реєстрації
| ID            | TC001                     |
|---------------|---------------------------|
| **Назва**     | Перевірка успішної реєстрації з валідними даними |
| **Передумови**| Відкрити форму реєстрації на вебсайті |
| **Кроки**     | 1. Ввести валідні дані (ім'я, email, пароль).<br>2. Натиснути кнопку "Зареєструватись". |
| **Очікуваний результат** | Система перенаправляє користувача на головну сторінку із повідомленням "Реєстрація успішна". |

### Приклад 2: Перевірка валідації полів
| ID            | TC002                     |
|---------------|---------------------------|
| **Назва**     | Валідація обов’язкових полів у формі реєстрації |
| **Передумови**| Відкрити форму реєстрації на вебсайті |
| **Кроки**     | 1. Залишити всі поля порожніми.<br>2. Натиснути кнопку "Зареєструватись". |
| **Очікуваний результат** | Система показує помилки біля всіх обов’язкових полів ("Це поле є обов'язковим"). |


---

## 🐞 **Bug Reports**

### Приклад 1: Некоректна валідація email
| Поле              | Значення                          |
|--------------------|-----------------------------------|
| **ID бага**        | BUG001                           |
| **Пріоритет**      | High                             |
| **Серйозність**    | Major                            |
| **Опис**          | При введенні некоректного email (без символу "@") система дозволяє завершити реєстрацію. |
| **Кроки для відтворення** | 1. Відкрити форму реєстрації.<br>2. Ввести "testemail.com" у поле email.<br>3. Натиснути "Зареєструватись". |
| **Очікуваний результат** | Система повинна відобразити помилку: "Некоректний формат email". |
| **Фактичний результат** | Реєстрація успішна. |


### Приклад 2: Кнопка "Зареєструватись" неактивна
| Поле              | Значення                          |
|--------------------|-----------------------------------|
| **ID бага**        | BUG002                           |
| **Пріоритет**      | Medium                           |
| **Серйозність**    | Minor                            |
| **Опис**          | Кнопка "Зареєструватись" залишається неактивною, навіть після заповнення всіх полів. |
| **Кроки для відтворення** | 1. Відкрити форму реєстрації.<br>2. Ввести валідні дані в усі поля.<br>3. Перевірити стан кнопки. |
| **Очікуваний результат** | Кнопка "Зареєструватись" має стати активною після заповнення полів. |
| **Фактичний результат** | Кнопка залишається неактивною. |
