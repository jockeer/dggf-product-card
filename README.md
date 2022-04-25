# DGGF-Product-Card

Paquete de pruebas de despliegue en NPM

### Daniel Gorianz

### Ejemplo

```
import {ProductCard, ProductImage, ProductTitle, ProductButtons } from 'dggf-product-card'
```
```
<ProductCard 
    product={product}
    initialValues= {{
    count: 6,
    maxCount: 10,
    }} 
>
    {
    ({reset, increaseBy,isMaxCountReached, count}) => (
        <>
        <ProductImage />
        <ProductTitle />
        <ProductButtons />
        
        </>
    )

    }
</ProductCard>
```