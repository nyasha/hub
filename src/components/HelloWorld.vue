<template>
  <section>
    <div class="form-group">
      <label>Select a date</label>
      <div class="input-group">
        <flat-pickr
                v-model="date"
                :config="config"                                                          
                class="form-control" 
                placeholder="Select date"               
                name="date">
        </flat-pickr>
        <div class="input-group-btn">
          <button class="btn btn-default" type="button" title="Toggle" data-toggle>
            <i class="fa fa-calendar">
              <span aria-hidden="true" class="sr-only">Toggle</span>
            </i>
          </button>
          <button class="btn btn-default" type="button" title="Clear" data-clear>
            <i class="fa fa-times">
              <span aria-hidden="true" class="sr-only">Clear</span>
            </i>               
          </button>
        </div>
      </div>
    </div>
    <pre>Selected date is - {{date}}</pre>
  </section>
</template>

<script>
// bootstrap is just for this example
import "bootstrap/dist/css/bootstrap.css";
// import this component
import flatPickr from "vue-flatpickr-component";
import "flatpickr/dist/flatpickr.css";
// theme is optional
// try more themes at - https://chmln.github.io/flatpickr/themes/
import "flatpickr/dist/themes/material_blue.css";
// l10n is optional
import { Hindi } from "flatpickr/dist/l10n/hi";

export default {
  name: "yourComponent",
  data() {
    return {
      // Initial value
      date: new Date(),
      // Get more form https://chmln.github.io/flatpickr/options/
      config: {
        wrap: true, // set wrap to true only when using 'input-group'
        altFormat: "M	j, Y",
        altInput: true,
        dateFormat: "Y-m-d",
        locale: Hindi // locale for this instance only
      }
    };
  },
  components: {
    flatPickr
  }
};
</script>
