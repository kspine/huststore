## zismember ##

**Interface:** `/zismember`

**Method:** `GET | POST`

**Parameter:** 

*  **tb** (Required)  
*  **key** (Required)  

This interface is a proxy interface for `/hustdb/zismember`. See more details in [here](../hustdb/hustdb/zismember.md).  

**Sample:**

    curl -i -X POST "http://localhost:8082/zismember?tb=test_table" -d "test_key"

[Previous](../ha.md)

[Home](../../index.md)