<template>
  <div class="container-fluid m-0 p-0">
    <div id="home-page" class="full-height p-4">
      <div class="container pt-3">
        <div class="row pb-5">
          <div class="col-lg-6 pt-4 my-auto">
            <div class="text-center mb-3 d-block d-lg-none">
              <h1 class="display-3">{{ title }}</h1>
              <h3>Find the World by doing it</h3>
            </div>
            <img
              id="iphone-img"
              src="../assets/phone.png"
              alt=""
              class="img-fluid"
            />
          </div>
          <div class="col-lg-6 my-auto pt-4">
            <div class="text-center mb-3 d-none d-lg-block">
              <h1 class="display-3">{{ title }}</h1>
              <h3>Find the World by doing it</h3>
            </div>
            <div class="border p-3 p-md-5 bg-white rounded shadow">
              <h2>Comming Soon</h2>
              <form action="">
                <div class="form-group">
                  <label for="emailSignUp"
                    >Reserve your account now, we'll contact you when it's
                    live</label
                  >
                  <input
                    id="emailSignUp"
                    type="text"
                    placeholder="Enter Email"
                    class="form-control"
                  />
                  <small id="emailHelp" class="form-text text-muted"
                    >We'll never share your email address</small
                  >
                  <button type="submit" class="btn btn-success mt-3">
                    Join Waiting List
                  </button>
                </div>
              </form>
            </div>
            <div id="available" class="p-2">
              <h4 class="text-center mb-2 mt-3 text-light">
                Available On
              </h4>
              <div class="row">
                <div class="col my-auto">
                  <img
                    src="..\assets\en_badge_web_generic.png"
                    alt=""
                    class="float-right img-fluid app_store_img"
                  />
                </div>
                <div class="col my-auto">
                  <img
                    src="..\assets\Download_on_the_App_Store_Badge_ES_RGB_blk_100217.svg"
                    alt=""
                    class="float-left img-fluid app_store_img"
                  />
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div id="about" class="bg-warning p-4"></div>
    <div id="contact" class="bg-info p-4"></div>
    <div id="footer" class="bg-primary p-4"></div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: "Run for your life",
    };
  },
};
</script>

<style scoped>
#home-page {
  background-color: #92d2f2;
  background: url(../assets/jogging-2343558.jpg);
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -ms-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}

#iphone-img {
  max-height: 80vh;
}
.app_store_img {
  max-height: 100px;
}
</style>
