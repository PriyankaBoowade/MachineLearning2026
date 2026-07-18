\# Data Dictionary — Lab 1



| Table | Column | Data Type | Description | Example |

|---|---|---|---|---|

| customers | customer\_id | String | Unique identifier for each order made by a customer | abc123 |

| customers | customer\_unique\_id | String | Permanent identifier for a real customer, same across all their orders | xyz456 |

| customers | customer\_city | String | City where the customer is located | sao paulo |

| customers | customer\_state | String | State where the customer is located | SP |

| orders | order\_id | String | Unique identifier for each order | ord789 |

| orders | order\_status | String | Current status of the order (delivered, shipped, canceled, etc.) | delivered |

| orders | order\_purchase\_timestamp | Date | Date and time the order was placed | 2018-01-05 |

| order\_items | order\_id | String | Identifier linking this item to its order | ord789 |

| order\_items | product\_id | String | Identifier of the product purchased | prod001 |

| order\_items | seller\_id | String | Identifier of the seller who sold the item | sell001 |

