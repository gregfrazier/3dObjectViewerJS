# 3dObjectViewerJS
JavaScript 3D Object Viewer using Canvas

View 3D Objects in "object space", can only handle one continous strip of vertexes. So models with seperate pieces are not supported.

Very primitive. 
Has single source lighting & texturing (auto generated texture from http://ricardocabello.com/blog/post/710)

This was more of an experiment and learning experience than an actual product. I don't recommend using this for anything.

"Cell" shading example:
http://htmlpreview.github.io/?https://github.com/gregfrazier/3dObjectViewerJS/blob/master/CellShade.html
I never read up on how cell shading is really done, I just took a guess by drawing a wide wireframe on the backface triangles. In practice, this would be really slow.
