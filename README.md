# Модуль добавляет хендлер-методы для обработчиков событий связанных сущностей сделка и эл-нт инфоблока тип список

otus.syncdealiblock - модуль для Bitrix24, при установке, регистрирует хендлер-методы для сущностей сделка и элемент инфоблока тип список.

Для Сделки CRM_DEAL
- OnBeforeCrmDealAdd
- OnAfterCrmDealAdd
 - OnBeforeCrmDealUpdate
- OnBeforeCrmDealDelete
- OnAfterCrmDealDelete

Для эл-та инфоблока
- OnBeforeIBlockElementAdd
- OnAfterIBlockElementAdd
- OnBeforeIBlockElementUpdate
- OnBeforeIBlockElementDelete
- OnAfterIBlockElementDelete

Хендлер-методы обеих связанных сущностей, реализуют синхронизацию изменений в полях и св-ствах (cумма и ответственный), 
а также создают и удаляют связанную сущность.
Т.е. если создается Сделка то по ней генерируется и заявка (эл-нт инфоблока) и наоборот.

---

### Установка
Модуль нужно скопировать в директорию /local/modules и затем произвести установку из админки

---

- [Видео демонстрация работы #1](https://youtu.be/9OrJly_QUQA)
- [Видео демонстрация работы #2](https://youtu.be/Fs6Q5-aefAs)

