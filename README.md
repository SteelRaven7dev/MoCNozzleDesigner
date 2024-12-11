# MethodOfCharacteristicsNozzle
A custom GUI app for rocket engine design using the Method of Characteristics in C++
Dependancies:
- C++
- [Qt Creator](https://www.qt.io/download)

FAQ:
- If you are unable to open rocketDesignApp.pro from QtCreator ("no valid settings" error), simply delete **rocketDesignApp.pro.user**, and then reopen the .pro file, you will need to configure again and a fresh new ".pro.user" file one will be created on your local machine. See (https://forum.qt.io/topic/132250/trying-to-import-qt-creator-project-from-previous-version/6) for more information.
- If you get the error file qcustomplot.h not found in ui_methodofcharacteristics.h, click on the file and in the line, change it to src/qcustomplot (be sure to add the "src").
