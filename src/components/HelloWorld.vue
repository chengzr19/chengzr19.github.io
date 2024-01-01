<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Zirui Cheng <br/> chengzr19@mails.tsinghua.edu.cn
    </p>
    <h2>Courses</h2>
    <h3>Artificial Intelligence</h3>
    <ul>
      <li><a href="https://web.stanford.edu/class/cs224n/">Natural Language Processing with Deep Learning</a> by Christopher D. Manning</li><br/>
      <li><a href="https://cmu-llms.org/">Large Language Models Methods and Applications</a> by Chenyan Xiong and Daphne Ippolito</li>
    </ul>
    <h3>Human-Computer Interaction</h3>
    <ul>
      <li><a href="https://hcicourses.stanford.edu/cs347/2023/">Human-Computer Interaction: Foundations and Frontiers</a> by Michael S. Bernstein</li>
    </ul>
    <h3>Software Engineering</h3>
    <ul>
      <li><a href="https://ckaestne.medium.com/machine-learning-in-production-book-overview-63be62393581">Machine Learning in Production</a> by Christian Kästner</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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
  color: #42b983;
}
</style>
