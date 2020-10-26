# kode-test
Подзадачи:
1. Создание страниц, настройка роутинга
  Проблем не возникло. 
  Затрачено времени примерно 30 минут.

2. Верстка с адаптивом
  Проблем не возникло.
  Затрачено времени примерно 4 часа.


3. Реализация состояния приложения, запрос к api, отрисовка покемонов
  Для реализаии стейта были выбраны два хука: useReducer для управления логикой и зименения сосотяния и 
  useContext для доступа к стейту и возможности диспачить экшены из разных компонентов. При первой реализации 
  стейт был создан в компоненте App, в дальнейшем стейт был вененсен в отдельные файлы. Выполнялось параллельно с 
  реализацией запроса к api покемонов, отрисовкой их на странице покемонов и выбором контретного покемона дял просмотра.
  Сложности возникли с закрытием селектов при клике вне селекта, проблема отложена для решения на последних этапах.
  Затраче времени примерно 6 часов.

4. Валидация
  Для реализаии валидации была использована библиотека formik. Трудности возникли с использованием
  компонента формы и реализации валидации для динамичского количества инпутов, в связи с чем компонент был
  переделан на обычную разметку. 
  Затрачено времени примерно 4 часа.
  
5. Реализация пагинации
  Затрачено времени примерно 2-3 часа. Возникли сложности с решением реализации пагинации вместе с активыми фильтрами (селектами).
  Пагинация оставлена в текущем состоянии, решение проблемы отложено на оставшееся время после реалзиации модального окна и сессии пользователя.

6. сохранение сессии: ?