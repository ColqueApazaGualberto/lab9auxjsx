#Si se trabaja con archivos .tsx, se utiliza TypeScript con JSX. En este caso, el código se verá casi idéntico al código en JavaScript, pero con la diferencia de que se nesecita especificar los tipos de datos para garantizar la integridad y seguridad del código.
El tipado se veria asi:
interface Product {
    title: string;
    description: string;
    brand: string;
    price: number;
}
