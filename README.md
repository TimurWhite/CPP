
## Запуск
Для того, щоб запустити лабораторну, варто виконати наступні команди.

Для збірки проекту:
```bash
dotnet build Build.proj -t:Build -p:Solution=Lab1
```
Запуск проекту:
```bash
dotnet build Build.proj -t:Run -p:Solution=Lab1
```
Запуску тестів:
```bash
dotnet build Build.proj -t:Test -p:Solution=Lab1
```


