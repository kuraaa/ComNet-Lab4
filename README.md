# NSTU ComNet 
#Lab 4 (Анализ структуры кадра/фрейма технологии Ethernet)
#Task
#Разработать и отладить программу, выполняющую  анализ потока кадров. Потоки кадров представлены в виде файлов двоичного формата, место нахождения которых уточняется у преподавателя. В кадрах отсутствует преамбула и контрольная сумма, для исходящего кадра длина может быть мен   ше минимальной. Каждая бригада выполняет обработку одного файла с именем ethersXX.bin, где ХХ – номер бригады. 
При выполнении работы в дистанционном режиме в обязательном порядке выполнить анализ файлов ethers06.bin и ethers07.bin.
Требования к программе:
-•	предусмотреть возможность ввода имени файла с клавиатуры; 
-•	обеспечить вывод на экран по каждому кадру: номер, размер, тип, IP- адресов (основную информацию заголовка IP-пакета), MAC- адресов (основную информацию заголовка кадра); также необходимо вывести итоговые результаты обработки: общее число обработанных кадров и число кадров каждого типа (IP, ARP, Novell, SNAP и т.д.);
Алгоритм определения формата кадров можно найти в Приложении 2. Там же находится вся необходимая информация по форматам кадров Ethernet, IP- пакетам и TCP-сегментам.
