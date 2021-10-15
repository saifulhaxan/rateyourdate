<template>
    <div class="row">
        <div class="col-md-6">
            <base-input addon-left-icon="ni ni-calendar-grid-58" classes="shadow">
                <flat-picker slot-scope="{focus, blur}"
                             @on-open="focus"
                             @on-close="blur"
                             :config="{allowInput: true}"
                             class="form-control datepicker border-0"
                             v-model="dates.simple">
                </flat-picker>
            </base-input>
        </div>
        <div class="col-md-6">
            <base-input addon-left-icon="ni ni-calendar-grid-58" classes="shadow">
                <flat-picker slot-scope="{focus, blur}"
                             @on-open="focus"
                             @on-close="blur"
                             :config="{allowInput: true}"
                             class="form-control datepicker border-0"
                             v-model="dates.range">
                </flat-picker>
            </base-input>
        </div>
        <!-- <div class="col-md-6">
            <div class="input-daterange datepicker row align-items-center">
                <div class="col">
                    <base-input addon-left-icon="ni ni-calendar-grid-58">
                        <flat-picker slot-scope="{focus, blur}"
                                     @on-open="focus"
                                     @on-close="blur"
                                     :config="{allowInput: true, mode: 'range',}"
                                     class="form-control datepicker"
                                     v-model="dates.range">
                        </flat-picker>
                    </base-input>
                </div>
            </div>
        </div> -->
    </div>
</template>
<script>
import flatPicker from "vue-flatpickr-component";
import "flatpickr/dist/flatpickr.css";
export default {
  components: {
    flatPicker
  },
  data() {
    return {
      dates: {
        type: String,
        simple: "2018-07-17",
        range: "2019-07-18"
      }
    };
  }
};
</script>
