# Do-Product-card

Estes es un paquete de pruebas de despliegue en NPM

### Daniel Hernandez

## Ejemplo

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'dh-product-card';
```

```
<ProductCard
    product={product}
    initialValues={{
        count: 5,
        // maxCount: 10,
    }}
    >
    {({ count, increaseBy, isMaxCountReached, maxCount, reset }) => (
        <>
        <ProductImage />
        <ProductTitle />
        <ProductButtons />
        </>
    )}
</ProductCard>
```
