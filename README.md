# php

docker-compose up -d --build

docker-compose exec php /bin/bash

curl -sS https://get.symfony.com/cli/installer | bash

mv /root/.symfony5/bin/symfony /usr/local/bin/symfony

symfony new . --version="6.1.*" --webapp

composer require webapp
