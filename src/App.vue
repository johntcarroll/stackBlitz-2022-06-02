<template>
  <div id="app">
    <div class="row m-2">
      <div class="col-4 d-flex flex-column">
        <div class="text-center">Last Printed</div>
        <div class="d-flex justify-content-end align-items-center">
          <div class="form-floating pe-2">
            <input type="date" class="form-select" />
            <label>Start Date</label>
          </div>
          <div class="text-cente pe-2">To</div>
          <div class="form-floating">
            <input type="date" class="form-select" />
            <label>End Date</label>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style></style>
