<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Plant Gallery</title>
    <!-- Bootstrap CSS link -->
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css"
      rel="stylesheet"
    />
  </head>
  <body>
    <!-- Container (Bootstrap Concept 1: Layout using Container) -->
    <div class="container my-5">
      <h1 class="text-center mb-4">🌱 My Plant Gallery 🌱</h1>

      <!-- Row and Columns (Bootstrap Concept 2: Grid System) -->
      <div class="row">
        <!-- First Plant -->
        <div class="col-12 col-md-6 text-center mb-4">
          <img
            src="https://www.shutterstock.com/image-photo/indoor-house-pot-plants-potted-600nw-1747639997.jpg"
            class="img-fluid rounded"
            alt="Coco"
            style="width: 200px; height: 300px; object-fit: cover"
          />
          <h5 class="mt-3">Aloe Vera</h5>
          <p>Known for its healing properties and easy care!</p>
        </div>

        <!-- Second Plant -->
        <div class="col-12 col-md-6 text-center mb-4">
          <img
            src="https://shop-static.arborday.org/media/0004367_snake-plant.jpeg"
            class="img-fluid rounded"
            alt="Lava Plant"
            style="width: 200px; height: 200px; object-fit: cover"
          />
          <h5 class="mt-3">Lava Plant</h5>
          <p>Good for protection towards heating settings.</p>
        </div>

        <!-- Third Plant -->
        <div class="col-12 col-md-6 text-center mb-4">
          <img
            src="https://media.houseandgarden.co.uk/photos/64677e9c55fc4e858e5b4d31/master/w_1600%2Cc_limit/492766473"
            class="img-fluid rounded"
            alt="Winter Plant"
            style="width: 200px; height: 200px; object-fit: cover"
          />
          <h5 class="mt-3">Peace Lily</h5>
          <p>It makes the air smell really good!</p>
        </div>
      </div>

        <!-- Fourth Plant -->
        <div class="col-12 col-md-6 text-center mb-4">
          <img
            src="https://media.houseandgarden.co.uk/photos/64677e9c55fc4e858e5b4d31/master/w_1600%2Cc_limit/492766473"
            class="img-fluid rounded"
            alt="Twin Plant"
            style="width: 200px; height: 200px; object-fit: cover"
          />
          <h5 class="mt-3">Peace Lily</h5>
          <p>It copies what nature throws at them!</p>
        </div>
      </div>


  

     <!-- Button (Bootstrap Concept 3: Components) -->
      <div class="text-center mt-4">
        <button class="btn btn-success">See More Plants</button>
      </div>
    </div>
  </body>
</html>
