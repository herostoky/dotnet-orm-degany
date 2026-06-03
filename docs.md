## Public file to expose: 
- class DbContext :
  * every changes in the DBSets of the context will be tracked, only executed when doing a SaveChanges()   
- abstract DbSet of T (implementation of IEnumerable) :
   * Find(object[] keys)
   * Add(T entity)
   * Remove(T entity)
   * Update(T entity)


## References: 

### [ORM]
- https://www.prisma.io/dataguide/types/relational/what-is-an-orm#do-i-need-an-orm 

### [ENTITY FRAMEWORK]
- https://www.excella.com/insights/entity-framework-core-the-cross-platform-orm-for-net
- https://learn.microsoft.com/en-us/ef/core/miscellaneous/internals/
- https://www.youtube.com/watch?v=5U2y__coNAQ
- https://medium.com/@leonardomartins_27620/navigating-seamless-data-management-entity-framework-dapper-and-nhibernate-comparison-eff318c44b0e
- https://www.infoq.com/articles/deep-diving-ef-core-jeremy-likness/
- https://www.roji.org/efcore-cross-database-suport/

### [CSHARP EXPRESSIONS]
- https://www.c-sharpcorner.com/article/understanding-expressions-in-c-sharp-dynamic-code-and-query-generation/








