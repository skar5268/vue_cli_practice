<template>
  <div
    id="carouselExampleCaptions"
    class="carousel slide"
    data-bs-ride="carousel"
  >
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
            <button
              type="button"
              class="btn btn-outline-light rounded-pill mt-2 py-3 px-5"
            >
              SHOP NOW
            </button>
          </router-link>
        </div>
      </div>
    </div>
  </div>

  <div class="container">
    <div class="row mt-5">
      <div class="col-md-4 mt-md-4">
        <div class="card border-0 mb-4">
          <img
            src="https://images.unsplash.com/photo-1533090368676-1fd25485db88?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=750&q=80"
            class="card-img-top rounded-0"
            alt="..."
          />
          <div class="card-body text-center">
            <h4>時尚簡約櫃組</h4>
            <div class="d-flex justify-content-between">
              <p class="card-text text-muted mb-0">
                Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed
                diam nonumy eirmod.
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-4 mt-md-4">
        <div class="card border-0 mb-4">
          <img
            src="https://images.unsplash.com/photo-1610671907006-ed6b3148aa9e?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=750&q=80"
            class="card-img-top rounded-0"
            alt="..."
          />
          <div class="card-body text-center">
            <h4>客廳居家沙發</h4>
            <div class="d-flex justify-content-between">
              <p class="card-text text-muted mb-0">
                Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed
                diam nonumy eirmod.
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-4 mt-md-4">
        <div class="card border-0 mb-4">
          <img
            src="https://images.unsplash.com/photo-1465224414649-ceb7f1db3999?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80"
            class="card-img-top rounded-0"
            alt="..."
          />
          <div class="card-body text-center">
            <h4>舒適好坐椅子</h4>
            <div class="d-flex justify-content-between">
              <p class="card-text text-muted mb-0">
                Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed
                diam nonumy eirmod.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="bg-light mt-4 mb-4 p-4 ">
    <div class="container">
      <div
        id="carouselExampleControls"
        class="carousel slide"
        data-ride="carousel"
      >
        <div class="carousel-inner">
          <div class="carousel-item active">
            <div class="row justify-content-center py-5">
              <div class="col-md-6 text-center py-4">
                <h3>RE：HOUSE，Make Life Easier</h3>
                <p class="my-3">
                  帶你進入美好生活，幫你找到最適合的傢俱，讓你享受每一刻精彩。
                </p>
                <p><small>— RE：HOUSE，您的居家最佳夥伴 —</small></p>
              </div>
            </div>
          </div>
          <div class="carousel-item">
            <div class="row justify-content-center py-5">
              <div class="col-md-6 text-center">
                <h3>Lorem ipsum.</h3>
                <p class="my-5">
                  “Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed
                  diam nonumy eirmod tempor invidunt ut labore et dolore magna
                  aliquyam erat.”
                </p>
                <p><small>—Lorem ipsum dolor sit amet.—</small></p>
              </div>
            </div>
          </div>
          <div class="carousel-item">
            <div class="row justify-content-center py-5">
              <div class="col-md-6 text-center">
                <h3>Lorem ipsum.</h3>
                <p class="my-5">
                  “Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed
                  diam nonumy eirmod tempor invidunt ut labore et dolore magna
                  aliquyam erat.”
                </p>
                <p><small>—Lorem ipsum dolor sit amet.—</small></p>
              </div>
            </div>
          </div>
        </div>
        <a
          class="carousel-control-prev"
          href="#carouselExampleControls"
          role="button"
          data-slide="prev"
        >
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
        </a>
        <a
          class="carousel-control-next"
          href="#carouselExampleControls"
          role="button"
          data-slide="next"
        >
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </a>
      </div>
    </div>
  </div>
  <div class="container my-7 mb-4">
    <div class="row">
      <div class="col-md-6 g-0">
        <img
          src="https://images.unsplash.com/photo-1589362281138-e3f7ebe47f1a?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80"
          alt=""
          class="img-fluid"
        />
      </div>
      <div class="col-md-4 m-auto text-center">
        <h4 class="mt-4">嚴選家居</h4>
        <p class="text-muted">
          收納櫃組、客廳家俱到寢具一應俱全。 <br />
          WFH居家必備，打造屬於自己的角落。
        </p>
      </div>
    </div>
    <div class="row flex-row-reverse justify-content-between ">
      <div class="col-md-6 g-0">
        <img
          src="https://images.unsplash.com/photo-1486591038957-19e7c73bdc41?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=750&q=80"
          alt=""
          class="img-fluid"
        />
      </div>
      <div class="col-md-4 m-auto text-center">
        <h4 class="mt-4">防疫樂活</h4>
        <p class="text-muted">
          WFH 盛行，選擇最適合你風格的工作環境，<br />
          搭配家中擺設與家俱風格，增添生活樂趣。
        </p>
      </div>
    </div>
  </div>
  <!-- sub -->
  <div class="bg-light py-4">
    <div class="container">
      <div
        class="d-flex flex-column flex-md-row justify-content-between
        align-items-md-center align-items-start"
      >
        <p class="mb-0 fw-bold">
          立即訂閱，獲取最新優惠
        </p>
        <div class="input-group w-md-50 mt-md-0 mt-3">
          <input type="text" class="form-control rounded-0" placeholder="" />
          <div class="input-group-append">
            <button class="btn btn-dark rounded-0" type="button" id="search">
              取得優惠
            </button>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- footer -->
  <div class="bg-dark">
    <div class="container">
      <div
        class="d-flex align-items-center justify-content-between text-white py-4"
      >
        <p class="mb-0">© 2020 LOGO All Rights Reserved.</p>
        <ul class="d-flex list-unstyled mb-0 h4">
          <li>
            <a href="#" class="text-white mx-3"
              ><i class="fab fa-facebook"></i
            ></a>
          </li>
          <li>
            <a href="#" class="text-white mx-3"
              ><i class="fab fa-instagram"></i
            ></a>
          </li>
          <li>
            <a href="#" class="text-white ms-3"><i class="fab fa-line"></i></a>
          </li>
        </ul>
      </div>
    </div>
  </div>
  <div class="home">
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
