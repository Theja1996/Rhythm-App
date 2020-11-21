<template>
  <div class="container">
    <div class="row">
      <form>
        <fieldset>
          <legend>Legend</legend>
          <div class="form-group">
            <label for="exampleInputmusic">music</label>
            <div class="col-md-10">
              <input
                type="music"
                class="form-control"
                id="exampleInputmusic"
                aria-describedby="music"
                placeholder="search music"
              />
            </div>
          </div>
        </fieldset>
      </form>
    </div>
    <div class="row">
        <div class="col-md-12">
        Result
        </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.exampleinputmusic: {
  align-items: center;
  justify-content: center;
  margin-top: 20px;
}
</style>
