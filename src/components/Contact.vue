<template>
  <div class="contact">
    <div class="contact__container">
      <div class="contact__main">
        <div class="contact__left">
          <div class="contact__content">
            <div class="contact__office">
              <h5>OFFICE</h5>
              <div class="contact__txt">
                20 Independant Avenue San Pedro, CA 90731 California
              </div>
            </div>
            <div class="contact__mail">
              <h5>CONTACTS</h5>
              <div class="contact__txt">
                holaagency@gmail.com <br />
                +1 900 577 473 84
              </div>
            </div>
          </div>
        </div>
        <div class="contact__cta">
          <div class="cta__content">
            Drop us a line or two, we are open for creative minds and
            collaborations!
          </div>
          <div class="cta__mail">holaagency@gmail.com</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Contact",
  components: {},
};
</script>

<style scoped>
.contact__container {
  display: flex;
  max-width: 1480px;
  padding-top: 150px;
  padding-left: 20px;
  margin: auto;
}
.contact__main {
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1290px;
  width: 100%;
  margin-left: auto;
}
.contact__left {
  display: flex;
  justify-content: center;
  max-width: 585px;
  width: 100%;
}
.contact__content {
  display: flex;
  justify-content: space-between;
  max-width: 458px;
  width: 100%;
}
.contact__office {
  display: flex;
  flex-direction: column;
  max-width: 165px;
  width: 100%;
}
.contact__mail {
  display: flex;
  flex-direction: column;
  max-width: 166px;
}
.contact__txt {
  font-size: 15px;
  line-height: 28px;
  padding-top: 24px;
}
.contact__cta {
  display: flex;
  flex-direction: column;
  max-width: 705px;
  width: 100%;
  background-color: #1c1c1c;
  color: #fff;
  font-size: 24px;
  line-height: 36px;
}
.cta__content {
  max-width: 458px;
  width: 100%;
  padding-left: 97px;
  padding-top: 113px;
  padding-right: 20px;
  letter-spacing: -0.4px;
}
.cta__mail {
  padding-left: 97px;
  padding-top: 20px;
  padding-bottom: 115px;
  color: #ffc001;
}
@media (max-width: 1195px) {
  .contact__container {
    padding-top: 0px;
  }
  .contact__cta {
    font-size: 22px;
  }
}
@media (max-width: 995px) {
  .contact__container {
    flex-direction: column;
  }
  .contact__left {
    padding-top: 20px;
  }
  .contact__content {
    width: auto;
  }
  .contact__office,
  .contact__mail {
    padding: 0px 20px 40px 20px;
    margin: 0 auto;
  }
  .contact__cta {
    width: 100%;
    align-items: center;
    margin-top: 0px;
    font-size: 18px;
  }
  .cta__content,
  .cta__mail {
    margin-left: 0px;
    padding: 20px 20px 20px 20px;
  }
}
@media (max-width: 850px) {
  .contact__container {
    padding-top: 0px;
    padding-left: 0px;
  }
  .contact__main {
    flex-direction: column;
  }
  .contact__txt {
    padding-top: 5px;
  }
}
@media (max-width: 728px) {
  .contact__office,
  .contact__mail,
  .cta__content {
    text-align: center;
  }
  .contact__txt {
    align-self: center;
  }
}
@media (max-width: 500px) {
  .contact__content {
    flex-direction: column;
  }
  .contact__mail {
    padding-bottom: 20px;
  }
}
</style>