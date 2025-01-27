# Buzumurha Anastasiia
| Junior QA Tester  

**Навички та інструменти:**
- 🛠️ Інструменти: Postman, DevTools, Jira, TestRail, Git
- 🧪 Тестування: Функціональне, UI/UX, API;
- 📜 Навички: написання тест-кейсів, створення bug-репортів, аналіз вимог

**Контакти:** [LinkedIn](www.linkedin.com/in/anastasii-buzumurga) | [Email](nastiabuzumurga@gmail.com)

## Pet-project

https://docs.google.com/spreadsheets/d/1Fa5UB9SEHSWRn76yFbR97yVJb7TYhqCAaoh2DZL1n3s/edit?usp=sharing

## Приклади


## 🧪 **Test Cases(Ukrainian)**

### Приклад 1: Тестування форми реєстрації
| ID            | TC001                     |
|---------------|---------------------------|
| **Назва**     | Перевірка можливості успішного завантаження зображення в профіль. |
| **Передумови**| Користувач авторизований у системі. <br>2 Користувач знаходиться на сторінці редагування профілю. |
| **Кроки**     | 1. Перейти на сторінку редагування профілю. <br>2. Натиснути кнопку "Завантажити зображення." <br>3 Вибрати файл з локального пристрою (у форматі .jpg або .png). <br>4 Натиснути "Зберегти." |
| **Очікуваний результат** |Зображення успішно завантажується та відображається в профілі. |

### Приклад 2: Перевірка валідації полів
| ID            | TC002                     |
|---------------|---------------------------|
| **Назва**     | Перевірка роботи форми зворотного зв’язку. |
| **Передумови**| Користувач перебуває на сторінці "Контакти".|
| **Кроки**     | 1. Заповнити всі поля форми (ім’я, email, повідомлення).<br>2. Натиснути кнопку "Відправити." |
| **Очікуваний результат** | Форма успішно відправлена, відображається підтвердження. |

---
## 🧪 **Test Cases (English)**

### Example 3: Profile Update
| ID            | TC003                    |
|---------------|---------------------------|
| **Title**     | Verify that the user can successfully update their profile information. |
| **Precondition**| User is logged in. <br>2. User is on the "Profile" page. |
| **Steps**     | 1. Navigate to the "Profile" page. <br>2. Click on the "Edit" button. <br>3 Update the name, email, and phone number fields with valid data. <br>4 Click "Save." |
| **Expected results** | The profile is updated successfully, and a confirmation message is displayed. |

### Example 4: Profile Update
| ID            | TC004                    |
|---------------|---------------------------|
| **Title**     | Verify that the password reset functionality sends a reset link to the registered email. |
| **Precondition**| User is logged out. |
| **Steps**     | 1. Open the "Forgot Password" page. <br>2 Enter the registered email address in the input field. <br>3 Click "Send Reset Link." |
| **Expected results** | A confirmation message is displayed, and the reset link is sent to the provided email address. |

---

## 🐞 **Bug Reports(English)**

### Example 1: Broken pagination on the search results page.
| Поле              | Значення                          |
|--------------------|-----------------------------------|
| **ID**        | BUG005                           |
| **Priority**      | High                             |
| **Severity**    | Medium                            |
| **Description**          | Broken pagination on the search results page.|
| **Steps to Reproduce:** | 1. Open the website. <br>2. Perform a search using any keyword.<br>3. Scroll to the bottom of the results and click on "Next Page." |
| **Expected result** | The pagination works correctly, displaying the next set of results. |
| **Actual result** | The page reloads but displays the same results instead of moving to the next set of results. |

---

### Example 2: Missing tooltips for icons in the navigation bar.
| Поле              | Значення                          |
|--------------------|-----------------------------------|
| **ID**        | BUG006                           |
| **Priority**      | Medium                             |
| **Severity**    | Low                            |
| **Description**          | Missing tooltips for icons in the navigation bar.|
| **Steps to Reproduce:** | 1. Open the homepage. <br>2. Hover over the icons in the navigation bar. |
| **Expected result** | Tooltips are displayed for each icon, describing its functionality. |
| **Actual result** | No tooltips are displayed. |

---
## 🐞 **Bug Reports(Ukrainian)**

### Приклад 3: Некоректне відображення дат у списку оголошень.
| Поле              | Значення                          |
|--------------------|-----------------------------------|
| **ID бага**        | BUG007                           |
| **Пріоритет**      | High                           |
| **Серйозність**    | Medium                            |
| **Опис**          | Некоректне відображення дат у списку оголошень.|
| **Кроки для відтворення** | 1.Відкрити вебсайт. <br>2. Перейти до списку оголошень. <br>3. Перевірити поле "Дата публікації".  |
| **Очікуваний результат** | Дата відображається у форматі DD-MM-YYYY (наприклад, "23-12-2024")|
| **Фактичний результат** | Дата відображається у некоректному форматі (наприклад, "23-13-2024") |
