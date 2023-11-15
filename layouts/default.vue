<template>
  <div class="">
    <div class="my-0 mx-auto min-h-full max-w-screen-sm">
      <div
        class="my-0 mx-auto min-h-screen max-w-480 overflow-x-hidden bg-white pb-[66px]"
      >
        <LayoutsHeader />
        <div
          class="relative m-auto flex h-full max-w-[480px] items-center p-0 px-4 w-full"
        >
          <slot />
          <LayoutsFooter />
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts"></script>
