Собеседование с DevOps. 300+ вопросов для Junior, Middle, Senior
Можно спорить о популярности DevOps , а можно просто готовиться к собеседованию и получить желанные 9K :) Чтобы помочь вам сориентироваться в вопросах, которые задают на интервью, мы пообщались с теми, кто их проводит, и составили список возможных вопросов.

Если вы не DevOps, просмотрите другие подборки вопросов .

Junior
Общие
1. Что такое DevOps?
2. Вы набираете google . com в браузере. Расскажите как можно подробнее, что происходит в это время?
3. Как работает HTTPS?
4. Объясните концепцию Infrastructure as Code, зачем это нужно и какие проблемы решает?

Linux
5. Опишите общую архитектуру операционной системы.
6. Опишите главное предназначение операционной системы.
7. Зачем нужны файловые системы? Какие существуют?
8. В чем разница между виртуализацией и контейнеризацией?
9. В чем преимущества контейнеров?
10. Какова файловая структура у Linux (UNIX) систем, расположенных в /etc,/dev,/proc,/sys,/lib,/var (несколько директорий по выбору)?
11. Что такое Load Average?
12. В чем разница между soft и hard symlink?
13. Как работают file permissions, зачем директории права исполнения (+x)?
14. Что такое zombie process?
15.С помощью чего можно собрать информацию о текущем состоянии процессора, памяти, диска, сети?
16. Что такое swappiness?
17. Как посмотреть свободное место на диске?
18. Что такое inode?
19. Расскажите поэтапно процесс загрузки Linux с момента включения питания компьютера.
20. Что произойдет при выполнении команд:

1. cat file1 > file2
2.cat file1 >> file2

21. В чем разница между Ctrl+C и Ctrl+Z?
22. Как перенаправить stderr и stdin одновременно?
23. Как уничтожить процесс? Какие типы сигналов?
24. Что делает команда grep?
25. Что такое сценарий bash?
26. Какие типы переменных используются в bash?
27. Что выведут команды:

1. echo ${hostname}; 
2.echo $(hostname);

Networks
28. Что такое OSI, TCP/IP?
29. Зачем нужны network masks?
30. Структура IP-пакета. Из чего состоит? Что такое фрагментация и почему она происходит?
31. Что такое коллизия? Почему возникает?
32. Что такое прокси?
33. Что такое firewalls и для чего они необходимы?
34. Что такое NAT и для чего он нужен?
35. Какие типы IP-адресов вы знаете?
36. По какому порту и протоколу работают Ping и Traceroute?

Clouds
37. В чем разница между IaaS, PaaS и SaaS?
38. Что такое VPC и из каких компонентов должно состоять?
39. Что такое cloud-init? init/systemd/upstart configs?

Automation
40. Что такое IaaC и для чего он нужен?
41. Что такое Terraform?
42. Какие инструменты автоматизации вы знаете?

Information Security
43. В чем разница между аутентификацией и авторизацией?
44. Сертификаты. Как работает HTTPS? Что такое certificate ciphers?
45. Как безопасно передать данные своему коллеге?
46. Что такое MFA, TOTP?

Виртуализация
47. В чем разница между виртуализацией и контейнеризацией? В чем плюсы и минусы?
48. Как при запуске Docker-контейнера «повесить» его с  80-го порта в контейнере на 8081 на хост?
49. Как передать виртуальную машину USB device?
50. Docker-контейнер потребляет многие SWAP. Что делать?

CI/CD
51. Что такое Continuous Integration и Continuous Deployment? В чем разница между Continuous Deployment и Continuous Delivery?
52. Опишите основные этапы CI/CD.
53. Опишите пример процесса CI (и/или CD), который начинается с момента, когда разработчик запушил изменения/PR в Git?
54. Расскажите о разновидностях тестов, которые мы можем использовать в пайплайне CI.
55. Какие инструменты CI вы использовали? Есть ли опыт работы с Jenkinsfile?
56. Какие виды тестов вы знаете и для чего они необходимы?

Development
57. Git. Как решить merge conflict? Что такое rebase, cherry-pick?
58. В чем разница между git merge и git rebase?
59. Какие UI использовали?
60. Какая разница между GitLab/GitHub/Bitbucket?
61. Какая разница между Git pull/Git fetch?
62. Что такое Git-Flow?
63. Версионирование. Какая разница между SemVer и CalVer?
64. Тестирование. Какие существуют виды? Как писать тесты, TDD?
65. В чем разница между компилируемыми и интерпретационными языками программирования?

Monitoring/Logging
66. Какие метрики нужно собирать? Разница между infrastructure и application monitoring.
67. Какая разница между pull и push model в системах мониторинга?
68. Какая разница между Black box и White box monitoring?
69. Расскажите о подходах к сбору application логов.

Практические задания
71. Напишите простую программу на ваш выбор. Программа должна получать сообщения из сервиса очередей и печатать его в stdout. Сервис очередей — по вашему усмотрению.
72. Разберите структуру сервиса (например, Docker-compose).
73. Практическая сессия работы по Git (Git command line: fetch, push, pull, rebase, checkout, submodules).

Middle
Linux
1. Опишите архитектуру ядра Linux.
2. Что такое ядро ​​и каково его предназначение?
3. Опишите общие части файловой системы Unix/Linux, архитектуру файловой системы.
4. В чем разница между RedHat и Debian?
5. В чем разница между /proc and/sys?
6. Ситуация: показывает, что на диске занято 50% места, а создать файл даже под пользователем root не можем. В чем проблема?
7. Мы удалили файл, открывший приложение. Как нам его восстановить?
8. Как найти PID процесса, его стартовые параметры?
9. Как проверить, открыт ли порт на удаленном хосте, локальном хосте?
10. Как искать файл по его содержимому?
11.Что такое SSH как организовать доступ на сервер без пароля или с определенных хостов? Как ограничить доступные для выполнения команды?
12. Как проверить потребленные ресурсы во время сеанса SSH?
13. Что означает разрешение на файл 755?
14. Что такое SELinux и для чего он нужен?
15. Как определить PCI устройство в системе, например RAID controller?
16. Как переименовать устройство, например сетевую карту или диск?
17. Что такое LVM? Какие знают примеры использования?
18. Что такое root reserved space?
19. Что такое exit code и как узнать?
20.Почему вывод df -h показывает, что на диске занято мало места, но система не позволяет записать файл с сообщением no space left on device?
21. В чем разница между command1 & command2 и command1 && command2, а также command1 && command2 || command3?
22. Из сети резко вырос исходящий трафик на  25-й порт. Как, имея доступ на гейтвей, обнаружить вредителя из внутренней сети?
23. Как закрыть параметры Linux Kernel?
24. Что такое ulimits?
25. В чем разница между символическими и hard links?
26. Что такое фрагментация ext3 и ext4?
27. Для чего файловые системы ext* резервируют 5% места?
28. Как увеличить размер файловой системы?
29.Можем ли мы уменьшить размер файловой системы?
30. Что такое chroot и для чего он нужен?
31. У нас есть Linux box с 2 Гб оперативной памяти и Java-приложение, которое пытается выделить 4 Гб при запуске. Удастся ли это?
32. Есть приложение, которое читает файл, который пользователь пытается удалить. Что случится? Можно ли удалить этот файл? Можно ли восстановить этот файл?
33. Какие механизмы создания процессов в Linux вы знаете?
34. Сравните systemd и init system.
35. У вас есть папка с большим количеством файлов, и вы хотите удалить все файлы с именами, начинающимися на A (прописная буква). Но команда rm –f A* выдает Argument list too long. Как удалить эти файлы?
36.Вы начинаете удалять файлы первым методом по предыдущему вопросу, но каждый rm запрашивает подтверждение. Это очень долго. Как ускорить эту операцию?

Networks
37. Расскажите о модели OSI. Опишите функции и назначение каждого уровня.
38. Какие сетевые топологии вы знаете? Опишите разницу между ними.
39. Зачем нужен IP-адрес, если MAC-адрес уникален? Разве мы не можем общаться только по MAC-адресу?
40. В чем разница между концентратором и коммутатором L2 в сетях Ethernet?
41. Что такое Vlan и для чего существует разделение на виртуальные локальные сети?
42. Какой номер порта используется для PING-коммуникации?
43. Что такое сеанс связи? Какой алгоритм использует TCP для доставки?
44. В чем основное отличие между TCP и UDP?
45. Зачем нам маршрутизатор по умолчанию?
46.Как хост решает DNS по умолчанию?
47. Компьютер начал получать IP-адрес из другой сети (есть подозрение, что в сети работает другой DHCP-сервер): как его найти и отключить? Какие методы защиты от такой проблемы?
48. Мы будем мигрировать сайт на новый IP-адрес. Как сделать, чтобы пользователи этого практически не заметили?
49. Что такое socket?
50. Как узнать, какие удаленные хосты подключаются к хосту через порт 8888? (с помощью команд и не используя /proc или /sys).
51. У нас есть несколько сетевых карт. Как увеличить пропускную способность сервера?
52. Как проверить открытые порты на удаленном сервере без команд Netcat или Nmap Linux?

Container orchestration
53. В чем преимущества Kubernetes как платформы?
54. Что такое control plane и из каких компонентов состоит?
55. Какие CNI вы использовали и чем они отличаются?
56. Чем отличается managed Kubernetes от self-deployed?
57. Как можно контролировать размещение дел в кластере? (taints/tolerations, affinities, topologies etc)
58. Скейлинг кластера. Cluster autoscaler vs HPA vs VPA? Как сделать zero-downtime node decommission/cluster upgrade? PDB? Lifecycle hooks?
59. Каковы способы внешнего доступа к кластеру? ingress, node port, port-forward и т.д.
60. С каким PID запускается процесс в контейнере?
61.Что лучше использовать для изоляции окружения – Vagrant или Docker?
62. Какой инструмент оркестрирования контейнеров использовали? (Swarm, Kubernetes, Openshift, Rancher и т.д.)
63. Что происходит в Kubernetes после запуска kubectl (API, ReplicaSet Controller, storage back-end, scheduler, kubelet, worker node, pod)?
64. Какая разница между pod и контейнером в K8s?
65. Как мы можем сделать любой микросервис, работающий на K8s, доступным из внешней среды?

Виртуализация и контейнеризация
66. Какие типы виртуализации вы знаете?
67. Как работает Docker на MacOS/Windows?
68. Что такое Docker-image и Docker-контейнер? Как они между собой связаны?
69. Каковы основные отличия между контейнерами докеров и виртуальными машинами?
70. Что такое image layer? Какое максимальное количество layers возможно? Почему нужно пытаться иметь малое количество layers? Какое оптимальное количество?
71. Как изменить размер диска после создания в виртуальной машине? Что нужно сделать с гостевой ОС?
72. Как в Docker реализовано ограничение ресурсов?
73. Существует виртуальная машина, к которой упущен доступ. Как, имея доступ к диску, восстановить root пароль/SSH-ключ?
74.Оптимизировать Dockerfile, объяснить, что и почему так:

FROM golang 
RUN  apt install -y pkg1 pkg2 pkgN  # Dependencies for app 
COPY . . 
RUN  go build -o app main.go 
CMD  ./app
75. Что такое IPVS и какой у него функционал?
76. Какова структура API в Kubernetes?
77. Что такое operators и зачем они нужны?

CI/CD
78. Какие стадии должны быть в любом пайплайне (lint, test, build, deploy etc)?
79. Как и где хранить строительные artifacts?
80. Что такое артефакт?
81. Есть два бренча: dev и stage. Мы забросили Dockerfile в dev, а затем оббелили в dev и stage. Это будет одним артефактом или разными?
82. Что вы использовали для автоматизации настройки Jenkins and GitLab CI?
83. Сравните CI инструментов: Jenkins, GitLab CI, AWS Code Pipeline, GCP cloudbuild, GitHub actions, Circle CI.
84. Deployment strategies. Какие существуют и чем отличаются (recreate, blue-green, canary etc)?
85. Как реализовать СI/CD для программы, которая зависит от нескольких других программ?
86.GitOps. В чем его преимущества и недостатки?

Clouds and Automation
87. Какова роль и преимущества облачных сервисов для DevOps?
88. Что такое immutable infrastructure? Как достичь? В чем преимущества и недостатки? Packer, AMI и т.д.
89. Структура Terraform. Как организовать multi-environment project? Terraform workspaces?
90. Лучшие практики по использованию многих Terraform states.
91. Как организовать доступ разработной команды к AWS/GCP/Azure? Role-based access, assume role, SSO.
92. Что такое Terraform provider, module?
93. Как версионировать Terraform modules?
94. Когда нужно использовать local-exec и remote-exec?
95. Что такое golden image и как его создать?

Monitoring/Logging
96. Как мониторинг помогает поддерживать всю архитектуру системы?
97. Какие инструменты мониторинга вы использовали?
98. Что такое медиана и процентиль?
99. Что такое SLI, SLO, SLA? Зачем это нужно?
100. Архитектура системы сбора логов, ELK, EFK etc. Как сохранить логи при отказе хранилища? Нужно ли использовать для этого брокер сообщения? Нужно ли делать throttling/rate limits?
101. Prometheus long-term storage. Какие варианты?
102. Как работает Prometheus?
103. В чем принципиальное отличие между Grafana и Kibana?
104. В чем главное отличие между Ansible and Terraform?
105.Что такое SAAS monitoring и какие виды знаете?
106. Если вы используете Datadog/NewRelic, то как нам следить за падением инструментов мониторинга?
107. Что такое distributed tracing и error tracking systems? Как вы думаете, когда следует их использовать?

Information Security
108. В чем разница между RBAC и ABAC?
109. В чем состоит XSS атака? SQL injection? Что такое CSP?
110. Какие базовые меры можно предпринять для защиты SSH-соединения?
111. Root-пароль неизвестен или потерян. Какова процедура обновления?
112. Как управлять правами на файловой системе в Linux?
113. Что такое Firewall?
114. Чем отличается stateless от stateful фаерволов?
115. Сколько таблиц в iptables?
116. Можно ли настроить трансляцию NAT с помощью iptables? Какую таблицу следует использовать?
117. Какую таблицу используют для смены заголовков пакетов?
118.Если вам ломают Linux-сервер, то как более эффективно блокировать трафик с IP-адресов?
119. Принцип работы GCP Firewall: можем ли мы фильтровать трафик на Load Balancer?
120. Что такое SELinux?
121. Можно ли полностью отключить SELinux на лету?
122. С какими secrets management systems вы работали?
123. У нас есть сервер NAT, и мы хотим обеспечить доступ по IP к серверу снаружи. Как нам это реализовать?
123. Чтобы попасть на сервер клиента, нужно залогиниться на 4+ jump хоста. Как автоматизировать? Где мы будем хранить наш SSH-ключ?

Development
125. Что такое cookies? Зачем нужны? JWT?
126. Что такое feature toggles и для чего они?
127. Что такое TDD (Test Driven Development) и BDD (Behaviour Driven Development)?

Databases
128. Что такое индекс и что такое ключ?
129. Каковы преимущества и недостатки индексов?
130. Представьте, вы разрабатываете систему биллинга, которая должна обрабатывать тысячи счетов. Какую стратегию обновления данных вы бы выбрали?
131. Какие методы чаще всего используются для масштабирования реляционных баз данных?
132. Опишите механизм транзакций БД.
133. Как мы можем удалить таблицу или базу данных?
134. Как найти медленные запросы в MySQL/PostgreSQL?
135. Какие SQL-операторы манипулирования данными вы знаете?
136. Можно ли вывести список баз данных/таблиц через CLI? Как мы можем переключаться между базами данных MySQL/PostgreSQL?
137.Какие storage engines в MySQL вы знаете? Какие отличия?
138. Как реализована репликация MySQL master-master? Сколько серверов MySQL может быть задействовано в таком взаимодействии?
139. Как работает репликация MySQL/PostgreSQL? Какие параметры должны быть настроены для репликации?
140. Сравните SQL и NoSQL.
141. Sharding vs replication?
142. Какие виды индексов? Когда и зачем использовать?
143. Требования к схеме БД. Character sets, collations, default, not null и т.д.
144. Мы мигрируем MySQL/PostgreSQL из on-prem в облако. Как нам это сделать с минимальным даунтаймом?
145. Зачем и как тестировать перформанс базы данных?

Практические задания
146. Напишите Terraform module для инфраструктуры тестового сервиса в AWS.
147. Напишите hello-world программу на ваш выбор и сформируйте для нее helm chart/kustomize.
148. Как организовать деплой без downtime?
149. Опишите методы troubleshooting для Docker-контейнера.
150. Разобрать и разъяснить структуру CI/CD pipeline (на примере gitlab . yml).
151. Продемонстрируйте навыки работы с GitOps, опишите деплоймент простенькой программы.
152. Как организовать деплой веб-приложения, запущенный на нескольких серверах без (или с минимальным) downtime?
153.Как с помощью Ansible узнать default gateway для пула серверов, и если он отличается от желаемого, записать строчку «hostname: gateway» в файл на локальной машине?

Senior
Linux
1. Что может создавать высокую нагрузку на CPU (процессы приложений потребляют очень мало ресурсов CPU)?
2. У нас нет команд ifconfig, ip и поставить мы их не можем. Как нам узнать ip address, mask, network, routes?
3. Что такое suid, sgid и sticky?
4. Что тюнилось с системой для погрузки трафика 1GB, 10G, 40G+?
5. Что тюнилось с системой для высокой нагрузки на диск?
6. Что такое Linux namespaces?
7. Что такое Ceph как работает?
8. Что нужно тюнить для Ceph?
9. Что произойдет, если /dev/sda1 перенесем в /root?
10. Мы удалили /dev/sda1. Как нам его восстановить? Что такое pseudo-devices?
11.Нам хакнули сервер и в директории /var/www создали два миллиона файлов небольшого размера. Если использовать команду cd /var/www и затем rm -rf*, то у нас зависнет терминал. Как удалить файлы?
12. На каком уровне работает iptables?
13. Что такое eBPF и зачем нужно?
14. У вас есть файл, содержащий IP-адреса серверов (по одному в строке). Есть SSH доступ к этим машинам, и вам нужно выполнить задание (например, установить список пакетов на все узлы). Объясните, как можно это сделать.

Networking
15. В чем отличия между IPv4 и IPv6? Зачем мы мигрируем на IPv6?
16. Сосуществование IPv4 и IPv6: что это значит?
17. Действительно ли работают межсетевые экраны с поддержкой IPv6?
18. Как работает DHCPv6? Чем она отличается от DHCPv4?
19. Как фрагментируются пакеты IPv6 и чем отличается от IPv4?
20 Или с IPv6 нужно больше использовать NAT?
21. Что такое DPDK?
22. Что такое SR-IOV? В чем разница между DPDK и SR-IOV?
23. Что такое NetFlow и зачем нужно?
24. Что такое OpenFlow?
25. Что такое SDN и какие контроллеры вы знаете? Сравните контроллеры.

Разное
26. Что такое SDLC?
27. Расскажите о последнем опыте реализации архитектуры для сервиса.
28. Какой трудный скрипт писали?
29. Что такое configuration drift? Почему это происходит и как это усложняет жизнь инженерам SRE? Ops?
30. Расскажите об архитектуре, за которую вы отвечаете, и укажите, как она масштабирована и отказоустойчива.
31. Назовите три важных KPI для DevOps-специалиста.
32. Как работает Kafka (clusters(brokers, controllers), topics, partitions)?
33. GitOps: Rancher Fleet vs Flux vs Argo?
34. Как использовать GitOps для обновления документации DevOps-приложений?
35.Расскажите об особенностях проектирования Kubernetes on-premise.
36. Как организовать On-Call процесс для команды DevOps?
37. Опишите главные шаги загрузки операционной системы Linux.

Container orchestration
38. Service mesh. Что это такое и зачем нужно?
39. Cluster federation. Что это такое и зачем нужно?
40. Pod fine-grained access. Как реализовать? IRSA vs kube2iam vs kiam?
41. Как реализуются услуги в кубернетах?
42. Как дебажить трафик контейнера?
43. Что такое unikernel и для чего он нужен?
44. Почему коммьюнити переезжает из Docker containerd?

Clouds and Automation
45. Каковы преимущества и недостатки cloud-провайдеров?
46. Cost оптимизация. Какие инструменты? Spot/preemptible instances, reservations?
47. Как организовать multi-account, multi-region cloud setup?
48. В чем разница между частными и публичными сетями AWS?
49. AWS Lambda: имели ли опыт работы?
50. Когда следует переходить на AWS Lambda? Когда не стоит? Аналогичные решения в GCP или Kubernetes?
51. Когда лучше использовать CloudFormation, а когда Terraform?

CI/CD
52. Что такое state в контексте использования Terraform?
53. Какие существуют branching strategy? На что опираться при выборе?
54. Каким образом реализовать feature/dynamic environments?
55. Как произвести эмуляцию ресурсов cloud-провайдера для локального тестирования и ускорения разработки?
56. Что такое MultiCloud?
57. Что такое Cloud-Agnostic и когда он потребуется?
58. Что такое Hybrid-Cloud и с какими решениями вы работали?

Information Security
59. Как храниться пароли в базах данных (Salt&Pepper, Rainbow Tables, Adaptive Hashing)?
60. Как передавать секреты в application (Secrets management)?
61. Сравните CI/CD SAST и DAST?
62. Какие вы знаете Kubernetes security practices? RBAC? OPA? Какие недостатки RBAC и какие кейсы знаете?
63. Расскажите о защите от атак DDOS, WAF.
64. Что такое Rootless containers и для чего он нужен?
65. Что такое AppArmor и Seccomp и зачем они нужны?
66. Приходилось ли работать с Falco? Если да, то что реализовывали?
67. HashiCorp Vault и как правильно передать нам секреты в контейнер и CI pipeline?
68.Что такое Admission Controllers и какие вы использовали?
69. Как хранятся секреты? Как просмотреть ресурсы в etcd?
70. Чем проверяете на уязвимости ваш Kubernetes cluster?
71. Что такое Secure SDLC?
72. Что вы знаете о Cloud Infrastructure Attack via a Pull Request и как этого избежать?

Observability
73. Что такое observability и чем отличается от обычного мониторинга? Какие особенности необходимо учитывать в микросервисной архитектуре (tracing)?
74. Что такое SLI, SLO, SLA и для чего они нужны? Для чего используют error budget?

Databases
75. Что такое теорема CAP? Зачем это нужно?
76. Как работать с миграциями? Что делать в случае rollback? Как проверить, что миграция backward-compatible?
77. Опишите, как бы вы оптимизировали работу базы данных? (БД по выбору кандидата) Slow queries, buffers, thread pools?
78. Зачем нужно тестировать перформанс базы данных и какими инструментами?

Практические задания
79. Представьте, что вы являетесь CTO Booking или Airbnb. Какие бы вы принимали решение по:

Языки программирования.
Infrastructure as a Code.
Архитектура инфраструктуры.
Настройка CI/CD.
80. У вас есть файл, содержащий патчи в директории. Например:

/var/tmp/temp/file1.c
/var/tmp/file.ext
/var/tmp/temp/

etc... один путь в строке. Если путь заканчивается на '/', это путь в каталог. Вам нужно восстановить дерево каталогов с пустыми файлами в другой файловой системе. Напишите bash-скрипт.

81. Представьте, что вам нужно убедить Spotify, использующий AWS, перейти на GCP. Как вы мотивируете Spotify мигрировать на GCP?
82. Есть сервисная компания, предоставляющая сервис трекинга перевозок. Есть клиенты, которые не желают, чтобы их данные процессировались в AWS. Как реализовать multi-cloud solution?
