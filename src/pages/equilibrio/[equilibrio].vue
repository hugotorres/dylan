<script setup lang="ts"></script>

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
  </div>
</template>
