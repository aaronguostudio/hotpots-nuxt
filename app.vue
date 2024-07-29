<script lang="ts" setup>
import HButton from '@/components/hotpots/button/HButton.vue'
import HAlert from '@/components/hotpots/alert/HAlert.vue'
import HAlertDialog from '@/components/hotpots/alert-dialog/HAlertDialog.vue'
import HDatePicker from '@/components/hotpots/date-picker/HDatePicker.vue'
import HDateRangePicker from '@/components/hotpots/date-picker/HDateRangePicker.vue'
</script>

<template>
  <div class="p-4 space-y-4">
    <div class="flex items-center space-x-4">
      <HButton size="xs">Click me</HButton>
      <HButton size="sm">Click me</HButton>
      <HButton size="default">Click me</HButton>
      <HButton size="lg">Click me</HButton>
      <HButton size="icon">+</HButton>
    </div>
    <div class="flex items-center space-x-4">
      <HButton size="xs" variant="default">Default</HButton>
      <HButton size="sm" variant="destructive">Destructive</HButton>
      <HButton size="default" variant="outline">Outline</HButton>
      <HButton size="lg" variant="secondary">Secondary</HButton>
      <HButton size="default" variant="ghost">Ghost</HButton>
      <HButton size="icon" variant="link">Link</HButton>
    </div>
    <div>
      <HAlert />
    </div>
    <div>
      <HAlertDialog />
    </div>
    <div>
      <HDatePicker />
    </div>
    <div>
      <HDateRangePicker />
    </div>
  </div>
</template>