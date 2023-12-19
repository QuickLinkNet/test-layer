<script setup lang="ts">
interface BoxProps {
  size?: "small" | "medium" | "large"
}

// withDefaults(defineProps<BoxProps>(), { size: "medium" })
</script>

<template>
  <button>
<!--      @click="setWorkStep(step.id)"-->
<!--      :title="$t(`${step.localeKey}.long`)"-->
<!--      :class="step.id === activeId ? 'active' : undefined"-->
<!--      :disabled="step.status === 'NOT_AVAILABLE'"-->
<!--  >-->
    <span class="label">
      123
<!--      {{ $t(`${step.localeKey}.short`) }}-->
    </span>
<!--    <StatusTag-->
<!--        :status="step.status.toLowerCase() as WorkstepStatus"-->
<!--        :date="step.resubmission?.resubmissionDate"-->
<!--        :small="true"-->
<!--    />-->
  </button>
</template>

<style scoped lang="scss">
</style>
