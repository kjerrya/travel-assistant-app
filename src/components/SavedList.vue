<template>
  <div class="savedlist">
    <h1>Saved List</h1>
    <h2>{{msg}}</h2>

<!-- <pre>{{ pushto }}</pre> -->

  </div>
</template>

<script>
//  import { mapState, mapGetters } from 'vuex'
  import list from '@/assets/dbstatic.js'

  export default {
    name: 'SavedList',
/*    computed: {
      ...mapState(['pushto']),
      ...mapGetters(['listCount'])

    },*/
    data () {
      return {

        msg: 'The saved list data is currently unavailable.',
        cities: list

      }

    }

  }

</script>
