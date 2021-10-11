this is a demo for local spark with 2 workers, accessed from jupyter notebook and write to minio file on local system to emulate s3

quick start:
1. boot: 
docker-compose up -d
2. get notebook token: 
docker-compose exec pyspark bash -c "jupyter server list" 
3. open localhost:9999
4. open work/write_read_to_minio.ipynb
5. execute
![image](https://user-images.githubusercontent.com/5821916/136770527-e6b2ea0e-1094-4043-bd7d-38229aa5640a.png)

6. see http://localhost:8080/ for the workers and DAG
![image](https://user-images.githubusercontent.com/5821916/136769304-24039d98-b3c7-4e22-93e8-e0632497ab5a.png)



