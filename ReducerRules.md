#Regrlas de un recucer

Que es un reducer?

Es una funcion comun y corriente, debe ser una funcion pura, es decir no debe llamar a otra funciones y toda su logica debe resolverse
internamente, esta siempre debe retornar un nuevo esta y lo normal es que esta solo reciba 2 argumentos (initialState y Action)

Reglas de los reducer

1-Debe resolver todo internamente sin recurrir a funciones externas
2-No debe tener tareas asincronas, siempre debe tener solamente tareaas sincronas
3-Retornasr siempre un nuevo estado sin mutar original
4-No debe llamr el local o session storage internamente (porque rompen la regla 1) dado que ests pueden devolver undefined o error
y estas siempre deben devolver un nuevo state
5- para modificar un state solo debe utilizarce una action y esta puede o no tener argumentos
