<template>
  <div>
    <div class="homePart1">
      <div class="content">
        <div class="col1">
          <div class="logo">
            <img alt="LivAlive logo" src="../assets/logo_livealive2.png" />
          </div>
        </div>
        <div class="col">
          <div class="title">Company</div>
          <div class="link">
            <a href=""> Company </a>
          </div>
          <div class="link">
            <a href=""> Company </a>
          </div>
          <div class="link">
            <a href=""> Company </a>
          </div>
        </div>
        <div class="col">
          <div class="title">Company</div>
          <div class="link">
            <a href=""> Company </a>
          </div>
          <div class="link">
            <a href=""> Company </a>
          </div>
          <div class="link">
            <a href=""> Company </a>
          </div>
        </div>
        <div class="col">
          <div class="title">Company</div>
          <div class="link">
            <a href=""> Company </a>
          </div>
          <div class="link">
            <a href=""> Company </a>
          </div>
          <div class="link">
            <a href=""> Company </a>
          </div>
        </div>
      </div>
      <div class="content2">
        <div class="left">
          <a href="">Made by Loris Caputo</a>
          <a href="">Privacy Policy</a>
          <a href="">Termini & Condizioni</a>
          <a href="">2022. Tutti i diritti riservati.</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "footerDesktop",
  props: {},
};
</script>

<style scoped>
@media (min-width: 1024px) {
  .homePart1 {
    background: #fff;
  }

  .homePart1 .content {
    display: flex;
    padding: 10rem;
  }

  .homePart1 .content .col1 {
    margin-right: 10rem;
    width: fit-content;
  }

  .content .col1 .logo img {
    height: 40px;
  }

  .content .col {
    margin-left: auto;
  }

  .content .col .title {
    color: rgb(46, 46, 46);
    font-size: 20px;
    line-height: 24px;
    font-weight: 600;
    margin-bottom: 1rem;
  }

  .content .col .link a {
    text-decoration: none;
    margin-right: 2rem;
    color: rgb(46, 46, 46);
  }

  .content .col .link {
    color: rgb(46, 46, 46);
    font-size: 16px;
    line-height: 20px;
    font-weight: 300;
    margin-bottom: 1rem;
  }

  .content2 {
    padding-left: 10rem;
    padding-bottom: 2rem;
    padding-right: 10rem;
    display: flex;
    align-items: center;
  }

  .content2 a {
    margin: 0;
    margin-right: 2rem;
    color: rgb(46, 46, 46);
    font-size: 14px;
    line-height: 28px;
    font-weight: 300;
    text-decoration: none;
  }
}

@media (max-width: 1023px) {
  .homePart1 {
    background: #fff;
  }

  .homePart1 .content {
    padding: 5rem;
    text-align: center;
  }

  .homePart1 .content .col1 {
    margin-left: auto;
    margin-right: auto;
    width: fit-content;
    margin-bottom: 2rem;
  }

  .content .col1 .logo img {
    height: 40px;
  }

  .content .col {
    margin-left: auto;
  }

  .content .col .title {
    color: rgb(46, 46, 46);
    font-size: 20px;
    line-height: 24px;
    font-weight: 600;
    margin-bottom: 1rem;
  }

  .content .col .link a {
    text-decoration: none;
    color: rgb(46, 46, 46);
  }

  .content .col .link {
    color: rgb(46, 46, 46);
    font-size: 16px;
    line-height: 20px;
    font-weight: 300;
    margin-bottom: 1rem;
  }

  .content2 {
    padding-left: 4rem;
    padding-bottom: 2rem;
    padding-right: 4rem;
    align-items: center;
  }

  .content2 a {
    margin: 0;
    margin-right: 2rem;
    color: rgb(46, 46, 46);
    font-size: 14px;
    line-height: 28px;
    font-weight: 300;
    text-decoration: none;
  }
}
</style>
