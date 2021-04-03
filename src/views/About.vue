<template>
  <div class="about">
    <h1>About us</h1>
    <b-container class="wrapper">
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Porro, at. Atque temporibus totam error a sequi est aperiam, earum tempore quia eum impedit ex laboriosam ad fugiat non tempora sint voluptas doloribus debitis. Suscipit deleniti vero rerum doloribus alias, voluptates nulla modi soluta neque necessitatibus eligendi dolorem aliquam eius quam?</p>
      <div>
        <b-card
          title="Card Title"
          img-src="https://picsum.photos/600/300/?image=25"
          img-alt="Image"
          img-top
          tag="article"
          style="max-width: 20rem;"
          class="mb-2"
        >
          <b-card-text>
            Some quick example text to build on the card title and make up the bulk of the card's content.
          </b-card-text>

          <b-button href="#" variant="primary">Go somewhere</b-button>
        </b-card>
      </div>
      <b-row>
        <b-col>
          <h3>List of contacts</h3>
          <ul>
            <li>Name: Sergey Savitski</li>
            <li>Email: sv.siarhei@gmail.com</li>
            <li>Phone: +375295866418</li>
          </ul>
        </b-col>

        <b-col>
          <h3>Address</h3>
          <p>Grodno, Akademicheskaya str. 17</p>
        </b-col>
      </b-row>

      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2362.64108285906!2d23.837549815851332!3d53.689021980052274!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x46dfd6189ed5fb87%3A0x2e629f44904a8ee5!2z0YPQuy4g0JDQutCw0LTQtdC80LjRh9C10YHQutCw0Y8gMTcsINCT0YDQvtC00L3QviAyMzAwMDU!5e0!3m2!1sru!2sby!4v1617439699508!5m2!1sru!2sby" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
    </b-container>
  </div>
</template>

<style>
  .wrapper {
    text-align: left;
  }
</style>
