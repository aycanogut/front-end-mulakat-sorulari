Karmaşık veri yapılarını bir arada tanımlamak için kullanılan özelliklerdir.

`type` yapısı genel olarak primitive, union, intersection, tuple ya da benzeri tip tanımlamaları için kullanılır.

```ts
type Point = {
  x: number;
  y: number;
}

// primitive
type Address = string;

// union
type Transport = 'Bus' | 'Car' | 'Bike' | 'Walk';
```

`interface` yapısı genel olarak bir verinin (bir obje gibi) türünü belirlemek için kullanılır.

```ts
interface Person { 
	name: string;
	age: number; 
	greet(): void; 
}
```

