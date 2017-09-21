# aerospike_connpool
Connection Pool for Aerospike.

## Getting Started
Have an environment setup to connect to Aerospike DB.

Install aerospike client
pip install aerospike

Install the connection pool library
pip install aerospike_connpool

'''
from aerospike_connpool.aerospikeConnectionWrapper import Pool
creds = {'host': '', 'port': ''} 

pool = Pool(creds, 3, 6)
'''

'''
To access the connections list
for c in poop._l:
    print (c.conn)
'''

'''
Methods inside Pool
get_client()
release_client(conn_object)
'''

## Authors
* **Gaurav Kumar**

## License
This project is licensed under the MIT License
