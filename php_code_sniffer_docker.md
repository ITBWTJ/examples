Docker PHP Code Sniffer

https://hub.docker.com/r/herloct/phpcs

Запустить docker run --rm --volume /local/path:/project herloct/phpcs 
    
/local/path - путь к коду на компе
/project - в докере (не менять)

Далее загуглить настройки
Выбрать интерпретатор, может быть none:none в Landuages.. -> PHP -> Code Sniffer и отключить отображение только для этого проекта
Выбрать стандарт PSR2 в Editor -> Inspections -> PHP -> validtion 
