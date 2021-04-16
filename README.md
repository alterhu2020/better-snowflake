# better-snowflake

A simple and quick snowflake libary, better performance and effective.

## How to use 

### 1. install better-snowflake

```
npm install better-snowflake --save

```
### 2. usage

```
  const snowflake= require('better-snowflake')
  const worker_id=3, datacenter_id=7
  const idWorker = new Snowflake(worker_id, datacenter_id)
 
  const uuid = idWorker.nextId()
  console.log(uuid)

```


## Contact/Issues

Email: alterhu2020@gmail.com