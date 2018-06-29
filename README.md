# Sinatra Blog

## Resumen

Vamos a crear un landing page con un blog. Esta aplicación sera la primera que hagamos con asociaciones y Sinatra.

Vamos a tener dos modelos: `Entry` y `Tag`. Un `Entry` puede tener muchos `Tag`s y un `Tag` puede estar en muchos `Entry`s.

## Pasos




Pensando en nuestros controladores podemos asumir que vamos a tener los siguientes 3 archivos.

1. clona este repositorio
2. cd BlogSinatra
3. bundle install
4. rake db:create
5. rake db:up
6. rackup config.ru

#Asegurate de tener instaldo y configurado postgres
