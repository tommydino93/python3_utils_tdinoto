# Changelog
____________
## v1.0.13 (Mar 08, 2024)
### Fix
- Updated `dcm2nii_sitk` in `utils_nifti_dicom.py`
____________
## v1.0.12 (Mar 05, 2024)
### Feature
- Added `extract_age_from_dcm_attribute` in `utils_nifti_dicom.py`
____________
## v1.0.11 (Feb 01, 2024)
### Fix
- Modified `find_common_elements` in `utils_lists.py`
### Feature
- Added `arrays_are_identical` in `utils_numpy.py`
____________
## v1.0.10 (Jan 09, 2024)
### Fix
- Modified `extract_unique_elements` in `utils_lists.py` to cope with list of lists
### Feature
- Added `extract_filename_from_nifti_path` in `utils_nifti_dicom.py`
____________
## v1.0.9 (Nov 22, 2023)
### Fix
- Modified floating point precision in `numeric.py`
- Modified `dcm2nii_sitk` in `utils_nifti_dicom.py`
- Corrected typo in `utils_numpy.py`
### Feature
- Added `convert_age_str2int` in `utils_bids_dcm_dataset.py`
____________
## v1.0.8 (Sep 06, 2023)
### Fix
- Modified imports from relative to absolute in `utils_plots.py`
____________
## v1.0.7 (Sep 06, 2023)
### Feature
- Added `first_argmin` in `utils_lists.py`
- Added `bias_field_correction_sitk` in `utils_nifti_dicom.py`
### Fix
- Included check that list is nested in `flatten_list` inside `utils_lists.py`
____________
## v1.0.6 (Aug 21, 2023)
### Feature
- Added `print_running_time_with_logger` in `numeric.py`
____________
## v1.0.5 (Aug 08, 2023)
### Feature
- Added `print_distribution_sessions_bids_dataset` in `utils_bids_dcm_dataset.py`
- Added `dcm2nii_sitk` in `utils_nifti_dicom.py`
- Added `binarize_array` in `utils_numpy.py`
- Added `contains_only_digits`, `load_json_file_as_dict`, `get_filename_without_extensions` and `get_filename_with_extensions` in `utils_strings.py`
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
____________
## v1.0.0 (Aug 15, 2022)
- First release