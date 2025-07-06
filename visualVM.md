# Исследование JVM через VisualVM
## 1. Консоль
23:49:15: Executing ':ru.netology.JvmExperience.main()'…

Starting Gradle Daemon...
Gradle Daemon started in 690 ms
> Task :compileJava UP-TO-DATE
> Task :processResources NO-SOURCE
> Task :classes UP-TO-DATE

> Task :ru.netology.JvmExperience.main()
Please open 'ru.netology.JvmExperience' in VisualVm
23:49:49.020809600: loading io.vertx
23:49:49.232147400: loaded 529 classes
23:49:52.249401200: loading io.netty
23:49:52.579726: loaded 2117 classes
23:49:55.588843900: loading org.springframework
23:49:55.712459200: loaded 869 classes
23:49:58.723964: now see heap
23:49:58.727174800: creating 5000000 objects
23:49:58.781177900: created
23:50:01.788901500: creating 5000000 objects
23:50:01.947091300: created
23:50:04.977184: creating 5000000 objects
23:50:05.082670400: created

BUILD SUCCESSFUL in 51s
2 actionable tasks: 1 executed, 1 up-to-date
23:50:08: Execution finished ':ru.netology.JvmExperience.main()'.

## Загрузка классов

![Загрузка классов](https://raw.githubusercontent.com/KomX512/JVM_HW/refs/heads/main/p1.png "Загрузка классов")

Увеличение размера Metaspace

![Metaspace](https://raw.githubusercontent.com/KomX512/JVM_HW/refs/heads/main/p2.png "Metaspace")

## Загрузка объектов в HEAP

![Загрузка объектов](https://raw.githubusercontent.com/KomX512/JVM_HW/refs/heads/main/p3.png "Загрузка объектов")
