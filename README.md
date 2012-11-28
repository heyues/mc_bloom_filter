mc_bloom_filter
===============

a bloom filter with memcache protocol ，you can use memcache's add、set、get、delete to admin your bloom filter.

mc_bloom_filter can set as much as 10,000,000,000 string or number,and get or set as fast as 10w/qps.

mc_bloom_fiter use only memory,now we don't have time to dump it on the disk

add: to create a bloom filter.
set: to set a string or number in a bloom filter
get: to get a string has been in a bloom filter
delete: to delete a bloom filter
try: to calculate the memory the bloom filter will malloc
stats: to see the server status

