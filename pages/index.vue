<template>
  <main class="vh-100 w-100 flex items-center justify-center flex-column">
    <ContentDoc v-slot="{ doc }">
      <article class="mw6">
        <ContentRenderer :value="doc" />
      </article>
    </ContentDoc>
  </main>
</template>
