# JV-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Johan Vergara

## Ejemplo
```
import { 
    ProductCard, 
    ProductButtons, 
    ProductImage, 
    ProductTitle 
} from 'jv-product-cart'
```
```
<ProductCard
    product={ product }
    initialValues={{
        count: 4,
        // maxCount: 10,
    }}
>
    {
        ({ reset, count, increaseBy, isMaxCountReached, maxCount }) => (
            <>
                <ProductImage />
                <ProductTitle />
                <ProductButtons />
            </>
        )
    }
</ProductCard>
```