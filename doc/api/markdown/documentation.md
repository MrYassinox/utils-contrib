<!-- markdownlint-disable -->

# API Overview

## Modules

- [`utils`](./utils.md#module-utils): Utils a contrib toolkits for devlops. 

## Classes

- [`utils.Argparse`](./utils.md#class-argparse): Argparse - Extended Argument Parser for Command-Line Argument Handling. 
- [`utils.AutoColorMatch`](./utils.md#class-autocolormatch): Automated color matching using histogram matching.
- [`utils.AutoCorrection_WhiteBalance`](./utils.md#class-autocorrection_whitebalance): Auto white balance correction opencv.
- [`utils.AxisCalc`](./utils.md#class-axiscalc): Calculate the top, bottom, right, and left coordinates of an object based on its axis.
- [`utils.ColorsConstants`](./utils.md#class-colorsconstants): Provide RGB color constants and a colors dictionary with elements formatted. 
- [`utils.ColorsConvartor`](./utils.md#class-colorsconvartor): Color converter class for different color formats.
- [`utils.EventsSignature`](./utils.md#class-eventssignature): EventsSignature class.
- [`utils.ExceptionsBase`](./utils.md#class-exceptionsbase): Class that defines variables for built-in exceptions derived from BaseException.
- [`utils.Image_ColorAverageDominant`](./utils.md#class-image_coloraveragedominant): Extract color average and dominant
- [`utils.LoggerHandle`](./utils.md#class-loggerhandle): LoggerHandle functionality and exception handling in applications.
- [`utils.Promise`](./utils.md#class-promise): A simplified implementation of promises in Python.
- [`utils.TaskTimer`](./utils.md#class-tasktimer): Task Execution Timer. 
- [`utils.Threaded`](./utils.md#class-threaded): Threaded 

## Functions

- [`utils.check_file_size`](./utils.md#function-check_file_size): Check if the file size is less than or equal to the allowed size.
- [`utils.check_run`](./utils.md#function-check_run): Check if a command runs successfully.
- [`utils.check_signature_object`](./utils.md#function-check_signature_object): introspect function parameters.
- [`utils.check_string_match_pattern`](./utils.md#function-check_string_match_pattern): Check if the characters in the string match the pattern.
- [`utils.checked_instances`](./utils.md#function-checked_instances): Checks the type of the provided object against the specified type checker.
- [`utils.clear`](./utils.md#function-clear): Clear the screen.
- [`utils.convert_cv2_to_pillow`](./utils.md#function-convert_cv2_to_pillow): Converts an image from OpenCV to Pillow.
- [`utils.convert_pillow_to_cv2`](./utils.md#function-convert_pillow_to_cv2): Converts an image from Pillow to OpenCV.
- [`utils.convert_pillow_to_numpy`](./utils.md#function-convert_pillow_to_numpy): Converts a Pillow image object to a NumPy array.
- [`utils.create_archive_tar_gz`](./utils.md#function-create_archive_tar_gz): Create a tar.gz archive containing specified files and directories.
- [`utils.create_directory`](./utils.md#function-create_directory): Create a directory.
- [`utils.decode_file_bytes`](./utils.md#function-decode_file_bytes): Decode a file encoded with base64.
- [`utils.detect_variable`](./utils.md#function-detect_variable): Detect if the given argument is a function.
- [`utils.edit_file_txt`](./utils.md#function-edit_file_txt): Edit a text file by adding, replacing, or removing content.
- [`utils.encode_file_bytes`](./utils.md#function-encode_file_bytes): Encode a file into base64 and optionally write the encoded data to a file.
- [`utils.get_data_from_csv_xlsx`](./utils.md#function-get_data_from_csv_xlsx): Get data from a CSV or XLSX file and return it as a list.
- [`utils.get_file_size`](./utils.md#function-get_file_size): Get the file size in bytes and convert it to bytes, KB, MB, GB, or TB.
- [`utils.get_h_w_c_to_image`](./utils.md#function-get_h_w_c_to_image): Returns the height, width, and number of channels of an image.
- [`utils.get_list_parameter_names_from_fun`](./utils.md#function-get_list_parameter_names_from_fun): Retrieves a list of parameter names from a Python function, method, or class.
- [`utils.get_opencv_formats`](./utils.md#function-get_opencv_formats): Returns a list of available image file formats supported by OpenCV.
- [`utils.get_pillow_formats`](./utils.md#function-get_pillow_formats): Returns a list of available image file formats supported by Pillow.
- [`utils.get_pkg_distribution`](./utils.md#function-get_pkg_distribution): Get the distribution information for a package.
- [`utils.get_string_before_pattern`](./utils.md#function-get_string_before_pattern): Get the string before the specified character pattern in the string.
- [`utils.import_from`](./utils.md#function-import_from): Imports module from a file path. and returns an object from a specified module.
- [`utils.import_lib`](./utils.md#function-import_lib): Imports a module from a file path.
- [`utils.measuring_average_color_lightness`](./utils.md#function-measuring_average_color_lightness): Measure the average color lightness based on different methods.
- [`utils.module_exists`](./utils.md#function-module_exists): Check if a module exists.
- [`utils.os_environ_get`](./utils.md#function-os_environ_get): Get the value of an environment variable.
- [`utils.os_environ_list`](./utils.md#function-os_environ_list): Return a list of environment variables.
- [`utils.os_environ_set`](./utils.md#function-os_environ_set): Set an environment variable locally.
- [`utils.platform_system_detect`](./utils.md#function-platform_system_detect): Detects the current platform or operating system.
- [`utils.read_pillow_from_array`](./utils.md#function-read_pillow_from_array): Creates a Pillow image object from the specified NumPy array.
- [`utils.read_with_opencv`](./utils.md#function-read_with_opencv): Reads an image from the specified file path using OpenCV and returns it as a NumPy array.
- [`utils.read_with_pillow`](./utils.md#function-read_with_pillow): Reads an image from the specified file path using Pillow and returns it as a NumPy array.
- [`utils.remove_files_older`](./utils.md#function-remove_files_older): Remove files that are older than specified days.
- [`utils.repositories`](./utils.md#function-repositories): Manage repositories.
- [`utils.requests_get`](./utils.md#function-requests_get): Download a file using requests.
- [`utils.retrieves_image_from_dir`](./utils.md#function-retrieves_image_from_dir): Retrieves image names or paths from a directory.
- [`utils.retrieves_modules_from_dir`](./utils.md#function-retrieves_modules_from_dir): Retrieves classes and/or functions from modules in a directory.
- [`utils.run_python`](./utils.md#function-run_python): Run a Python command and capture the output.
- [`utils.safe_exception_execute`](./utils.md#function-safe_exception_execute): Executes a target function or action safely, catching specified exceptions and returning a default value or the exception itself.
- [`utils.search_and_edite_module`](./utils.md#function-search_and_edite_module): Searches for a specified content in a module file and replaces it with new content.
- [`utils.search_and_replace`](./utils.md#function-search_and_replace): Search for a word in a file and optionally replace it with a new word.
- [`utils.search_scanne_folder`](./utils.md#function-search_scanne_folder): Scan a folder and return the list of files and other relevant information.
- [`utils.search_str`](./utils.md#function-search_str): Search for a word in a file and print if it exists or not.
- [`utils.search_str_by_line`](./utils.md#function-search_str_by_line): Search for a word in each line of a file and print the line and line number if found.
- [`utils.setup_temp`](./utils.md#function-setup_temp): Initialize a temporary folder path.
- [`utils.split_file_path`](./utils.md#function-split_file_path): Splits a file path into its directory name, base name, and extension.
- [`utils.store_img_binary`](./utils.md#function-store_img_binary): Store images in binary PIL mode.
- [`utils.store_metadata_png`](./utils.md#function-store_metadata_png): Store metadata in a PNG image.
- [`utils.strTobool`](./utils.md#function-strtobool): Convert a string representation to an actual boolean value.
- [`utils.sub_gitclone`](./utils.md#function-sub_gitclone): Clone a Git repository from a given URL.
- [`utils.sub_gitinstall`](./utils.md#function-sub_gitinstall): Install a Git module.
- [`utils.sub_run`](./utils.md#function-sub_run): Run a subprocess command and capture the output.
- [`utils.sub_wget`](./utils.md#function-sub_wget): Download a file using wget.
- [`utils.temporary_file`](./utils.md#function-temporary_file): Create a temporary file and write the bytes data to it.
- [`utils.threading_manager_functions`](./utils.md#function-threading_manager_functions): Manage threading operations by creating and returning either a Thread or a Timer object.
- [`utils.wget`](./utils.md#function-wget): Download a file using wget.
- [`utils.wrapper_decorator`](./utils.md#function-wrapper_decorator): Decorator sample.
- [`utils.wrapper_decorator_threaded`](./utils.md#function-wrapper_decorator_threaded): Decorator to create threaded functions.
- [`utils.wrapper_decorator_timetask`](./utils.md#function-wrapper_decorator_timetask): Decorator function to measure the execution time of a given function.
