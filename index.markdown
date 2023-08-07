# eplus

A set of database conventions used in addition to Laravel's [Eloquent](https://laravel.com/docs/10.x/eloquent) database model.

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

## Dates

All date and time fields are named after their event and then `_at`. For example `published_at`. 

The default timestamps fieldnames are `creadted_at` and `updated_at`. The default soft delete field name is `deleted_at`. 

---

<a href="https://codeadam.ca">
<img src="https://codeadam.ca/images/code-block.png" width="50">
</a>


<style>@import url("//readme.codeadam.ca/readme.css");</style>
