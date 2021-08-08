<template>
  <div class="container">
    <div class="main-page">
      <header>
        <div class="header-panel">
          <a href="#" class="header-panel_logo">KATTAgroceries</a>
        </div>
        <div class="header-top">
          <h1 class="header-top_t">
            <span class="header-top_subt">Your shopping, picked personally!</span>
            KATTA good living.
          </h1>
          <p class="header-top_tx">
            You'll find food news, recipes, lifestyle hints, hacks and tips, family activities, community and more.
            Katta stores house all sorts of services to make shopping with us, fast and friendly.
          </p>
        </div>
      </header>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="sass">
.main-page
  border: 1px solid #ededed
  font-family: Arial, sans-serif
  header
    position: relative
    background: url('~assets/images/bg-header.jpg') no-repeat 50% 60%
    background-size: cover
    color: #ffffff
    .header-panel
      background-color: #ffffff
      &_logo
        display: block
        padding: 10px 20px
        color: #444
        text-decoration: none
        &:hover
          opacity: .9
    .header-top
      padding: 60px
      &_t
        font-size: 60px
        font-weight: 400
        letter-spacing: -1px
        line-height: 1em
        margin-bottom: 0
      &_subt
        display: block
        margin: 0
        font-weight: 400
        font-size: 30px
      &_tx
        font-size: 17px
        max-width: 600px
        line-height: 23px
        margin-top: 35px
</style>
