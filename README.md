# DBMS-PL-SQL-2
BEGIN
declare
n int(4);
declare fac,i int(4);
 
set i=1,n=5,fac=1;
while(i<=n) do
set fac=fac*i;
set i=i+1;
end while;
select fac;
END
