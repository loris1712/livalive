<template>
  <div>
    <div
      class="navbarDesktop"
      :class="{
        change_color: scrollPosition > 50,
        change_color2: scrollPosition < 50,
      }"
    >
      <div class="left">
        <div class="logo">
          <img alt="LivAlive logo" src="../assets/logo_livealive.png" />
        </div>

        <div class="number">
          <p>+34 9595 3019 390</p>
        </div>
      </div>

      <div class="right">
        <div class="menu">
          <a href="">
            <div class="link">Products</div>
          </a>

          <a href="">
            <div class="link">Resources</div>
          </a>

          <a href="">
            <div class="link">Get a Demo</div>
          </a>

          <a href="">
            <div class="link">Contact</div>
          </a>

          <div class="lastRight">
            <a href="">
              <div class="link">Log in</div>
            </a>

            <div class="btn">
              <a href="">
                <div class="link">Princing & Free Trial</div>
              </a>
            </div>
          </div>
        </div>

        <div class="menuBtn" @click="openMenu()">
          <img
            src="https://img.icons8.com/ios-filled/50/undefined/circled-menu.png"
          />
        </div>
        <div class="menuBtnClose" @click="closeMenu()">
          <p>-</p>
        </div>
      </div>
    </div>
    <div class="subMenu">
      <div class="link">
        <a href=""> Products </a>
      </div>
      <div class="link">
        <a href=""> Resources </a>
      </div>
      <div class="link">
        <a href=""> Get a Demo </a>
      </div>
      <div class="link">
        <a href=""> Contact </a>
      </div>
      <div class="link">
        <a href=""> Log in </a>
      </div>
      <div class="link">
        <a href=""> Pricing & Free Trial </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "navbarDesktop",
  components: {},
  data() {
    return {
      scrollPosition: null,
    };
  },
  mounted() {
    window.addEventListener("scroll", this.updateScroll);
  },
  methods: {
    updateScroll() {
      this.scrollPosition = window.scrollY;
    },

    openMenu() {
      let content = document.querySelector(".subMenu");
      content.style.width = "-webkit-fill-available";
      content.style.opacity = "1";
      content.style.visibility = "visible";
      content.style.display = "inline";

      let content2 = document.querySelector(".menuBtn");
      content2.style.display = "none";

      let content3 = document.querySelector(".menuBtnClose");
      content3.style.display = "inline";
    },

    closeMenu() {
      let content = document.querySelector(".subMenu");
      content.style.width = "0%";
      content.style.opacity = "0";
      content.style.visibility = "hidden";
      content.style.display = "unset";

      let content2 = document.querySelector(".menuBtn");
      content2.style.display = "inline";

      let content3 = document.querySelector(".menuBtnClose");
      content3.style.display = "none";
    },
  },
};
</script>

<style scoped>
@media (min-width: 1024px) {
  .change_color {
    background-color: #1e7af5;
    backdrop-filter: blur(12px);
    width: fit-content;
    -webkit-transition: all 0.3s ease-in-out;
    transition: all 0.3s ease-in-out;
    box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
  }

  .change_color2 {
    background: transparent;
    width: fit-content;
    -webkit-transition: all 0.3s ease-in-out;
    transition: all 0.3s ease-in-out;
  }

  .menuBtn {
    display: none;
  }

  .menuBtnClose {
    display: none;
  }

  .subMenu {
    display: none;
  }

  .navbarDesktop {
    width: -webkit-fill-available;
    text-align: center;
    position: fixed;
    padding-top: 1rem;
    padding-bottom: 1rem;
    z-index: 15;
    display: flex;
    height: 60px;
    margin-top: 1rem;
    margin-left: 2rem;
    margin-right: 2rem;
    align-items: center;
    transition: all 0.3s ease-in-out;
    border-radius: 20px;
  }

  .navbarDesktop .left {
    display: flex;
    align-items: center;
    margin-left: 3rem;
  }

  .navbarDesktop .logo {
    margin-right: 2rem;
  }

  .navbarDesktop .logo img {
    height: 40px;
  }

  .navbarDesktop .left .number {
    padding-left: 2rem;
    border-left: 1px solid rgba(255, 255, 255, 0.205);
  }

  .navbarDesktop .left .number p {
    color: white;
    font-size: 14px;
    letter-spacing: 1px;
    font-weight: 300;
  }

  .navbarDesktop .right {
    display: flex;
    align-items: center;
    margin-left: auto;
    margin-right: 3rem;
  }

  .navbarDesktop .right .menu {
    display: flex;
    align-items: center;
  }

  .navbarDesktop .right .menu a {
    text-decoration: none;
    margin-right: 2rem;
  }

  .navbarDesktop .right .menu .link {
    color: white;
    font-size: 14px;
    letter-spacing: 0.8px;
    font-weight: 300;
  }

  .navbarDesktop .right .menu .lastRight {
    display: flex;
    align-items: center;
    border-left: 1px solid rgba(255, 255, 255, 0.205);
    padding-left: 2rem;
  }

  .navbarDesktop .right .menu .lastRight .btn {
    display: flex;
    align-items: center;
    padding-top: 0.6rem;
    padding-bottom: 0.6rem;
    padding-left: 1rem;
    padding-right: 1rem;
    background: rgba(255, 255, 255, 0.349);
    text-align: center;
    border-radius: 25rem;
  }

  .navbarDesktop .right .menu .lastRight .btn a {
    margin-right: 0;
  }
}

@media (max-width: 1023px) {
  .change_color {
    background-color: #1e7af5;
    backdrop-filter: blur(12px);
    width: fit-content;
    -webkit-transition: all 0.3s ease-in-out;
    transition: all 0.3s ease-in-out;
    box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
  }

  .change_color2 {
    background: transparent;
    width: fit-content;
    -webkit-transition: all 0.3s ease-in-out;
    transition: all 0.3s ease-in-out;
  }

  .menuBtnClose {
    margin-top: 0;
    width: fit-content;
    font-size: 70px;
    font-weight: 400;
    margin-right: 0.3rem;
    display: none;
    margin-right: 1rem;
    -webkit-transition: all 0.3s ease-in-out;
    transition: all 0.3s ease-in-out;
    cursor: pointer;
  }

  .subMenu {
    position: fixed;
    padding: 2rem;
    padding-top: 6.5rem;
    background: #1e7af5;
    width: -webkit-fill-available;
    height: fit-content;
    width: 0%;
    opacity: 0;
    visibility: hidden;
    display: inline;
    -webkit-transition: all 0.3s ease-in-out;
    transition: all 0.3s ease-in-out;
  }

  .subMenu .title {
    color: #fff;
    font-size: 22px;
    line-height: 26px;
    font-weight: 600;
    margin-bottom: 1rem;
  }

  .subMenu .link a {
    text-decoration: none;
    color: #fff;
  }

  .subMenu .link {
    color: #fff;
    font-size: 18px;
    line-height: 22px;
    font-weight: 300;
    margin-bottom: 2rem;
  }

  .navbarDesktop {
    width: 100%;
    text-align: center;
    position: fixed;
    padding-top: 1rem;
    z-index: 15;
    display: flex;
    height: 60px;
    align-items: center;
    transition: all 0.3s ease-in-out;
  }

  .navbarDesktop .left {
    display: flex;
    align-items: center;
    margin-left: 2rem;
  }

  .navbarDesktop .logo {
    margin-right: 1rem;
  }

  .navbarDesktop .logo img {
    height: 30px;
  }

  .navbarDesktop .left .number {
    display: none;
  }

  .navbarDesktop .left .number p {
    color: white;
    font-size: 14px;
    letter-spacing: 1px;
    font-weight: 300;
  }

  .navbarDesktop .right {
    display: flex;
    align-items: center;
    margin-left: auto;
    margin-right: 1rem;
  }

  .menuBtn {
    display: inline;
    margin-right: 1rem;
    -webkit-transition: all 0.3s ease-in-out;
    transition: all 0.3s ease-in-out;
    cursor: pointer;
  }

  .menuBtn img {
    width: 30px;
  }

  .navbarDesktop .right .menu {
    display: none;
  }

  .navbarDesktop .right .menu a {
    text-decoration: none;
    margin-right: 2rem;
  }

  .navbarDesktop .right .menu .link {
    color: white;
    font-size: 14px;
    letter-spacing: 0.8px;
    font-weight: 300;
  }

  .navbarDesktop .right .menu .lastRight {
    display: flex;
    align-items: center;
    border-left: 1px solid rgba(255, 255, 255, 0.205);
    padding-left: 2rem;
  }

  .navbarDesktop .right .menu .lastRight .btn {
    display: flex;
    align-items: center;
    padding-top: 0.6rem;
    padding-bottom: 0.6rem;
    padding-left: 1rem;
    padding-right: 1rem;
    background: rgba(255, 255, 255, 0.349);
    text-align: center;
    border-radius: 25rem;
  }

  .navbarDesktop .right .menu .lastRight .btn a {
    margin-right: 0;
  }
}
</style>
