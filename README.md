# Map compositions schema

Presentation about map compositions: https://tinyurl.com/thc3hxw

Specific version of map compositions JSON schema is published in tagged commits, eg.
https://raw.githubusercontent.com/hslayers/map-compositions/1.0.0/schema.json

The $id parameter defines the unique identifier and the resource URL of the raw schema.json file at the same time.

```
{
  "$schema": "http://json-schema.org/draft-07/schema#",
  "$id": "https://raw.githubusercontent.com/hslayers/map-compositions/1.0.0/schema.json",
  ...
}
```

Version numbering follows the semantic versioning notation in the form of MODEL.REVISION.ADDITION

*MODEL breaking schema change is carried out which will prevent interaction with any historical data
*REVISION schema change which may prevent interaction with some historical data
*ADDITION schema change that will not cause any incompatibility with historical data

See [SchemaVer](https://snowplowanalytics.com/blog/2014/05/13/introducing-schemaver-for-semantic-versioning-of-schemas/#schemaver) for details.
