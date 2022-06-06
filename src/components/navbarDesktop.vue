<template>
  <div>
    <div class="navbarDesktop">
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
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "navbarDesktop",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
.navbarDesktop {
  width: 100vw;
  text-align: center;
  position: fixed;
  padding-top: 1rem;
  z-index: 15;
  display: flex;
  height: 60px;
  margin-left: auto;
  margin-right: auto;
  align-items: center;
  -webkit-transition: all 0.3s ease-in-out;
  transition: all 0.3s ease-in-out;
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
</style>
