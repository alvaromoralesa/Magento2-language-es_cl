# Magento2-language-es_cl

## Magento 2 Spanish (Chile) language package - Paquete de idioma Español (Chile) para Magento 2
Magento2 Spanish (Chile) language pack

## Instalación Automática

### Lo añadimos al composer del proyecto:

Añadir a repositorio composer.json

"minimum-stability": "alpha",
    "prefer-stable": true,
    "repositories": [
        {
            "type":"package",
            "package": {
                "name": "alvaromoralesa/magento2-language-es_cl",
                "version":"master",
                "source": {
                    "url": "https://github.com/alvaromoralesa/Magento2-language-es_cl.git",
                    "type": "git",
                    "reference":"master"
                }
            }
        }

    ],

```
composer require alvaromoralesa/magento2-language-es_cl dev-master
```

### Lo instalamos a través de la consola de Magento

```
php bin/magento i18n:pack --mode=replace -d vendor/alvaromorales/magento2-language-es_cl/es_CL.csv es_CL
```

### Actualizamos el contenido estático

```
php bin/magento setup:static-content:deploy es_CL
```

### Recuerda limpiar la caché después de instalar el paquete de idioma
