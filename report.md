# Отчет по лабораторной работе №3

Создаем три виртуальные машины: A, B, C

![6](https://github.com/user-attachments/assets/44921f59-676c-4d53-9fbe-4ed85ee8cbe7)

Создаем сеть local_net

![8](https://github.com/user-attachments/assets/c3227aeb-f30c-4781-84a1-c0dbf9e86e77)

Проверяем доступ в сеть Интернет машины A

![1](https://github.com/user-attachments/assets/31193051-d027-466a-af93-979ef2e488b4)

Проверяем доступ из машины A в B

![2](https://github.com/user-attachments/assets/b132ad83-0b36-4201-b990-99f2f9890d9c)


Проверяем доступ из машины A в C

![9](https://github.com/user-attachments/assets/b832b214-bf59-4ffd-a638-a318bade0da4)


Запрещаем доступ из B в C

```bash
sudo ufw deny from 10.0.2.7
sudo ufw enable
```


![4](https://github.com/user-attachments/assets/11fade62-bf5d-44cd-ab51-294a011d57aa)

Все машины

![5](https://github.com/user-attachments/assets/c79dde07-e080-4da7-a21c-0593be24c14f)





