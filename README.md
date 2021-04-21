# MOZ\_lightmap

## Contributors

* Takahiro Aoyagi, Mozilla, [@takahirox](https://github.com/takahirox)

## Status

Draft

## Dependencies

Written against the glTF 2.0 spec.

## Overview

T.B.D.

## Example screenshot

T.B.D.

## Defining light map

```
"materials": [
    {
        "pbrMetallicRoughness": {
            "baseColorFactor": [ 1.0, 0.0, 0.0, 1.0 ],
            "baseColorTexture": {
                "index": 0
            },
        },
        "extensions": {
            "MOZ_lightmap": {
                index: 1,
                intensity: 1.0
            }
        }
    }
]
```

## Fallback

T.B.D.

## Toon material Types

| Property | Type | Description | Requires |
|:------|:------|:------|:------|
| `index` | `integer` | The index of texture. | :white_check_mark: Yes |
| `intensity` | `number` | light map intensity | No, default is `1.0` |
