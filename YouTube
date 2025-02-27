<html>
 <head>
  <title>
   Responsive YouTube Video App
  </title>
  <script src="https://cdn.tailwindcss.com">
  </script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&amp;display=swap" rel="stylesheet"/>
  <style>
   body {
            font-family: 'Roboto', sans-serif;
        }
  </style>
 </head>
 <body class="bg-gray-100">
  <header class="bg-white shadow-md">
   <div class="container mx-auto px-4 py-4 flex justify-between items-center">
    <div class="text-2xl font-bold text-red-600">
     YouTube
    </div>
    <nav class="space-x-4">
     <a class="text-gray-700 hover:text-red-600" href="#">
      Home
     </a>
     <a class="text-gray-700 hover:text-red-600 cursor-pointer" id="searchButton">
      Search
     </a>
    </nav>
   </div>
  </header>
  <main class="container mx-auto px-4 py-6">
   <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6" id="videoGrid">
    <div class="bg-white shadow-md rounded-lg overflow-hidden">
     <img alt="Thumbnail of a video showing a beautiful landscape with mountains and a lake" class="w-full h-48 object-cover" height="400" src="https://storage.googleapis.com/a1aa/image/6Yh9974-NhweaZ99T-ZAH5et5DKbOsRER5go9Jhx834.jpg" width="600"/>
     <div class="p-4">
      <h2 class="text-lg font-semibold text-gray-800">
       Beautiful Landscape
      </h2>
      <p class="text-gray-600">
       A breathtaking view of mountains and a lake.
      </p>
     </div>
    </div>
    <div class="bg-white shadow-md rounded-lg overflow-hidden">
     <img alt="Thumbnail of a video showing a city skyline at night with bright lights" class="w-full h-48 object-cover" height="400" src="https://storage.googleapis.com/a1aa/image/P-AMVGCgfoDDfYQglSs9eQWibM0us8ziNjgIBasaTt8.jpg" width="600"/>
     <div class="p-4">
      <h2 class="text-lg font-semibold text-gray-800">
       City Skyline at Night
      </h2>
      <p class="text-gray-600">
       The beauty of a city illuminated by lights at night.
      </p>
     </div>
    </div>
    <div class="bg-white shadow-md rounded-lg overflow-hidden">
     <img alt="Thumbnail of a video showing a close-up of a cat's face with green eyes" class="w-full h-48 object-cover" height="400" src="https://storage.googleapis.com/a1aa/image/0PydcTguE6-I1n_Lw9-9JH1xE1MrH70cKNytTQJ7WW8.jpg" width="600"/>
     <div class="p-4">
      <h2 class="text-lg font-semibold text-gray-800">
       Cute Cat
      </h2>
      <p class="text-gray-600">
       A close-up of a cute cat with green eyes.
      </p>
     </div>
    </div>
    <div class="bg-white shadow-md rounded-lg overflow-hidden">
     <img alt="Thumbnail of a video showing a delicious plate of pasta with tomato sauce and basil" class="w-full h-48 object-cover" height="400" src="https://storage.googleapis.com/a1aa/image/pIqm2OqQMITVKk3pcDlL-aPY_xkF-GhJ6DsTNq6ehXw.jpg" width="600"/>
     <div class="p-4">
      <h2 class="text-lg font-semibold text-gray-800">
       Delicious Pasta
      </h2>
      <p class="text-gray-600">
       A plate of pasta with tomato sauce and basil.
      </p>
     </div>
    </div>
    <div class="bg-white shadow-md rounded-lg overflow-hidden">
     <img alt="Thumbnail of a video showing a person surfing on a big wave in the ocean" class="w-full h-48 object-cover" height="400" src="https://storage.googleapis.com/a1aa/image/vCRPbgC6hVFNdrb7kiCfPDqXSU7s22tPtNWlOaJQfTs.jpg" width="600"/>
     <div class="p-4">
      <h2 class="text-lg font-semibold text-gray-800">
       Surfing Adventure
      </h2>
      <p class="text-gray-600">
       A thrilling surfing adventure on a big wave.
      </p>
     </div>
    </div>
    <div class="bg-white shadow-md rounded-lg overflow-hidden">
     <img alt="Thumbnail of a video showing a beautiful sunset over the ocean with orange and pink hues" class="w-full h-48 object-cover" height="400" src="https://storage.googleapis.com/a1aa/image/DaSAV-K_3EWCsw3NUG7rGa0CjnQsYWaPhVH5gEwKz4M.jpg" width="600"/>
     <div class="p-4">
      <h2 class="text-lg font-semibold text-gray-800">
       Sunset Over the Ocean
      </h2>
      <p class="text-gray-600">
       A beautiful sunset over the ocean with vibrant colors.
      </p>
     </div>
    </div>
   </div>
  </main>
  <footer class="bg-white shadow-md mt-6">
   <div class="container mx-auto px-4 py-4 text-center text-gray-600">
    © 2023 YouTube. All rights reserved.
   </div>
  </footer>
  <div class="fixed inset-0 bg-gray-900 bg-opacity-50 flex items-center justify-center hidden" id="searchModal">
   <div class="bg-white p-6 rounded-lg shadow-lg w-11/12 md:w-1/2 lg:w-1/3">
    <div class="flex justify-between items-center mb-4">
     <h2 class="text-xl font-semibold text-gray-800">
      Search Videos
     </h2>
     <button class="text-gray-600 hover:text-gray-800" id="closeSearchModal">
      <i class="fas fa-times">
      </i>
     </button>
    </div>
    <form id="searchForm">
     <input class="w-full p-2 border border-gray-300 rounded-lg mb-4" id="searchQuery" placeholder="Search for videos..." type="text"/>
     <button class="w-full bg-red-600 text-white p-2 rounded-lg hover:bg-red-700" type="submit">
      Search
     </button>
    </form>
   </div>
  </div>
  <script>
   document.getElementById('searchButton').addEventListener('click', function() {
            document.getElementById('searchModal').classList.remove('hidden');
        });

        document.getElementById('closeSearchModal').addEventListener('click', function() {
            document.getElementById('searchModal').classList.add('hidden');
        });

        document.getElementById('searchForm').addEventListener('submit', function(event) {
            event.preventDefault();
            const query = document.getElementById('searchQuery').value;
            const apiKey = 'YOUR_YOUTUBE_API_KEY';
            const apiUrl = `https://www.googleapis.com/youtube/v3/search?part=snippet&type=video&q=${query}&key=${apiKey}`;

            fetch(apiUrl)
                .then(response => response.json())
                .then(data => {
                    const videoGrid = document.getElementById('videoGrid');
                    videoGrid.innerHTML = '';
                    data.items.forEach(item => {
                        const videoElement = document.createElement('div');
                        videoElement.classList.add('bg-white', 'shadow-md', 'rounded-lg', 'overflow-hidden');
                        videoElement.innerHTML = `
                            <img src="${item.snippet.thumbnails.high.url}" alt="${item.snippet.title}" class="w-full h-48 object-cover">
                            <div class="p-4">
                                <h2 class="text-lg font-semibold text-gray-800">${item.snippet.title}</h2>
                                <p class="text-gray-600">${item.snippet.description}</p>
                            </div>
                        `;
                        videoGrid.appendChild(videoElement);
                    });
                    document.getElementById('searchModal').classList.add('hidden');
                })
                .catch(error => console.error('Error fetching data:', error));
        });
  </script>
 </body>
</html>
