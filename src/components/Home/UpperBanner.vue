<template>
  <div class="upper_banner">
    <v-container>
      <v-row>
        <v-col cols="5">
          <div class="upper_banner_content">
            <h2><strong>Huge Saving </strong>on UHD Televisions</h2>
          </div>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss">
.upper_banner {
  background: rebeccapurpleS;
  height: 500px;
  background-image: url("@/assets/images/banner-bg.jpg");
  background-size: cover;
  background-position: left top;
  &_content {
    padding: 120px 0;

    strong {
      color: #10ffda;
    }
    h2 {
      color: white;
      font-size: 50px;
      font-weight: 900;
    }
  }
}
</style>
