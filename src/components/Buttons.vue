<script setup>
import Button from "./Button.vue";
import { BeakerIcon } from '@heroicons/vue/solid'

</script>

<template>
  <div class="space-y-5">
    <div class="flex gap-5 flex-wrap">
      <!-- <Button 
        intent="primary"
        as="a"
        :left-icon="BeakerIcon"
        :right-icon="BeakerIcon"
        loading
        href="https://tallpad.com" target="blank"
        > -->
      <Button
        intent="primary"
        :left-icon="BeakerIcon"
      >
        Primary
      </Button> 
      <Button
        intent="secondary"
        :left-icon="BeakerIcon"
      >
        Secondary
      </Button> 
      <Button
        intent="danger"
        :left-icon="BeakerIcon"
      >
        Danger
      </Button> 
      <Button
        intent="text"
        :left-icon="BeakerIcon"
      >
       Text
      </Button> 
    </div>

    <div class="flex gap-5 flex-wrap">
      <Button disabled
        intent="primary"
        :left-icon="BeakerIcon"
      >
        Primary
      </Button> 
      <Button disabled
        intent="secondary"
        :left-icon="BeakerIcon"
      >
        Secondary
      </Button> 
      <Button disabled
        intent="danger"
        :left-icon="BeakerIcon"
      >
        Danger
      </Button> 
      <Button disabled
        intent="text"
        :left-icon="BeakerIcon"
      >
       Text
      </Button> 
    </div>

    <div class="flex gap-5 flex-wrap">
      <Button 
        intent="primary"
        :right-icon="BeakerIcon"
      >
        Primary
      </Button> 
      <Button 
        intent="secondary"
        :right--icon="BeakerIcon"
      >
        Secondary
      </Button> 
      <Button 
        intent="danger"
        :right-icon="BeakerIcon"
      >
        Danger
      </Button> 
      <Button 
        intent="text"
        :right-icon="BeakerIcon"
      >
       Text
      </Button> 
    </div>

    <div class="flex gap-5 flex-wrap">
      <Button intent="primary">Primary</Button> 
      <Button intent="secondary">Secondary</Button> 
      <Button intent="danger">Danger</Button> 
      <Button intent="text">Text</Button> 
    </div>

    <div class="flex gap-5 flex-wrap">
      <Button loading intent="primary">Primary</Button> 
      <Button loading intent="secondary">Secondary</Button> 
      <Button loading intent="danger">Danger</Button> 
      <Button loading intent="text">Text</Button> 
    </div>

  </div>
</template>
