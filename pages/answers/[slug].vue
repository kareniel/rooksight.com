<template>
  <main class="w-100 flex flex-column items-center pv1 ph3">
    <ContentDoc v-slot="{ doc }">
      <article class="mw6">
        <h1>{{ doc.title }}</h1>
        <ContentRenderer :value="doc" />
      </article>
    </ContentDoc>
  </main>
</template>
