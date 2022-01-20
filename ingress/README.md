# Ingress Intent

While all facets applications are accessible via their internal DNS within the facets provisioned Kubernetes cluster, to make them accessible from outside it, one would require an ingress. An ingress could be internet facing or internal to the network it resides in.

## Ingress Instance

### Filename
instances/{ingress-name}.json

### Defined by

Central Platform/DevOps Teams

### Schema location
Include this in your json file to get autocomplete
```
{
"$schema": "https://docs.facets.cloud/schemas/ingress/instances/ingress.schema",
}
```