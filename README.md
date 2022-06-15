# Metadata Extraction Script

Table of Contents
=================

* [Metadata Extraction Script](#metadata-extraction-script)
   * [Installing all the dependencies](#Installing-all-the-dependencies)
   * [Running Metadata Extraction Script](#running-metadata-extraction-script)

## Installing all the dependencies

Basic **[command line usage]**:

	pip install -r requirements.txt

## Running Metadata Extraction Script

Basic **[command line usage]**:
    parser.add_argument("pdf_doc_path", help='Insert pdf_file for metadata extraction', type=str, nargs='?')

    run_metadata_extraction.py [path to pdf file]

For more information about the various command line options use `run_metadata_extraction.py --help`.


## Example of running

	run_metadata_extraction.py ExampleOfPdfFile.pdf
