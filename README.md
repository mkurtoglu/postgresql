[postgres@node1 ~]$ sh postgresql_index_advice.sh 5433 postgres "select * from test ,test t2 where test.x=t2.x and  test.y='fsdf' "

table:test adviced_index_columns:y  index_create_script : create index ix_sample_20230505143335 on test ( y)  psql_bash_command: psql -p5433 -d postgres -c "create index ix_sample_20230505143335 on test ( y)"

