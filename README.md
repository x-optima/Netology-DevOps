# Netology-DevOps — портфолио

Практические DevOps-проекты за 2025–2026: инфраструктура в облаке, автоматизация, CI/CD, мониторинг, базы данных, отказоустойчивость и безопасность.

**59 репозиториев** на GitHub ([все](https://github.com/x-optima?tab=repositories)) · **56 собственных** · **автор:** [Виталий · x-optima](https://github.com/x-optima/x-optima)

---

## Навигация

| Раздел | Ссылка |
|--------|--------|
| Ключевые проекты | [Ключевые проекты](#ключевые-проекты) |
| Terraform / IaC | [Terraform / IaC](#terraform--iac) |
| Ansible | [Ansible](#ansible) |
| CI/CD и Git | [CI/CD и Git](#cicd-и-git) |
| Мониторинг и логи | [Мониторинг и логи](#мониторинг-и-логи) |
| БД, отказоустойчивость, backup | [PostgreSQL и SQL](#postgresql-и-sql), [HA / DR / Backup](#ha--dr--backup) |

---

## Стек портфолио

| Область | Технологии |
|---------|------------|
| Облако / IaC | Yandex Cloud, Terraform, Ansible |
| CI/CD | GitLab CI, TeamCity, Jenkins, GitHub Actions |
| Контейнеры / HA | Docker, Compose, HAProxy, Keepalived |
| Мониторинг и логи | Prometheus, Grafana, Zabbix, ELK, Filebeat, Vector, Alertmanager, TICK |
| Базы данных | PostgreSQL, MySQL, Redis, RabbitMQ, ClickHouse |
| Безопасность | hardening хоста, SSH, firewall, fail2ban |
| ОС / скрипты | Linux, Bash, Python, C++ |

---

## Ключевые проекты

Стенды полного цикла: облако, CI/CD, мониторинг, БД, HA.

| Область | Репозиторий | Что сделано | Навыки |
|---------|-------------|-------------|--------|
| IaC | [terraform6](https://github.com/x-optima/terraform6) | Полный стенд в YC: приложение, БД, секреты, удалённый state | Terraform · YC · Lockbox · Ansible · Container Registry |
| CI/CD | [gitlab-yc](https://github.com/x-optima/gitlab-yc) | GitLab в Docker на ВМ в YC: Terraform + Ansible | GitLab · Terraform · Ansible · YC |
| CI/CD | [teamcity](https://github.com/x-optima/teamcity) | TeamCity + агент + Nexus в YC: Maven test/deploy по ветке | TeamCity · Nexus · Terraform · Ansible · YC |
| Мониторинг | [apm](https://github.com/x-optima/apm) | Мониторинг парка ТС: метрики, дашборды, алерты | Prometheus · Grafana · MQTT · Alertmanager · Docker Compose |
| Мониторинг | [monitoring4](https://github.com/x-optima/monitoring4) | Prometheus, Grafana, Alertmanager на ВМ в YC | Prometheus · Grafana · Terraform · Ansible · YC |
| Ansible | [ansible3](https://github.com/x-optima/ansible3) | ClickHouse + Vector + LightHouse в облаке | Ansible · ClickHouse · Vector · LightHouse · YC |
| HA | [cluster](https://github.com/x-optima/cluster) | Балансировка нагрузки между сервисами | HAProxy · Ansible · Terraform · YC |
| MySQL | [replica1](https://github.com/x-optima/replica1) | Master-slave репликация в Docker Compose | MySQL · replication |
| PostgreSQL | [sql2](https://github.com/x-optima/sql2) | Оптимизация тяжёлого JOIN-запроса | EXPLAIN ANALYZE · оптимизация запросов |
| Backup | [dbbackup](https://github.com/x-optima/dbbackup) | Стратегии backup PostgreSQL: pg_dump, PITR, cron — отчёт | PostgreSQL · backup |
| Логирование | [monlog3](https://github.com/x-optima/monlog3) | Elastic Stack 8.x: hot/warm ES, Logstash, Kibana, Filebeat | Elasticsearch · Logstash · Kibana · Filebeat · Docker |
| Логирование | [elk](https://github.com/x-optima/elk) | Централизованные логи в Docker | ELK · Docker · Kibana |
| Безопасность | [protecthost](https://github.com/x-optima/protecthost) | Hardening Linux-хоста | SSH · firewall · fail2ban |

---

## Terraform / IaC

От базового Terraform до итогового облачного проекта.

| Проект | Навыки |
|--------|--------|
| [terraform1](https://github.com/x-optima/terraform1) | Terraform · провайдер · ресурсы · структура HCL |
| [terraform2](https://github.com/x-optima/terraform2) | переменные · outputs · параметризация |
| [terraform3](https://github.com/x-optima/terraform3) | модули · декомпозиция · несколько окружений |
| [terraform4](https://github.com/x-optima/terraform4) | YC · VPC · ВМ · cloud-init |
| [terraform5](https://github.com/x-optima/terraform5) | удалённый state · блокировки · командная работа |
| [terraform6](https://github.com/x-optima/terraform6) | YC · Managed MySQL · Lockbox · Ansible · Container Registry · FastAPI |
| [cloud_balancer](https://github.com/x-optima/cloud_balancer) | HAProxy · Keepalived · переключение при отказе |
| [kursovoy_site](https://github.com/x-optima/kursovoy_site) | Terraform · YC · инфраструктура под веб-проект |

---

## Ansible

От playbook до собственных roles и collection.

| Проект | Навыки |
|--------|--------|
| [ansible1](https://github.com/x-optima/ansible1) | inventory · ad-hoc · playbook |
| [ansible2](https://github.com/x-optima/ansible2) | playbook · модули · идемпотентность |
| [ansible3](https://github.com/x-optima/ansible3) | ClickHouse · Vector · LightHouse · YC |
| [ansible4](https://github.com/x-optima/ansible4) | roles · ClickHouse · Vector · LightHouse |
| [ansible5](https://github.com/x-optima/ansible5) | собственные модули · Ansible collection |
| [lighthouse-role](https://github.com/x-optima/lighthouse-role) | Ansible role · LightHouse |
| [vector-role](https://github.com/x-optima/vector-role) | Ansible role · Vector · сбор логов |
| [x-optima-my_own_collection](https://github.com/x-optima/x-optima-my_own_collection) | собственная Ansible collection |

---

## CI/CD и Git

От commit и веток до GitLab, TeamCity и Nexus в облаке.

| Проект | Навыки |
|--------|--------|
| [gitlab-yc](https://github.com/x-optima/gitlab-yc) | GitLab на ВМ · Terraform · Ansible · YC |
| [teamcity](https://github.com/x-optima/teamcity) | TeamCity · Nexus · Maven · Kotlin DSL · Terraform · Ansible · YC |
| [github-hw3](https://github.com/x-optima/github-hw3) | GitHub Actions · автоматизация workflow |
| [github-hw4](https://github.com/x-optima/github-hw4) | GitHub · issues · pull requests · CI |
| [github-hw](https://github.com/x-optima/github-hw) | Git · ветки · merge · remote |
| [git1](https://github.com/x-optima/git1) | Git · commit · log · diff |
| [git3](https://github.com/x-optima/git3) | Git · shell · ветвление |
| [devops-cases1](https://github.com/x-optima/devops-cases1) | разбор инцидентов · практические кейсы |

---

## Мониторинг и логи

От Zabbix и Prometheus до Grafana alerting, TICK и Elastic Stack.

| Проект | Навыки |
|--------|--------|
| [apm](https://github.com/x-optima/apm) | Prometheus · Grafana · MQTT · Alertmanager · Docker Compose · Terraform |
| [monitoring](https://github.com/x-optima/monitoring) | Zabbix · агенты · триггеры · дашборды |
| [monitoring2](https://github.com/x-optima/monitoring2) | Zabbix · шаблоны · autodiscovery |
| [monitoring3](https://github.com/x-optima/monitoring3) | Prometheus · exporters · scrape-конфиг |
| [monitoring4](https://github.com/x-optima/monitoring4) | Prometheus · Grafana · Terraform · Ansible · YC |
| [monlog1](https://github.com/x-optima/monlog1) | TICK · Telegraf · Chronograf · SLA · сбор метрик из /proc |
| [monlog2](https://github.com/x-optima/monlog2) | Grafana · Prometheus · Node Exporter · PromQL · alerting · Mailpit |
| [monlog3](https://github.com/x-optima/monlog3) | Elasticsearch hot/warm · Logstash · Kibana · Filebeat · Docker Compose |
| [elk](https://github.com/x-optima/elk) | Elasticsearch · Logstash · Kibana · Docker |

---

## HA / DR / Backup

От балансировки нагрузки до VIP и резервного копирования.

| Проект | Навыки |
|--------|--------|
| [cluster](https://github.com/x-optima/cluster) | HAProxy · round-robin · Ansible · Terraform · YC |
| [disaster1](https://github.com/x-optima/disaster1) | Keepalived · FHRP · переключение при отказе |
| [cloud_balancer](https://github.com/x-optima/cloud_balancer) | HAProxy · Keepalived · виртуальный IP |
| [rsync](https://github.com/x-optima/rsync) | rsync · резервное копирование файлов · инкрементальная синхронизация |

---

## PostgreSQL и SQL

От схемы и запросов до репликации, индексов и backup.

| Проект | Навыки |
|--------|--------|
| [database](https://github.com/x-optima/database) | PostgreSQL · MySQL · основы |
| [database1](https://github.com/x-optima/database1) | 3NF · нормализация · ERD |
| [database2](https://github.com/x-optima/database2) | проектирование схем · ER-диаграммы |
| [sql1](https://github.com/x-optima/sql1) | SQL · агрегаты · база Sakila |
| [sql2](https://github.com/x-optima/sql2) | оптимизация JOIN · EXPLAIN ANALYZE |
| [indexes](https://github.com/x-optima/indexes) | GIN · BRIN · SP-GiST · PostgreSQL |
| [replica1](https://github.com/x-optima/replica1) | MySQL · master-slave · Docker Compose |
| [replica2](https://github.com/x-optima/replica2) | репликация · Python · health-check |
| [cache](https://github.com/x-optima/cache) | Redis · кэширование |
| [dbbackup](https://github.com/x-optima/dbbackup) | pg_dump · PITR · отчёт по стратегиям backup |
| [dbcloud](https://github.com/x-optima/dbcloud) | Managed DB в YC · backup · восстановление |

---

## Очереди

Очереди сообщений и pub/sub на RabbitMQ.

| Проект | Навыки |
|--------|--------|
| [rabbitmq](https://github.com/x-optima/rabbitmq) | RabbitMQ · очереди · pub/sub |

---

## Виртуализация

От основ гипервизора до сетей и автоматизации ВМ.

| Проект | Навыки |
|--------|--------|
| [virt1](https://github.com/x-optima/virt1) | ВМ · основы гипервизора |
| [virt2](https://github.com/x-optima/virt2) | управление ВМ · провизионинг |
| [virt3](https://github.com/x-optima/virt3) | ВМ · сети |
| [virt4](https://github.com/x-optima/virt4) | Python · автоматизация ВМ *(fork)* |

---

## Безопасность

От обзора угроз до hardening хоста: SSH, firewall, fail2ban.

| Проект | Навыки |
|--------|--------|
| [ib1](https://github.com/x-optima/ib1) | безопасность хоста · сети · сервисов |
| [protecthost](https://github.com/x-optima/protecthost) | hardening · SSH · firewall · fail2ban |

---

## Прочее

Профиль, учебные репозитории и форки.

| Проект | Навыки |
|--------|--------|
| [x-optima](https://github.com/x-optima/x-optima) | профиль · резюме · контакты |
| [new-repo](https://github.com/x-optima/new-repo) | Git · тренировочный репозиторий |
| [github-hw2](https://github.com/x-optima/github-hw2) | материалы по Git *(fork)* |
| [jenkins-dz1](https://github.com/x-optima/jenkins-dz1) | материалы по Jenkins *(fork)* |

---

## О портфолио

Собрано в рамках программы **«DevOps-инженер с нуля: расширенный курс»** (Нетология, 2025–2026) и самостоятельной практики. Каждый репозиторий — законченная задача: поднять сервис, описать инфраструктуру кодом, настроить мониторинг или обеспечить отказоустойчивость.

**Профиль и контакты:** [x-optima](https://github.com/x-optima/x-optima)

---

## Контакты

- Email: [vkuchin-home@yandex.ru](mailto:vkuchin-home@yandex.ru)
- Telegram: [@kuchinvn](https://t.me/kuchinvn)
- Max: [set.ki/5wVk9Nj](https://set.ki/5wVk9Nj)
- GitHub: [github.com/x-optima](https://github.com/x-optima)
