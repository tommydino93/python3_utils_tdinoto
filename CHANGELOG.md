# Changelog

____________
## v1.0.4 (Apr 28, 2023)
### Feature
- Added utils_io.py
- Added `save_dict_to_disk_with_pickle` and `load_dict_from_disk_with_pickle` to utils_dict
- Added `is_empty` in utils_numpy
____________
## v1.0.3 (Feb 14, 2023)
### Feature
- Added utils_bids_dcm_dataset.py
- Added utils_dict
- Added `mean_excluding_zeros` in `utils_numpy`
- Added `re_orient_to_nib_closest_canonical` and `change_dcm_tags_one_derived_image` in `utils_nifti_dicom`
____________
## v1.0.2 (Oct 26, 2022)
### Feature
- Re-organized all functions to new style, with each input argument in a different line
- Added function `generate_binary_array_with_exact_proportion` in `utils_numpy.py`
- Added a second example in README.md
### Fix
- Changed one data type in `round_half_up` inside `numeric.py`
____________
## v1.0.1 (Aug 19, 2022)
### Feature
- Added function `str2bool` in `utils_strings.py`
- Added CHANGELOG.md
- Updated README.md with one example
### Fix
____________
## v1.0.0 (Aug 15, 2022)
- First release