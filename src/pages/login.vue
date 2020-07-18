<template>
<q-page>
LOGIN
  <q-form
      @submit="onSubmit"
      @reset="onReset"
      class="q-gutter-md"
    >
    <q-input filled v-model="text" label="masukan email" />
    <q-input filled v-model="text" label="masukan password" />
      <q-toggle v-model="accept" label="I accept the license and terms" />

      <div>
        <q-btn label="Submit" type="submit" color="primary" to="/"/>
        <q-btn label="Reset" type="reset" color="primary" flat class="q-ml-sm" />
      </div>
    </q-form>
</q-page>
</template>
<script>
export default {
}
</script>
