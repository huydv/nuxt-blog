<template>
  <div class="single-post-page">
    <!-- <section class="post">
      <h1>Title of the post</h1>
      <div class="post-details">
        <div>Last updated on </div>
        <div>Written by Name</div>
      </div>

      <p>Content of post</p>
    </section>

    <section class="post-feedback">
      Post feedback
    </section> -->

    <b-card>
    <b-media>
      <template #aside>
        <b-img blank blank-color="#ccc" width="64" alt="placeholder"></b-img>
      </template>

      <h5 class="mt-0">Title of the post</h5>
      <p>
        Content of post
      </p>


      <b-media>
        <h5 class="mt-0">Nested Media</h5>
        <p class="mb-0">
          Last updated on
        </p>
         <p class="mb-0">
          Written by Name
        </p>
      </b-media>
    </b-media>
  </b-card>
  </div>
</template>
