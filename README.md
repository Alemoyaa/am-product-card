# AM-Product-Card

This is a deployment test package in NPM


### Alejandro Moya

## Ejemplo

```
import {
    ProductCard,
    ProductImage,
    ProductTitle,
    ProductButtons
} from 'am-product-card'
```

```

            <ProductCard
                product={product}
                key={product.id}
                initialValues = {{
                    count: 4,
                    maxCount: 10
                }}
            >
                {
                    ({ count, increaseBy, reset }) => (
                        <>
                            <ProductImage />
                            <ProductTitle />
                            <ProductButtons />
                        </>
                    )
                }
            </ProductCard>
```