
<template>
    <div class="container">
        <div class="row justify-content-center">
          <div class="col-md-8">
                <div class="card">
                <p>{{message}}</p>
                <small>{{author}}</small>
                </div>
          </div>
          </div>
        </div>

</template>

<script>
    export default {
      data() {

          return {
              message : "this is your message",
              author : "abhilash das"
          }

      }
    }
</script>
