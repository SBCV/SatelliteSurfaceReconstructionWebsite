---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<!--
Create the build directory of potree:
    cd potree_dp && npm start
Copy potree_dp (including the build directory) to github_io_dp such that:
    github_io_dp
        ...
        potree
        ...
        _config.yml
-->

Project page of the [Satellite Surface Reconstruction](https://github.com/SBCV/SatelliteSurfaceReconstruction) pipeline.

### Example satellite surface reconstruction of a site in the IARPA MVS3DM dataset:
(Loading the model might take a while - be patient!)
<iframe src="potree/examples/satellite_mesh_obj_ply.html" width="100%" height="500px" style="display: block;">
</iframe>
In order to reduce the file size, the materials have been converted to vertex colors - which results in a lower texture quality. To inspect the original results [follow these steps](https://github.com/SBCV/SatelliteSurfaceReconstruction) to execute the pipeline. 
