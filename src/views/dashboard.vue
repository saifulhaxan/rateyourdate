<template>
  <div class="row w-100">
    <div class="col-lg-3">
      <sideBar />
    </div>
    <div class="col-lg-9">
      <topBar />
      <div class="total-stats text-center mt-5">
        <h3>Dashboard</h3>
        <div class="d-flex gap-15 justify-content-center my-5">
          <div
            class="
              total-box
              d-flex
              text-left
              gap-15
              bg-white
              rounded-3
              shadow
              p-3
            "
          >
            <figure class="mb-0">
              <img src="img/theme/bag.png" alt="" class="mw-100 w-75" />
            </figure>
            <div class="total-text d-flex flex-column justify-content-between">
              <p class="mb-0"><strong>TOTAL USER</strong></p>
              <h4 class="text-success mb-0">100</h4>
            </div>
            <div class="new-box d-flex align-items-end">
              <p class="mb-0"><i class="fa fa-arrow-up"></i>100%</p>
            </div>
          </div>
          <div
            class="
              total-box
              d-flex
              text-left
              gap-15
              bg-white
              rounded-3
              shadow
              p-3
            "
          >
            <figure class="mb-0">
              <img src="img/theme/plus.png" alt="" class="mw-100 w-75" />
            </figure>
            <div class="total-text d-flex flex-column justify-content-between">
              <p class="mb-0"><strong>TOTAL USER</strong></p>
              <h4 class="text-success mb-0">100</h4>
            </div>
            <div class="new-box d-flex align-items-end">
              <p class="mb-0"><i class="fa fa-arrow-up"></i>100%</p>
            </div>
          </div>
        </div>
      </div>
      <div class="total-stats text-center mt-5">
        <h3>Users</h3>
        <select
          name="year"
          id=""
          class="bg-white border-0 p-2 px-2 shadow text-light w-25 mt-3"
        >
          <option value="">Year</option>
          <option value="">Year</option>
          <option value="">Year</option>
        </select>
      </div>
      <div class="main-dashboard-screen">
        <img src="img/theme/dashboad-graph.png" alt="" class="mw-100" />
      </div>
    </div>
  </div>
</template>

<script>
import topBar from "../layout/AppHeader";
import sideBar from "../components/sidebar";

export default {
  name: "dashboard",
  components: {
    topBar,
    sideBar,
  },
};
</script>
