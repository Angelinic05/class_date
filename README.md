# Clase `Date` en JavaScript

En JavaScript, la clase `Date` se utiliza para trabajar con fechas y horas. Aquí hay una descripción de las principales propiedades y métodos de la clase `Date`:

## Propiedades:

1. **`Date.prototype.constructor`**: Retorna la función que creó el prototipo del objeto.

   ```javascript
   const date = new Date()
   console.log(date.constructor());
   ```

2. **`Date.prototype.getDate()`**: Retorna el día del mes (1-31) para la fecha especificada según la hora local.

   ```javascript
   const date = new Date()
   console.log(date.getDate());
   ```

3. **`Date.prototype.getDay()`**: Retorna el día de la semana (0-6) para la fecha especificada según la hora local.

   ```javascript
   const date = new Date()
   console.log(date.getDay());
   ```

4. **`Date.prototype.getFullYear()`**: Retorna el año (4 dígitos para fechas con años AD) de la fecha especificada según la hora local.

   ```javascript
   const date = new Date()
   console.log(date.getFullYear());
   ```

5. **`Date.prototype.getHours()`**: Retorna la hora (0-23) de la fecha especificada según la hora local.

   ```javascript
   const date = new Date()
   console.log(date.getHours());
   ```

6. **`Date.prototype.getMilliseconds()`**: Retorna los milisegundos (0-999) de la fecha especificada según la hora local.

   ```javascript
   const date = new Date()
   console.log(date.getMilliseconds());
   ```

7. **`Date.prototype.getMinutes()`**: Retorna los minutos (0-59) de la fecha especificada según la hora local.

   ```javascript
   const date = new Date()
   console.log(date.getMinutes());
   ```

8. **`Date.prototype.getMonth()`**: Retorna el mes (0-11) para la fecha especificada según la hora local.

   ```javascript
   const date = new Date()
   console.log(date.getMonth());
   ```

9. **`Date.prototype.getSeconds()`**: Retorna los segundos (0-59) de la fecha especificada según la hora local.

   ```javascript
   const date = new Date()
   console.log(date.getSeconds());
   ```

10. **`Date.prototype.getTime()`**: Retorna el valor numérico correspondiente a la fecha y hora especificadas según la hora universal coordinada (UTC).

    ```javascript
    const date = new Date()
    console.log(date.getTime());
    ```

11. **`Date.prototype.getTimezoneOffset()`**: Retorna la diferencia de minutos entre la hora local y la hora UTC.

    ```javascript
    const date = new Date()
    console.log(date.getTimezoneOffset());
    ```

12. **`Date.prototype.getUTCDate()`**: Retorna el día del mes (1-31) para la fecha especificada según la hora UTC.

    ```javascript
    const date = new Date()
    console.log(date.getUTCDate());
    ```

13. **`Date.prototype.getUTCDay()`**: Retorna el día de la semana (0-6) para la fecha especificada según la hora UTC.

    ```javascript
    const date = new Date()
    console.log(date.getUTCDay());
    ```

14. **`Date.prototype.getUTCFullYear()`**: Retorna el año (4 dígitos para años AD) de la fecha especificada según la hora UTC.

    ```javascript
    const date = new Date()
    console.log(date.getUTCFullYear());
    ```

15. **`Date.prototype.getUTCHours()`**: Retorna la hora (0-23) de la fecha especificada según la hora UTC.

    ```javascript
    const date = new Date()
    console.log(date.getUTCHours());
    ```

16. **`Date.prototype.getUTCMilliseconds()`**: Retorna los milisegundos (0-999) de la fecha especificada según la hora UTC.

    ```javascript
    const date = new Date()
    console.log(date.getUTCMilliseconds());
    ```

17. **`Date.prototype.getUTCMinutes()`**: Retorna los minutos (0-59) de la fecha especificada según la hora UTC.

    ```javascript
    const date = new Date()
    console.log(date.getUTCMinutes());
    ```

18. **`Date.prototype.getUTCMonth()`**: Retorna el mes (0-11) para la fecha especificada según la hora UTC.

    ```javascript
    const date = new Date()
    console.log(date.getUTCMonth());
    ```

19. **`Date.prototype.getUTCSeconds()`**: Retorna los segundos (0-59) de la fecha especificada según la hora UTC.

    ```javascript
    const date = new Date()
    console.log(date.getUTCSeconds());
    ```

20. **`Date.prototype.setFullYear()`**: Establece el año para una fecha especificada según la hora local.

    ```javascript
    const date = new Date('December 05, 2002')
    date.setFullYear(2022)
    console.log(date);
    ```

21. **`Date.prototype.setHours()`**: Establece la hora para una fecha especificada según la hora local.

    ```javascript
    const date = new Date()
    date.setHours(10, 15, 04)
    console.log(date);
    ```

22. **`Date.prototype.setMilliseconds()`**: Establece los milisegundos para una fecha especificada según la hora local.

    ```javascript
    const date = new Date()
    date.setMilliseconds(20)
    console.log(date.getMilliseconds());
    ```

23. **`Date.prototype.setMinutes()`**: Establece los minutos para una fecha especificada según la hora local.

    ```javascript
    const date = new Date()
    date.setMinutes(30)
    console.log(date);
    ```

24. **`Date.prototype.setMonth()`**: Establece el mes para una fecha especificada según la hora local.

    ```javascript
    const date = new Date()
    date.setMonth(3)
    console.log(date);
    ```

25. **`Date.prototype.setSeconds()`**: Establece los segundos para una fecha especificada según la hora local.

    ```javascript
    const date = new Date()
    date.setSeconds(15)
    console.log(date);
    ```

26. **`Date.prototype.setTime()`**: Establece una fecha y hora según la hora universal coordinada (UTC) correspondiente al número de milisegundos especificado desde el 1 de enero de 1970 00:00:00 UTC.

    ```javascript
    const date = new Date()
    date.setTime(Date.UTC(2025, 2, 3, 5, 0, 0))
    console.log(date);
    ```

27. **`Date.prototype.setUTCDate()`**: Establece el día del mes para una fecha especificada según la hora UTC.

    ```javascript
    const date = new Date()
    date.setUTCDate(2)
    console.log(date);
    ```

28. **`Date.prototype.setUTCHours()`**: Establece la hora para una fecha especificada según la hora UTC.

    ```javascript
    const date = new Date()
    date.setUTCHours(20)
    console.log(date);
    ```

29. **`Date.prototype.setUTCMilliseconds()`**: Establece los milisegundos para una fecha especificada según la hora UTC.

    ```javascript
    const date = new Date()
    date.setUTCMilliseconds(14)
    console.log(date);
    ```

30. **`Date.prototype.setUTCMinutes()`**: Establece los minutos para una fecha especificada según la hora UTC.

    ```javascript
    const date = new Date()
    date.setUTCMinutes(25)
    console.log(date);
    ```

31. **`Date.prototype.setUTCMonth()`**: Establece el mes para una fecha especificada según la hora UTC.

    ```javascript
    const date = new Date()
    date.setUTCMonth(2)
    console.log(date);
    ```

32. **`Date.prototype.setUTCSeconds()`**: Establece los segundos para una fecha especificada según la hora UTC.

    ```javascript
    const date = new Date()
    date.setUTCSeconds(42)
    console.log(date);
    ```

## Métodos:

1. **`Date.now()`**: Retorna el valor numérico correspondiente al número de milisegundos desde el 1 de enero de 1970 00:00:00 UTC.

   ```javascript
   console.log(Date.now());
   ```

2. **`Date.parse()`**: Analiza una cadena de texto y devuelve el número de milisegundos desde el 1 de enero de 1970 00:00:00 UTC.

   ```javascript
   console.log(Date.parse("2024-02-13"));
   ```

3. **`Date.UTC()`**: Acepta los mismos parámetros que el constructor de fecha, pero interpreta los parámetros como una hora y fecha UTC (coordinada universalmente).

   ```javascript
   console.log(Date.UTC(2024, 1, 13));
   ```

4. **`Date.prototype.toDateString()`**: Retorna la parte de la fecha de la instancia de Date como una cadena legible para humanos en el formato específico de la implementación.

   ```javascript
   const date = new Date();
   console.log(date.toDateString()); 
   ```

5. **`Date.prototype.toISOString()`**: Retorna una cadena en formato ISO extendido representando la fecha proporcionada por la instancia de Date.

   ```javascript
   const date = new Date();
   console.log(date.toISOString());
   ```

6. **`Date.prototype.toLocaleDateString()`**: Retorna una cadena con la porción de fecha de la instancia de Date convertida a una cadena usando la configuración regional actual.

   ```javascript
   const date = new Date();
   console.log(date.toLocaleDateString());
   ```

7. **`Date.prototype.toLocaleTimeString()`**: Retorna una cadena con la porción de tiempo de la instancia de Date convertida a una cadena usando la configuración regional actual.

   ```javascript
   const date = new Date();
   console.log(date.toLocaleTimeString());
   ```

8. **`Date.prototype.toString()`**: Retorna una cadena que representa la instancia de Date.

   ```javascript
   const date = new Date();
   console.log(date.toString());
   ```

9. **`Date.prototype.toTimeString()`**: Retorna la parte de tiempo de la instancia de Date como una cadena legible para humanos en el formato específico de la implementación.

   ```javascript
   const date = new Date();
   console.log(date.toTimeString());
   ```

10. **`Date.prototype.toUTCString()`**: Retorna una cadena que representa la instancia de Date en formato UTC.

    ```javascript
    const date = new Date();
    console.log(date.toUTCString());
    ```