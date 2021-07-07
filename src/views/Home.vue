<template>
  <div class="home">
      <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-indicators"></div>
    <div class="carousel-inner">
      <div class="carousel-item active ">
        <div
          class="card-img-top"
          style="height: 80vh; background-image: url(https://images.unsplash.com/photo-1519974719765-e6559eac2575?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=750&q=100);
          background-size: cover;
          background-position:bottom center;
          "
        ></div>
        <div class="carousel-caption d-none d-md-block ">
          <h1>讓你的居家風格更加獨特</h1>
          <p>帶你進入美好生活，創造你的生活美學</p>

          <router-link to="/products">
            <button type="button" class="btn btn-outline-light rounded-pill mt-2 py-3 px-5">
              SHOP NOW
            </button>
          </router-link>
        </div>
      </div>
    </div>
  </div>
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <Form v-slot="{ errors, values, validate }" @submit="onSubmit">
      {{ errors }} {{ values }}

      <div class="mb-3">
        <label for="email" class="form-label">Email</label>

        <Field
          id="email"
          name="email"
          type="email"
          class="form-control"
          :class="{ 'is-invalid': errors['email'] }"
          placeholder="請輸入 Email"
          rules="email|required"
          v-model="user.email"
        ></Field>

        <error-message name="email" class="invalid-feedback"></error-message>
      </div>

      <button
        class="btn me-2 btn-outline-primary"
        type="button"
        @click="validate"
      >
        驗證
      </button>

      <button class="btn btn-primary" type="submit">Submit</button>
    </Form>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',

  data () {
    return {
      user: {}
    }
  },

  components: {
    HelloWorld
  },

  methods: {
    onSubmit () {
      console.log(this.user)
    }
  },

  created () {
    console.log(this)
  }
}
</script>
