<template>
  <div class="content01">
    <div class="content01__container">
      <div class="content01__menu">
        <div class="content01__link">
          <a class="link__txt" href="#">Parcel Tracking</a>
        </div>
        <div class="content01__link">
          <a class="link__txt" href="#">Inside Devices</a>
        </div>
        <div class="content01__link">
          <a class="link__txt" href="#">Technical Specs.</a>
        </div>
        <div class="content01__link">
          <a class="link__txt" href="#">Software Service</a>
        </div>
      </div>
      <div class="content01__main">
        <div class="content01__picture">
          <img src="@/assets/img/Content01-pic.png" />
        </div>
        <div class="content01__text">
          <h3>Well thought with super easy to use</h3>
          <p class="content01__paragraph">
            Mobile augmented reality applications are gaining popularity due to
            the wide adoption of mobile and especially wearable devices.
            However, they often rely on computationally intensive computer
            vision algorithms.
          </p>
          <div class="content01__feat-resp">
            <div class="content01__feat-1">
              <svg
                class="feat-svg"
                width="22"
                height="22"
                viewBox="0 0 22 22"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M17.7973 2.81553C17.4069 2.42507 16.7737 2.42509 16.3832 2.81559L15.6761 3.52261L14.9689 2.81557C14.5783 2.42503 13.9452 2.42505 13.5547 2.81556L2.71056 13.6597C2.51307 13.8572 2.40714 14.1284 2.41846 14.4074L2.55698 17.8046C2.57826 18.3248 2.99517 18.7417 3.51546 18.7629L6.91247 18.9015C7.19171 18.913 7.46281 18.8069 7.66031 18.6094L18.5044 7.76531C18.8949 7.3748 18.8949 6.74157 18.5044 6.35111L17.7974 5.64393L18.5044 4.93691C18.8949 4.5464 18.8949 3.91311 18.5044 3.52257L17.7973 2.81553ZM14.9689 5.64397L15.676 6.35108L16.3832 7.05825L8.605 14.8363L6.48368 12.715L14.2619 4.93693L14.9689 5.64397ZM5.06933 14.1293L4.4347 14.764L4.51786 16.8023L6.55602 16.8853L7.19065 16.2507L5.06933 14.1293Z"
                  fill="black"
                />
                <mask
                  id="mask0"
                  style="mask-type: alpha"
                  maskUnits="userSpaceOnUse"
                  x="2"
                  y="2"
                  width="17"
                  height="17"
                >
                  <path
                    fill-rule="evenodd"
                    clip-rule="evenodd"
                    d="M17.7973 2.81553C17.4069 2.42507 16.7737 2.42509 16.3832 2.81559L15.6761 3.52261L14.9689 2.81557C14.5783 2.42503 13.9452 2.42505 13.5547 2.81556L2.71056 13.6597C2.51307 13.8572 2.40714 14.1284 2.41846 14.4074L2.55698 17.8046C2.57826 18.3248 2.99517 18.7417 3.51546 18.7629L6.91247 18.9015C7.19171 18.913 7.46281 18.8069 7.66031 18.6094L18.5044 7.76531C18.8949 7.3748 18.8949 6.74157 18.5044 6.35111L17.7974 5.64393L18.5044 4.93691C18.8949 4.5464 18.8949 3.91311 18.5044 3.52257L17.7973 2.81553ZM14.9689 5.64397L15.676 6.35108L16.3832 7.05825L8.605 14.8363L6.48368 12.715L14.2619 4.93693L14.9689 5.64397ZM5.06933 14.1293L4.4347 14.764L4.51786 16.8023L6.55602 16.8853L7.19065 16.2507L5.06933 14.1293Z"
                    fill="white"
                  />
                </mask>
              </svg>
              <h5 class="feat__txt">BOLD TYPO</h5>
            </div>
            <div class="content01__feat-2">
              <svg
                class="feat-svg"
                width="14"
                height="18"
                viewBox="0 0 14 18"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M6.99999 0C9.23687 0 11.0502 1.79089 11.0502 4H11.9749C12.5014 4 12.9401 4.39868 12.9839 4.91699L13.9964 16.917C14.0456 17.5 13.5798 18 12.9874 18H1.01259C0.420229 18 -0.0456261 17.5 0.00356744 16.917L1.01611 4.91699C1.05981 4.39868 1.49853 4 2.02513 4H2.9498C2.9498 1.79089 4.7631 0 6.99999 0ZM4.97489 4H9.02508C9.02508 2.89539 8.11841 2 6.99999 2C5.88158 2 4.97489 2.89539 4.97489 4ZM2.11302 16L2.95685 6H11.0431L11.887 16H2.11302Z"
                  fill="black"
                />
              </svg>
              <h5 class="feat__txt">NICE PACKAGE</h5>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Content01",
  components: {},
};
</script>

<style scoped>
.content01__container {
  max-width: 1480px;
  background-color: #f8f8f8;
  margin: 0 auto;
}
.content01__menu {
  display: flex;
  justify-content: space-between;
  max-width: 1200px;
  gap: 20px;
  margin: auto;
  flex-wrap: wrap;
  padding: 150px 20px 0px 20px;
}
.content01__link {
  display: flex;
  font-weight: 700;
  font-size: 13px;
  /* max-width: 263px; */
  width: 20%;
  height: 36px;
  border-bottom: 2px solid #d4d4d4;
}
.content01__link:active {
  border-bottom: 2px solid #000;
}
.link__txt {
  padding-top: 7px;
}
.link__txt:hover {
  transition: 0.4s;
  font-size: 14px;
}
.content01__main {
  display: flex;
  align-self: center;
  max-width: 1200px;
  flex-direction: row;
  margin: auto;
}
.content01__picture {
  padding: 100px 0px 150px 0px;
  margin-left: -11.5%;
}
.content01__text {
  display: flex;
  flex-direction: column;
  max-width: 500px;
  padding: 90px 20px 0px 10px;
  margin-left: auto;
}
.content01__paragraph {
  padding-top: 40px;
  padding-bottom: 55px;
}
.content01__feat-1,
.content01__feat-2 {
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 118px;
  height: 36px;
}
.feat-svg {
  margin-left: 7px;
}
.content01__feat-2 {
  width: 140px;
  padding-top: 18px;
}
@media (max-width: 1355px) {
  .content01__picture {
    margin-left: auto;
    padding-right: 20px;
  }
}
@media (max-width: 1115px) {
  .content01__main {
    flex-direction: column;
    padding: 0px 20px 0px 20px;
  }
  .content01__menu {
    padding-top: 55px;
  }
  .content01__picture {
    margin: auto;
    padding: 80px 0px 0px 0px;
  }
  .content01__text {
    margin: auto;
    text-align: left;
    padding: 50px 0px 0px 0px;
  }
  .content01__paragraph {
    padding-top: 30px;
    padding-bottom: 40px;
  }
  .content01__feat-resp {
    display: flex;
    justify-content: space-between;
    flex-direction: row;
    padding-bottom: 55px;
  }
  .content01__feat-2 {
    padding-top: 0px;
  }
}
@media (max-width: 728px) {
  .content01__text {
    text-align: center;
  }
}
@media (max-width: 600px) {
  .content01__menu {
    gap: 10px;
  }
  .content01__link {
    width: 100%;
  }
  .link__txt {
    margin: auto;
  }
  .content01__picture {
    padding: 50px 0px 0px 0px;
  }
}
@media (max-width: 521px) {
  .content01__paragraph {
    padding-top: 20px;
    padding-bottom: 25px;
  }
}
</style>