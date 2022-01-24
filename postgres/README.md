# Postgres Intent


## Sizing

An Intent providing tshirt sizing for the Postgres Instances

### Defined by

Central Platform/DevOps Teams

### Filename
sizing_<flavour>.json

### Schema location
Include this in your json file to get autocomplete
```
{
"$schema": "https://docs.facets.cloud/schemas/postgres/sizing_<flavour>.schema",
}
```

## Postgres

### Defined by

Individual Developers/ Development teams

### Filename
instances/{postgres-name}.json

### Schema location
Include this in your json file to get autocomplete
```
{
"$schema": "https://docs.facets.cloud/schemas/postgres/instances/sample.schema",
}
```
