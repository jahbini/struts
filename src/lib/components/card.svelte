<script>
 export let post
</script>

<div class="card card-compact w-96 bg-base-100 shadow-xl"> 
  <figure><img src="{post.photo}" alt="{post.summary}" /></figure> 
  <div class="card-body"> 
    <h2 class="card-title">{post.title}!</h2> 
    <p>{post.summary}</p> 
    <div class="card-actions justify-end"> 
      <a class="btn btn-primary" href="{post.path}">Read more</a> 
    </div> 
  </div>
</div>

