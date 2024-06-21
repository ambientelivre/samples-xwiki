# Deploy xWiki Extension by Deployment using Docker Compose


## Install Extensions
this smple install a simple extension in jar 

 - Hello World Extension [source](https://github.com/ambientelivre/samples-xwiki/tree/main/helloworld)
 
## Deploy and Run

```bash
git clone git@github.com:ambientelivre/samples-xwiki.git

cd docker-compose/deploy-extension

docker-compose up --build 
```
 
## Structure  

xwiki - directory for build image

xwiki/extensions - extension copy to webapps/WEB-INF/lib

import_xwiki_ui  - Extensions Componentes  UI ( install for management UI not deployment this moment)
