# Tarjeta de producto

Este es un paquete de pruebas de despliegue a NPM.


## Ejemplo
```
import { ProductImage, ProductTitle, ProductButtons } from cd-tarjeta-producto
```


```
<ProductCard
    product={product}
    initialValues={{
        count: 6,
        //maxCount: 10,
    }}
>
    {({ reset, count, isMaxCountReached, maxCount, increaseBy }) => (
        <>
            <ProductImage />
            <ProductTitle />
            <ProductButtons />
        </>
    )}
</ProductCard>
```