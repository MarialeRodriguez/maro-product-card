# maro-product-card

Este es un paquete de pruebas de despliegue en NPM

### Maria Alejandra Rodriguez Osorio

## Ejemplo
```
import { ProductCard, ProductImage, ProductTitle,ProductButtons } from 'mr-product-card';
```
```
<ProductCard  
        product={ product }
        initialValues={{
            count: 4,
            maxCount: 10,
        }}
>
        {
        ({ reset, count, isMaxCountReached, maxCount, increaseBy }) => (
        <>
            <ProductImage />
            <ProductTitle />
            <ProductButtons />
        </>
        )
        }
</ProductCard>
```
