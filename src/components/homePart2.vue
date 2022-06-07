<template>
  <div>
    <div class="homePart1">
      <div class="content">
        <div class="hr"></div>
        <h2>Organize, manages and improve relationships</h2>
        <p>
          Organize, manages and improve relationships, Organize, manages and
          improve relationships, Organize, manages and improve relationships.,
          Organize, manages and improve relationships.
        </p>
        <div class="people">
          <img alt="People" src="../assets/people3.jpg" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "homePart2",
  props: {},
};
</script>

<style scoped>
@media (min-width: 1024px) {
  .homePart1 {
    background: #fff;
  }

  .homePart1 .content {
    padding: 5rem;
  }

  .homePart1 .content .hr {
    width: 5%;
    background: rgb(36, 36, 36);
    height: 3px;
    margin-left: auto;
    margin-right: auto;
  }

  .homePart1 .content h2 {
    color: rgb(46, 46, 46);
    font-size: 48px;
    line-height: 52px;
    font-weight: 400;
    margin-bottom: 0;
    width: 70%;
    margin-left: auto;
    margin-right: auto;
    text-align: center;
  }

  .homePart1 .content p {
    color: rgb(87, 86, 86);
    font-size: 18px;
    line-height: 28px;
    font-weight: 200;
    margin-top: 2rem;
    width: 70%;
    margin-left: auto;
    margin-right: auto;
    text-align: center;
  }

  .homePart1 .content .people {
    margin-top: 5rem;
    text-align: center;
  }

  .homePart1 .content .people img {
    width: auto;
    height: 600px;
  }
}

@media (max-width: 1023px) {
  .homePart1 {
    background: #fff;
  }

  .homePart1 .content {
    padding: 4rem;
    text-align: center;
  }

  .homePart1 .content .hr {
    width: 5%;
    background: rgb(36, 36, 36);
    height: 3px;
    margin-left: auto;
    margin-right: auto;
  }

  .homePart1 .content h2 {
    color: rgb(46, 46, 46);
    font-size: 45px;
    line-height: 49px;
    font-weight: 400;
    margin-bottom: 0;
  }

  .homePart1 .content p {
    color: rgb(87, 86, 86);
    font-size: 18px;
    line-height: 28px;
    font-weight: 200;
    margin-top: 2rem;
    width: 70%;
    margin-left: auto;
    margin-right: auto;
    text-align: center;
  }

  .homePart1 .content .people {
    margin-top: 5rem;
    text-align: center;
    display: none;
  }

  .homePart1 .content .people img {
    width: auto;
    height: 600px;
  }
}
</style>
