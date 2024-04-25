# Métodos numéricos -> Tema 4: Métodos de solución de problemas aplicando diferenciación y integración.

<h1> <font color = "darkred" size="+5" font face = "cooper black"> <b> <i> SALUDO </i> </b> </font> </h1>

¡Hola a todos! Soy Rubí Veloz Jiménez, estudiante de Ingeniería en Sistemas Computacionales. En esta ocasión, les presento un problemario relacionado con la materia de Métodos Numéricos sobre los Métodos de solución de problemas aplicando diferenciación y integración (método de trapecio, regla se Simpson 1/3, regla se Simpson 3/8 y método de la Cuadratura Gaussiana ).

# <h2 align = "center"> <font color = "darkorange" size = "+6"  font face = "bauhaus 93">  ÍNDICE </font> </h2>
<header> <font color = "red" size="+1" font face = "aharoni">
                <nav class="navegacion">
                    <ul class="Indice">
                       <li> <a href="#Descripción del Problemario"> Descripción del Problemario. </a> <br> </li>
                        <li> <a href="#Sobre la materia"> Sobre la materia. </a> <br> </li>
                            <ul class="subindice"> 
                                <li> <a href="#Competencia de la Asignatura"> Competencia de la Asignatura. </a> </li>
                                <li> <a href="#Competencia del tema"> Competencia del tema. </a> </li>
                                <li> <a href="#Temario"> Temario. </a> </li>  
                            </ul>
                      <li> <a href="#Métodos Numéricos sobre los métodos de solución de sistemas de problemas aplicando diferenciación y integración que se encuentran en nuestro repositorio"> Métodos Numéricos sobre los métodos de solución de sistemas de problemas aplicando diferenciación y integración que se encuentran en nuestro repositorio. </a> <br> </li>
                            <ul class="subindice"> 
                                <li> <a href="#Método del Trapecio"> Método del Trapecio. </a> </li>
                                    <ul class="subindice"> 
                                        <li> <a href="#DescripciónT"> Descripción. </a> </li>
                                        <li> <a href="#AlgoritmoT"> Algoritmo. </a> </li> 
                                        <li> <a href="#Representación gráficaT"> Representación gráfica. </a> </li>
                                        <li> <a href="#ImplementaciónT"> Implementación. </a> </li>  
                                    </ul>
                                <li> <a href="#Método de la Regla de Simpson 1/3"> Método de la Regla de Simpson 1/3. </a> </li>
                                      <ul class="subindice"> 
                                          <li> <a href="#Descripción1/3"> Descripción. </a> </li>
                                          <li> <a href="#Algoritmo1/3"> Algoritmo. </a> </li>
                                          <li> <a href="#Representación gráfica1/3"> Representación gráfica. </a> </li>
                                          <li> <a href="#Implementación1/3"> Implementación. </a> </li>  
                                      </ul>
                                <li> <a href="#Método de la Regla de Simpson 3/8"> Método de la Regla de Simpson 3/8. </a> </li> 
                                      <ul class="subindice"> 
                                          <li> <a href="#Descripción3/8"> Descripción. </a> </li>
                                          <li> <a href="#Algoritmo3/8"> Algoritmo. </a> </li>
                                          <li> <a href="#Representación gráfica3/8"> Representación gráfica. </a> </li>
                                          <li> <a href="#Implementación3/8"> Implementación. </a> </li>  
                                      </ul>
                                <li> <a href="#Método de la Cuadratura Gaussiana"> Método de la Cuadratura Gaussiana. </a> </li> 
                                      <ul class="subindice"> 
                                          <li> <a href="#DescripciónCG"> Descripción. </a> </li>
                                          <li> <a href="#AlgoritmoCG"> Algoritmo. </a> </li>
                                          <li> <a href="#Representación gráficaCG"> Representación gráfica. </a> </li>
                                          <li> <a href="#ImplementaciónCG"> Implementación. </a> </li>  
                                      </ul>
                            </ul>
                    </ul>
                </nav>
            </font> </header>


# <h2 align = "center"> <font  font face = "bauhaus 93">  <a name="Descripción del Problemario"> Descripción del Problemario </a> </font> </h2>

En este conjunto de ejercicios, exploraremos cuatro métodos de solución de problemas aplicando diferenciación y integración. Estos métodos son:

1. **Método del Trapecio**:
   - Divide el intervalo de integración en segmentos trapezoidales.
   - Aproxima la integral de una función como la suma de áreas de estos trapezoides.
   - Simple de implementar pero menos preciso que otros métodos.
   - La precisión mejora al aumentar el número de segmentos.

2. **Método de Simpson 1/3**:
   - Utiliza parábolas para aproximar la función en cada segmento.
   - Divide el intervalo en subintervalos de igual longitud.
   - Más preciso que el método del trapecio.
   - Funciona bien para funciones suaves.

3. **Método de Simpson 3/8**:
   - Similar al método de Simpson 1/3, pero divide el intervalo en subintervalos de longitud diferente.
   - Utiliza polinomios cúbicos para aproximar la función.
   - Mayor precisión que el método de Simpson 1/3.

4. **Método de la Cuadratura Gaussiana**:
   - Selecciona puntos y pesos óptimos para la aproximación de la integral.
   - No ajusta polinomios a la función, lo que lo hace más preciso.
   - Ideal para funciones con oscilaciones rápidas o discontinuidades.


# <h2 align = "center"> <font  font face = "bauhaus 93"> <a name="Sobre la materia"> Sobre la materia </a> </font> </h2>

<h3> <font font face = "forte"> <a name="Competencia de la Asignatura"> Competencia de la Asignatura </a> </h3>

...
  
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


<h3> <font font face = "forte"> <a name="Competencia del tema"> Competencia del tema </a> </h3>

...

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


<h3> <font font face = "forte"> <a name="Temario"> Temario  </a> </h3>

...

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------



# <h2 align = "center"> <font  font face = "bauhaus 93"> <a name="Métodos Numéricos sobre los métodos de solución de sistemas de problemas aplicando diferenciación y integración que se encuentran en nuestro repositorio"> Métodos Numéricos sobre los métodos de solución de sistemas de problemas aplicando diferenciación y integración que se encuentran en nuestro repositorio. </a> </font> </h2>

# <h3 align = "center"> <font font face = "forte"> <a name="Método del Trapecio"> 1. Método del Trapecio </a> </h3>

<h4> <font font face = "arial"> <a name="DescripciónT"> Descripción. </a> </h4>

El Método del Trapecio es una técnica de integración numérica que se utiliza para estimar el valor de una integral definida. Este método se basa en la idea de aproximar el área bajo la curva de una función mediante la suma de las áreas de varios trapecios.

El procedimiento del Método del Trapecio se puede describir de la siguiente manera:

1. **Segmentación**: El intervalo de integración, desde `a` hasta `b`, se divide en `n` segmentos de igual longitud. Esta longitud, denotada como `h`, se calcula como `(b - a) / n`.

2. **Evaluación de la función**: Se evalúa la función que se desea integrar en los puntos `a`, `a + h`, `a + 2h`, ..., hasta `b`. Estos valores representan las alturas de los trapecios.

3. **Cálculo de la suma**: Se suman todos los valores de la función obtenidos en el paso anterior. Sin embargo, los valores en los extremos del intervalo de integración (es decir, en `a` y `b`) se multiplican por 0.5. Esto se debe a que, en el cálculo del área de un trapecio, las alturas se suman y luego se dividen por 2.

4. **Estimación de la integral**: La suma obtenida en el paso anterior se multiplica por `h`. El resultado es la estimación de la integral definida.

Es importante destacar que el Método del Trapecio proporciona una aproximación de la integral definida y que la precisión de esta aproximación aumenta con el número de segmentos `n` utilizados. Sin embargo, para funciones complejas o cuando se requiere una alta precisión, pueden ser necesarios métodos de integración numérica más sofisticados.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<h4> <font font face = "arial"> <a name="AlgoritmoT"> Algoritmo. </a> </h4>

1. **Divide el área bajo la curva** que quieres integrar en `n` segmentos de igual ancho. Este ancho se conoce como `h` y se calcula como `(b - a) / n`, donde `a` y `b` son los límites inferior y superior de la integral, respectivamente.

2. **Calcula los valores de la función** en los puntos `a`, `a + h`, `a + 2h`, ..., `b`. Estos son los valores de `y` en cada punto.

3. **Suma los valores de la función** en todos los puntos, pero multiplica por 0.5 los valores en los puntos extremos (es decir, en `a` y `b`).

4. **Multiplica la suma obtenida** en el paso anterior por `h`. El resultado es la aproximación de la integral definida.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<h4> <font font face = "arial"> <a name="Representación gráficaT"> Representación gráfica. </a> </h4>

![Captura de pantalla 2024-04-24 201152](https://github.com/rubivj13/MetodosNumericos_Tema4/assets/147438464/a70b8b80-f72b-4284-a767-70fb837f85c3)


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<h4> <font font face = "arial"> <a name="ImplementaciónT"> Implementación. </a> </h4>

<h5> <font font face = "arial"> <b> <i> Ejemplo en código. </i> </b> </h5>

    package MetodoTrapecio;
    
    import java.util.function.Function;
    
    /**
     *
     * @author Rub_1
     */
    public class Ejercicio1 {
    
        public static double trapezoidalRule(Function<Double, Double> f, double a, double b, int n) {
            double h = (b - a) / n;
            double sum = 0.5 * (f.apply(a) + f.apply(b));
            for (int i = 1; i < n; i++) {
                double x = a + i * h;
                sum += f.apply(x);
            }
            return h * sum;
        }
    
        public static void main(String[] args) {
            
            System.out.println("\t\t\t\t Método Trapecio - Ejercicio 1 \n");
            
            // Definir la función a integrar
            Function<Double, Double> f = x -> Math.exp(Math.pow(x, 4)); // Definir la función a integrar: e^(x^4)
    
            // Límites de integración
            double a = -1; // Límite inferior
            double b = 1; // Límite superior
    
            // Número de subintervalos
            int n = 1; // Ajustar este valor según la precisión deseada
    
            // Calcular la integral usando la regla del trapecio
            double result = trapezoidalRule(f, a, b, n);
            System.out.println("El resultado de la integral es: " + result);
        }
    }



<h5> <font font face = "arial"> <b> <i> Ejecución del programa. </i> </b> </h5>

![Captura de pantalla 2024-04-24 202409](https://github.com/rubivj13/MetodosNumericos_Tema4/assets/147438464/a414add6-f39a-4793-a395-41a5feb0c3c6)


Te invito a que puedas checar mis ejercicios para profundizar en la implementación: <a href="https://github.com/rubivj13/MetodosNumericos_Tema4/tree/master/src/MetodoTrapecio"> <font font face = "arial"> https://github.com/rubivj13/MetodosNumericos_Tema4/tree/master/src/MetodoTrapecio </font> </a>










# <h3 align = "center"> <font font face = "forte"> <a name="Método de la Regla de Simpson 1/3"> 2. Método de la Regla de Simpson 1/3 </a> </h3>

<h4> <font font face = "arial"> <a name="Descripción1/3"> Descripción. </a> </h4>

El Método de Simpson 1/3 es una técnica de integración numérica que se utiliza para estimar el valor de una integral definida. Este método se basa en la idea de aproximar el área bajo la curva de una función utilizando parábolas.

El procedimiento del Método de Simpson 1/3 se puede describir de la siguiente manera:

1. **Segmentación**: El intervalo de integración, desde `a` hasta `b`, se divide en `n` segmentos de igual longitud. Esta longitud, denotada como `h`, se calcula como `(b - a) / n`. Para el Método de Simpson 1/3, `n` debe ser un número par.

2. **Evaluación de la función**: Se evalúa la función que se desea integrar en los puntos `a`, `a + h`, `a + 2h`, ..., hasta `b`. Estos valores representan las alturas de las parábolas.

3. **Cálculo de la suma**: Se suman todos los valores de la función obtenidos en el paso anterior. Los valores en los extremos del intervalo de integración (es decir, en `a` y `b`) se multiplican por 1, y los valores en los puntos intermedios se multiplican por 4 si su índice es impar, y por 2 si su índice es par.

4. **Estimación de la integral**: La suma obtenida en el paso anterior se multiplica por `h/3`. El resultado es la estimación de la integral definida.

Es importante destacar que el Método de Simpson 1/3 proporciona una aproximación de la integral definida y que la precisión de esta aproximación aumenta con el número de segmentos `n` utilizados. Sin embargo, para funciones complejas o cuando se requiere una alta precisión, pueden ser necesarios métodos de integración numérica más sofisticados.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<h4> <font font face = "arial"> <a name="Algoritmo1/3"> Algoritmo. </a> </h4>

1. **Divide el área bajo la curva** que quieres integrar en `n` segmentos de igual ancho. Este ancho se conoce como `h` y se calcula como `(b - a) / n`, donde `a` y `b` son los límites inferior y superior de la integral, respectivamente. Para el Método de Simpson 1/3, `n` debe ser un número par.

2. **Calcula los valores de la función** en los puntos `a`, `a + h`, `a + 2h`, ..., `b`. Estos son los valores de `y` en cada punto.

3. **Suma los valores de la función** en todos los puntos, pero multiplica por 1 los valores en los puntos extremos (es decir, en `a` y `b`), y multiplica por 4 los valores en los puntos con índice impar, y por 2 los valores en los puntos con índice par.

4. **Multiplica la suma obtenida** en el paso anterior por `h/3`. El resultado es la aproximación de la integral definida.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<h4> <font font face = "arial"> <a name="Representación gráfica1/3"> Representación gráfica. </a> </h4>

![Captura de pantalla 2024-04-24 203923](https://github.com/rubivj13/MetodosNumericos_Tema4/assets/147438464/c7bdf1cb-850c-4aef-9395-f1dffd736718)



![Captura de pantalla 2024-04-24 204028](https://github.com/rubivj13/MetodosNumericos_Tema4/assets/147438464/987e92ba-ca30-4bde-9428-78d6153d4ad4)


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<h4> <font font face = "arial"> <a name="Implementación1/3"> Implementación. </a> </h4>

<h5> <font font face = "arial"> <b> <i> Ejemplo en código. </i> </b> </h5>

    package MetodoReglaSimpson1_3;

    import java.util.function.Function;
    
    /**
     *
     * @author Rub_1
     */
    public class Ejercicio4 {
        
        public static double simpsonOneThirdRule(Function<Double, Double> f, double a, double b, int n) {
            double h = (b - a) / n;
            double sum = f.apply(a) + f.apply(b);
            
            for (int i = 1; i < n; i++) {
                double x = a + i * h;
                if (i % 2 == 0) {
                    sum += 2 * f.apply(x);
                } else {
                    sum += 4 * f.apply(x);
                }
            }
            
            return (h / 3) * sum;
        }
    
        public static void main(String[] args) {
            
            System.out.println("\t\t\t\t Método de la Regla de Simpson 1/3 - Ejercicio 4 \n");
            
            // Definir la función a integrar
            Function<Double, Double> f = x -> Math.exp(-x) / Math.sqrt(x + 1); // Función a integrar: e^(-x) / sqrt(x + 1)
    
            // Límites de integración
            double a = 0; // Límite inferior
            double b = 2; // Límite superior
    
            // Número de subintervalos (debe ser par)
            int n = 2; // Ajustar este valor según la precisión deseada
            if (n % 2 != 0) {
                System.out.println("El número de subintervalos debe ser par.");
                return;
            }
    
            // Calcular la integral usando el método de Simpson 1/3
            double result = simpsonOneThirdRule(f, a, b, n);
            System.out.println("El resultado de la integral es: " + result);
        }
    }



<h5> <font font face = "arial"> <b> <i> Ejecución del programa. </i> </b> </h5>

![Captura de pantalla 2024-04-24 204257](https://github.com/rubivj13/MetodosNumericos_Tema4/assets/147438464/8b81bdb7-3474-4391-a31f-0231b0e25490)


Te invito a que puedas checar mis ejercicios para profundizar en la implementación: <a href="https://github.com/rubivj13/MetodosNumericos_Tema4/tree/master/src/MetodoReglaSimpson1_3"> <font font face = "arial"> https://github.com/rubivj13/MetodosNumericos_Tema4/tree/master/src/MetodoReglaSimpson1_3 </font> </a>










# <h3 align = "center"> <font font face = "forte"> <a name="Método de la Regla de Simpson 3/8"> 3. Método de la Regla de Simpson 3/8 </a> </h3>

<h4> <font font face = "arial"> <a name="Descripción3/8"> Descripción. </a> </h4>

El Método de Simpson 3/8 es una técnica de integración numérica que se utiliza para estimar el valor de una integral definida. Este método se basa en la idea de aproximar el área bajo la curva de una función utilizando parábolas.

El procedimiento del Método de Simpson 3/8 se puede describir de la siguiente manera:

1. **Segmentación**: El intervalo de integración, desde `a` hasta `b`, se divide en `n` segmentos de igual longitud. Esta longitud, denotada como `h`, se calcula como `(b - a) / n`. Para el Método de Simpson 3/8, `n` debe ser un múltiplo de 3.

2. **Evaluación de la función**: Se evalúa la función que se desea integrar en los puntos `a`, `a + h`, `a + 2h`, ..., hasta `b`. Estos valores representan las alturas de las parábolas.

3. **Cálculo de la suma**: Se suman todos los valores de la función obtenidos en el paso anterior. Los valores en los extremos del intervalo de integración (es decir, en `a` y `b`) se multiplican por 1, los valores en los puntos con índice múltiplo de 3 se multiplican por 2, y los demás valores se multiplican por 3.

4. **Estimación de la integral**: La suma obtenida en el paso anterior se multiplica por `3h/8`. El resultado es la estimación de la integral definida.

Es importante destacar que el Método de Simpson 3/8 proporciona una aproximación de la integral definida y que la precisión de esta aproximación aumenta con el número de segmentos `n` utilizados. Sin embargo, para funciones complejas o cuando se requiere una alta precisión, pueden ser necesarios métodos de integración numérica más sofisticados.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<h4> <font font face = "arial"> <a name="Algoritmo3/8"> Algoritmo. </a> </h4>

1. **Divide el área bajo la curva** que quieres integrar en `n` segmentos de igual ancho. Este ancho se conoce como `h` y se calcula como `(b - a) / n`, donde `a` y `b` son los límites inferior y superior de la integral, respectivamente. Para el Método de Simpson 3/8, `n` debe ser un múltiplo de 3.

2. **Calcula los valores de la función** en los puntos `a`, `a + h`, `a + 2h`, ..., `b`. Estos son los valores de `y` en cada punto.

3. **Suma los valores de la función** en todos los puntos, pero multiplica por 1 los valores en los puntos extremos (es decir, en `a` y `b`), multiplica por 3 los valores en los puntos con índice que no es múltiplo de 3, y multiplica por 2 los valores en los puntos con índice múltiplo de 3.

4. **Multiplica la suma obtenida** en el paso anterior por `3h/8`. El resultado es la aproximación de la integral definida.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<h4> <font font face = "arial"> <a name="Representación gráfica3/8"> Representación gráfica. </a> </h4>

![Captura de pantalla 2024-04-24 205002](https://github.com/rubivj13/MetodosNumericos_Tema4/assets/147438464/f842c66f-70b7-40ba-82fa-255d492803d6)



![Captura de pantalla 2024-04-24 205221](https://github.com/rubivj13/MetodosNumericos_Tema4/assets/147438464/482efc62-98c2-432a-ac79-16f6273309b4)


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<h4> <font font face = "arial"> <a name="Implementación3/8"> Implementación. </a> </h4>

<h5> <font font face = "arial"> <b> <i> Ejemplo en código. </i> </b> </h5>

    package MetodoReglaSimpson3_8;

    import java.util.function.Function;
    
    /**
     *
     * @author Rub_1
     */
    public class Ejercicio2 {
        
        public static double simpsonThreeEighthRule(Function<Double, Double> f, double a, double b, int n) {
            double h = (b - a) / n;
            double sum = f.apply(a) + f.apply(b);
            
            for (int i = 1; i < n; i++) {
                double x = a + i * h;
                if (i % 3 == 0) {
                    sum += 2 * f.apply(x);
                } else {
                    sum += 3 * f.apply(x);
                }
            }
            
            return (3 * h / 8) * sum;
        }
    
        public static void main(String[] args) {
            
            System.out.println("\t\t\t\t Método de la Regla de Simpson 3/8 - Ejercicio 2 \n");
            
            // Definir la función a integrar
            Function<Double, Double> f = x -> Math.log(x * x + 1) / Math.sqrt(x + 1);
    
            // Límites de integración
            double a = 1; // Límite inferior
            double b = 5; // Límite superior
    
            // Número de subintervalos (debe ser múltiplo de 3)
            int n = 6; // Ajustar este valor según la precisión deseada
            if (n % 3 != 0) {
                System.out.println("El número de subintervalos debe ser múltiplo de 3.");
                return;
            }
    
            // Calcular la integral usando el método de Simpson 3/8
            double result = simpsonThreeEighthRule(f, a, b, n);
            System.out.println("El resultado de la integral es: " + result);
        }
        
    }



<h5> <font font face = "arial"> <b> <i> Ejecución del programa. </i> </b> </h5>

![Captura de pantalla 2024-04-24 205402](https://github.com/rubivj13/MetodosNumericos_Tema4/assets/147438464/db2db153-d411-4852-b384-75eabeb027df)


Te invito a que puedas checar mis ejercicios para profundizar en la implementación: <a href="https://github.com/rubivj13/MetodosNumericos_Tema4/tree/master/src/MetodoReglaSimpson3_8"> <font font face = "arial"> https://github.com/rubivj13/MetodosNumericos_Tema4/tree/master/src/MetodoReglaSimpson3_8 </font> </a>











# <h3 align = "center"> <font font face = "forte"> <a name="Método de la Cuadratura Gaussiana"> 4. Método de la Cuadratura Gaussiana </a> </h3>

<h4> <font font face = "arial"> <a name="DescripciónCG"> Descripción. </a> </h4>

El Método de la Cuadratura Gaussiana se basa en la elección óptima de los puntos en los que se evalúa la función, en lugar de utilizar un conjunto uniforme de puntos como en los métodos del Trapecio o Simpson. Estos puntos, conocidos como los puntos de Gauss, se eligen de tal manera que se maximiza la precisión de la integral para un número dado de puntos.

El procedimiento del Método de la Cuadratura Gaussiana se puede describir de la siguiente manera:

1. **Elección de los puntos de Gauss y los pesos asociados**: Los puntos de Gauss y sus pesos asociados se eligen de antemano. Estos se pueden obtener de tablas o calcular utilizando polinomios ortogonales. El número de puntos de Gauss determina el grado del polinomio que se ajustará exactamente por el método.

2. **Transformación del intervalo de integración**: El intervalo de integración original, desde `a` hasta `b`, se transforma a un intervalo estándar, generalmente de `-1` a `1` o de `0` a `1`. Esto se hace para facilitar el cálculo y porque los puntos de Gauss se definen para estos intervalos estándar.

3. **Evaluación de la función**: Se evalúa la función que se desea integrar en los puntos de Gauss transformados.

4. **Cálculo de la suma ponderada**: Se calcula la suma ponderada de los valores de la función en los puntos de Gauss, utilizando los pesos de Gauss.

5. **Estimación de la integral**: La suma ponderada obtenida en el paso anterior es la estimación de la integral definida en el intervalo estándar. Esta estimación se transforma de nuevo al intervalo original para obtener la estimación final de la integral.

Es importante destacar que el Método de la Cuadratura Gaussiana proporciona una aproximación de la integral definida y que la precisión de esta aproximación puede ser muy alta, incluso con un número relativamente pequeño de puntos de Gauss. Sin embargo, el cálculo de los puntos de Gauss y sus pesos puede ser complejo, y el método puede ser menos eficaz para funciones que no son suaves o que tienen discontinuidades.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<h4> <font font face = "arial"> <a name="AlgoritmoCG"> Algoritmo. </a> </h4>

1. **Elección de los puntos de Gauss y los pesos asociados**: Los puntos de Gauss y sus pesos asociados se eligen de antemano. Estos se pueden obtener de tablas o calcular utilizando polinomios ortogonales. El número de puntos de Gauss determina el grado del polinomio que se ajustará exactamente por el método.

2. **Transformación del intervalo de integración**: El intervalo de integración original, desde `a` hasta `b`, se transforma a un intervalo estándar, generalmente de `-1` a `1` o de `0` a `1`. Esto se hace para facilitar el cálculo y porque los puntos de Gauss se definen para estos intervalos estándar.

3. **Evaluación de la función**: Se evalúa la función que se desea integrar en los puntos de Gauss transformados.

4. **Cálculo de la suma ponderada**: Se calcula la suma ponderada de los valores de la función en los puntos de Gauss, utilizando los pesos de Gauss.

5. **Estimación de la integral**: La suma ponderada obtenida en el paso anterior es la estimación de la integral definida en el intervalo estándar. Esta estimación se transforma de nuevo al intervalo original para obtener la estimación final de la integral.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<h4> <font font face = "arial"> <a name="Representación gráficaT"> Representación gráfica. </a> </h4>

![Captura de pantalla 2024-04-24 210315](https://github.com/rubivj13/MetodosNumericos_Tema4/assets/147438464/7472dc68-d1d6-4832-a5c9-a4f429f2353e)



![Captura de pantalla 2024-04-24 210402](https://github.com/rubivj13/MetodosNumericos_Tema4/assets/147438464/92f193e6-db70-4f59-a867-43afe23c3b11)


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<h4> <font font face = "arial"> <a name="ImplementaciónCG"> Implementación. </a> </h4>

<h5> <font font face = "arial"> <b> <i> Ejemplo en código. </i> </b> </h5>

    package MetodoCuadraturaGaussiana;

    import java.util.function.Function;
    
    /**
     *
     * @author Rub_1
     */
    public class Ejercicio5 {
        
        // Coeficientes y nodos para la cuadratura Gaussiana con 8 puntos
        private static final double[] nodos = {0, 0.183434642495650, -0.183434642495650, 0.525532409916329, -0.525532409916329, 0.796666477413627, -0.796666477413627, 0.960289856497536, -0.960289856497536};
        private static final double[] pesos = {0.361418309562439, 0.313706645877887, 0.313706645877887, 0.222381034453374, 0.222381034453374, 0.101228536290376, 0.101228536290376, 0.062303530026471, 0.062303530026471};
        
    
        public static double cuadraturaGaussiana(Function<Double, Double> f, double a, double b) {
            double suma = 0;
            double escala = (b - a) / 2.0;
            double desplazamiento = (a + b) / 2.0;
            for (int i = 0; i < nodos.length; i++) {
                double x = escala * nodos[i] + desplazamiento;
                suma += pesos[i] * f.apply(x);
            }
            return escala * suma;
        }
    
        public static void main(String[] args) {
            
            System.out.println("\t\t\t\t Método de la Cuadratura Gaussiana - Ejercicio 5 \n");
            
            // Definir la función a integrar
            Function<Double, Double> f = x -> Math.sin(x) + Math.cos(x); // Función: sin(x) + cos(x)
    
            // Límites de integración
            double a = 0; // Límite inferior
            double b = Math.PI / 2; // Límite superior
    
            // Calcular la integral usando el método de cuadratura Gaussiana
            double resultado = cuadraturaGaussiana(f, a, b);
            System.out.println("El resultado de la integral es: " + resultado);
        }
        
    }



<h5> <font font face = "arial"> <b> <i> Ejecución del programa. </i> </b> </h5>

![Captura de pantalla 2024-04-24 210524](https://github.com/rubivj13/MetodosNumericos_Tema4/assets/147438464/81fb253a-87e3-4461-83bd-906ec5ea4647)


Te invito a que puedas checar mis ejercicios para profundizar en la implementación: <a href="https://github.com/rubivj13/MetodosNumericos_Tema4/tree/master/src/MetodoCuadraturaGaussiana"> <font font face = "arial"> https://github.com/rubivj13/MetodosNumericos_Tema4/tree/master/src/MetodoCuadraturaGaussiana </font> </a>






# <h3 align = "center"> <font font face = "forte"> <a name="Referencias"> 4. Referencias. </a> </h3>

    C. Chapra, S. (2006). Métodos numéricos para ingenieros (Quinta ed.). Pablo E. Roig Vázquez.





# <h3 align = "center"> <font font face = "forte">  Despedida </h3>

Me despido con un cordial saludo. Si tienen alguna duda o sugerencia, contactar por redes sociales: facebook, instagram, etc.
