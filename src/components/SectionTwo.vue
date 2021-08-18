<template>
  <div id="section-two">
    <div class="container">
      <h1>design</h1>
      <div class="content-wrapper">
        <div class="content-container">
          <div class="block-1-wrapper">
            <div class="block-1-container">
              <h2>
                Premium Design
                <br />
                Amazing Photo
                <br />
                Creative Ideas
                <br />
                Unique Strategy
              </h2>
            </div>
          </div>
          <div class="block-2-wrapper">
            <div class="block-2-container">
              <p>
                Dignissim suspendisse in est ante in nibh mauris. Varius quam
                quisque id diam vel quam elementum pulvinar etiam. Nunc pulvinar
                sapien et ligula ullamcorper malesuada proin. Nunc mattis enim
                ut tellus elementum sagittis vitae et leo.
              </p>
              <div class="round"></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SectionTwo",
};
</script>

<style lang="scss" scoped>
#section-two {
  height: 794px;

  .container {
    width: 1140px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    margin: auto;

    h1 {
      font-family: "Oswald", sans-serif;
      color: #d2668d;
      font-size: 10rem;
      font-weight: 300;
      line-height: 1.1;
      text-transform: uppercase;
      margin: 60px 278px 0 0;
    }

    .content-wrapper {
      width: 788px;
      margin: 25px 0 60px auto;

      .content-container {
        display: flex;
        color: #111111;

        .block-1-wrapper {
          width: 50%;

          .block-1-container {
            display: flex;
            flex-direction: column;
            justify-content: flex-start;
            text-align: center;
            padding: 30px;

            h2 {
              font-family: "Oswald", sans-serif;
              font-size: 2.25rem;
              font-weight: 400;
              line-height: 2.2;
              margin: 0 27px 0 25px;
            }
          }
        }

        .block-2-wrapper {
          width: 50%;

          .block-2-container {
            background-color: #ffffff;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            padding: 60px 30px 30px;

            p {
              line-height: 2;
              margin: 0;
            }

            .round {
              background-color: #d2668d;
              width: 69px;
              height: 69px;
              border-radius: 50%;
              margin: 122px 0 0 auto;
            }
          }
        }
      }
    }
  }
}
</style>
