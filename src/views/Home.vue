<template>
  <div class="home">
    <h1 class="header" width="" onclick="" onmouseover="">List of islands to choose</h1>
    <p></p>
    <label for=""></label>

    <b-container>
      <b-input-group size="lg">
        <b-form-input></b-form-input>
        <b-input-group-append>
          <b-button variant="info">Search</b-button>
        </b-input-group-append>
      </b-input-group>

      <b-table striped hover :items="items"></b-table>

      <div class="overflow-auto">
        <b-pagination-nav
          :link-gen="linkGen"
          :number-of-pages="numberOfPages"
          use-router
        ></b-pagination-nav>
      </div>
    </b-container>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        items: [
          { age: 100, first_name: 'Dickerson', last_name: 'Macdonald' },
          { age: 21, first_name: 'Larsen', last_name: 'Shaw' },
          { age: 89, first_name: 'Geneva', last_name: 'Wilson' },
          { age: 38, first_name: 'Jami', last_name: 'Carney' }
        ],
        numberOfPages: 10,
      }
    },
    methods: {
      linkGen(pageNum) {
        return pageNum === 1 ? '?' : `?page=${pageNum}`
      },
    }
  }
</script>
