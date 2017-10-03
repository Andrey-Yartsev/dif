<template>
  <div>
    <div class="breadcrumbs">Demo Bank > <a href="#">Accounts</a></div>
    <h1>Accounts</h1>
    <div class="body">
      <div class="body-text">
        <p>Hi guys, I join this conversation cause I been burning my brains out trying to figure out how to do this.</p>
        <p>I'm making a news site that fetches data from the wordpress api (we're using wordpress for the client to upload the news).</p>
        <p>So naturally I made dynamic routes with the name of the news post in it like so: www.mywebsite.com/news/a-news-title</p>
        <p>So the problem is, one of the requirements is that users should be able to copy and paste that link on facebook and get the right preview (the news post image, title and short description).</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'accounts',
  data () {
    return {
    }
  }
}
</script>
