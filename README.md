Ansible-playbook по созданию RAID1 массива с помощью mdadm.
Установка проводилась на удаленный хост в Yandex.Cloud на Ubuntu 24.01
Изначально в систему было добавлено 4 виртуальных диска. RAID1 собирался из первых свободных.
Ниже представлен результат отработки playbook'a.
![lsblk_raid127](https://github.com/user-attachments/assets/211ddf6f-f68c-4db4-9719-48d0ad106a7e)
