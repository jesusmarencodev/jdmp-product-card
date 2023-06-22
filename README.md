# jdmp-product-card

Este es un paquete de prueba de despliegue NPM

### Jesus Dario Marenco Porto

##Ejemplo
```
import {ProductCard, ProductImage, ProductTitle, ProductButtons} from 'jdmp-product-card';
```

```
<ProductCard
  product={product}
  initialValues={{
    count: 4,
  }}
>
  {({ reset, count, increaseBy, isMaxCountReached }) => (
    <>
      <ProductImage />
      <ProductTitle />
      <ProductButtons/>
    </>
  )}
</ProductCard>
```
