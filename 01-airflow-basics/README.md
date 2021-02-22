# แนวคิดของ Airflow (Airflow Concepts)

* DAG มาจาก Directed Acyclic Graph ซึ่งก็คือ เซตของ Task ที่มี dependency ระหว่างกัน โดยจะมีการทำงานที่เป็นลำดับ
* Operator คือ wrapper ที่มีไว้เพื่อจะกระทำสิ่งๆ หนึ่งที่เราต้องการ
* Task คือ หน่วยของงานที่ทำอะไรสักอย่างหนึ่ง ถูกสร้างมาจาก Operator

