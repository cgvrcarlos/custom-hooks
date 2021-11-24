# useForm Hook

Ejemplo de uso:

```
const initialForm = {
	inputsFormulario: 'inicializacion',
};

const [ formValues, handleInputChange, reset ] = useForm(initialForm);
```

## `formValues`

Es un arreglo que guarda los estados de cada uno de los inputs en el formulario.

## `handleInputChange`

Una función encargada de actualizar los valores con cada entrada en el formulario.

## `reset`

Resetea los inputs despues de un submit.
