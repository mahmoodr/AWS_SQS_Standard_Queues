# AWS_SQS_Standard_Queues
AWS SQS Standard Queues

Requirements:
python3
boto3


1. Run below script to create a SQS on AWS:
python3 create_queue.py

2. update sqs_url.py by replacing the SQS you created:
QUEUE_URL = 'https://queue.amazonaws.com/xxxxxxxxxxxx/mynewq'

3. run below script to see the queue status:
python3 queue_status.py

4. send data to queue using slow or fast method:
python3 slow_producer.py

or:

python3 fast_producer.py

5. consume the queue content using one of slow or fast method:
python3 fast_consumer.py

or:
python3 slow_consumer.py

6. purge the queue:
python3 purge_queue.py
