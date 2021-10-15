<template>
  <div class="row w-100">
    <div class="col-lg-3">
      <sideBar/>
    </div>
    <div class="col-lg-9">
      <topBar />
      <div class="total-stats text-center mt-5">
        <h3>Users</h3>
        <div class="d-flex gap-15 justify-content-center my-5">
          <div
            class="
              total-box
              d-flex
              text-left
              gap-15
              p-3
              w-100
              align-items-center
            "
          >
          <div class="label-box">
              <p class="mb-0">User Status:</p>
          </div>
          <div class="select-box w-75">
            <select
            name="year"
            id=""
            class="bg-white border-0 p-2 px-2 shadow text-light w-100"
            >
          <option value="">Year</option>
          <option value="">Year</option>
          <option value="">Year</option>
            </select>
          </div>

          </div>
          <div
            class="
              total-box
              d-flex
              text-left
              gap-15
              p-3
              w-100
              align-items-center
            "
          >
            <div class="label-box">
                <p class="mb-0">Show:</p>
            </div>
            <div class="select-box w-50">
                <select
                name="year"
                id=""
                class="bg-white border-0 p-2 px-2 shadow text-light w-100"
                >
            <option value="">10</option>
            <option value="">9</option>
            <option value="">8</option>
                </select>
            </div>
            <div class="entries-box">
                <p class="mb-0">Entries:</p>
            </div>
          </div>
          <div
            class="
              total-box
              d-flex
              text-left
              gap-15
              p-3
              w-100
              align-items-center
            "
          >
          <div class="label-box">
              <p class="mb-0">Sort by date:</p>
          </div>
          <div class="date-box w-75">
            <date-pickers addon-left-icon="hello"></date-pickers>
          </div>

          </div>
        </div>
      </div>
      <div class="d-flex search-bar w-25 justify-content-center m-auto">
          <base-input alternative
            placeholder="Search"
            addon-left-icon="ni ni-zoom-split-in"
            classes="shadow">
         </base-input>
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
import Search from "../views/components/Inputs.vue"
const DatePickers = () => import("../views/components/JavascriptComponents/DatePickers.vue");

export default {
  name: "user",
  components: {
    topBar,
    sideBar,
    DatePickers,
    Search
  },
};
</script>
