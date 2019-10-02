<template>
  <div id="app">
    <b-navbar toggleable="lg" type="dark" variant="info">
    <b-navbar-brand href="#">Merflix</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-nav-form>
          <b-form-input size="sm" class="mr-sm-2"></b-form-input>
          <b-button size="sm" class="my-2 my-sm-0" type="submit">Busca tu serie favorita</b-button>
        </b-nav-form>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
   <b-card-group deck>
    <b-card title="Title" img-src="https://wallpapersite.com/images/pages/pic_w/15948.jpg" img-alt="Image" img-top to="/detail">
      <b-card-text>
        This is a wider card with supporting text below as a natural lead-in to additional content.
        This content is a little bit longer.
      </b-card-text>
    </b-card>

    <b-card title="Title" img-src="https://wallpapersite.com/images/pages/pic_w/15927.jpg" img-alt="Image" img-top>
      <b-card-text>
        This card has supporting text below as a natural lead-in to additional content.
      </b-card-text>
    </b-card>

    <b-card title="Title" img-src="https://wallpapercave.com/wp/wp1808933.jpg" img-alt="Image" img-top>
      <b-card-text>
        This is a wider card with supporting text below as a natural lead-in to additional content.
        This card has even longer content than the first to show that equal height action.
      </b-card-text>
    </b-card>
  </b-card-group>
   <b-card-group deck>
    <b-card title="Title" img-src="https://wallpapersite.com/images/pages/pic_w/17994.jpg" img-alt="Image" img-top>
      <b-card-text>
        This is a wider card with supporting text below as a natural lead-in to additional content.
        This content is a little bit longer.
      </b-card-text>
    </b-card>

    <b-card title="Title" img-src="https://wallpapersite.com/images/pages/pic_w/18223.jpg" img-alt="Image" img-top>
      <b-card-text>
        This card has supporting text below as a natural lead-in to additional content.
      </b-card-text>
    </b-card>

    <b-card title="Title" img-src="https://wallpapersite.com/images/pages/pic_w/17618.jpg" img-alt="Image" img-top>
      <b-card-text>
        This is a wider card with supporting text below as a natural lead-in to additional content.
        This card has even longer content than the first to show that equal height action.
      </b-card-text>
    </b-card>
  </b-card-group>
  </div>
</template>

