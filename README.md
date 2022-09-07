# TA-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Tomas Arcostanzo

## Ejemplo

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'ta-product-card'
```

```
const product = {
    id: '1',
    title: 'Coffee Mug - Card',
    img: './coffee-mug.png',
};


    <ProductCard
        product={product}
        initialValues = {{
            quantity: 4,
            // maxQuantity: 10,
        }}
    >
        {
            ( {reset, quantity, isMaxQuantityReached, increaseBy, maxQuantity} ) => (
                <>
                    <ProductImage />
                    <ProductTitle  />
                    <ProductButtons />
                </>
            )
        }
    </ProductCard>



```
