
# Know Your Code
**Addition and Subtraction on two matrices**

Adding and subtracting matrices is very simple. Once you know the matrices are the same size, just add/subtract the numbers in the position of the first matrix with the number in the same position of the other matrix.

## Example
![alt text](https://www.math-only-math.com/images/subtraction-of-two-matrices.png)
![alt text](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAATEAAACOCAMAAABuUM9OAAAABlBMVEX///8AAABVwtN+AAAFDUlEQVR4nO2d6bqzIAyEzf3f9Lc8bRWyDmIXnPlzLIWQvCxSsD3b9k+yYQryo6aKJcfNzpOYl3jh4htnjH4HsIMXI+44Zc5Fdkk7zJQ0f/5f/lWQX7J+qRPFfedlNCzfGrHdE/OVFEE7ITupXYVxDZLn7ROf3vgN0cYVE6v067bGAjInm8NbugpzYjGyICmKttpz7d6oWskx7ajJJmZqn/1QdzgmM0/jpAnEGvemEbO9LBKrVPHJPrb1IZkl2hpryCBiXhPFps2c0axcJJa2gx2bn6M2+dsXTvNBxEznVYI81KQFBlFioirwa6wQe90reqt2ZoRYMoB/tI+5g/48MQlf/ioxs3aAWAYsmqUHiKmZNCE2f+Z35g5jhn++cUQQry72UZ742pZp/lo5UhuWe9aVUWOhix2jamA4+Yu3X7tsljDDaGq2fquaogWIATPvDK1AzM9wAbA1iL1VJIaKxFCRGCoSQ0ViqEgMFYmhIjFUJIYK2u3Jthn6hH6zw3MhqR/4EFSrURcqGX+mdw7HH2vjrSwTfrbzUN/t0UXtnDAxK5TggFWCl9od6ROOF2bZy/rY0de4JQv16xA+Rix3fzaxgS42Tszqn7bl5vojxMQL753EJK5PNuexkvnEjgdh/mCfQ6yJCyOmOpHKrHrk1pzyja0MhvrYwdfmnHFoLfKIS/J22jpi+b3ZnmGDPnYZsdZXiXPXfYBn/qzCdxErtbYd3lcR85ZOPrGK+6P3Sju8EWClR4b29DIxNV7nEOvmgfcTc+5mC59XvlkkhorEUJEYKhJDRWKoSAwViaEiMVQkhorEUJEYKhJDZRwvJHuK5oPJTsJeJvEiMGpsTDjmum0jSXuDt38qKk+z/yb7W8/sQUVysFgllvaR0OhW9dDaZ4sbP6nvmOfYaqLeTWPEiOWDqkjM8tDbGAu6rG3cMfSqTPYUnBg4Kr+amKiLC4gZlUTuSTIxPgrW5zGbWA+sdrRkcBKVox3gODF05u8mTs9oYGOEmArUqVaX7wv06IvEzCPBiNhewG2C9qBzoI+pL0RalWp7OhZlqLV0to9tJWJdYmFsnJzHjGmsEgpuSPq8dWJhbFadsb1gEAUevp2Y6Lz5tFPpDW1ixWCZmG5lo2BtHssNhcT2LyZGNRRX522ZwGBnNSRmeGhdHfMUY/ENNdPb1tIDFfeGQTnlK2ad1prlQ9OiaxDzJ9EZTnQDa8TumdhQo8PIBr3xDXnT5pDRYVOlsmc77xyJeYkWBd4aN/odyL7BB4qiKIqiKOpXdNHCeF1d9OFrXV30AX9dGZsJ5V+TtsuvLhVx+qHd2Hu+kzBg1sby3ZCBxIwsdydWfDAhsLC4dBcrnxD6NpbW8zQifzChLxIkLC07/PAkspCysmBi5bPnVWX2mAzYrdewVpfJng6496p/RrQk9gkbvyMSQ0ViqEgMFYmhIjFUJIaKxFCRGCoSQ0ViqEgMlfG8br45lv+U8cLaHwlP/8GX+83omxKr9zG1qUhiSW4S6y9JrJf3e7AkVhKJoSKxgjgqT2lkBcv12OMKWMJyzf95G78jEkNFYqhIDBWJoSIxVCSGisRQkRgqEkNFYqhIDBWJoVLRFsLvt4XuTaz0m3nN35sTK/3cO/tY85LEEqndVBJLpDbsSSyROhOywzfPn0hMrK9pBWXuSUwvL+pFpFxiKZEYKpxYv4S9G7HTAd8OGInhOhfyDYGdC/qWwM6EPRvYH1YhBh+Yi9pRAAAAAElFTkSuQmCC)

## A simple approach to implement a addition and subtraction is -

First we need to check that the number of rows of matrix A is equal to the number of rows of matrix B, Also we should perform the same check in case of column. 
But in our program we assume that number of rows of A and B are equal, as well as the column of A is equal to column of B. Then we goes

c[00]=a[00]+b[00], c[01]=a[01]+b[01]… and so on.
d[00]=a[00]-b[00], c[01]=a[01]-b[01]… and so on.

## Input and Output -
![alt text](https://photos.app.goo.gl/nxWApA4yHbaU4nu66)
