<template>
    <div>
        <b-alert v-model="showConfirmation" variant="success" dismissible show>{{ message }}
        </b-alert>
    </div>
</template>
<script>
export default {
  props: ['message'],
};
</script>
