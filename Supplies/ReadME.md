# Полезная информация
1. https://www.reddit.com/r/ArmaReforger/comments/1jw4fr3/understanding_how_supplies_grant_xp_in_13/
2. https://discord.com/channels/105462288051380224/1356309674001043586/1356309674001043586
3. https://discord.com/channels/105462288051380224/1358054264504717322


# Логика работы
1. Радиус базы не влияет на радиус поиска припасов в главной палатке
2. На карте отображается кол-во припасов, которые видит компонент _SCR_ResourceComponent_
   - Consumers -> SCR_ResourceConsumer -> Resource Range -> меняем значение со 100 на другое и видим, что значение на карте меняется
3. 
