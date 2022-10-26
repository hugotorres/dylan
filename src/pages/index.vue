<template>
  <div>
    <Header />

    <h1 p-4 class="mb-2 text-lg font-semibold text-gray-900 dark:text-white">
      Equilibrio quimico
    </h1>

    <div class="grid grid-cols-2 gap-4 divide-y divide-blue-200">
      <div class="text-left" p-4>
        <p>
          El equilibrio químico es el estado en el que las actividades químicas
          o las concentraciones de los reactivos y los productos no tienen
          ningún cambio neto. Normalmente, este sería el estado que se produce
          cuando una reacción reversible evoluciona hacia adelante en la misma
          proporción que su reacción inversa. La velocidad de reacción de las
          reacciones directa e inversa por lo general no son cero, pero, si
          ambas son iguales, no hay cambios netos en cualquiera de las
          concentraciones de los reactivos o productos. Este proceso se denomina
          equilibrio dinámico
        </p>
        <p>Existen varios principios pero uno de los mas importantes es el:</p>
        <h2 class="underline" p-4>
          Principio de Le Chatelier. Variaciones en el equilibrio.
        </h2>
        <p p-4>
          “Un cambio o perturbación en cualquiera de las variables que
          determinan el estado de equilibrio químico produce un desplazamiento
          del equilibrio en el sentido de contrarrestar o minimizar el efecto
          causado por la perturbación Un ejemplo de este en el siguiente video.
        </p>
      </div>

      <div>
        <iframe
          width="100%"
          height="400"
          src="https://www.youtube.com/embed/wKvkINPRj4U"
          title="Principio de Le Chatelier. Ejemplo | Química | Khan Academy en Español"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
        />
      </div>
    </div>

    <h1 p-4 class="mb-2 text-lg font-semibold text-gray-900 dark:text-white">
      Constante de Equilibrio
    </h1>

    <div class="grid grid-cols-2 gap-4 divide-y divide-blue-200">
      <div class="text-left">
        <p p-4>
          La constante de equilibrio de una reacción química es el valor de su
          cociente de reacción en el equilibrio químico, un estado que se acerca
          a un sistema químico dinámico después de que haya transcurrido el
          tiempo suficiente, en el que su composición no tiene una tendencia
          medible hacia un cambio adicional. Para un conjunto dado de
          condiciones de reacción, la constante de equilibrio es independiente
          de las concentraciones analíticas iniciales del reactivo y las
          especies de productos en la mezcla. Por lo tanto, dada la composición
          inicial de un sistema, se pueden usar valores constantes de equilibrio
          conocidos para determinar la composición del sistema en equilibrio.
          Sin embargo, los parámetros de reacción como la temperatura, el
          disolvente y la fuerza iónica pueden influir en el valor de la
          constante de equilibrio.
        </p>
        <p p-6>
          Tipos de equilibrios:
        </p>
        <ul
          p-6
          class="space-y-1 max-w-md list-disc list-inside text-gray-500 dark:text-gray-400"
        >
          <li>Equilibrio químico</li>
          <li>Estabilidad química</li>
          <li>Equilibrio dinámico</li>
          <li>Equilibrio de solubilidad</li>
          <li>quilibrio termodinámico</li>
          <li>Equilibrio vapor-líquido</li>
        </ul>
      </div>

      <div>
        <iframe
          width="100%"
          height="400"
          src="https://www.youtube.com/embed/BAAzOsAMcGY"
          title="Cómo expresar y calcular la Constante de Equilibrio (Ke)(ejercicios)"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
        />
      </div>

      <div />
    </div>

    <h1 p-4 class="mb-2 text-lg font-semibold text-gray-900 dark:text-white">
      Clases de Equilibrio
    </h1>

    <div class="grid grid-cols-3 gap-4">
      <div class="text-left">
        <h2>Equilibrio ácido-base</h2>
        <p p-4>
          El concepto de ácido y base que, hoy en día sigue prevaleciendo con
          algunas mejoras, fue propuesto por Svante Arrhenius en 1884 como parte
          de otra teoría, también propuesta por él: la teoría de la ionización..
          Arrhenius observó que cuando el HCI se disuelve en el agua (aq) sus
          moléculas se disocian en la forma: HCl 􏰖 H+ (aq) + Cl- (aq)
        </p>
      </div>

      <div class="text-left">
        <h2>Equilibrio redox</h2>
        <p p-4>
          En química, se llama redox al equilibrio químico que se da en una
          reacción de reducción-oxidación (redox). Una reacción de oxidación al
          equilibrio es una de la forma: Oxidante_1 \, + \, Reductor_2 \, = \,
          Reductor_1 \, + \, Oxidante_2 Que puede ser vista como la suma de dos
          semireacciones al equilibrio: Una oxidación de una sustancia que actúa
          como agente reductor, que cede electrones o incrementa su número de
          oxidación
        </p>
      </div>

      <div class="text-left">
        <h2>Equilibrio de solubilidad</h2>
        <p p-4>
          Equilibrio de solubilidad es cualquier tipo de relación de equilibrio
          químico entre los estados sólido y disuelto de un compuesto en la
          saturación. Los equilibrios de solubilidad implican la aplicación de
          los principios químicos y las constantes para predecir la solubilidad
          de sustancias en condiciones específicas (porque la solubilidad es
          sensible a las condiciones, mientras que las constantes lo son menos).
          La sustancia que se disuelve puede ser un sólido orgánico como el
          azúcar o un sólido iónico como la sal de mesa. La principal diferencia
          es que los sólidos iónicos se disocian en sus iones constituyentes,
          cuando se disuelven en agua. La mayor parte de las veces, el agua es
          el disolvente de interés, aunque los mismos principios básicos son
          aplicables a cualquier disolvente.x
        </p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.header {
  font-weight: bold;
  font-size: 20px;
}
nav {
  text-align: left;
}
</style>
