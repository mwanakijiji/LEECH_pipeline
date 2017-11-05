# leech
preliminary reduction code.

0. \_\_init\_\_.py ---set the raw data and save data directory trunks...

1. find_star.py ---Identify the position of the star in each image

2. nod_subtract.py ---consolidate images into blocks of nods, subtract the correct nod from each image to remove background

3. register.py ---cross correlate images and shift them to a common pixel registration

4. combine_frames.py ---combine images in sets of 20 images with less than 2 degrees of parallactic angle changes

5. annular_PCA.py ---subtract the central star

See do.py
# LEECH_pipeline
