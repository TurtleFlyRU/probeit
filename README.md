# probeit
ProbeIt -  G code generator for scanning a workpiece plane. Batch script for Windows and NCStudio.

probeit.bat - этот скрипт, в диалоговом режиме, создает файл с G кодом для сканирования плоскости заготовки
на портальном фрезере под управлением NCStudio.

log_parser.bat - этот скрипт копирует данные замеров из лог-файла NcStudio.log в новый файл, в формате подходящем для дальнейшей работы 
с утилитой G-Code Ripper.

probeitgcode.txt - Пример результата работы probeit.bat. Файл с G-кодом для загрузки в NCStudio и для проведения измерений заготовки.

001_result_surf_scan.txt - пример результата работы log_parser.bat.  Этот файл загружается в утилиту G-Code Ripper и на его основании
пересчитываются все задания, подготовленные, например, в АртКаме.

Для установки и начала работы скопируйте эти два файла в папку с конфигурацией вашего станка, которая находится в папке NcStudio.
В моём случае файлы размещены в папке по адресу C:\NCStudioV8\PCIMC-6A\config\6B_std
Работа проверена на Windows 7 32-bit и 64-bit, в NcStudio 8.299 и G-Code Ripper 017

Перед началом измерения заготовки, запустите симуляцию, изучите результаты, проверьте окно сообщений на предмет ошибок.
Потренируйтесь на бросовом материале. 
Эти два скрипта являются продолжением вот этой работы https://www.cnc-club.ru/forum/viewtopic.php?f=156&t=25772&p=535037#p535037
и позволяют в разы ускорить описаный способ.

ВНИМАНИЕ! Вы используете эти файлы на свой страх и риск. Я не несу никакой отвественности за результаты работы этих двух скриптов.
Поддержка пользователей не осуществляется. Свои вопросы Вы можете задавать тут https://www.cnc-club.ru/forum/viewtopic.php?f=156&t=25772&p=535037#p535037
