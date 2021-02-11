## API Report File for "@dcl/schemas"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { JSONSchemaType } from 'ajv';
import { ValidateFunction } from 'ajv';

// Warning: (ae-missing-release-tag) "generateValidator" is exported by the package, but it is missing a release tag (@alpha, @beta, @public, or @internal)
//
// @public (undocumented)
export function generateValidator<T>(schema: Schema<T>): ValidateFunction<T>;

// Warning: (ae-missing-release-tag) "MetaTransaction" is exported by the package, but it is missing a release tag (@alpha, @beta, @public, or @internal)
// Warning: (ae-missing-release-tag) "MetaTransaction" is exported by the package, but it is missing a release tag (@alpha, @beta, @public, or @internal)
//
// @public (undocumented)
export type MetaTransaction = {
    from: string;
    params: [string, string];
};

// @public (undocumented)
export namespace MetaTransaction {
    const // (undocumented)
    schema: Schema<MetaTransaction>;
    const // (undocumented)
    validate: ValidateFunction<MetaTransaction>;
}

// Warning: (ae-missing-release-tag) "Schema" is exported by the package, but it is missing a release tag (@alpha, @beta, @public, or @internal)
//
// @public (undocumented)
export type Schema<T> = JSONSchemaType<T>;

export { ValidateFunction }


// (No @packageDocumentation comment for this package)

```