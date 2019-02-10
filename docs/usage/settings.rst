=================
SermonCut.ini
=================

When SermonCut is first started a file name sermoncut.ini is created.

Here the settings of SermonCut is stored. Here you can customize tagging and more. See table below for supported
values.

*********
[app]
*********

======================== ==============================================================
Variable                 Instructions
======================== ==============================================================
language                 Set interface language by language code. E.g. *en* (english),
                         *sv* (swedish)
======================== ==============================================================

*********
[tagging]
*********

======================== ==============================================================
Variable                 Instructions
======================== ==============================================================
autotag_title            *Advanced*: Enable fetching of date based on imported ID3 tag.
                         See autotagging section for more information.
autotag_title_format     *Advanced*: String to use in autotagging function. {} is used
                         as placeholder for year, month and date.
default_title            Here you can set a default title to use when opening audiofile.
default_artist           Here you can set a default artist to use when opening audiofile.
default_genre            Here you can set a default genre to use when opening audiofile.
default_album            Here you can set a default album to use when opening audiofile.
======================== ==============================================================

*********
[effects]
*********

======================== ==============================================================
Variable                 Supported values
======================== ==============================================================
normalize                1 (enabled) or 0 (disabled)
normalize_value          Value of normalization in -dB. Number needs to be negative
======================== ==============================================================

********
[export]
********

======================== ==============================================================
Variable                 Supported values
======================== ==============================================================
default_folder           Path to default folder. *Example: D:/Export*
export_based_on_autotag  *Advanced*: Enable auto-naming of exportfile.
                         See autotagging
======================== ==============================================================