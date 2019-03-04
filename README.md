# Mapping Function
It maps on range of values to another range.

## Javascript
```javascript
function map(value, vmin, vmax, min, max)
{
    return (((value - vmin) / (vmax - vmin)) * (max - min)) + min;
}
```

## Typescript
```typescript
function map(value : number, vmin : number, vmax : number, min : number, max : number) : number
{
    return (((value - vmin) / (vmax - vmin)) * (max - min)) + min;
}
```

## Python
```python
def map(value, vmin, vmax, min, max):
    return (((value - vmin) / (vmax - vmin)) * (max - min)) + min;
```

## C
```C
double map(double value, double vmin, double vmax, double min, double max)
{
    return (((value - vmin) / (vmax - vmin)) * (max - min)) + min;
}
```

## PHP
```php
function map($value, $vmin, $vmax, $min, $max)
{
    return ((($value - $vmin) / ($vmax - $vmin)) * ($max - $min)) + $min;
}
```

