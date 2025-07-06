# Исследование JVM через VisualVM
## 1. Консоль
23:49:15: Executing ':ru.netology.JvmExperience.main()'…<br>

Starting Gradle Daemon...<br>
Gradle Daemon started in 690 ms<br>
> Task :compileJava UP-TO-DATE<br>
> Task :processResources NO-SOURCE<br>
> Task :classes UP-TO-DATE<br>

> Task :ru.netology.JvmExperience.main()<br>
Please open 'ru.netology.JvmExperience' in VisualVm<br>
23:49:49.020809600: loading io.vertx<br>
23:49:49.232147400: loaded 529 classes<br>
23:49:52.249401200: loading io.netty<br>
23:49:52.579726: loaded 2117 classes<br>
23:49:55.588843900: loading org.springframework<br>
23:49:55.712459200: loaded 869 classes<br>
23:49:58.723964: now see heap<br>
23:49:58.727174800: creating 5000000 objects<br>
23:49:58.781177900: created<br>
23:50:01.788901500: creating 5000000 objects<br>
23:50:01.947091300: created<br>
23:50:04.977184: creating 5000000 objects<br>
23:50:05.082670400: created<br>

BUILD SUCCESSFUL in 51s<br>
2 actionable tasks: 1 executed, 1 up-to-date<br>
23:50:08: Execution finished ':ru.netology.JvmExperience.main()'.<br>

## Загрузка классов

![Загрузка классов](https://raw.githubusercontent.com/KomX512/JVM_HW/refs/heads/main/p1.png "Загрузка классов")

Увеличение размера Metaspace

![Metaspace](https://raw.githubusercontent.com/KomX512/JVM_HW/refs/heads/main/p2.png "Metaspace")

## Загрузка объектов в HEAP

![Загрузка объектов](https://raw.githubusercontent.com/KomX512/JVM_HW/refs/heads/main/p3.png "Загрузка объектов")
