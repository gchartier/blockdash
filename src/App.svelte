<style>
	#main {
		width: 100vw;
		height: 100vh;
		background-color: #4B5236;
	}

  .grid-container {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: repeat(2, 1fr);
    gap: 10px;
    padding: 10px;
    background-color: lightgray;
  }

  .grid-item {
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 48px;
    font-weight: bold;
    color: white;
    background-color: lightblue;
	min-width: 2rem;
	min-height: 12rem;
  }

  .grid-item:nth-child(even) {
    background-color: lightgreen;
  }
</style>

<div id="main">
	<h1>Hello!</h1>
	<div class="grid-container">
    <div class="grid-item">1</div>
    <div class="grid-item">2</div>
    <div class="grid-item">3</div>
    <div class="grid-item">4</div>
  </div>
</div>
