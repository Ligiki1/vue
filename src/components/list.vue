<template>
  <div>
    <!-- <list></list> -->

    <body>
      <h3>list</h3>
      <div class="zentrierte-tabelle">

        <table>
          <tr>
            <th>Hauptgericht 1</th>
          </tr>
          <tr>
            <th>Hauptgericht 2</th>
          </tr>
          <tr>
            <th>Hauptgericht 3</th>
          </tr>
          <tr>
            <th>...</th>
          </tr>
        </table>
      </div>
    </body>
  </div>
</template>

<script>
  export default {
    name: "list"
  }
</script>

<style scoped>
  .zentrierte-tabelle {
    width: 100px;
    margin-left: auto;
    margin-right: auto;
    text-align: center;
  }
</style>