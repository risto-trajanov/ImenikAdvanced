# ImenikAdvanced
Advanced Imenik
Телефонски именик
Да се напише програма која ќе биде телефонски именик. Во телефонскиот именик има листа од контакти за кои се чуваат: телефонски број и име. На почетокот на програмата, во телефонскиот именик има внесено 5 контакти. Програмата ќе ги испише 5те контакти во конзола и ќе праша дали сакаме да измениме број на некој контакт.
- Ако сакаме, треба да го внесеме индексот на контактот што сакаме да го смениме во листата и новиот телефонски број, одвоени со празно место. Програмата тогаш го зема контактот на тој индекс, го поставува новиот број и повторно ги печати сите контакти како на почетокот на програмата.
- Програмата не завршува додека не внесеме “done” и цело време ни дозволува да менуваме детали за контактите.
Пример:
enter input in format: 'index newphonenumber' to update phone contact. note the space
if you are done with updating, type 'done'
0) Aleksandar: 070123456
1) Marko: 078567890
2) Ivana: 075246810
3) Monika: 076357911
4) Kristijan: 077951862
1 123456
------------------------------------------------
enter input in format: 'index newphonenumber' to update phone contact. note the space
if you are done with updating, type 'done'
0) Aleksandar: 070123456
1) Marko: 123456
2) Ivana: 075246810
3) Monika: 076357911
4) Kristijan: 077951862

Проширување
1) Да се прошири програмата така што ако внесеното не е во бараниот формат ‘индекс нов_телефонски_број’, тогаш програмата
○ пишува порака дека внесеното е грешно
○ го печати телефонскиот именик повторно и на корисникот му дава да внесе повторно се додека не внесе точно.
2) Да се прошири програмата така што, ако внесениот индекс не е број, или во листата со контакти нема елемент со тој индекс, тогаш програмата
○ пишува дека внесеното е грешно
○ го печати телефонскиот именик повторно и на корисникот му дава да внесе повторно се додека не внесе точно
3) Да се прошири програмата така што откога ќе се внесе индексот на контактот и новиот број, да праша дали сакаме да го смениме и името на контактот.
○ Ако внесеме било што што не е yes, програмата не го менува името на контактот туку само телефонскиот број
○ Ако внесеме yes, наредно не прашува кое е новото име на контактот.
i) Името на контактот не смее да биде празен стринг или сочинето од празни места. Смее да биде друго било што.
○ Откога ќе внесеме точно име, програмата го променува контактот на првично внесениот индекс со нов телефон и ново име.
4) Да се прошири програмата така што кога ќе започне ќе не праша дали сакаме да го пополниме именикот сами или сакаме да се пополни со 5те првични вредности кои постоеа до сега.
○ Ако внесеме било што, ќе го пополни со 5те првични вредности
○ Ако внесеме ‘yes’, програмата ќе не прашува да внесуваме контакти во именикот се додека не внесеме “done”:
i) програмата ќе не праша за името на конактот
(1) Ако внесеме празно име, програмата ќе напише порака дека имаме грешно име и ќе продокжи со додавање на наредниот контакт
ii) Ако е внесено точно име за контактот, ќе не праша за телефонскиот број
(1) Ако внесеме празно за телефонскиот број, програмата ќе напише порака дека имаме грешен број и ќе продолжи со додавање на наредниот контакт
○ Откгоа именикот ќе биде пополнет, програмата продолжува како претходно, со прашање дали сакаме да измениме некој контакт.
