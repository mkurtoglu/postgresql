# postgresql
postgresql_index_advice code usage
bash script.
parameters 
1. port of postgresql cluster
2. database name
3. sql in double quotes 

# sh  postgresql_index_advice.sh 5433 postgres "explain select * from test ,test t2 where test.x=t2.x and   t2.y2='ASFD' and t2.y ='asdfa' "
# table:test adviced_index_columns:y y2
