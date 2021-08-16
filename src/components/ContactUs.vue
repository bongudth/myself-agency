<template>
  <div id="contact-us">
    <div class="bg-image"></div>
    <div class="bg-pink"></div>
    <div class="agency-wrapper">
      <div class="agency-container">
        <div class="circle"></div>
        <h1>Agency</h1>
        <h3>branding & design</h3>
        <p>
          Image from <a href="https://www.freepik.com/photos/city">Freepik</a>
        </p>
      </div>
    </div>
    <div class="contact-wrapper">
      <div class="contact-container">
        <h3>Expert Branding Services</h3>
        <ul>
          <li>
            <i class="fas fa-check"></i>
            Massa ultricies mi quis hendrerit
          </li>
          <li>
            <i class="fas fa-check"></i>
            Ac ut consequat semper nam
          </li>
          <li>
            <i class="fas fa-check"></i>
            Libero id tincidunt eget
          </li>
          <li>
            <i class="fas fa-check"></i>
            Arcu odio ut sem nulla
          </li>
          <li>
            <i class="fas fa-check"></i>
            Et magnis dis parturient montes
          </li>
          <li>
            <i class="fas fa-check"></i>
            Imperdiet sed euismod
          </li>
        </ul>
        <a href="https://nicepage.com/k/adult-html-templates">Contact Us</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ContactUs",
};
</script>

<style lang="scss" scoped>
#contact-us {
  .bg-image {
    background-image: url("../assets/dsff-min.jpg");
    height: 697px;
  }

  .bg-pink {
    background-color: #d2668d;
    height: 788px;
    width: 231px;
    margin: -498px auto 0 calc(((100% - 1140px) / 2) + 378px);
  }

  .agency-wrapper {
    background-color: #ffffff;
    color: #111111;
    min-height: 380px;
    max-width: 460px;
    margin: -734px auto 0 calc(((100% - 1140px) / 2) + 39px);

    .agency-container {
      padding: 30px 70px 30px 45px;

      .circle {
        background-color: #d2668d;
        width: 69px;
        height: 69px;
        border-radius: 50%;
        margin: 20px 275px 0 1px;
      }

      h1 {
        font-family: "Oswald", sans-serif;
        font-size: 6rem;
        font-weight: 400;
        line-height: 1.1;
        letter-spacing: normal;
        text-transform: uppercase;
        margin: 20px 1px 0;
      }

      h3 {
        font-family: "Roboto", sans-serif;
        font-size: 1.875rem;
        font-weight: 400;
        line-height: 1.2;
        letter-spacing: 2px;
        text-transform: uppercase;
        margin: 16px 0 0 1px;
      }

      p {
        font-size: 1rem;
        line-height: 1.6;
        letter-spacing: 1px;
        margin: 22px 1px 0;

        a {
          color: #111111;
          text-decoration: none;
          border-bottom: 1px solid #000000;

          &:hover {
            color: #0f0f0f;
          }
        }
      }
    }
  }

  .contact-wrapper {
    width: 598px;
    min-height: 481px;
    background-color: #292d33;
    color: #ffffff;
    box-shadow: 5px 5px 20px 0 rgba(0, 0, 0, 0.4);
    margin: -190px calc(((100% - 1140px) / 2) + 102px) 60px auto;

    .contact-container {
      padding: 50px 50px 30px 40px;
      display: flex;
      flex-direction: column;
      justify-content: center;

      h3 {
        font-family: "Roboto", sans-serif;
        font-size: 1.875rem;
        font-weight: 400;
        line-height: 1.2;
        margin: 0;
      }

      ul {
        font-size: 1.125rem;
        line-height: 2;
        list-style-type: none;
        padding-left: 0;
        margin: 41px 0 0;

        i {
          color: #d2668d;
          font-size: 0.8em;
          margin-right: 0.4em;
        }
      }

      a {
        color: #ffffff;
        font-size: 1.25rem;
        font-weight: 400;
        letter-spacing: 2px;
        text-transform: uppercase;
        text-decoration: none;
        border: 1px solid #ffffff;
        padding: 11px 67px;
        margin: 41px auto 0 0;
      }
    }
  }
}
</style>
