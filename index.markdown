# ePlus

A set of database conventions based off of Laravel's [Eloquent](https://laravel.com/docs/10.x/eloquent) database model.

## Field Order

Fields are orgamized by field type. Fields are placed in the following order:

 - id (primary key)
 - char, varchar, and text
 - blob, binary, and varbinary
 - json
 - interger, smallint, tinyint, mediumint, and bigint
 - decimal, numeric, float, and double
 - enums and sets
 - foreign keys
 - dates
 - timestamps
 - soft deletes

---

<a href="https://codeadam.ca">
<img src="https://codeadam.ca/images/code-block.png" width="50">
</a>
