<template>

</template>

<script lang="ts" setup>
import { useDataSource } from './hooks';
import { componentProps } from './types';

const props = defineProps(componentProps);

useDataSource(props);
</script>

<style lang="less" scoped>

</style>