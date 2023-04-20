### Huananzhi X99-TF
### BIOS 2020/05/25 (GHX99015)

    + При использовании серверной (ECC) памяти активна функция коррекции ошибок
    + Тайминг Command Rate (CR) может принимать любое заданное значение от 1 до 3

Данный биос совместим с [Ultimate Patcher Tool](https://github.com/Koshak1013/HuananzhiX99_BIOS_mods#Ultimate-Patcher-Tool) (рекомендуется последняя версия программы)

Также доступна версия с отключённым бипером

*v011:* 
* + добавлена поддержка Resizable BAR (SAM)
* обновлено лого на официальное (взято из новой версии биос) и включено его отображение по умолчанию
* добавлено +3.3V в HardwareMonitor
* основа биоса GHX99015
* обновлены микрокоды и Realtek Boot Agent GE, добавлен Realtek UNDI Driver, удалено лишнее (Matrox GOP и Intel Gbit)
* настроено управление оборотами вентилятора процессора (<45°=30%/>80°=100%)
* исправлена дата биоса в его настройках
* пункты меню "Memory Frequency" и "OverClocking Feature" больше не будут пропадать
* открыты пункты меню "Memory Thermal", "CPU C State Control", "Program PP0_CURT_CFG_CTRL_MSR", "SOCKET RAPL Config", "Per-Socket Configuration" и "PCI Subsystem Settings"
* BCLK 100.00MHz (0.00% SSC)

*v010:*
* + открыт пункт меню "Memory Thermal"
* - убрана включенная ранее поддержка ASPM, т.к. наблюдалась проблема совместимости с видеокартами серии AMD Radeon RX 6000
* обновлено лого на официальное (взято из новой версии биос) и включено его отображение по умолчанию
* добавлено +3.3V в HardwareMonitor
* основа биоса GHX99015
* обновлены микрокоды и Realtek Boot Agent GE, добавлен Realtek UNDI Driver, удалено лишнее (Matrox GOP и Intel Gbit)
* настроено управление оборотами вентилятора процессора (<45°=30%/>80°=100%)
* исправлена дата биоса в его настройках
* пункты меню "Memory Frequency" и "OverClocking Feature" больше не будут пропадать
* открыты пункты меню "CPU C State Control", "Program PP0_CURT_CFG_CTRL_MSR", "SOCKET RAPL Config", "Per-Socket Configuration" и "PCI Subsystem Settings"
* BCLK 100.00MHz (0.00% SSC)

*v009:*
* - убран фикс шины PCI-E, т.к. некоторые видеокарты вообще перестали стартовать
* обновлено лого на официальное (взято из новой версии биос) и включено его отображение по умолчанию
* добавлено +3.3V в HardwareMonitor
* основа биоса GHX99015
* включена поддержка ASPM
* обновлены микрокоды и Realtek Boot Agent GE, добавлен Realtek UNDI Driver, удалено лишнее (Matrox GOP и Intel Gbit)
* настроено управление оборотами вентилятора процессора (<45°=30%/>80°=100%)
* исправлена дата биоса в его настройках
* пункты меню "Memory Frequency" и "OverClocking Feature" больше не будут пропадать
* открыты пункты меню "CPU C State Control", "Program PP0_CURT_CFG_CTRL_MSR", "SOCKET RAPL Config", "Per-Socket Configuration" и "PCI Subsystem Settings"
* BCLK 100.00MHz (0.00% SSC)

*v008:*
* + обновлено лого на официальное (взято из новой версии биос) и включено его отображение по умолчанию
* + исправлена проблема с шиной PCI-E, когда она работала в режиме 1.1 на некоторых видеокартах *спасибо Снуки Лоу*
* + микрокоды для V3 и V4 обновлены до актуальных версий
* + также доступна версия с отключённым бипером
* добавлено +3.3V в HardwareMonitor
* основа биоса GHX99015
* включена поддержка ASPM
* обновлены микрокоды и Realtek Boot Agent GE, добавлен Realtek UNDI Driver, удалено лишнее (Matrox GOP и Intel Gbit)
* настроено управление оборотами вентилятора процессора (<45°=30%/>80°=100%)
* исправлена дата биоса в его настройках
* пункты меню "Memory Frequency" и "OverClocking Feature" больше не будут пропадать
* открыты пункты меню "CPU C State Control", "Program PP0_CURT_CFG_CTRL_MSR", "SOCKET RAPL Config", "Per-Socket Configuration" и "PCI Subsystem Settings"
* BCLK 100.00MHz (0.00% SSC)

*v007:*
* + микрокод для V4 и Realtek UNDI Driver обновлены до актуальных версий
* + открыты пункты меню "SOCKET RAPL Config", "Per-Socket Configuration" и "PCI Subsystem Settings" *спасибо Pavlon и MacArrow*
* добавлено +3.3V в HardwareMonitor
* основа биоса GHX99015
* включена поддержка ASPM
* пункт меню "OverClocking Feature" больше не будет пропадать
* обновлены микрокоды и Realtek Boot Agent GE, добавлен Realtek UNDI Driver, удалено лишнее (Matrox GOP и Intel Gbit)
* настроено управление оборотами вентилятора процессора (<45°=30%/>80°=100%)
* исправлена дата биоса в его настройках
* открыт пункт меню "Program PP0_CURT_CFG_CTRL_MSR"
* пункт меню "Memory Frequency" больше не будет пропадать
* открыт пункт меню "CPU C State Control"
* BCLK 100.00MHz (0.00% SSC)

*v006:*
* + добавлено +3.3V в HardwareMonitor
* + основа биоса GHX99015 *спасибо v111*
* + включена поддержка ASPM
* + пункт меню "OverClocking Feature" больше не будет пропадать *спасибо Vitaliy Pukhov*
* обновлены микрокоды и Realtek Boot Agent GE, добавлен Realtek UNDI Driver, удалено лишнее (Matrox GOP и Intel Gbit)
* настроено управление оборотами вентилятора процессора (<45°=30%/>80°=100%)
* исправлена дата биоса в его настройках
* открыт пункт меню "Program PP0_CURT_CFG_CTRL_MSR"
* пункт меню "Memory Frequency" больше не будет пропадать
* открыт пункт меню "CPU C State Control"
* BCLK 100.00MHz (0.00% SSC)

*v005:*
* + обновлены микрокоды и Realtek Boot Agent GE, добавлен Realtek UNDI Driver, удалено лишнее (Matrox GOP и Intel Gbit) *спасибо v111*
* настроено управление оборотами вентилятора процессора (<45°=30%/>80°=100%)
* исправлена дата биоса в его настройках
* открыт пункт меню "Program PP0_CURT_CFG_CTRL_MSR"
* пункт меню "Memory Frequency" больше не будет пропадать
* открыт пункт меню "CPU C State Control"
* BCLK 100.00MHz (0.00% SSC)

*v004:*
* + настроено управление оборотами вентилятора процессора (<45°=30%/>80°=100%) *спасибо mozg13 и v111*
* + исправлена дата биоса в его настройках
* открыт пункт меню "Program PP0_CURT_CFG_CTRL_MSR"
* пункт меню "Memory Frequency" больше не будет пропадать
* открыт пункт меню "CPU C State Control"
* BCLK 100.00MHz (0.00% SSC)

*v003:*
* + открыт пункт меню "Program PP0_CURT_CFG_CTRL_MSR"
* + пункт меню "Memory Frequency" больше не будет пропадать
* открыт пункт меню "CPU C State Control"
* BCLK 100.00MHz (0.00% SSC)

*v002:*
* + открыт пункт меню "CPU C State Control"
* BCLK 100.00MHz (0.00% SSC)

*v001:*
* + BCLK 100.00MHz (0.00% SSC) *спасибо iEngineer*
