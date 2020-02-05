<script>
  let pos = {x: 0, y: 0};
  let thecanvas;

  var handleEvent = (event) => {
    if (event.code == "KeyW") {
      --pos.y;
      alert("Up -> Key W");
    }
    else if (event.code == "KeyS") {
      ++pos.y;
      alert("Down -> Key S");
    }
    if (event.code == "KeyA") {
      --pos.x;
      alert("Left -> Key A");
    }
    else if (event.code == "KeyD") {
      ++pos.x;
      alert("Right -> Key D");
    }
    let ctx = thecanvas.getContext("2d");
    ctx.fillStyle = "#0000FF";
    ctx.fillRect(pos.x, pos.y, 20, 20);
  }
</script>

<style>
  canvas {
    border: 1px solid #FF0000;
    width: 100%;
    height: 150px;
  }
</style>

<canvas bind:this={thecanvas} on:keyup={handleEvent}>
</canvas>