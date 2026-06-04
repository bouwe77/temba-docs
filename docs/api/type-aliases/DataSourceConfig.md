# Type Alias: DataSourceConfig

> **DataSourceConfig** = \{ `type`: `"memory"`; \} \| \{ `filename`: `string`; `type`: `"file"`; \} \| \{ `folder`: `string`; `type`: `"folder"`; \} \| \{ `authSource?`: `string`; `connectTimeoutMS?`: `number`; `maxPoolSize?`: `number`; `minPoolSize?`: `number`; `password?`: `string`; `readPreference?`: `string`; `replicaSet?`: `string`; `serverSelectionTimeoutMS?`: `number`; `tls?`: `boolean`; `tlsAllowInvalidCertificates?`: `boolean`; `tlsCAFile?`: `string`; `tlsCertificateKeyFile?`: `string`; `type`: `"mongodb"`; `uri`: `string`; `username?`: `string`; `writeConcern?`: `string`; \}

Defined in: [config/index.ts:8](https://github.com/bouwe77/temba/blob/6cf83f6030587f43dbcde01143a958210eaee651/packages/temba/src/config/index.ts#L8)

## Type Declaration

\{ `type`: `"memory"`; \}

### type

> **type**: `"memory"`

In-memory storage — data is lost on restart

\{ `filename`: `string`; `type`: `"file"`; \}

### filename

> **filename**: `string`

### type

> **type**: `"file"`

Single JSON file on disk — all resources stored in one file

\{ `folder`: `string`; `type`: `"folder"`; \}

### folder

> **folder**: `string`

### type

> **type**: `"folder"`

Folder of JSON files on disk — one file per resource

\{ `authSource?`: `string`; `connectTimeoutMS?`: `number`; `maxPoolSize?`: `number`; `minPoolSize?`: `number`; `password?`: `string`; `readPreference?`: `string`; `replicaSet?`: `string`; `serverSelectionTimeoutMS?`: `number`; `tls?`: `boolean`; `tlsAllowInvalidCertificates?`: `boolean`; `tlsCAFile?`: `string`; `tlsCertificateKeyFile?`: `string`; `type`: `"mongodb"`; `uri`: `string`; `username?`: `string`; `writeConcern?`: `string`; \}

### authSource?

> `optional` **authSource**: `string`

Authentication database, defaults to 'admin'

### connectTimeoutMS?

> `optional` **connectTimeoutMS**: `number`

Timeout (ms) for initial connection

### maxPoolSize?

> `optional` **maxPoolSize**: `number`

Maximum number of connections in the connection pool

### minPoolSize?

> `optional` **minPoolSize**: `number`

Minimum number of connections in the connection pool

### password?

> `optional` **password**: `string`

Password for authentication (alternative to embedding in URI)

### readPreference?

> `optional` **readPreference**: `string`

Read preference (e.g. 'primary', 'secondary', 'nearest')

### replicaSet?

> `optional` **replicaSet**: `string`

Replica set name

### serverSelectionTimeoutMS?

> `optional` **serverSelectionTimeoutMS**: `number`

Timeout (ms) for server selection

### tls?

> `optional` **tls**: `boolean`

Enable TLS/SSL

### tlsAllowInvalidCertificates?

> `optional` **tlsAllowInvalidCertificates**: `boolean`

Allow invalid TLS certificates (not recommended for production)

### tlsCAFile?

> `optional` **tlsCAFile**: `string`

Path to the CA certificate file

### tlsCertificateKeyFile?

> `optional` **tlsCertificateKeyFile**: `string`

Path to the client certificate/key file

### type

> **type**: `"mongodb"`

### uri

> **uri**: `string`

### username?

> `optional` **username**: `string`

Username for authentication (alternative to embedding in URI)

### writeConcern?

> `optional` **writeConcern**: `string`

Write concern (e.g. 'majority')

MongoDB database
