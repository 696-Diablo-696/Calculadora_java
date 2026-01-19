# Calculadora_java
NIVEL BÁSICO:
        1. Cambia los colores del degradado del fondo.
        2. Añade una operación de módulo (%) que calcule el resto de una división.
        3. Modifica los textos de las etiquetas y placeholders.
        4. Cambia el tamaño de fuente del resultado a 24px.
        
        NIVEL INTERMEDIO:
        5. Añade un botón "Limpiar" que borre todos los campos.
           Pista: Crea un <button>, dale un id, selecciónalo con getElementById,
           añade un addEventListener con 'click', y dentro asigna '' a todos los .value.
        
        6. Añade validación para que los números no puedan ser negativos.
           Pista: Usa el atributo min="0" en los inputs.
        
        7. Formatea el resultado para mostrar máximo 2 decimales.
           Pista: res.toFixed(2)
        
        8. Añade una operación de potencia (num1 elevado a num2).
           Pista: Usa Math.pow(num1, num2) o num1 ** num2
        
        NIVEL AVANZADO:
        9. Añade un historial de operaciones que muestre las últimas 5 operaciones realizadas.
           Pista: Crea un array para guardar operaciones, usa .push() para añadir,
           y actualiza un <ul> en el HTML con los resultados.
        
        10. Implementa operaciones con 3 números (por ejemplo: (num1 + num2) * num3).
            Pista: Añade un tercer input y un segundo select para elegir cómo combinar.
        
        11. Añade un modo de operaciones científicas con raíz cuadrada, seno, coseno, etc.
            Pista: Usa Math.sqrt(), Math.sin(), Math.cos(), etc.
        
        12. Implementa un tema oscuro/claro con un botón para cambiar.
            Pista: Usa una variable para el tema, y cambia los estilos dinámicamente
            con elemento.style.backgroundColor = '...';
        
        13. Guarda el último resultado en localStorage para que persista al recargar.
            Pista: localStorage.setItem('ultimoResultado', res);
            localStorage.getItem('ultimoResultado');
        
        ═══════════════════════════════════════════════════════════════
                        CONCEPTOS CLAVE APRENDIDOS
        ═══════════════════════════════════════════════════════════════
        
        HTML:
        - Estructura semántica con etiquetas apropiadas
        - Inputs de diferentes tipos (number, text)
        - Select y options para menús desplegables
        - Atributos: id, class, type, placeholder, readonly, for
        
        CSS:
        - Selectores: etiqueta, .clase, #id, [atributo]
        - Box model: padding, margin, border
        - Flexbox para centrado
        - Pseudo-selectores: :focus
        - Transiciones suaves
        - Degradados lineales
        
        JavaScript:
        - Selección de elementos del DOM
        - Variables: const, let
        - Tipos de datos: number, string, boolean
        - Conversión de tipos: parseFloat()
        - Condicionales: if, else
        - Switch para múltiples opciones
        - Operadores: aritméticos (+,-,*,/), lógicos (||, &&), comparación (===)
        - Funciones: declaración y ejecución
        - Event Listeners: 'input', 'change'
        - Validación de datos
        
        Buenas prácticas:
        - Validar entrada de usuario
        - Manejar casos especiales (división por cero)
        - Código comentado y legible
        - Nombres de variables descriptivos
        - Separación de responsabilidades (HTML estructura, CSS estilo, JS lógica)
        
