# RSR-Product-Card

Este es un paquete de pruebas de despliegue a NPM

## Ejemplo

```
import {ProductCard,ProductImage,ProductTitle,ProductButtons} from 'rsr-product-card'
```

```
    <ProductCard 
        product={product}
        initialValues={{
            count:4,
            maxCount: 10
        }}
    >
        {
            ({reset, count, increaseBy, isMaxCountReached}) => (
                <>
                    <ProductImage/>
                    <ProductTitle/>
                    <ProductButtons/>
                </>
            )
        }

    </ProductCard>
```