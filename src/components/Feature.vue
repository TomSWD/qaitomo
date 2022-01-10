<template>
  <div class="feature">
    <div class="feature__container">
      <div class="feature__small-talks">Small Talks</div>
      <div class="feature__feat">Feature</div>
      <h4 class="feature__heading">
        There are some similarities between BVHs and scene graphs. A scene graph
        can easily be adapted to include/become a BVH.
      </h4>
      <div class="feature__text">
        <p class="feature__text--left">
          Scene graphs for dense regular objects such as heightfields and
          polygon meshes tend to employ quadtrees and octrees, which are
          specialized variants of a 3D bounding box hierarchy. Since a
          heightfield occupies a box volume itself, recursively subdividing this
          box into eight subboxes
        </p>
        <p class="feature__text--right">
          A similar efficiency holds in 2D applications as well. If the user has
          magnified a document so that only part of it is visible on his
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Feature",
  components: {},
};
</script>

<style scoped>
.feature__container {
  display: flex;
  flex-direction: column;
  max-width: 820px;
  margin: 0 auto;
  padding: 0px 20px 140px 20px;
}
.feature__small-talks {
  font-weight: 700;
  font-size: 15px;
  line-height: 24px;
  padding-top: 100px;
}
.feature__feat {
  font-size: 15px;
  color: #979ea6;
  line-height: 28px;
}
.feature__heading {
  font-weight: 700;
  font-size: 36px;
  line-height: 52px;
  letter-spacing: -1px;
  padding-top: 78px;
}
.feature__text {
  display: flex;
  flex-direction: row;
  padding-top: 80px;
}
.feature__text--left {
  max-width: 458px;
}
.feature__text--right {
  max-width: 195px;
  font-size: 15px;
  line-height: 28px;
  color: #979ea6;
  margin-left: auto;
}
@media (max-width: 728px) {
  .feature__container {
    align-items: center;
    text-align: center;
    padding-bottom: 80px;
  }
  .feature__small-talks {
    padding-top: 60px;
  }
  .feature__heading {
    font-size: 32px;
    padding-top: 20px;
  }
  .feature__text {
    flex-direction: column;
    max-width: 458px;
    padding-top: 40px;
  }
  .feature__text--right {
    margin: auto;
    padding-top: 20px;
  }
}
@media (max-width: 545px) {
  .feature__container {
    padding-top: 0px;
  }
}
</style>
