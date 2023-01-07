
# Warm Up

Print the number of products.

Print the name of the last product.

Write a function called `getSongCountInFirst` which returns the number of songs (details) of the first album. Call this function and print its return value.

Write a function called `getAvailableAmount` which returns the number of albums (products) that are available (use `status`). Call this function and print its return value.

=============================================================


# PA 1

### Task 1

Create a function called `searchAlbums` that takes one parameter called `namePart`. This function must return an array of all the album objects, the name of which contains the `namePart`.

Call `searchAlbums` with "World" as its argument and print the return value.

### Task 2

Create a function called `averageTrackCount`. This function must return the average number of tracks per album.

Call `averageTrackCount` and print the return value.

### Task 3

Create a function called `getAlbumsWithHigherPrice` which takes one parameter called `minPrice`. This function must return an array of products (albums) that only contains the albums which have a higher price than `minPrice`.

Call `getAlbumsWithHigherPrice` and print the return value.


=============================================================

# PA 2

### Task 1

Write a function called `getAlbumRuntime` which takes one parameter called `product`. This parameter is going to be a product (album) object. The function must return the sum length of all tracks from the album, in seconds.

Using the `getAlbumRuntime` function, print the total runtime of the last product from the `products` array.

### Task 2

Some albums only have a single 3 minute song while being very expensive and other albums may have an hour long runtime while being cheap. Follow the task below to find the album that's the most expensive relative to how long it is.

Write a function called `getMostValuableAlbumForRuntime`. This function must return the product (album) which has the highest `price/runtime` ratio. Use the `getAlbumRuntime` function for the solution.

Call `getMostValuableAlbumForRuntime` and print its return value.

=============================================================

# PA 3

### Task 1

Create a function called `getGenreCount` that takes a parameter called `album`. The `album` parameter is going to be a product object. This function must return the number of different `genre_id`s among all of its songs.

Call the `getGenreCount` function with the last product as its argument. Print the return value.

### Task 2

Create a function called `getAlbumsWithMultipleGenres` which returns an array of product objects (albums) that have more than 1 genre. Use the `getGenreCount` function  for the solution.

### Task 3

Write a function called `getOneWordArtistNames` that returns an array with the name of all artists (vendors) whos name does not contain a space. Be careful that each artist name must appear at most once in the array.

Call the `getOneWordArtistNames` function and print its return value to the console.


=============================================================


# EXTRA

### Task 1

If we assume that all song files use the same compression and have the same quality then we can estimate the "complexity" of the song if we divide the file-size by the duration. (`bytes/milliseconds`)

Create a function called `getMostComplexSong` that returns the title of the song which has the highest `bytes/milliseconds` ratio.

Call `getMostComplexSong` and print its return value.
