(select country from customers) union (select country from suppliers);
(select country from customers) union all (select country from suppliers);
(select country from customers) intersect (select country from suppliers);
