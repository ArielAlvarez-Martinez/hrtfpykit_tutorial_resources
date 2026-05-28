# hrtfpykit Tutorial Resources

This repository stores small resource files used by [`hrtfpykit`](https://github.com/ArielAlvarez-Martinez/hrtfpykit) tutorials, examples, and documentation. It provides shared tutorial assets in a separate repository so the main hrtfpykit package stays focused on source code while examples can still reference stable external files.

## Contents

At present, the repository contains a collection of example ear renderings generated from the 3D meshes available in the HUTUBS dataset. These images are provided for demonstration purposes, offering a visual representation of the rendering pipeline and the type of data that can be produced from the underlying 3D models.

```text
hutubs_images/
  subject_1/
    subject_100.png
    subject_101.png
    subject_102.png
  subject_2/
    subject_200.png
    subject_201.png
    subject_202.png
  subject_3/
    subject_300.png
    subject_302.png
    subject_303.png
```

The files are small tutorial assets arranged by subject folder. They are intended for examples that need subject-aligned image resources alongside HRTF dataset workflows.

## Repository Scope

The repository is intended for small, stable tutorial assets that support hrtfpykit examples and documentation. Resources may be added over time as new tutorials need shared files outside the main hrtfpykit package.
