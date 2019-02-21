# CascadeType.REMOVEJPAHibernate

JPA Cascade types

The cascade types supported by the Java Persistence Architecture are as below:

CascadeType.PERSIST (continue, carry on): means that save() or persist() operations cascade (waterfall) to related entities.

CascadeType.MERGE (join together): means that related entities are merged when the owning entity is merged.

CacadeTpe.REFRESH: does the same thing for the refresh() operation.

CascadeType.REMOVE: removes all related entities association with this setting when the owning entity is deleted.

CascadeType.DETACH (unfasten, disconnect): detaches all related entities if a “manual detach” occurs.

CascadeType.ALL: is shorthand for all the above cascade operations.
