
MRI Processing
==============

.. currentmodule:: mne

Step by step instructions for using :func:`gui.coregistration`:

 - `Coregistration for subjects with structural MRI
   <https://www.slideshare.net/mne-python/mnepython-coregistration>`_
 - `Scaling a template MRI for subjects for which no MRI is available
   <https://www.slideshare.net/mne-python/mnepython-scale-mri>`_

.. autosummary::
   :toctree: generated/

   coreg.get_mni_fiducials
   gui.coregistration
   gui.fiducials
   create_default_subject
   head_to_mni
   head_to_mri
   read_freesurfer_lut
   read_talxfm
   scale_mri
   scale_bem
   scale_labels
   scale_source_space
   surface.marching_cubes
   transforms.apply_volume_registration
   transforms.compute_volume_registration
   vertex_to_mni
   voxel_neighbors
