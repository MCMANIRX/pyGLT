# pyGLT

Python rewrite of GLTool for Super Mario Strikers (2005) and Mario Strikers Charged (2007).

Capable of handling .glt, beta .glt, and .rlt formats, supporting CMPR and RGB5a3 encodings.

## Usage

```python
python name.glt [enc|dec]
```

## Features

| Encoding | Encode | Decode |
|-------------|-|--------------|
| CMPR | Yes | Yes
| RGB5a3| Yes | Yes*

*NOTE: Some stage textures might not properly extract.