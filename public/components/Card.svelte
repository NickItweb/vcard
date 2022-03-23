<script>
  let cardImg = "./image/default.png";
  let cardTitle = "Viral Jadhav";
  let cardCaption = "Digital Marketer";
</script>
<div class="card">
	<div class="card-body">
    <img  src="{cardImg}" class="card-img" alt="profile" >
    <div class="card-title" >{cardTitle}</div>
    <div class="card-caption">{cardCaption}</div>
  </div>
</div>

<style>
  .card {
    background: url("./image/coverbg.png");
    background-size: cover;
    width: 100%;
    height: 200px;
  }
  .card-body {
    background: white;
    width: 100%;
    height: auto;
    margin: 10px;
    margin-top: 50px;
    position: absolute;
    border-radius: 20px;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.1), 0 6px 20px 0 rgba(0, 0, 0, 0.1);
  }

  .card-img {
    border-radius: 50%;
    width: 100px;
    margin-top: 20px;
  }

  .card-title {
    font-weight: 600;
    font-size: 20px;
    color: grey;
    margin-top: 10px;
  }

  .card-caption {
    font-weight: 500;
    font-size: 15px;
    color: grey;
    margin-top: 5px;
    margin-bottom: 50px;
  }
</style>
