<script>
</script>

<main>
  <div class="ocean-background">
    <h1>Representación de magnitudes:</h1>
    
    <div class="images-container">
      <div class="image-column">
        <div class="image-wrapper">
          <img src="./images/Shark.svg" alt="Shark" class="shark-image" />
        </div>
        <p class="magnitude">87</p>
      </div>
      
      <div class="image-column">
        <div class="image-wrapper">
          <img src="./images/Fish.svg" alt="Fish" class="fish-image" />
        </div>
        <p class="magnitude">24</p>
      </div>
    </div>
</main>

<style>
  :global(body), :global(html) {
    margin: 0;
    padding: 0;
    height: 100vh;
    overflow: hidden;
    background: linear-gradient(to bottom, #1a6ed5, #0c3b7c, #001e4d);
  }

  main {
    width: 100%;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
  }
  
  .ocean-background {
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    position: relative;
    overflow: hidden;
  }
  
  h1 {
    color: rgb(157, 198, 247);
    font-size: 2.5rem;
    text-align: center;
    margin-bottom: 15rem;
  }
  
  .images-container {
    display: flex;
    justify-content: center;
    align-items: flex-start;
    gap: 4rem;
  }
  
  .image-column {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 300px;
  }
  
  .image-wrapper {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 200px; 
  }
  
  .shark-image {
    width: 300px;
    height: auto;
  }
  
  .fish-image {
    width: 100px;
    height: auto;
  }
  
  .magnitude {
    font-size: 2.5rem;
    
    color: rgb(157, 198, 247);
    margin-top: 1rem;
  }
  
  @media (max-width: 768px) {
    .images-container {
      gap: 2rem;
    }
    
    .image-column {
      width: 200px;
    }
    
    .shark-image {
      width: 200px;
    }
    
    .fish-image {
      width: 70px;
    }
    
    h1 {
      font-size: 1.8rem;
    }
    
    .magnitude {
      font-size: 2rem;
    }
  }
</style>