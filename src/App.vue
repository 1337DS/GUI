<template>


  <button class="btn-cta">{{ text }}</button>
  <br>
  <table>
    <tr> 
      <td>Data 1</td>
      <td>Data 2</td>
      <td>Data 3</td>
    </tr>
    <tr> 
      <td>Column 1</td>
      <td>Column 2</td>
      <td>Column 3</td>
    </tr>
  </table> 

</template>

<script>

export default {
  name: "FccButton", // vue component name
  props: {
    text: {
      type: String,
      default: "Next Picture"
    }
  },
  data() {}
};

</script>

<style>

.btn-cta {
  background-color: #d0d0d5;
  border-width: 3px;
  border-color: #1b1b32;
  border-radius: 0;
  border-style: solid;
  color: #1b1b32;
  display: block;
  margin-bottom: 0;
  font-weight: normal;
  text-align: center;
  -ms-touch-action: manipulation;
  touch-action: manipulation;
  cursor: pointer;
  white-space: nowrap;
  padding: 6px 12px;
  font-size: 18px;
  line-height: 1.42857143;
}

.btn-cta:active:hover, .btn-cta:focus, .btn-cta:hover {
  background-color: #1b1b32;
  border-width: 3px;
  border-color: #000;
  background-image: none;
  color: #f5f6f7;
}

</style>