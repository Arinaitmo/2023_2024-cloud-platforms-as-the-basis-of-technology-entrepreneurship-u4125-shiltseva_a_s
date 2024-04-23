University: [ITMO University](https://itmo.ru/ru/)
Faculty: [FICT](https://fict.itmo.ru)
Course: [Cloud platforms as the basis of technology entrepreneurship](https://) ADD link
Year: 2023/2024
Group: U4125
Author: Shiltseva Arina Sergeevna
Lab: Lab1
Date of create: 23.04.2024
Date of finished: 

Отчет по лабороторной работе №1 

Зайдити в вкладку IAM, создайть service account с ролью Storage Admin
![Снимок экрана 2024-04-23 153315](https://github.com/Arinaitmo/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-shiltseva_a_s/assets/164926878/845665f2-689a-4416-a88e-36782438f423)
![Снимок экрана 2024-04-23 153455](https://github.com/Arinaitmo/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-shiltseva_a_s/assets/164926878/1cb9f2be-b2bf-443e-b12f-6d5bd5156b7a)
![Снимок экрана 2024-04-23 153732](https://github.com/Arinaitmo/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-shiltseva_a_s/assets/164926878/616c956c-c5ae-40cc-9ab8-a66cecd2ca94)
Создать минимальный compute engine (виртуальную машину) с Machine type e2-micro в режиме spot
![Снимок экрана 2024-04-23 154335](https://github.com/Arinaitmo/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-shiltseva_a_s/assets/164926878/4f4b3bf7-7fac-414a-8d72-877ab8c75b45)
![Снимок экрана 2024-04-23 154348](https://github.com/Arinaitmo/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-shiltseva_a_s/assets/164926878/7ad73eaa-64d9-49aa-a59c-5e9ff1dfc15c)
![Снимок экрана 2024-04-23 154504](https://github.com/Arinaitmo/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-shiltseva_a_s/assets/164926878/835803ae-741c-4bb8-b571-7e1db39d354f)
![Снимок экрана 2024-04-23 154625](https://github.com/Arinaitmo/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-shiltseva_a_s/assets/164926878/85c6e54a-b531-4177-8c6d-28f90de5a0ba)
С помощью утилиты gsutils найден бакет lab1-bucket-itmo и скопированы 3 файла в локальную папку на VM. 
![Снимок экрана 2024-04-23 162154](https://github.com/Arinaitmo/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-shiltseva_a_s/assets/164926878/66de93ec-bea6-4508-9013-589576578788)
![Снимок экрана 2024-04-23 163335](https://github.com/Arinaitmo/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-shiltseva_a_s/assets/164926878/724c5908-fef7-4ee2-ac2a-b83a6a74d1a0)
![Снимок экрана 2024-04-23 163606](https://github.com/Arinaitmo/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-shiltseva_a_s/assets/164926878/bde30999-0fe4-457e-87d2-1ff3fb6467e1)
![Снимок экрана 2024-04-23 163915](https://github.com/Arinaitmo/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-shiltseva_a_s/assets/164926878/ebf304d3-fd57-4a17-a6ca-00ea1a905955)
![Снимок экрана 2024-04-23 163925](https://github.com/Arinaitmo/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-shiltseva_a_s/assets/164926878/58a4ee2d-a403-4d2f-972b-81e81270a449)
![Снимок экрана 2024-04-23 163940](https://github.com/Arinaitmo/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-shiltseva_a_s/assets/164926878/e3d06655-41d1-4583-a07b-cfce2fdb76ce)
![Снимок экрана 2024-04-23 163952](https://github.com/Arinaitmo/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-shiltseva_a_s/assets/164926878/d4dbe3a5-995d-4f6f-91d0-37a5fcb4492d)
Поменяйть права доступа = service account с Storage Admin на Compute Viewer
![Снимок экрана 2024-04-23 164141](https://github.com/Arinaitmo/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-shiltseva_a_s/assets/164926878/dbac071c-5fef-4bb7-93ab-e4d22dcfb6e9)
![Снимок экрана 2024-04-23 164612](https://github.com/Arinaitmo/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-shiltseva_a_s/assets/164926878/de5c756a-9aa0-494c-aa18-5b0dbcb01dab)
![Снимок экрана 2024-04-23 164743](https://github.com/Arinaitmo/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-shiltseva_a_s/assets/164926878/3c235c7b-325a-4e74-8850-93ae422a56eb)
![Снимок экрана 2024-04-23 164852](https://github.com/Arinaitmo/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-shiltseva_a_s/assets/164926878/bdf74fe4-49f3-4d45-8133-7148020853ce)
![Снимок экрана 2024-04-23 165029](https://github.com/Arinaitmo/2023_2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-shiltseva_a_s/assets/164926878/2a0932cb-5a87-41b6-8f94-acb31d968fdc)
Можно сделать вывод что разные роль Compute Viewer дает ограниченное право доступа, когда Storage Admin роль предоставляет полный контроль над объектами в хранилище.
