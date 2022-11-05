<template>
    <div >
      <div class="rightWrapper">
        <div class="wrapper">
        <div>
          <h2 aria-level="2" role="heading">
            <div dir="auto"><span>New to
                Twitter?</span></div>
            <div></div>
          </h2>
        </div>
        <div>
          <div class="buttons">Sign up with Google</div>
          <div class="buttons">Sign up with Apple</div>
          <div class="buttons">Sign up with Email</div>
        </div>
      </div>
        <div 
          >
          <small>© 2022 Twitter, Inc.</small>
        </div>
      </div>
    </div>
</template>
  
<script>
export default {
  name: 'RightContainer',
}
</script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.buttons {
  padding: 12px 16px;
  border: 1px solid grey;
  border-radius: 19px;
  margin-block: 0.5rem;
  text-align: center;
}
.rightWrapper{
  position: sticky;
    top: 61px;
}
.wrapper{
  border-radius: 16px;
    border: 1px solid rgb(239, 243, 244);
    padding: 11px;
}
small{
  color: rgb(83, 100, 113);
}
</style>
  