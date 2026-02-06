
<img width="1052" height="206" alt="image" src="https://github.com/user-attachments/assets/97358d6a-101c-48d8-be92-f24a745b0e58" />

Academic archived lessons & activities from Information Management courses (IM1 & IM2)


### SQL Operators

| Operator | Use Case | Example |
|----------|----------|---------|
| `LIKE '%text%'` | Pattern matching | Find names containing "John" |
| `IN (...)` | Multiple values | Countries in ('US', 'UK', 'CA') |
| `BETWEEN x AND y` | Range filtering | Age between 18 and 65 |

### SQL Join Types

| Join Type | Returns |
|-----------|---------|
| **INNER JOIN** | Only matching records from both tables |
| **LEFT JOIN** | All from left table + matches from right |
| **RIGHT JOIN** | All from right table + matches from left |
| **FULL OUTER JOIN** | All records from both tables |
| **CROSS JOIN** | All possible combinations (Cartesian product) |
| **SELF JOIN** | Table joined to itself |

### Analytic Functions Quick Guide

```sql
-- Ranking
RANK() OVER (ORDER BY column)
DENSE_RANK() OVER (ORDER BY column)
ROW_NUMBER() OVER (ORDER BY column)

-- Window Aggregates
SUM(column) OVER (ORDER BY date ROWS UNBOUNDED PRECEDING)
AVG(column) OVER (ORDER BY date ROWS BETWEEN 1 PRECEDING AND 1 FOLLOWING)

-- Ratio Comparisons
RATIO_TO_REPORT(column) OVER (PARTITION BY group)
CUME_DIST() OVER (ORDER BY column)
PERCENT_RANK() OVER (ORDER BY column)
```

---

## Database Types Reference

| Type | Description | Example |
|------|-------------|---------|
| **Relational** | Tables with rows/columns | MySQL, PostgreSQL, Oracle |
| **NoSQL** | Flexible, non-tabular | MongoDB, Cassandra |
| **Distributed** | Data across multiple nodes | Apache Cassandra, HBase |
| **Cloud** | Hosted in cloud environment | AWS RDS, Azure SQL |
| **Hierarchical** | Tree-like parent-child | IBM IMS |




##  Additional Resources

- [W3Schools SQL Tutorial](https://www.w3schools.com/sql/)
- [SQLZoo Interactive Tutorials](https://sqlzoo.net/)
- [Mode Analytics SQL Tutorial](https://mode.com/sql-tutorial/)
- [PostgreSQL Documentation](https://www.postgresql.org/docs/)


---

**Happy Learning! 🎓**

*Last Updated: February 2026*
