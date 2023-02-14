# simple-terraform-serverless

Simple example of using Terraform to create a new CockroachDB Serverless Cluster

1. Initialize the provider.

```
terraform init
```

2. Create the Terraform plan. This shows the actions the provider will take, but won't perform them.

```
terraform plan
```

3. Create the cluster.

```
terraform apply
```

See full instructions documented here: [terraform-provider-cockroach](https://github.com/cockroachdb/terraform-provider-cockroach)
