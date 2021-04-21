<template>
  <div>
    <b-nav tabs>
      <b-nav-item disabled m-b="20"><b>Fancy Quiz App</b></b-nav-item>
      <b-nav-item disabled>Counter: {{ numCorrect }}/{{ numTotal }}</b-nav-item>
    </b-nav>
  </div>
</template>
<script>
export default {
  props: [
    'numCorrect',
    'numTotal'
  ]
}
</script>