<template>
  <div>
    <h2>{{ msg }}</h2>
    <section id="main-one">
      <p>
        I'm
        <strong>Adebowale Damilare Desmond</strong>
      </p>
      <p>You: Who bears that long name?</p>
      <p>
        Me: Yea, it's a long one, you can always call me
        <strong>Desmond</strong>
      </p>
      <div id="main-two">
        I'm a
        <strong>Software Developer</strong>
        <p>
          I listen to music a lot in my free time,
          hopefully I am going to put one out there one day.
        </p>
      </div>
    </section>
    <form action method="post">
      <p>
        Subscribe to my newsletter to receive updates on my work and also to
        crack you up on my funny activities
      </p>
      <input type="text" placeholder="e.g. your email address" />
      <input type="submit" />
    </form>

    <footer>
      <h4>You can also reach me on the following channels below</h4>
      <ul>
        <li>
          <a href="https://twitter.com/Whizdes" target="_blank">Twitter</a>
        </li>
        <li>
          <a href="https://medium.com/@desmondadebowale" target="_blank">Medium</a>
        </li>
        <li>
          <a href="https://linkedin.com/in/damilare-adebowale-456057129" target="_blank">linkedin</a>
        </li>
        <li>
          <a href="https://github.com/desmondadebowale" target="_blank">GitHub</a>
        </li>
        <li>
          <a href="https://dev.to/whizdes" target="_blank">Dev</a>
        </li>
      </ul>

      <p>Copyright &copy; 2020 Adebowale Damilare Desmond</p>
    </footer>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#main-one,
#main-two {
  width: 90%;
  margin: auto;
  overflow: hidden;
  box-sizing: border-box;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: rgb(10, 5, 5);
  text-decoration: none;
  font-size: 18px;
  padding-right: 15px;
}
</style>
