Сборка в Ubuntu 16.04+

Загрузите набор утилит для сборки: 
sudo wget "https://github.com/AppImage/AppImageKit/releases/download/continuous/appimagetool-x86_64.AppImage"
sudo chmod a+x appimagetool-x86_64.AppImage

Создайте образ приложения кошелька в каталоге electrum-skynet-4.1.5-x86_64_linux/build/electrum.AppDir.

Проверьте запуск приложения кошелька перед сборкой:
sudo electrum-skynet-4.1.5-x86_64_linux/build/electrum.AppDir/AppRun 

Соберите приложение для linux:
sudo ./appimagetool-x86_64.AppImage electrum-skynet-4.1.5-x86_64_linux/build/electrum.AppDir

Готовое приложение сохраняется в каталоге запуска набора утилит appimagetool-x86_64.AppImage.


