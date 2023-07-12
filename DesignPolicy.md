# Protobuf design policy

## Versioning

New service proposals must be created as beta versions.

In example the newly created version 1 for SomeTestService must use version `v1beta1`.
For each breaking changing in this version 1 proposal the number of beta versions must be increased, so the next version will have `v1beta2`.

Once the version is stable only the version it self must be used, in example `v1`.

## Service Names
Service names should use singular naming, e.g. for a service providing functions for `Items` the service should be named `ItemService`.
