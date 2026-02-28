<script setup>
import { Button } from "@repo/ui";
import { Badge } from "@repo/ui";
</script>

<template>
  <div class="p-6 space-y-4">
    <h1 class="text-3xl font-bold underline">Hello world!</h1>

    <Button>Hello from UI button</Button>

    <Badge variant="default | outline | secondary | destructive"> Badge </Badge>

    <Badge as-child>
      <a href="#">Badge</a>
    </Badge>
  </div>
</template>
