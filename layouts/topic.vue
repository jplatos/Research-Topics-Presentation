<script setup lang="ts">
defineProps<{
  image?: string
  contactPhoto?: string
  contactName?: string
}>()
</script>

<template>
  <div class="absolute inset-0 flex" style="background: #f5f5f5">
    <div class="flex-[6] flex flex-col px-10 py-8 overflow-hidden">
      <h1 class="text-3xl font-extrabold leading-tight mb-1" style="color: #00A499">
        {{ $frontmatter.title }}
      </h1>
      <div class="w-16 mb-2" style="height: 3px; background: #00A499; border-radius: 2px"></div>
      <div class="text-sm leading-relaxed mb-4 topic-annotation" style="color: #525252">
        <slot name="annotation" />
      </div>
      <div class="flex-1 overflow-hidden topic-bullets">
        <slot name="bullets" />
      </div>
      <div class="rounded-xl py-3 px-4 flex items-center gap-4 mt-2" style="background: #1e293b">
        <img
          class="w-12 h-12 rounded-full object-cover shrink-0"
          :src="contactPhoto"
          alt="Garant"
          style="border: 2px solid #00A499"
        />
        <h4 class="font-bold text-sm leading-snug" style="color: white">{{ contactName }}</h4>
      </div>
    </div>
    <div class="flex-[4] relative overflow-hidden">
      <img :src="image" class="absolute left-0 top-0 w-full object-cover object-top" style="height: 110%" />
      <div class="absolute inset-y-0 left-0 w-1" style="background: #00A499"></div>
    </div>
  </div>
</template>

<style scoped>
.topic-annotation :deep(p) {
  margin: 0;
}
.topic-bullets :deep(ul) {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  column-gap: 1.5rem;
  row-gap: 0.5rem;
  list-style: none;
  padding: 0;
  margin: 0;
  align-content: start;
}
.topic-bullets :deep(li) {
  position: relative;
  padding-left: 1.25rem;
  font-size: 0.875rem;
  color: #404040;
  line-height: 1.5;
}
.topic-bullets :deep(li)::before {
  content: '';
  position: absolute;
  left: 0;
  top: 0.375rem;
  width: 0.5rem;
  height: 0.5rem;
  border-radius: 50%;
  background: #00A499;
}
</style>
