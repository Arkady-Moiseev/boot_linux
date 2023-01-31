# Загрузка Linux
1. Попасть в систему без пароля несколокими способами
2. Установить систему с LVM, после чего переименовать VG
3. Добавить модуль в initrd
________________________________________________________________________________
1. Попасть в систему без пароля несколокими способами

Для получения доступа необходимо открыть GUI VirtualBox (или другой системы
виртуализации), запустить виртуальную машину и при выборе ядра для загрузки нажать e - в
данном контексте edit. Попадаем в окно где мы можем изменить параметры загрузки:

1.1 init=/bin/sh

![img_1](https://github.com/Arkady1996/boot_linux/blob/main/1.png)
![img_11](https://github.com/Arkady1996/boot_linux/blob/main/11.png)

1.2 rd.break

![img_2](https://github.com/Arkady1996/boot_linux/blob/main/2.png)
![img_21](https://github.com/Arkady1996/boot_linux/blob/main/21.png)
![img_22](https://github.com/Arkady1996/boot_linux/blob/main/22.png)

1.3 rw init=/sysroot/bin/sh

![img_23](https://github.com/Arkady1996/boot_linux/blob/main/23.png)
![img_24](https://github.com/Arkady1996/boot_linux/blob/main/24.png)

2. Установить систему с LVM, после чего переименовать VG

![img_3](https://github.com/Arkady1996/boot_linux/blob/main/3.png)
![img_31](https://github.com/Arkady1996/boot_linux/blob/main/31.png)
![img_32](https://github.com/Arkady1996/boot_linux/blob/main/32.png)

3. Добавить модуль в initrd

![img_33](https://github.com/Arkady1996/boot_linux/blob/main/33.png)
![img_34](https://github.com/Arkady1996/boot_linux/blob/main/34.png)
