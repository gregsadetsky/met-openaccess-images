# Archived -> Moved to a better repo!

Museums sharing data through Open access programs but not including image URLs seems to be a "thing"! I have a created a new repository which includes image URLs for the Met and the Art Institute of Chicago, and possibly more museums. You can find it all here:

https://github.com/gregsadetsky/open-access-is-great-but-where-are-the-images

Cheers

---

## The Met - Open Access - Images

The "met-openaccess-images.csv" file in this repo links Metropolitan Museum object IDs with their respective Open Access image file URL paths.

Object IDs (the `id` column) should be cross-referenced with the dataset made available by the Met [here](https://github.com/metmuseum/openaccess). This is also the same object ID as found in the URL of an artwork's page: `435809` in `https://www.metmuseum.org/art/collection/search/435809`

To form a full image URL path, prepend `https://images.metmuseum.org/CRDImages/` to the `urlpath` column values. For example, if the `urlpath` in the CSV file is `ph/original/DP146203.jpg`, the full URL would be `https://images.metmuseum.org/CRDImages/ph/original/DP146203.jpg`

Note that URL paths may contain UTF-8 characters, as in `dp/original/Bertall_LeDiableàParis_61-538-4.jpg`

Finally, note that there may be more than 1 image for the same `id` e.g.,
```
708,ad/original/133258.jpg
708,ad/original/133259.jpg
```

---

This project is not affiliated with the Metropolitan Museum of Art.
