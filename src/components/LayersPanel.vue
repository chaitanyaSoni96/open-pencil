<script setup lang="ts">
import AppMenu from './AppMenu.vue'
import LayerTree from './LayerTree.vue'
import PagesPanel from './PagesPanel.vue'
</script>

<template>
  <aside
    class="flex min-w-0 flex-1 flex-col overflow-x-hidden overflow-y-auto border-r border-border bg-panel"
    style="contain: paint layout style"
  >
    <AppMenu />
    <PagesPanel />
    <header class="shrink-0 px-3 py-2 text-[11px] uppercase tracking-wider text-muted">
      Layers
    </header>
    <LayerTree />
  </aside>
</template>
