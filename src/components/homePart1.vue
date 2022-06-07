<template>
  <div>
    <div class="homePart1">
      <div class="content">
        <div class="col1">
          <div class="hr"></div>
          <h2>Organize, manages and improve relationships</h2>
          <p>Organize, manages and improve relationships.</p>
          <div class="buttons">
            <div class="button btn1">Try it free</div>
            <div class="button btn2">Get a demo</div>
          </div>
        </div>
        <div class="col2">
          <div class="people">
            <img alt="People" src="../assets/people2.jpg" />
          </div>
          <div class="people2">
            <img alt="People" src="../assets/people1.jpg" />
          </div>
        </div>
      </div>
      <div class="btnElement">
        <img
          src="https://img.icons8.com/ios-filled/50/undefined/appointment-reminders--v1.png"
        />
        <p>The platform is coming soon, keep in touch.</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "homePart1",
  props: {},
};
</script>

<style scoped>
@media (min-width: 1024px) {
  .homePart1 {
    background: #1e7af5; /* fallback for old browsers */
    background: -webkit-linear-gradient(
      to top,
      #42a7f7,
      #1e7af5
    ); /* Chrome 10-25, Safari 5.1-6 */
    background: linear-gradient(
      to top,
      #42a7f7,
      #1e7af5
    ); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
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
    background: white;
    height: 3px;
  }

  .homePart1 .content .col1 h2 {
    color: white;
    font-size: 74px;
    line-height: 78px;
    text-align: left;
    font-weight: 400;
    margin-bottom: 0;
  }

  .homePart1 .content .col1 p {
    color: white;
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
    background: #fff;
    color: #1e7af5;
  }

  .homePart1 .content .col1 .buttons .btn2 {
    border: 2px solid #fff;
    background: transparent;
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
    position: absolute;
    top: 20%;
    right: 10%;
  }

  .homePart1 .content .col2 .people img {
    height: 500px;
  }

  .homePart1 .content .col2 .people2 {
    margin-right: 2rem;
    position: absolute;
    top: 50%;
    right: 25%;
  }

  .homePart1 .content .col2 .people2 img {
    height: 400px;
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
    background: #1e7af5; /* fallback for old browsers */
    background: -webkit-linear-gradient(
      to top,
      #42a7f7,
      #1e7af5
    ); /* Chrome 10-25, Safari 5.1-6 */
    background: linear-gradient(
      to top,
      #42a7f7,
      #1e7af5
    ); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
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
    background: white;
    height: 3px;
    margin-left: auto;
    margin-right: auto;
  }

  .homePart1 .content .col1 h2 {
    color: white;
    font-size: 45px;
    line-height: 49px;
    font-weight: 400;
    margin-bottom: 0;
  }

  .homePart1 .content .col1 p {
    color: white;
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
    background: #fff;
    color: #1e7af5;
  }

  .homePart1 .content .col1 .buttons .btn2 {
    border: 2px solid #fff;
    background: transparent;
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
    top: 20%;
    right: 10%;
  }

  .homePart1 .content .col2 .people img {
    height: 400px;
  }

  .homePart1 .content .col2 .people2 {
    top: 50%;
    right: 25%;
  }

  .homePart1 .content .col2 .people2 img {
    height: 400px;
  }

  .btnElement {
    border-top-left-radius: 20px;
    border-top-right-radius: 20px;
    background: white;
    width: fit-content;
    margin-left: auto;
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
</style>
