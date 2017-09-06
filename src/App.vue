<template>
  <div id="app">
    <div id="wrapper">
      <header id="header">
        <div class="content">
          <div class="inner">
            <h1>{{title}}</h1>
						<p>{{description}}</p>
            <div id="speecharea">
              <p id="response" cols="40" rows="20"><b>Ask me something!</b></p>
              <input id="input" type="text" placeholder="Medium, show me..."> <button id="rec"><i class="fa fa-microphone" aria-hidden="true"></i></button>
            </div>
          </div>
				</div>
      </header>
      <a href="https://twitter.com/medium"><i class="fa fa-twitter" aria-hidden="true"></i></a>
      <a href="https://facebook.com/medium"><i class="fa fa-facebook" aria-hidden="true"></i></a>
    </div>
  </div>
</template>

<script>
export default {
    name: 'app',
    data () {
        return {
            title: 'Medium Digital Assistant',
            description: 'Start by using a voice command such as "Medium, show me music" or "Medium, show me food". The assistant will then redirect you to the appropriate page on medium.com.'
        }
    }
}
</script>
