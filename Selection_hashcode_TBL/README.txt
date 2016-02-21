===
Algorithm description

1. Sort order by size (smaller one first)

--
2. Foreach turn
> Foreach non-completed order
>> Foreach product type of the order
>>> Find the closest warehouse containing given product type 
>>> Find the closest non-busy drone of the previously found closest warehouse
>>> Load and deliver maximum possible product type to order with previously found drone

3. Compute score
===
