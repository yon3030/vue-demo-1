<template>
  <div class="features">
    <v-container>
      <v-row>
        <v-col>
          <div class="features_shipping">
            <ShippingIcons />
            <span>Free Shipping & Returns</span>
          </div>
        </v-col>
        <v-col>
          <div class="features_Guarante">
            <GuaranteeIcon />
            <span>Lowest Price Guarantee</span>
          </div>
        </v-col>
        <v-col>
          <div class="features_Trophy">
            <TrophyIcon />
            <span>Longest Warranties Offer</span>
          </div>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>
<script>
import ShippingIcons from "@/svg/featuresIons/ShippingIcons.vue";
import GuaranteeIcon from "@/svg/featuresIons/GuaranteeIcon.vue";
import TrophyIcon from "@/svg/featuresIons/TrophyIcon.vue";
export default {
  name: "TheFeatures",
  components: {
    ShippingIcons,
    GuaranteeIcon,
    TrophyIcon,
  },
};
</script>
<style lang="scss">
.features {
  font-size: 25px;
  span {
    vertical-align: top;
    margin-left: 10px;
  }
}
.features_Guarante,
.features_shipping {
  position: relative;
}
.features_Guarante::after,
.features_shipping::after {
  content: "";
  background: #dadada;
  width: 2px;
  height: 70%;
  position: absolute;
  top: 50%;
  right: 0;
  transform: translateY(-50%);
}
</style>
