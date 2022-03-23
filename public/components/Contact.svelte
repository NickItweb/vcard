<script>
  let cardHead = "";
</script>

<div class="card">
  <div class="card-head">
    <span style="padding-left:5px;">{cardHead}<span>
  </div>
  <div class="card-social">
    <div class="row" >
      <div class="column" >
        <img class="card-img" src="./image/call.png" >
        <p>Call Me</p>
      </div>
      <div class="column">
        <img class="card-img" src="./image/email.png" >
        <p>Email Me</p>
      </div>
      <div class="column">
        <img class="card-img" src="./image/whatsapp.png" >
        <p>Whatsapp</p>
      </div>
      <div class="column">
        <img class="card-img" src="./image/skype.png" >
        <p>Skype</p>
      </div>
      <div class="column">
        <img class="card-img" src="./image/fbchat.png" >
        <p>FB Chat</p>
      </div>
    </div>
  </div>
</div>

<style>
  .column {
    float: left;
    width: 20%;
  }

  .row:after {
    content: "";
    display: table;
    clear: both;
  }
  .card-head {
    width: 100%;
    position: relative;
    margin-top: 100px;
    background: rgb(230, 230, 230);
    color: gray;
    border-left: 5px solid gray;
    text-align: left;
    padding-top: 5px;
    padding-bottom: 5px;
    font-size: 16px;
    font-weight: bold;
  }

  .card-img {
    border-radius: 50%;
    width: 40px;
    margin-top: 20px;
  }

  p {
    font-size: 14px;
  }
</style>