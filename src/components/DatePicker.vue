<template>
   <Datepicker v-model="date"></Datepicker>
</template>

<script>
import Datepicker from '@vuepic/vue-datepicker';
import '@vuepic/vue-datepicker/dist/main.css'

export default {
  name: 'DatePicker',
  props: {
    msg: String
  },
  components: { Datepicker },
        data() {
            return {
                date: null,
            };
        }
}
</script>
<style>
</style>
