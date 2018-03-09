## Oracle 12C Docker
 * The data folder contains the data stored in the databases created with oracle 
 * Run instance of docker 12c
	```bash
	docker-compose up -d
	```
 * Exec bash into docker container
	```bash
	docker-compose exec oracle bash
	````
 * Exec sqlplus: once in the docker-container exec
	```bash
	sqlplus system/oracle
	```

And now run your commands :) enjoy it
	
