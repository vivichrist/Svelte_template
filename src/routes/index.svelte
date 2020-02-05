<script>
  import Header from "../components/Header.svelte";
  import Footer from "../components/Footer.svelte";
  import Sprite from "../components/Sprite.svelte";
</script>

<svelte:head>
	<title>Sapper project template</title>
</svelte:head>

<Header/>

<div class="container-fluid bg-light pl-5 pr-5">
    <!-- row 2 -->
    <div class="row pt-3 pb-3">
      <div class="col-md-4 offset-md-3">
        <h3>
          <i class="fas fa-beer"></i> text with <small>secondary text</small>
        </h3>
      </div>
      <div class="col-md-5">
        <h3>
          <i class="fas fa-school"></i> Add to your favorites
          <small>
            <kbd><kbd>ctrl</kbd> + <kbd>d</kbd></kbd>
          </small>
        </h3>
      </div>
    </div>
    <!-- row 3 -->
    <div class="row">
      <div class="col-md-12">
        <Sprite/>
      </div>
    </div>
    <!-- row 4 -->
    <div class="row pt-5 pb-5">
      <div class="col-md-3 m-auto">
        <img src="bs.png" class="img-fluid float-right rounded" alt="blah"/>
      </div>
      <div class="col-md-6 p-4">
        <blockquote class="blockquote article-content">
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            Integer posuere erat a ante.</p>
          <footer class="blockquote-footer">Testimonial from someone at <cite title="Source Title">Source Title</cite></footer>
        </blockquote>
      </div>
      <div class="col-md-3 m-auto">
        <img src="logo.png" class="img-fluid rounded" alt="blah"/>
      </div>
    </div>
    <!-- row 5 -->
    <div class="row">
      <div class="col-md-3">
        <p class="text-left">Left</p>
      </div>
      <div class="col-md-3">
        <p class="text-center">Center</p>
      </div>
      <div class="col-md-3">
        <p class="text-justify">Jusitfy</p>
      </div>
      <div class="col-md-3">
        <p class="text-right">Right</p>
      </div>
    </div>
    <!-- row 6 – grid -> flex column overflow -->
    <div class="row pt-4 pb-4">
      <div class="col-md-6 col-lg-4">
        <div class="d-flex flex-column flex-wrap" style="height: 768px;">
          <div class="article-content">
            <h3>Lowercase</h3>
            <p class="text-lowercase">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias blanditiis eveniet earum minus obcaecati qui assumenda officia eaque culpa, ex repudiandae! Vel minima nesciunt sed quae! Saepe, possimus! Non, quia?
            </p>
          </div>
          <div class="article-content">
            <h3>Uppercase</h3>
            <p class="text-uppercase">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias blanditiis eveniet earum minus obcaecati qui
              assumenda officia eaque culpa, ex repudiandae! Vel minima nesciunt sed quae! Saepe, possimus! Non, quia?
            </p>
          </div>
          <div class="article-content">
            <h3>Strong and italic</h3>
            <p>
              <strong>Lorem ipsum</strong> dolor sit amet <em>consectetur adipisicing elit.</em> Molestias blanditiis eveniet
              earum minus obcaecati qui assumenda officia eaque culpa, ex repudiandae! Vel minima nesciunt sed quae! Saepe,
              possimus! Non, quia?
            </p>
          </div>
          <div class="article-content">
            <h3>Uppercase</h3>
            <p class="text-uppercase">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias blanditiis eveniet earum minus obcaecati qui assumenda officia eaque culpa, ex repudiandae! Vel minima nesciunt sed quae! Saepe, possimus! Non, quia?
            </p>
          </div>
          <div class="article-content">
            <h3>Capitalize</h3>
            <p class="text-capitalize">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias blanditiis eveniet earum minus obcaecati qui assumenda officia eaque culpa, ex repudiandae! Vel minima nesciunt sed quae! Saepe, possimus! Non, quia?
            </p>
          </div>
          <div class="article-content">
            <h3>Strong and italic</h3>
            <p>
                <strong>Lorem ipsum</strong> dolor sit amet <em>consectetur adipisicing elit.</em> Molestias blanditiis eveniet earum minus obcaecati qui assumenda officia eaque culpa, ex repudiandae! Vel minima nesciunt sed quae! Saepe, possimus! Non, quia?
            </p>
          </div>
          <div class="article-content">
              <h3>Capitalize</h3>
              <p class="text-capitalize">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias blanditiis eveniet earum minus obcaecati qui assumenda officia eaque culpa, ex repudiandae! Vel minima nesciunt sed quae! Saepe, possimus! Non, quia?
              </p>
            </div>
        </div>
      </div>
    </div>
    <!-- row 7 -->
    <div class="row">
      <div class="col-md-10 clearfix">
        <table class="table table-striped table-bordered">
          <thead>
            <tr>
              <th class="bg-success">
                <h4 class="text-center">Free plan</h4>
              </th>
              <th class="bg-info">
                <h4 class="text-center">Standard plan</h4>
              </th>
              <th class="bg-danger">
                <h4 class="text-center">Premium plan</h4>
              </th>
            </tr>
          </thead>
          <tbody class="table-hover">
            <tr>
              <td>
                <h3 class="text-center">$ 0</h3>
              </td>
              <td>
                <h3 class="text-center">$ 99</h3>
              </td>
              <td>
                <h3 class="text-center">$ 999</h3>
              </td>
            </tr>
            <tr>
              <td>Lorem ipsum</td>
              <td>Lorem ipsum</td>
              <td>Lorem ipsum</td>
            </tr>
            <tr>
              <td>Lorem ipsum</td>
              <td>Lorem ipsum</td>
              <td>Lorem ipsum</td>
            </tr>
            <tr>
              <td>Dolor sit amet</td>
              <td>Lorem ipsum</td>
              <td>Lorem ipsum</td>
            </tr>
            <tr>
              <td>-</td>
              <td>Dolor sit amet</td>
              <td>Lorem ipsum</td>
            </tr>
            <tr>
              <td>-</td>
              <td>-</td>
              <td>Lorem ipsum</td>
            </tr>
            <tr>
              <td><a href="#" class="btn btn-success btn-block">Purchase</a></td>
              <td><a href="#" class="btn btn-info btn-block">Purchase</a></td>
              <td><a href="#" class="btn btn-danger btn-block">Purchase</a></td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>

  <Footer/>
