<template>
  <div id="app">
    <VueProjectTimeline :projects="projects" />
  </div>
</template>

<script>
import VueProjectTimeline from '@gerwinov/vue-project-timeline';

export default {
  name: 'app',

  components: {
    VueProjectTimeline
  },

  data () {
    return {
      projects: [
        {
          title: 'Client A',
          subtitle: 'Developer',
          description: `Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
                       tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
                       quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
                       consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
                       cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
                       proident, sunt in culpa qui officia deserunt mollit anim id est laborum.`,
          image: `./img/circle.svg`,
          startYear: 2010,
          endYear: 2012,
          color: '#4A63E0'
        },
        {
          title: 'Client G',
          subtitle: 'Developer',
          description: `Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
                       tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
                       quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
                       consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
                       cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
                       proident, sunt in culpa qui officia deserunt mollit anim id est laborum.`,
          image: `./img/circle.svg`,
          startYear: 2012,
          endYear: 2017,
          color: '#A09DD3'
        },
        {
          title: 'Client T',
          subtitle: 'Developer',
          description: `Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
                       tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
                       quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
                       consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
                       cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
                       proident, sunt in culpa qui officia deserunt mollit anim id est laborum.`,
          image: `./img/circle.svg`,
          startYear: 2014,
          endYear:  null,
          color: '#518070'
        },
        {
          title: 'Client X',
          subtitle: 'Developer',
          description: `Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
                       tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
                       quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
                       consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
                       cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
                       proident, sunt in culpa qui officia deserunt mollit anim id est laborum.`,
          image: `./img/circle.svg`,
          startYear: 2016,
          endYear: 2018,
          color: '#6DBAA1'
        }
      ]
    }
  }
}
</script>

<style>
  body {
    margin: 0px;
  }

  h1, h2, h3 {
    font-family: 'Oxygen', sans-serif;
    font-weight: 400;
  }

  p {
    font-family: 'Source Sans Pro', sans-serif;
  }
</style>
