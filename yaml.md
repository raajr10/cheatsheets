# yaml

Extension - .yaml, .yml

Full form - Yaml aint markup language

It is a serialisation language like xml, json. It is a common, standard format while transferring data.

## Features
* human readable & intuitive
* Can be useful for writing configs

<b>Line separation & indentation</b> is really important

Example:
1. use cases 
2. docker compose
3. k8s
4. ansible

## key-value pairs
key: value

Example:
```
port: 9000
version: 1.0
```

comments - #

## objects
```
metadata:
  name: <>
  label: <>
  annotations: <>
```

recommended to use yaml extensions/validator

## lists
```
containers:
  - name:
    image: 
  - name:
    image:
containers: [v1, v2]
```


## boolean - true/false, yes/no, on/off

## multi line string
```
multiLine String: |-
    line 1
    line 2
    line 3
```

## env variable
$VARIABLE

## placeholder
{{ }}

## multiple yaml documents
---