<template>
  <div class="home">
    <section class="hero">
      <h2>Get All Your Home Essentials in One Place</h2>
    </section>
    <section class="speaker">
      <img
        src="https://www.legrand.us/-/media/brands/nuvo/images/products/speakers/outdoor/350x350_0008_nv-2lsk-bk.ashx?h=350&w=350&bc=FFFFFF"
        alt="speaker image"
        class="speaker-pic"
      />
      <div class="speaker-text-wrapper">
        <h3>NUVO LANDSCAPE SPEAKERS</h3>
        <p>
          Deliver immersive sound throughout any outdoor environment with the
          durable and scalable Nuvo Series Two Landscape Speaker Kit, complete
          with four, two-way satellite speakers and an eight inch, in-ground
          subwoofer. The low-profile, black teardrop satellite speakers have
          3.5” poly woofers and .5" UFLC tweeters for clear, robust audio and
          even coverage. The powerful, eight inch subwoofer's cylindrical
          enclosure blends subtly into landscaping while providing stand-out
          bass response. Designed to provide years of performance outdoors, this
          8 ohm system is IP67 compliant for dust resistance and protection from
          water penetration, as well as MIL-STD-810 rated to withstand cracking
          through extreme weather and temperature changes. Additional satellite
          speakers and subwoofers can be added to extend the system.
        </p>
      </div>
    </section>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "home"
};
</script>

<style lang="scss" scoped>
.home {
  padding: 0 20px;
}
.hero {
  height: 500px;
  width: 100%;
  background-image: url("https://www.legrand.us/-/media/images/modularcontent/fullscreenphotocarousels/nuvo/speakers/768x345-nuvo-landscape-speakers.ashx?h=345&w=768&la=en&hash=6F10551868ADF27B58DB80452292F2C4592221DE");
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  display: flex;
  justify-content: flex-start;
  h2 {
    padding: 60px 0 0 0;
    background-color: rgba(11, 54, 2, 0.664);
    color: white;
    text-align: center;
    font-size: 5rem;
    max-width: 500px;
  }
}
.speaker {
  display: flex;
  .speaker-text-wrapper {
    background-color: #90957a;
    padding: 20px;
    h3 {
      font-weight: 700;
      font-size: 2.5rem;
      margin-bottom: 20px;
    }
    p {
      font-size: 1rem;
    }
  }
  .speaker-pic {
    max-height: 350px;
  }
}
</style>
