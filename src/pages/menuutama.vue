<template>
<q-page>
RAPORT ONLINE
  <q-form
      @submit="onSubmit"
      @reset="onReset"
      class="q-gutter-md"
    >
    <q-input filled v-model="text" label="masukan nama" />
    <q-input filled v-model="text" label="masukan kelas" />
    <q-input filled v-model="text" label="masukan NIS" />
    <q-input filled v-model="text" label="masukan Ma.Pel" />
    <q-input filled v-model="text" label="nilai" />
      <q-toggle v-model="accept" label="I accept the license and terms" />

      <div>
        <q-btn label="Submit" type="submit" color="primary"/>
        <q-btn label="Reset" type="reset" color="primary" flat class="q-ml-sm" />
      </div>
    </q-form>
</q-page>
</template>
<script>
export default {
}
</script>
