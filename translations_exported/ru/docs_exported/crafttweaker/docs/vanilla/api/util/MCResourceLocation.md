# Расположение MCResource-ресурсов

## Импорт класса

It might be required for you to import the package if you encounter any issues (like casting an Array), so better be safe than sorry and add the import at the very top of the file.
```zenscript
import crafttweaker.api.util.MCResourceLocation;
```


## Implemented Interfaces
MCResourceLocation implements the following interfaces. That means all methods defined in these interfaces are also available in MCResourceLocation

- Comparable&lt;[MCResourceLocation](/vanilla/api/util/MCResourceLocation)&gt;

## Constructors


```zenscript
new MCResourceLocation(namespace as string, path as string) as MCResourceLocation
```

| Параметр          | Тип    | Description                                                          |
| ----------------- | ------ | -------------------------------------------------------------------- |
| пространство имён | string | Usually a ModId                                                      |
| path              | string | May only contain lower-cased alphanumeric values, as well as / and _ |



## Утилиты

| Тип результата                   | Является неявным |
| -------------------------------- | ---------------- |
| [IData](/vanilla/api/data/IData) | true             |
| string                           | true             |

## Methods

### asData

Return Type: [IData](/vanilla/api/data/IData)

```zenscript
MCResourceLocation.asData() as IData
myMCResourceLocation.asData();
```

### сравнить

Return Type: int

```zenscript
MCResourceLocation.compareTo(other as MCResourceLocation) as int
```

| Параметр | Тип                                                                      | Description             |
| -------- | ------------------------------------------------------------------------ | ----------------------- |
| other    | [Расположение MCResource-ресурсов](/vanilla/api/util/MCResourceLocation) | No Description Provided |


### equals

Return Type: boolean

```zenscript
MCResourceLocation.equals(other as Object) as boolean
```

| Параметр | Тип    | Description             |
| -------- | ------ | ----------------------- |
| other    | Object | No Description Provided |


### getNamespace

Return Type: string

```zenscript
MCResourceLocation.getNamespace() as string
myMCResourceLocation.getNamespace();
```

### getPath

Return Type: string

```zenscript
MCResourceLocation.getPath() as string
myMCResourceLocation.getPath();
```

### hashCode

Return Type: int

```zenscript
MCResourceLocation.hashCode() as int
myMCResourceLocation.hashCode();
```

### toString

Return Type: string

```zenscript
MCResourceLocation.toString() as string
myMCResourceLocation.toString();
```


## Свойства

| Название          | Тип    | Имеет Getter | Имеет Setter |
| ----------------- | ------ | ------------ | ------------ |
| commandString     | string | true         | false        |
| пространство имён | string | true         | false        |
| path              | string | true         | false        |

