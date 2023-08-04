JSX (JavaScript XML), JavaScript ve XML benzeri sözdizimlerinin birleşiminden oluşan, React'ta kullanılan bir syntax uzantısıdır. JSX, JavaScript'te XML benzeri bir syntax kullanarak, React bileşenlerinin görünümünü tanımlamak için kullanılır.

JSX, JavaScript ifadelerini HTML benzeri elementlere dönüştürmek için kullanılır. Bu sayede, React bileşenleri oluşturmak daha kolay ve okunaklı hale gelir. Bu duruma `syntatic sugar` adı verilir.

JSX ile yazılan kodlar, `babel` aracılığıyla JavaScript'e derlenir.

```js
const Title = (props) => {
	return (
		<h1 className='title' {...props}>Hello world! </h1>
	)
}

ReactDOM.render(Title, document.getElementById('root'));
```

```js
const Title = (props) => {
	return (
		React.createElement(
		'h1',
		{ className='title', ...props},
		'Hellor world!'
		)
	)
}

ReactDOM.render(Title, document.getElementById('root'));
```

