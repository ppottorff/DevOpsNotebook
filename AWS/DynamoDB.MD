# DynamoDB Reference
DynamoDB is an AWS managed NoSQL database service that charges based on throughput. Where it has limits per table, it is designed for extremely high-velocity use cases. Tables can be general purpose or specifically for infrequent access. It can be used on demand and with provisioned capacity to reduce cost. It can also be purchased with 1-3 yr reservations to further reduce cost.
 <details><summary>Basics of tables, items, and attributes</summary>

1. **Attributes** - Like a column. It's a data element or field. Attributes can only have one value.
2. **Nested Attributes** - You can nest attributes up to 32 levels deep. Think multiple Phone Number attributes for person.
2. **Items** - Like a row. Each item represents a record. There's no limit per table for Items.
3.  **Table** - similar to other database systems. However what you store in each Item is more like the Union join you could create in a relational Db.
</details>