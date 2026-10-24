# micronaut.validation Skill

Use this skill to work with Norm module `micronaut.validation` version 4. Use only declarations listed below.

## `micronaut.validation`

Source: `JavaArrays.norm`

### `JavaClassArray`

```norm
class JavaClassArray
```

#### `JavaClassArray`

```norm
JavaClassArray(JavaClassArrayBindingToken token)
```

Parameters:

- `token`: `JavaClassArrayBindingToken`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `get`

```norm
Class<?>? get(Integer index)
```

Parameters:

- `index`: `Integer`

Returns: `Class<?>?`

#### `set`

```norm
Void set(Integer index, Class<?>? value)
```

Parameters:

- `index`: `Integer`
- `value`: `Class<?>?`

Returns: `Void`

### `javaClassArrayNew`

```norm
JavaClassArray javaClassArrayNew(Integer size)
```

Parameters:

- `size`: `Integer`

Returns: `JavaClassArray`

## `micronaut.validation`

Source: `Validated.norm`

### `Validated`

```norm
annotation Validated implements TypeTarget, FunctionTarget, RuntimeRetention, InheritedAnnotation
```

#### `groups`

```norm
List<Class<?>> groups
```

Type: `List<Class<?>>`

#### `Validated`

```norm
Validated(List<Class<?>>? groups)
```

Parameters:

- `groups`: `List<Class<?>>?`

