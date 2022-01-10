<template>
  <div class="presentation">
    <div class="presentation__container">
      <div class="presentation__cube cube-1">
        <img
          class="presentation__img"
          src="@/assets/img/PresentationImg01.png"
        />
        <a class="presentation__number" href="#">01</a>
        <h3 class="presentation__heading">Identity</h3>
        <div class="presentation__description">
          Client: Nike <br />Creative Direction, Design
        </div>
        <a class="presentation__arrow-btn" href="#">
          <h5>DISCOVER</h5>
          <svg
            class="right"
            width="8"
            height="12"
            viewBox="0 0 8 12"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M8 5.95041L2.3256 0.639553C1.94111 0.279697 1.34343 0.279697 0.958938 0.639553L0.927438 0.669035C0.505529 1.06391 0.505164 1.73317 0.926643 2.12851L5.00127 5.95041L0.926643 9.77232C0.505164 10.1677 0.505528 10.8369 0.927437 11.2318L0.958937 11.2613C1.34343 11.6211 1.94111 11.6211 2.3256 11.2613L8 5.95041Z"
              fill="black"
              fill-opacity="0.7"
            />
          </svg>
        </a>
      </div>
      <div class="presentation__cube cube-2">
        <img
          class="presentation__img"
          src="@/assets/img/PresentationImg02.png"
        />
        <a class="presentation__number" href="#">02</a>
        <h3 class="presentation__heading">Mountains</h3>
        <div class="presentation__description">
          Client: Nike <br />Creative Direction, Design
        </div>
        <a class="presentation__arrow-btn" href="#">
          <h5>DISCOVER</h5>
          <svg
            class="right"
            width="8"
            height="12"
            viewBox="0 0 8 12"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M8 5.95041L2.3256 0.639553C1.94111 0.279697 1.34343 0.279697 0.958938 0.639553L0.927438 0.669035C0.505529 1.06391 0.505164 1.73317 0.926643 2.12851L5.00127 5.95041L0.926643 9.77232C0.505164 10.1677 0.505528 10.8369 0.927437 11.2318L0.958937 11.2613C1.34343 11.6211 1.94111 11.6211 2.3256 11.2613L8 5.95041Z"
              fill="black"
              fill-opacity="0.7"
            />
          </svg>
        </a>
      </div>
      <div class="presentation__cube cube-3">
        <img
          class="presentation__img"
          src="@/assets/img/PresentationImg03.png"
        />
        <a class="presentation__number" href="#">03</a>
        <h3 class="presentation__heading">Fruit Scene</h3>
        <div class="presentation__description">
          Client: Nike <br />Creative Direction, Design
        </div>
        <a class="presentation__arrow-btn" href="#">
          <h5>DISCOVER</h5>
          <svg
            class="right"
            width="8"
            height="12"
            viewBox="0 0 8 12"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M8 5.95041L2.3256 0.639553C1.94111 0.279697 1.34343 0.279697 0.958938 0.639553L0.927438 0.669035C0.505529 1.06391 0.505164 1.73317 0.926643 2.12851L5.00127 5.95041L0.926643 9.77232C0.505164 10.1677 0.505528 10.8369 0.927437 11.2318L0.958937 11.2613C1.34343 11.6211 1.94111 11.6211 2.3256 11.2613L8 5.95041Z"
              fill="black"
              fill-opacity="0.7"
            />
          </svg>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Presentation",
  components: {},
};
</script>

<style scoped>
.presentation__container {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
  gap: 32px;
  max-width: 1480px;
  padding: 150px 20px 150px 20px;
  margin: auto;
  height: 100%;
  background-color: #f8f8f8;
}
.presentation__cube {
  max-width: 360px;
}
.presentation__img {
  position: relative;
}
.presentation__number {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 60px;
  height: 60px;
  background-color: #fff;
  font-weight: 700;
  font-size: 11px;
  line-height: 20px;
  position: absolute;
  margin-top: -63px;
  margin-left: 300px;
}
.presentation__number:hover {
  background-color: #ffc001;
}
.presentation__heading {
  padding-top: 40px;
}
.presentation__description {
  font-size: 15px;
  line-height: 28px;
  padding-top: 19px;
}
.presentation__arrow-btn {
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 97px;
  padding-top: 42px;
}
.presentation__arrow-btn:hover,
.right:hover {
  color: #ffc001;
}
.right {
  width: 22px;
}
@media (max-width: 1195px) {
  .presentation__container {
    padding: 100px 20px 100px 20px;
  }
  .cube-3 {
    padding-top: 25px;
  }
}
@media (max-width: 806px) {
  .cube-2 {
    padding-top: 15px;
  }
  .cube-3 {
    padding-top: 15px;
  }
  .presentation__heading {
    padding-top: 15px;
  }
  .presentation__arrow-btn {
    padding-top: 22px;
  }
}
@media (max-width: 419px) {
  .presentation__number {
    margin-top: -63px;
    margin-right: 0px;
    margin-left: auto;
  }
}
</style>