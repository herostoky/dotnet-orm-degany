Public file to expose: 
- class DbContext :
  * every changes in the DBSets of the context will be tracked, only executed when doing a SaveChanges()   
- abstract DbSet of T (implementation of IEnumerable) :
   * Find(object[] keys)
   * Add(T entity)
   * Remove(T entity)
   * Update(T entity)


