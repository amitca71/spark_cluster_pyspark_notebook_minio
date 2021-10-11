this is a demo for local spark with 2 workers, accessed from jupyter notebook and write to minio file on local system to emulate s3

quick start:
1. docker-compose up -d
2. docker-compose exec pyspark bash, 
3. localhost:9999
4. open work/write_read_to_minio.ipynb
5. execute
6. see http://localhost:8080/ for the workers DAG

