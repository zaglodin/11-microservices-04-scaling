
# Домашнее задание к занятию "11.04 Микросервисы: масштабирование"

Вы работаете в крупной компанию, которая строит систему на основе микросервисной архитектуры.
Вам как DevOps специалисту необходимо выдвинуть предложение по организации инфраструктуры, для разработки и эксплуатации.

## Задача 1: Кластеризация

Под указанные требования хорошо подходит Kubernetes в связке спродуктами Hashicorp.

- Поддержка контейнеров; Kubernetes
- Обеспечивать обнаружение сервисов и маршрутизацию запросов; Consul
- Обеспечивать возможность горизонтального масштабирования; Kubernetes и HPA
- Обеспечивать возможность автоматического масштабирования; Terraform
- Обеспечивать явное разделение ресурсов доступных извне и внутри системы; Boundary 
- Обеспечивать возможность конфигурировать приложения с помощью переменных среды, в том числе с возможностью безопасного хранения чувствительных данных таких как пароли, ключи доступа, ключи шифрования и т.п. Vault