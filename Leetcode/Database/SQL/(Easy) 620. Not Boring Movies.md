[620. Not Boring Movies](https://leetcode.com/problems/not-boring-movies/description/)

**MySql**
```sql
SELECT * FROM Cinema WHERE id % 2 <> 0 AND description <> "boring" ORDER BY rating DESC
```