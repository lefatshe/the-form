<template>
  <div class="index container">
    <!-- <h1>{{ msg }}</h1> -->
    <div class="divider"></div>
    <div class="section">
      <div class="col s12">
        <div class="row">
          <div class="input-field col s6">
            <input placeholder="Placeholder" id="first_name" type="text" class="validate">
            <label for="first_name">First Name</label>
          </div>
          <div class="input-field col s6">
            <input id="last_name" type="text" class="validate">
            <label for="last_name">Last Name</label>
          </div>
        </div>
      </div>
    </div>
    <div class="divider"></div>
    <div class="section">
      <h5>Section 2</h5>
      <p>Add more</p>
    </div>
    <div class="divider"></div>
    <div class="section">
      <h5>Section 3</h5>
      <p>Stuff</p>
    </div>


  </div>
</template>

<script>
  export default {
    name: 'Form',
    data() {
      return {
        msg: 'Welcome to form'
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h1, h2 {
    font-weight: normal;
  }

  ul {
    list-style-type: none;
    padding: 0;
  }

  li {
    display: inline-block;
    margin: 0 10px;
  }

  a {
    color: #42b983;
  }
</style>
