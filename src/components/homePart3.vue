<template>
  <div>
    <div class="homePart1">
      <div class="content">
        <div class="col2">
          <div class="people">
            <img alt="People" src="../assets/people4.jpg" />
          </div>
        </div>
        <div class="col1">
          <div class="hr"></div>
          <h2>Organize, manages and improve relationships</h2>
          <p>Organize, manages and improve relationships.</p>
          <div class="buttons">
            <div class="button btn1">Try it free</div>
            <div class="button btn2">Get a demo</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "homePart3",
  props: {},
};
</script>

<style scoped>
@media (min-width: 1024px) {
  .homePart1 {
    background: #1e7bf558;
  }

  .homePart1 .content {
    display: flex;
    align-items: center;
    padding: 10rem;
  }

  .homePart1 .content .col1 {
    margin-top: 3rem;
    width: 60%;
  }

  .homePart1 .content .col1 .hr {
    width: 15%;
    background: rgb(36, 36, 36);
    height: 3px;
  }

  .homePart1 .content .col1 h2 {
    color: rgb(46, 46, 46);
    font-size: 74px;
    line-height: 78px;
    text-align: left;
    font-weight: 400;
    margin-bottom: 0;
  }

  .homePart1 .content .col1 p {
    color: rgb(87, 86, 86);
    font-size: 24px;
    line-height: 28px;
    text-align: left;
    font-weight: 100;
    margin-top: 1rem;
  }

  .homePart1 .content .col1 .buttons {
    display: flex;
    align-items: center;
    margin-top: 4rem;
  }

  .homePart1 .content .col1 .buttons .button {
    display: flex;
    align-items: center;
    padding-top: 1rem;
    padding-bottom: 1rem;
    padding-left: 2.2rem;
    padding-right: 2.2rem;
    background: rgba(255, 255, 255, 0.349);
    text-align: center;
    border-radius: 25rem;
    color: white;
    margin-right: 2rem;
    cursor: pointer;
  }

  .homePart1 .content .col1 .buttons .btn1 {
    background: #1e7af5;
    color: #fff;
  }

  .homePart1 .content .col1 .buttons .btn2 {
    border: 2px solid #fff;
    background: #fff;
    color: #1e7af5;
  }

  .homePart1 .content .col2 {
    margin-top: 3rem;
    width: 40%;
  }

  .homePart1 .content .col2 .logo {
    margin-right: 2rem;
  }

  .homePart1 .content .col2 .logo img {
    height: 400px;
  }

  .homePart1 .content .col2 .people {
    margin-right: 2rem;
  }

  .homePart1 .content .col2 .people img {
    height: 500px;
  }

  .homePart1 .content .col2 .people2 {
    margin-right: 2rem;
  }

  .homePart1 .content .col2 .people2 img {
    height: 500px;
  }

  .btnElement {
    border-top-left-radius: 20px;
    border-top-right-radius: 20px;
    background: white;
    width: fit-content;
    margin-left: auto;
    margin-right: 10rem;
    display: flex;
    align-items: center;
  }

  .btnElement p {
    margin: 0;
    font-weight: 500;
    padding: 1rem;
    width: 70%;
    text-align: left;
  }

  .btnElement img {
    height: 30px;
    padding: 0.5rem;
    margin: 0.5rem;
    margin-left: 1rem;
    background: #1e7bf546;
    border-radius: 25rem;
  }
}

@media (max-width: 1023px) {
  .homePart1 {
    background: #1e7bf558;
  }

  .homePart1 .content {
    align-items: center;
    padding: 4rem;
  }

  .homePart1 .content .col1 {
    margin-top: 3rem;
    text-align: center;
  }

  .homePart1 .content .col1 .hr {
    width: 15%;
    background: rgb(36, 36, 36);
    height: 3px;
  }

  .homePart1 .content .col1 h2 {
    color: rgb(46, 46, 46);
    font-size: 45px;
    line-height: 49px;
    font-weight: 400;
    margin-bottom: 0;
  }

  .homePart1 .content .col1 p {
    color: rgb(87, 86, 86);
    font-size: 24px;
    line-height: 28px;
    font-weight: 100;
    margin-top: 1rem;
  }

  .homePart1 .content .col1 .buttons {
    align-items: center;
    margin-top: 4rem;
  }

  .homePart1 .content .col1 .buttons .button {
    align-items: center;
    padding-top: 1rem;
    padding-bottom: 1rem;
    padding-left: 2.2rem;
    padding-right: 2.2rem;
    background: rgba(255, 255, 255, 0.349);
    text-align: center;
    border-radius: 25rem;
    color: white;
    margin-bottom: 1.5rem;
    cursor: pointer;
  }

  .homePart1 .content .col1 .buttons .btn1 {
    background: #1e7af5;
    color: #fff;
  }

  .homePart1 .content .col1 .buttons .btn2 {
    border: 2px solid #fff;
    background: #fff;
    color: #1e7af5;
  }

  .homePart1 .content .col2 {
    margin-top: 3rem;
    width: 40%;
  }

  .homePart1 .content .col2 .logo {
    margin-right: 2rem;
  }

  .homePart1 .content .col2 .logo img {
    height: 400px;
  }

  .homePart1 .content .col2 .people {
  }

  .homePart1 .content .col2 .people img {
    height: 400px;
  }

  .homePart1 .content .col2 .people2 {
    margin-right: 2rem;
  }

  .homePart1 .content .col2 .people2 img {
    height: 500px;
  }
}
</style>
