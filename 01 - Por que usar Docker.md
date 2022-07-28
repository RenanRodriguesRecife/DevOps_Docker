# Docker

Por que usar docker? 

Máquina Virtual (VM) - possibilita rodar um sistema operacional dentro do outro sem que eles tenham uma interação direta. Você poderia separar recursos computacionais (uso de RAM, uso de CPU e HD) do computador para poder fazer com que aplicações direferentes pudessem rodar em diferentes sistemas operacionais ao mesmo tempo.

Em um ambito empresarial é assim que nasse as VPS (transformando um computador em vários)

``` 
O mercado percebeu que em muitos casos é um disperdício rodar um sistema operacional completo expecialmente se o seu interece é apenas rodar uma aplicação.
É preciso de 1 kernel para cada sistema, usar mais recursos de processadores e de ram e usa mais armazenamento do que é necessário se só você rodasse apenas a aplicação.
Daí nasce a idéia de software em containers.
```

Container - Diferente do que acontece com uma VM um container Docker consegue compartilhar recursos da própria máquina hospedeira como o Kernel, evitando redundancias e reduzindo o uso de recursos desnecessários. E como os containers são isolados uns dos outros você consegue um bom nível de segurança.

Uma vantagem dos Containers docker por ser de tamanho reduzido você consegue ter backups relativamente simples, já configuradas e pré-prontos (Ex: ao invés d subir uma disto e instalar o NGINX nela, você pode simplesmente subir um NGINX já pré-instalado) facilitando a escalabilidade e diminuindo o timer de vários serviços.

A tecnologia de Container dimuinui os custos e possibilita uma série de negócios que antigamente estava restrito apenas a quem tinha grandes infraestruturas.

Ex: é possível fazer Streamer de APP via docker com interface

