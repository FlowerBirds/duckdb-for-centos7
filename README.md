# duckdb-for-centos7
duckdb仓库默认构建时使用的是ubuntu-24.04版本，其glibc为2.28版本，但是在CentOS7中使用的glibc 2.17版本，故默认构建和发布到maven仓库的duckdb_jdbc包中so均无法在centos7下面使用，故单独编译so解决此问题。

# DuckDB
https://github.com/duckdb/duckdb
