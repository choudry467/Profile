<template>
    <a href="https://www.facebook.com/choudhry467" class="fa fa-facebook"></a>
    <a href="https://www.linkedin.com/in/choudry-abdulrehman/" class="fa fa-linkedin"></a>
    <a href="https://github.com/choudry467" class="fa fa-github"></a>
</template>

<script>
export default {
  name: 'SocialMedia'
}
</script>

<style scoped>
.fa {
    margin: 30px 5px;
   padding: 20px;
  font-size: 30px;
  width: 30px;
  text-align: center;
  text-decoration: none;
  border-radius: 50%;
}

/* Add a hover effect if you want */
.fa:hover {
  opacity: 0.7;
  width: 28px;
  font-size: 28px;
}

/* Set a specific color for each brand */

/* Facebook */
.fa-facebook {
  background: #3B5998;
  color: white;
}

/* Twitter */
.fa-linkedin {
  background: #55ACEE;
  color: white;
}

.fa-github {
  background: white;
  color: black;
}
</style>