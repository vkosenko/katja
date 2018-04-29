# A simple gallery

# Usage

## folder structure:
```
./galleries/
    galleryname/
        thumbs/
        images/
```

## gallery container / array
```
var galleries = [
    {
        name: 'Gallery Name', // name of the gallery
        hash: 'galleryname', // url hash of the gallery, e.g. http://example.com/#galleryname
        gallery: [ // gallery images
            {
                thumb: 'pic1.jpg',
                image: 'pic1.jpg', // optional, thumb name is taken if not set
                title: 'Picture Title', // optional, no title if not set
                desc: 'Picture Description' // optional, no description if not set
            }
        ]
    }
];
```