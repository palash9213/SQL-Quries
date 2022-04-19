# SQL-Quries
select
branch_master.branch_city, count(account_master.account_number) as No_of_Accounts from branch_master left join account_master on account_master.branch_id=branch_master.branch_id
group by branch_master.branch_city order by branch_city
