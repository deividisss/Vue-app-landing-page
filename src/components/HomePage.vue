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

    <div id="about" class="bg-light p-3 p-md-5">
      <div class="row">
        <div class="col-lg">
          <img src="../assets/icons/app.svg" alt="" height="120" class="m-4" />
          <h5 class="ml-md-4 mr-md-4">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Nobis sequi
            quod dolores quisquam ullam sunt, iure minus animi quis officia
            necessitatibus temporibus nam quae obcaecati voluptatum ab maxime
            dignissimos?
          </h5>
        </div>
        <div class="col-lg">
          <img
            src="../assets/icons/folder.svg"
            alt=""
            height="120"
            class="m-4"
          />
          <h5 class="ml-md-4 mr-md-4">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Nobis sequi
            quod dolores quisquam ullam sunt, iure minus animi quis officia
            necessitatibus temporibus nam quae obcaecati voluptatum ab maxime
            dignissimos? Magni iure esse nobis tempora eum? Accusantium,
            ducimus.
          </h5>
        </div>
        <div class="col-lg">
          <img
            src="../assets/icons/smartphone.svg"
            alt=""
            height="120"
            class="m-4"
          />
          <h5 class="ml-md-4 mr-md-4">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Nobis sequi
            quod dolores quisquam ullam sunt, iure minus animi quis officia
            necessitatibus temporibus nam quae obcaecati voluptatum ab maxime
            dignissimos?
          </h5>
        </div>
      </div>
    </div>

    <div id="contact" class=" p-4">
      <div class="row justify-content-center mt-3 mb-3">
        <div class="col-lg-4">
          <h2>Have Any Question?</h2>
          <p>Contanct us by filling out the information below</p>

          <form>
            <div class="form-group text-left">
              <input
                type="email"
                class="form-control"
                placeholder="Enter your Email"
              />
              <textarea
                class="form-control mt-3"
                placeholder="Enter Your Message"
                rows="5"
              ></textarea>
            </div>
          </form>
        </div>
      </div>
    </div>
    <div id="footer" class="p-4">
      <footer class="text-light p-4">
        <a href="https://www.youtube.com/" target="_blank" class="text-warning"
          >Build This App |
        </a>
        <a href="#" class="text-warning">Privacy Policy</a>
        <br />
        <small>&copy; 2020, TravelTreasury.app</small>
      </footer>
    </div>
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
#about {
  min-height: 40vh;
}
#contact {
  background-color: #57aeaf;
}
#footer {
  background-color: #252223;
}
</style>
