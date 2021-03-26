# ex_polars

This is a Elixir nif based on [Polars](https://github.com/ritchie46/polars). 

[![Build Status](https://travis-ci.org/thanos/ex_polars.svg?branch=main)](https://travis-ci.org/thanos/ex_polars)


## Installation

Add `ex_polars` to your list of dependencies in `mix.exs`:

```
def deps do
  [{:ex_polars, "~> 0.1.0"}]
end
```


Why am I spending time wrapping Polars when I could invest into NX? Well its a question of need. I need Polars now but once this requirement is met I will take what was laeernt and focus on NX.

Polars currently consists of an eager API similar to pandas and a lazy API that is somewhat similar to spark. 


To learn more about the inner workings of Polars read the [WIP book](https://ritchie46.github.io/polars-book/).




## Polars Functionality still to do

- [ ] Filters    
- [ ] Shifts                       
- [ ] Joins
- [ ] GroupBys + aggregations  
- [ ] Comparisons  
- [ ] Arithmetic
- [ ] Sorting 
- [ ] Reversing             
- [ ] Closure application (User Defined Functions) 
- [ ] SIMD
- [ ] Pivots         
- [ ] Melts  
- [ ] Filling nulls + fill strategies 
- [ ] Aggregations       
- [ ] Moving Window aggregates       
- [ ] Find unique values   
- [ ] Rust iterators  
- [ ] IO (csv, json, parquet, Arrow IPC  
- [ ] Query optimization: (predicate pushdown)
- [ ] Query optimization: (projection pushdown) 
- [ ] Query optimization: (type coercion)
- [ ] Query optimization: (simplify expressions)  
- [ ] Query optimization: (aggregate pushdown)   



## Documentation
There's lost of good documentaion at https://github.com/ritchie46/polars/edit/master/README.md




