<template id="Layout_4_4_4">
    <div class="row">
        <div class="col-4">
               <slot name="zone_1"></slot>
        </div>
	   <div class="col-4">
               <slot name="zone_2"></slot>
        </div>
	    <div class="col-4">
               <slot name="zone_3"></slot>
        </div>
    </div>
</template>


<script>

export default {
     name: 'Layout_4_4_4',
     components: {},
     data() {
          return {}
     },
     computed: {},
     watch: {},
     methods: {},
     beforeCreate: function () {},
     created: function () {},
     beforeMount: function () {},
     mounted: function () {},
     beforeUpdate: function () {},
     updated: function () {},
     beforeDestroy: function () {},
     destroyed: function () {},
     errorCaptured: (err, vm, info) => {}
}
</script>