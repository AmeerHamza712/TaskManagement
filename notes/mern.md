# MongoDB Notes Today

## Day-1 (Date-30-7-2026)

1---
lookup
{
"$lookup": {
"from": "customer",
"localField": "id",
"foreignField": "customer_id",
"as": "customer_details"
}
}

# Day-2
