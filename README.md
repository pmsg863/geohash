# geohash
geohash oracle function 存储过程

plsql 调用 java.class 实现geohash的功能
Geohash_encode(lat,lon,geohash_length);

示例
select Geohash_encode(24.52, 117.94,6) from dual;

return 'ws7g7z';
