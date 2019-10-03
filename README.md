# Cost_surface_generalization
Geographic profiling aims at highlighting the anchor point of an author of several space and time localized crimes, using cost surfaces built from each of these crime sites. Three method are here implemented, based on several assumptions:

- the difference between maximal and minimal hours passing through each pixel;
- the minimization of journeys-to-crime mean (Note that it does not require time data);
- the minimization of journeys-to-crime variance (Note that it does not require time data);

For each method, the pixel that minimizes the value corresponds in theory to the anchor point.

**IMPORTANT:** the [Skimage](https://scikit-image.org/docs/dev/api/skimage.html) library need to be installed. You can do it with [PyPi](https://pypi.org/project/skimage/).
